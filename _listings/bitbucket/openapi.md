---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 1
info:
  title: Bitbucket
  description: code-against-the-bitbucket-api-to-automate-simple-tasks-embed-bitbucket-data-into-your-own-site-build-mobile-or-desktop-apps-or-even-add-custom-ui-addons-into-bitbucket-itself-using-the-connect-framework-
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/commit/{node}/statuses/build:
    parameters:
      summary: Parameters Repositories Username Repo Slug Commit Node Statuses Build
      description: Parameters repositories username repo slug commit node statuses
        build
      operationId: parametersRepositoriesUsernameRepoSlugCommitNodeStatusesBuild
      x-api-path-slug: repositoriesusernamerepo-slugcommitnodestatusesbuild-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Commit
      - Node
      - Statuses
      - Build
    post:
      summary: Add Repositories Username Repo Slug Commit Node Statuses Build
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
      operationId: postRepositoriesUsernameRepoSlugCommitNodeStatusesBuild
      x-api-path-slug: repositoriesusernamerepo-slugcommitnodestatusesbuild-post
      parameters:
      - in: path
        name: node
        description: The commits SHA1
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Commit
      - Node
      - Statuses
      - Build
  /repositories/{username}/{repo_slug}/commit/{node}/statuses/build/{key}:
    get:
      summary: Get Repositories Username Repo Slug Commit Node Statuses Build Key
      description: Get repositories username repo slug commit node statuses build
        key
      operationId: getRepositoriesUsernameRepoSlugCommitNodeStatusesBuildKey
      x-api-path-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-get
      parameters:
      - in: path
        name: key
        description: The build status unique key
      - in: path
        name: node
        description: The commits SHA1
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Commit
      - Node
      - Statuses
      - Build
      - Key
    parameters:
      summary: Parameters Repositories Username Repo Slug Commit Node Statuses Build
        Key
      description: Parameters repositories username repo slug commit node statuses
        build key
      operationId: parametersRepositoriesUsernameRepoSlugCommitNodeStatusesBuildKey
      x-api-path-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Commit
      - Node
      - Statuses
      - Build
      - Key
    put:
      summary: Update Repositories Username Repo Slug Commit Node Statuses Build Key
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
      operationId: putRepositoriesUsernameRepoSlugCommitNodeStatusesBuildKey
      x-api-path-slug: repositoriesusernamerepo-slugcommitnodestatusesbuildkey-put
      parameters:
      - in: path
        name: key
        description: The commit status unique key
      - in: path
        name: node
        description: The commits SHA1
      - in: body
        name: _body
        description: The updated build status object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Commit
      - Node
      - Statuses
      - Build
      - Key
---