---
swagger: "2.0"
x-collection-name: CircleCI
x-complete: 0
info:
  title: CircleCI Parameters Project Username Project Build Num Artifacts
  description: Parameters project username project build num artifacts.
  version: 1.0.0
host: circleci.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /project/{username}/{project}/build-cache:
    delete:
      summary: Delete Project Username Project Build Cache
      description: Delete project username project build cache.
      operationId: deleteProjectUsernameProjectBuildCache
      x-api-path-slug: projectusernameprojectbuildcache-delete
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Build
      - Cache
    parameters:
      summary: Parameters Project Username Project Build Cache
      description: Parameters project username project build cache.
      operationId: parametersProjectUsernameProjectBuildCache
      x-api-path-slug: projectusernameprojectbuildcache-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Build
      - Cache
  /project/{username}/{project}/{build_num}:
    get:
      summary: Get Project Username Project Build Num
      description: |-
        Full details for a single build. The response includes all of the fields from the build summary.
        This is also the payload for the [notification webhooks](/docs/configuration/#notify), in which case this object is the value to a key named 'payload'.
      operationId: getProjectUsernameProjectBuildNum
      x-api-path-slug: projectusernameprojectbuild-num-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Build
      - Num
    parameters:
      summary: Parameters Project Username Project Build Num
      description: Parameters project username project build num.
      operationId: parametersProjectUsernameProjectBuildNum
      x-api-path-slug: projectusernameprojectbuild-num-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Build
      - Num
  /project/{username}/{project}/{build_num}/artifacts:
    get:
      summary: Get Project Username Project Build Num Artifacts
      description: Get project username project build num artifacts.
      operationId: getProjectUsernameProjectBuildNumArtifacts
      x-api-path-slug: projectusernameprojectbuild-numartifacts-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Build
      - Num
      - Artifacts
    parameters:
      summary: Parameters Project Username Project Build Num Artifacts
      description: Parameters project username project build num artifacts.
      operationId: parametersProjectUsernameProjectBuildNumArtifacts
      x-api-path-slug: projectusernameprojectbuild-numartifacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Build
      - Num
      - Artifacts
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---