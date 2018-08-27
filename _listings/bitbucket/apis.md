---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Builds
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket - Parameters Repositories Username Repo Slug Commit Node Statuses
    Build
  x-api-slug: repositoriesusernamerepo-slugcommitnodestatusesbuild-parameters
  description: Parameters repositories username repo slug commit node statuses build
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuild-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuild-parameters-openapi.md
- name: Bitbucket - Add Repositories Username Repo Slug Commit Node Statuses Build
  x-api-slug: repositoriesusernamerepo-slugcommitnodestatusesbuild-post
  description: |-
    Creates a new build status against the specified commit.

    If the specified key already exists, the existing status object will
    be overwritten.

    When creating a new commit status, you can use a URI template for the URL.
    Templates are URLs that contain variable names that Bitbucket will
    evaluate at runtime whenever the URL is displayed anywhere similar to
    parameter substitution in
    [Bitbucket Connect](https://developer.atlassian.com/bitbucket/concepts/context-parameters.html).
    For example, one could use `https://foo.com/builds/{repository.full_name}`
    which Bitbucket will turn into `https://foo.com/builds/foo/bar` at render time.
    The context variables available are `repository` and `commit`.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuild-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuild-post-openapi.md
- name: Bitbucket - Get Repositories Username Repo Slug Commit Node Statuses Build
    Key
  x-api-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-get
  description: Get repositories username repo slug commit node statuses build key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuildkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuildkey-get-openapi.md
- name: Bitbucket - Parameters Repositories Username Repo Slug Commit Node Statuses
    Build Key
  x-api-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-parameters
  description: Parameters repositories username repo slug commit node statuses build
    key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuildkey-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuildkey-parameters-openapi.md
- name: Bitbucket - Update Repositories Username Repo Slug Commit Node Statuses Build
    Key
  x-api-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-put
  description: |-
    Used to update the current status of a build status object on the
    specific commit.

    This operation can also be used to change other properties of the
    build status:

    * `state`
    * `name`
    * `description`
    * `url`
    * `refname`

    The `key` cannot be changed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/builds/master/_listings/bitbucket/repositoriesusernamerepo-slugcommitnodestatusesbuildkey-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://bigoven.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bitbucket.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitbucket
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: http://bitbucket.org
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---