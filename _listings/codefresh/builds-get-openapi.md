---
swagger: "2.0"
x-collection-name: Codefresh
x-complete: 0
info:
  title: Codefresh Get Builds
  description: Get builds.
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /builds/{buildId}:
    get:
      summary: Get Builds Buildid
      description: Get builds buildid.
      operationId: getBuildsBuild
      x-api-path-slug: buildsbuildid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Buildid
  /builds/{serviceId}:
    post:
      summary: Post Builds Serviceid
      description: Post builds serviceid.
      operationId: postBuildsService
      x-api-path-slug: buildsserviceid-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: options
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Serviceid
  /builds/{buildId}/update:
    post:
      summary: Post Builds Buildid Update
      description: Post builds buildid update.
      operationId: postBuildsBuildUpdate
      x-api-path-slug: buildsbuildidupdate-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: options
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Buildid
  /builds:
    get:
      summary: Get Builds
      description: Get builds.
      operationId: getBuilds
      x-api-path-slug: builds-get
      parameters:
      - in: query
        name: account
        description: account name
      - in: query
        name: repoName
        description: repo name
      - in: query
        name: repoOwner
        description: repo owner
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