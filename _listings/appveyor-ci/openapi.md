swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 1
info:
  title: App Veyor
  description: appveyor-is-a-hosted-continuous-integration-service-which-runs-on-microsoftwindows---the-appveyor-rest-api-provides-a-restful-way-to-interact-with-theappveyor-service---this-includes-managing-projects-builds-deploymentsand-the-teams-that-build-them-additional-help-and-discussion-of-the-appveyor-rest-api-is-available-athttphelp-appveyor-comdiscussionsthis-swagger-definition-is-an-unofficial-description-of-the-appveyorrest-api-maintained-at-httpsgithub-comkevinoidappveyorswaggerplease-report-any-issues-or-suggestions-for-this-swagger-definition-athttpsgithub-comkevinoidappveyorswaggerissuesnew-api-conventionsfields-which-are-missing-from-update-operations-put-requests-aretypically-reset-to-their-default-values---so-although-most-fields-are-nottechnically-required-they-should-usually-be-specified-in-practice-
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
  /projects/{accountName}/{projectSlug}/build/{buildVersion}:
    get:
      summary: Get Projects Accountname Projectslug Build Buildversion
      description: Get projects accountname projectslug build buildversion.
      operationId: getProjectsAccountnameProjectslugBuildBuildversion
      x-api-path-slug: projectsaccountnameprojectslugbuildbuildversion-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Build
      - BuildVersion
    parameters:
      summary: Parameters Projects Accountname Projectslug Build Buildversion
      description: Parameters projects accountname projectslug build buildversion.
      operationId: parametersProjectsAccountnameProjectslugBuildBuildversion
      x-api-path-slug: projectsaccountnameprojectslugbuildbuildversion-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Build
      - BuildVersion
  /projects/{accountName}/{projectSlug}/settings/build-number:
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Build Number
      description: Parameters projects accountname projectslug settings build number.
      operationId: parametersProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
    put:
      summary: Put Projects Accountname Projectslug Settings Build Number
      description: Put projects accountname projectslug settings build number.
      operationId: putProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
  /projects/status/{statusBadgeId}/branch/{buildBranch}:
    get:
      summary: Get Projects Status Statusbadgeid Branch Buildbranch
      description: Get projects status statusbadgeid branch buildbranch.
      operationId: getProjectsStatusStatusbadgeBranchBuildbranch
      x-api-path-slug: projectsstatusstatusbadgeidbranchbuildbranch-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
      - Branch
      - BuildBranch
    parameters:
      summary: Parameters Projects Status Statusbadgeid Branch Buildbranch
      description: Parameters projects status statusbadgeid branch buildbranch.
      operationId: parametersProjectsStatusStatusbadgeBranchBuildbranch
      x-api-path-slug: projectsstatusstatusbadgeidbranchbuildbranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
      - Branch
      - BuildBranch
  /projects/{accountName}/{projectSlug}/branch/{buildBranch}:
    get:
      summary: Get Projects Accountname Projectslug Branch Buildbranch
      description: Get projects accountname projectslug branch buildbranch.
      operationId: getProjectsAccountnameProjectslugBranchBuildbranch
      x-api-path-slug: projectsaccountnameprojectslugbranchbuildbranch-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Branch
      - BuildBranch
    parameters:
      summary: Parameters Projects Accountname Projectslug Branch Buildbranch
      description: Parameters projects accountname projectslug branch buildbranch.
      operationId: parametersProjectsAccountnameProjectslugBranchBuildbranch
      x-api-path-slug: projectsaccountnameprojectslugbranchbuildbranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Branch
      - BuildBranch
  /projects/status/{webhookId}/branch/{buildBranch}:
    get:
      summary: Get Projects Status Webhookid Branch Buildbranch
      description: Get projects status webhookid branch buildbranch.
      operationId: getProjectsStatusWebhookBranchBuildbranch
      x-api-path-slug: projectsstatuswebhookidbranchbuildbranch-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - WebhookId
      - Branch
      - BuildBranch
    parameters:
      summary: Parameters Projects Status Webhookid Branch Buildbranch
      description: Parameters projects status webhookid branch buildbranch.
      operationId: parametersProjectsStatusWebhookBranchBuildbranch
      x-api-path-slug: projectsstatuswebhookidbranchbuildbranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - WebhookId
      - Branch
      - BuildBranch
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
    parameters:
      summary: Parameters Builds Accountname Projectslug Buildversion
      description: Parameters builds accountname projectslug buildversion.
      operationId: parametersBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion