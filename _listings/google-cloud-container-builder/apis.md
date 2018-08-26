---
name: Google Cloud Container Builder
x-slug: google-cloud-container-builder
description: Google Cloud Container Builder lets you create Docker container images
  from application source code located in Google Cloud Storage. Container images created
  by Container Builder are automatically stored in Google Container Registry. You
  can deploy the container images you create on Google Container Engine, Google Compute
  Engine, Google App Engine flexible environment or other services where you can run
  applications from Docker containers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Builds
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/google-cloud-container-builder/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Container Builder - Get Builds
  x-api-slug: v1projectsprojectidbuilds-get
  description: |-
    Lists previously requested builds.

    Previously requested builds may still be in-progress, or may have finished
    successfully or unsuccessfully.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
  humanURL: https://cloud.google.com/container-builder/
  baseURL: ://cloudbuild.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/google-cloud-container-builder/v1projectsprojectidbuilds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/google-cloud-container-builder/v1projectsprojectidbuilds-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.billing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.container.builder.stack.network
- type: x-documentation
  url: https://cloud.google.com/container-builder/docs/
- type: x-pricing
  url: https://cloud.google.com/container-builder/pricing
- type: x-website
  url: https://cloud.google.com/container-builder/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---