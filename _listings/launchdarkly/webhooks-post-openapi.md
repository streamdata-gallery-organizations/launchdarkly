---
swagger: "2.0"
x-collection-name: LaunchDarkly
x-complete: 0
info:
  title: Launch Darkly Create a webhook
  description: Create a webhook.
  termsOfService: https://launchdarkly.com/terms
  contact:
    name: LaunchDarkly Support
    url: https://support.launchdarkly.com
    email: support@launchdarkly.com
  version: 2.0.0
host: app.launchdarkly.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: Get the root resource
      description: Get the root resource.
      operationId: getRoot
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - ""
  /auditlog:
    get:
      summary: Fetch a list of all webhooks
      description: Fetch a list of all webhooks.
      operationId: getAuditLogEntries
      x-api-path-slug: auditlog-get
      responses:
        200:
          description: OK
      tags:
      - Auditlog
  /auditlog/{resourceId}:
    get:
      summary: Get a webhook by ID
      description: Get a webhook by id.
      operationId: getAuditLogEntry
      x-api-path-slug: auditlogresourceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Auditlog
      - ResourceId
  /environments/{projectKey}:
    post:
      summary: Create an environment
      description: Create an environment.
      operationId: postEnvironment
      x-api-path-slug: environmentsprojectkey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
  /environments/{projectKey}/{environmentKey}:
    delete:
      summary: Delete an environment by ID
      description: Delete an environment by id.
      operationId: deleteEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
    get:
      summary: Get an environment by key.
      description: Get an environment by key..
      operationId: getEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
    patch:
      summary: Modify an environment by ID
      description: Modify an environment by id.
      operationId: patchEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-patch
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
  /flag-statuses/{projectKey}/{environmentKey}:
    get:
      summary: Get a list of statuses for all feature flags
      description: Get a list of statuses for all feature flags.
      operationId: getFeatureFlagStatus
      x-api-path-slug: flagstatusesprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flag-statuses
      - Projects
      - Keys
      - EnvironmentKey
  /flag-statuses/{projectKey}/{environmentKey}/{featureFlagKey}:
    get:
      summary: Get a list of statuses for all feature flags
      description: Get a list of statuses for all feature flags.
      operationId: getFeatureFlagStatuses
      x-api-path-slug: flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flag-statuses
      - Projects
      - Keys
      - EnvironmentKey
      - FeatureFlagKey
  /flags/{projectKey}:
    get:
      summary: Get a list of all features in the given project.
      description: Get a list of all features in the given project..
      operationId: getFeatureFlags
      x-api-path-slug: flagsprojectkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flags
      - Projects
      - Keys
    post:
      summary: Create a feature flag
      description: Create a feature flag.
      operationId: postFeatureFlag
      x-api-path-slug: flagsprojectkey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flags
      - Projects
      - Keys
  /flags/{projectKey}/{featureFlagKey}:
    delete:
      summary: Delete a feature flag by ID
      description: Delete a feature flag by id.
      operationId: deleteFeatureFlag
      x-api-path-slug: flagsprojectkeyfeatureflagkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flags
      - Projects
      - Keys
      - FeatureFlagKey
    get:
      summary: Get a single feature flag by key.
      description: Get a single feature flag by key..
      operationId: getFeatureFlag
      x-api-path-slug: flagsprojectkeyfeatureflagkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flags
      - Projects
      - Keys
      - FeatureFlagKey
    patch:
      summary: Modify a feature flag by ID
      description: Modify a feature flag by id.
      operationId: patchFeatureFlag
      x-api-path-slug: flagsprojectkeyfeatureflagkey-patch
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flags
      - Projects
      - Keys
      - FeatureFlagKey
  /projects:
    get:
      summary: Returns a list of all projects in the account.
      description: Returns a list of all projects in the account..
      operationId: getProjects
      x-api-path-slug: projects-get
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Create a project
      description: Create a project.
      operationId: postProject
      x-api-path-slug: projects-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{projectKey}:
    delete:
      summary: Delete a project by ID
      description: Delete a project by id.
      operationId: deleteProject
      x-api-path-slug: projectsprojectkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Projects
      - Keys
    get:
      summary: Get a project by key.
      description: Get a project by key..
      operationId: getProject
      x-api-path-slug: projectsprojectkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Projects
      - Keys
    patch:
      summary: Modify a project by ID
      description: Modify a project by id.
      operationId: patchProject
      x-api-path-slug: projectsprojectkey-patch
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Projects
      - Keys
  /user-search/{projectKey}/{environmentKey}:
    get:
      summary: Search users in LaunchDarkly based on their last active date, or a
        search query.
      description: Search users in launchdarkly based on their last active date, or
        a search query..
      operationId: getSearchUsers
      x-api-path-slug: usersearchprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - User-search
      - Projects
      - Keys
      - EnvironmentKey
  /users/{projectKey}/{environmentKey}:
    get:
      summary: List all users in the environment.
      description: List all users in the environment..
      operationId: getUsers
      x-api-path-slug: usersprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
  /users/{projectKey}/{environmentKey}/{userKey}:
    delete:
      summary: Delete a user by ID
      description: Delete a user by id.
      operationId: deleteUser
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
    get:
      summary: Get a user by key.
      description: Get a user by key..
      operationId: getUser
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
  /users/{projectKey}/{environmentKey}/{userKey}/flags:
    get:
      summary: Lists the current flag settings for a given user.
      description: Lists the current flag settings for a given user..
      operationId: getUserFlagSettings
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkeyflags-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
      - Flags
  /users/{projectKey}/{environmentKey}/{userKey}/flags/{featureFlagKey}:
    get:
      summary: Get a user by key.
      description: Get a user by key..
      operationId: getUserFlagSetting
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
      - Flags
      - FeatureFlagKey
    put:
      summary: Specifically enable or disable a feature flag for a user based on their
        key.
      description: Specifically enable or disable a feature flag for a user based
        on their key..
      operationId: putFlagSetting
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
      - Flags
      - FeatureFlagKey
  /webhooks:
    get:
      summary: Fetch a list of all webhooks
      description: Fetch a list of all webhooks.
      operationId: getWebhooks
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    post:
      summary: Create a webhook
      description: Create a webhook.
      operationId: postWebhook
      x-api-path-slug: webhooks-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Webhooks
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