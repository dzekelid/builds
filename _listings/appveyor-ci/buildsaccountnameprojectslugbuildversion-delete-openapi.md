---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Delete Builds Accountname Projectslug Buildversion
  description: Delete builds accountname projectslug buildversion.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buildjobs/{jobId}/artifacts:
    get:
      summary: Get Buildjobs Jobid Artifacts
      description: Get buildjobs jobid artifacts.
      operationId: getBuildjobsJobArtifacts
      x-api-path-slug: buildjobsjobidartifacts-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
    parameters:
      summary: Parameters Buildjobs Jobid Artifacts
      description: Parameters buildjobs jobid artifacts.
      operationId: parametersBuildjobsJobArtifacts
      x-api-path-slug: buildjobsjobidartifacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
  /buildjobs/{jobId}/artifacts/{artifactFileName}:
    get:
      summary: Get Buildjobs Jobid Artifacts Artifactfilename
      description: Get buildjobs jobid artifacts artifactfilename.
      operationId: getBuildjobsJobArtifactsArtifactfilename
      x-api-path-slug: buildjobsjobidartifactsartifactfilename-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
      - Files
    parameters:
      summary: Parameters Buildjobs Jobid Artifacts Artifactfilename
      description: Parameters buildjobs jobid artifacts artifactfilename.
      operationId: parametersBuildjobsJobArtifactsArtifactfilename
      x-api-path-slug: buildjobsjobidartifactsartifactfilename-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
      - Files
  /buildjobs/{jobId}/log:
    get:
      summary: Get Buildjobs Jobid Log
      description: Get buildjobs jobid log.
      operationId: getBuildjobsJobLog
      x-api-path-slug: buildjobsjobidlog-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Log
    parameters:
      summary: Parameters Buildjobs Jobid Log
      description: Parameters buildjobs jobid log.
      operationId: parametersBuildjobsJobLog
      x-api-path-slug: buildjobsjobidlog-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Log
  /builds:
    post:
      summary: Post Builds
      description: Post builds.
      operationId: postBuilds
      x-api-path-slug: builds-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Builds
  /builds/{accountName}/{projectSlug}/{buildVersion}:
    delete:
      summary: Delete Builds Accountname Projectslug Buildversion
      description: Delete builds accountname projectslug buildversion.
      operationId: deleteBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-delete
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion
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