---
name: GitLab
x-slug: gitlab
description: GitLab is a web-based Git-repository manager with wiki, issue-tracking
  and CI/CD pipelines features, using an open-source license, developed by GitLab
  Inc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: Builds
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/apis.md
specificationVersion: "0.14"
apis:
- name: API title - Get Projects Builds Build
  x-api-slug: v3projectsidbuildsbuild-id-get
  description: Get a specific build of a project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-id-get-openapi.md
- name: API title - Get Projects Builds Build Artifacts
  x-api-slug: v3projectsidbuildsbuild-idartifacts-get
  description: This feature was introduced in GitLab 8.5
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idartifacts-get-openapi.md
- name: API title - Get Projects Builds Build Trace
  x-api-slug: v3projectsidbuildsbuild-idtrace-get
  description: Get a trace of a specific build of a project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idtrace-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idtrace-get-openapi.md
- name: API title - Post Projects Builds Build Cancel
  x-api-slug: v3projectsidbuildsbuild-idcancel-post
  description: Cancel a specific build of a project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idcancel-post-openapi.md
- name: API title - Post Projects Builds Build Retry
  x-api-slug: v3projectsidbuildsbuild-idretry-post
  description: Retry a specific build of a project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idretry-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idretry-post-openapi.md
- name: API title - Post Projects Builds Build Erase
  x-api-slug: v3projectsidbuildsbuild-iderase-post
  description: Erase build (remove artifacts and build trace)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-iderase-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-iderase-post-openapi.md
- name: API title - Post Projects Builds Build Artifacts Keep
  x-api-slug: v3projectsidbuildsbuild-idartifactskeep-post
  description: Keep the artifacts to prevent them from being deleted
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idartifactskeep-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idartifactskeep-post-openapi.md
- name: API title - Post Projects Builds Build Play
  x-api-slug: v3projectsidbuildsbuild-idplay-post
  description: This feature was added in GitLab 8.11
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idplay-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsbuild-idplay-post-openapi.md
- name: API title - Post Projects Merge Request Merge Request Cancel Merge When Build
    Succeeds
  x-api-slug: v3projectsidmerge-requestmerge-request-idcancel-merge-when-build-succeeds-post
  description: Post projects merge request merge request cancel merge when build succeeds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidmerge-requestmerge-request-idcancel-merge-when-build-succeeds-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidmerge-requestmerge-request-idcancel-merge-when-build-succeeds-post-openapi.md
- name: API title - Post Projects Merge Requests Merge Request Cancel Merge When Build
    Succeeds
  x-api-slug: v3projectsidmerge-requestsmerge-request-idcancel-merge-when-build-succeeds-post
  description: Post projects merge requests merge request cancel merge when build
    succeeds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidmerge-requestsmerge-request-idcancel-merge-when-build-succeeds-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidmerge-requestsmerge-request-idcancel-merge-when-build-succeeds-post-openapi.md
- name: API title - Get Projects Builds
  x-api-slug: v3projectsidbuilds-get
  description: Get a project builds
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuilds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuilds-get-openapi.md
- name: API title - Get Projects Repository Commits Sha Builds
  x-api-slug: v3projectsidrepositorycommitsshabuilds-get
  description: Get builds for a specific commit of a project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidrepositorycommitsshabuilds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidrepositorycommitsshabuilds-get-openapi.md
- name: API title - Get Projects Builds Artifacts Ref Name Download
  x-api-slug: v3projectsidbuildsartifactsref-namedownload-get
  description: Get projects builds artifacts ref name download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsartifactsref-namedownload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidbuildsartifactsref-namedownload-get-openapi.md
- name: API title - Put Projects Services Builds Email
  x-api-slug: v3projectsidservicesbuildsemail-put
  description: Set builds-email service for project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidservicesbuildsemail-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidservicesbuildsemail-put-openapi.md
- name: API title - Post Projects (ref Ref )trigger Builds
  x-api-slug: v3projectsidrefreftriggerbuilds-post
  description: Post projects (ref ref )trigger builds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidrefreftriggerbuilds-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/gitlab/v3projectsidrefreftriggerbuilds-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://github.api.gallery.streamdata.io
- type: x-api-stack
  url: http://gitlab.stack.network
- type: x-documentation
  url: https://docs.gitlab.com/
- type: x-github
  url: https://github.com/gitlab
- type: x-openapi
  url: https://axil.gitlab.io/swaggerapi/static/swagger.json
- type: x-pricing
  url: https://about.gitlab.com/pricing/
- type: x-privacy-policy
  url: https://about.gitlab.com/privacy/
- type: x-support
  url: https://about.gitlab.com/getting-help/
- type: x-terms-of-service
  url: https://about.gitlab.com/terms/
- type: x-twitter
  url: https://twitter.com/gitlab
- type: x-website
  url: http://gitlab.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---