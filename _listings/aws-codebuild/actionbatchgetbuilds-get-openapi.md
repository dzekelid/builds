---
swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 0
info:
  title: AWS CodeBuild API Batch Get Builds
  version: 1.0.0
  description: Gets information about one or more builds.
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