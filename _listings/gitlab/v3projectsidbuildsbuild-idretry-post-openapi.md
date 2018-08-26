---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Post Projects Builds Build Retry
  version: 1.0.0
  description: Retry a specific build of a project
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/builds:
    get:
      summary: Get Projects Builds
      description: Get a project builds
      operationId: getV3ProjectsIdBuilds
      x-api-path-slug: v3projectsidbuilds-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: query
        name: scope
        description: The scope of builds to show
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
  /v3/projects/{id}/repository/commits/{sha}/builds:
    get:
      summary: Get Projects Repository Commits Sha Builds
      description: Get builds for a specific commit of a project
      operationId: getV3ProjectsIdRepositoryCommitsShaBuilds
      x-api-path-slug: v3projectsidrepositorycommitsshabuilds-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: query
        name: scope
        description: The scope of builds to show
      - in: path
        name: sha
        description: The SHA id of a commit
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
      - Builds
  /v3/projects/{id}/builds/{build_id}:
    get:
      summary: Get Projects Builds Build
      description: Get a specific build of a project
      operationId: getV3ProjectsIdBuildsBuildId
      x-api-path-slug: v3projectsidbuildsbuild-id-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
  /v3/projects/{id}/builds/{build_id}/artifacts:
    get:
      summary: Get Projects Builds Build Artifacts
      description: This feature was introduced in GitLab 8.5
      operationId: getV3ProjectsIdBuildsBuildIdArtifacts
      x-api-path-slug: v3projectsidbuildsbuild-idartifacts-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Artifacts
  /v3/projects/{id}/builds/artifacts/{ref_name}/download:
    get:
      summary: Get Projects Builds Artifacts Ref Name Download
      description: Get projects builds artifacts ref name download.
      operationId: getV3ProjectsIdBuildsArtifactsRefNameDownload
      x-api-path-slug: v3projectsidbuildsartifactsref-namedownload-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: job
        description: The name for the build
      - in: path
        name: ref_name
        description: The ref from repository
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Artifacts
      - Ref
      - Name
      - Download
  /v3/projects/{id}/builds/{build_id}/trace:
    get:
      summary: Get Projects Builds Build Trace
      description: Get a trace of a specific build of a project
      operationId: getV3ProjectsIdBuildsBuildIdTrace
      x-api-path-slug: v3projectsidbuildsbuild-idtrace-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Trace
  /v3/projects/{id}/builds/{build_id}/cancel:
    post:
      summary: Post Projects Builds Build Cancel
      description: Cancel a specific build of a project
      operationId: postV3ProjectsIdBuildsBuildIdCancel
      x-api-path-slug: v3projectsidbuildsbuild-idcancel-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Cancel
  /v3/projects/{id}/builds/{build_id}/retry:
    post:
      summary: Post Projects Builds Build Retry
      description: Retry a specific build of a project
      operationId: postV3ProjectsIdBuildsBuildIdRetry
      x-api-path-slug: v3projectsidbuildsbuild-idretry-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Retry
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