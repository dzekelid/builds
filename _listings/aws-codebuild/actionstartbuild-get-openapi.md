---
swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 0
info:
  title: AWS CodeBuild API Start Build
  version: 1.0.0
  description: Starts running a build.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetBuilds:
    get:
      summary: Batch Get Builds
      description: Gets information about one or more builds.
      operationId: batchGetBuilds
      x-api-path-slug: actionbatchgetbuilds-get
      parameters:
      - in: query
        name: ids
        description: The IDs of the builds to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Builds
  /?Action=ListBuilds:
    get:
      summary: List Builds
      description: Gets a list of build IDs, with each build ID representing a single
        build.
      operationId: listBuilds
      x-api-path-slug: actionlistbuilds-get
      parameters:
      - in: query
        name: nextToken
        description: During a previous call, if there are more than 100 items in the
          list, only the first 100 items are returned, along with a unique string
          called a next token
        type: string
      - in: query
        name: sortOrder
        description: The order to list build IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Builds
  /?Action=StartBuild:
    get:
      summary: Start Build
      description: Starts running a build.
      operationId: startBuild
      x-api-path-slug: actionstartbuild-get
      parameters:
      - in: query
        name: artifactsOverride
        description: Build output artifact settings that override, for this build
          only, the latest ones already defined in the corresponding build project
        type: string
      - in: query
        name: buildspecOverride
        description: A build spec declaration that overrides, for this build only,
          the latest one already defined in the corresponding build project
        type: string
      - in: query
        name: environmentVariablesOverride
        description: A set of environment variables that overrides, for this build
          only, the latest ones already defined in the corresponding build project
        type: string
      - in: query
        name: projectName
        description: The name of the build project to start running a build
        type: string
      - in: query
        name: sourceVersion
        description: A version of the build input to be built, for this build only
        type: string
      - in: query
        name: timeoutInMinutesOverride
        description: The number of build timeout minutes, from 5 to 480 (8 hours)
          that overrides, for this build only, the latest setting already defined
          in the corresponding build project
        type: string
      responses:
        200:
          description: OK
      tags:
      - Builds
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