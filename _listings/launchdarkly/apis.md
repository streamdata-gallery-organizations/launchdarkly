---
name: LaunchDarkly
x-slug: launchdarkly
description: Our vision is to eliminate risk for developers and operations teams from
  the software development cycle. As companies transition to a world built on software,
  there is an increasing requirement to move quickly&mdash;but that often comes with
  the desire to maintain control. LaunchDarkly is the feature management platform
  that enables dev and ops teams to control the whole feature lifecycle, from concept
  to launch to value. Feature flagging is an industry best practice of wrapping a
  new or risky section of code or infrastructure change with a flag. Each flag can
  easily be turned on/off independent of code deployment (aka &rdquo;dark launching&rdquo;).
  Equipping businesses with the ability to move at the speed of every deploy allows
  an entire company to learn rapidly, deliver value to their customers faster, and
  produce more value. Developers can build, marketing can launch, product can iterate,
  and sales can sell.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
x-kinRank: "7"
x-alexaRank: "187776"
tags: LaunchDarkly
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/apis.md
specificationVersion: "0.14"
apis:
- name: Launch Darkly Get the root resource
  x-api-slug: launch-darkly
  description: Get the root resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//
  tags: ""
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/get-openapi.md
- name: Launch Darkly Fetch a list of all webhooks
  x-api-slug: launch-darkly
  description: Fetch a list of all webhooks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//auditlog
  tags: Auditlog
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/auditlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/auditlog-get-openapi.md
- name: Launch Darkly Get a webhook by ID
  x-api-slug: launch-darkly
  description: Get a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//auditlog/{resourceId}
  tags: Auditlog,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/auditlogresourceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/auditlogresourceid-get-openapi.md
- name: Launch Darkly Create an environment
  x-api-slug: launch-darkly
  description: Create an environment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//environments/{projectKey}
  tags: Environments,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkey-post-openapi.md
- name: Launch Darkly Delete an environment by ID
  x-api-slug: launch-darkly
  description: Delete an environment by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//environments/{projectKey}/{environmentKey}
  tags: Environments,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-delete-openapi.md
- name: Launch Darkly Get an environment by key.
  x-api-slug: launch-darkly
  description: Get an environment by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//environments/{projectKey}/{environmentKey}
  tags: Environments,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly Modify an environment by ID
  x-api-slug: launch-darkly
  description: Modify an environment by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//environments/{projectKey}/{environmentKey}
  tags: Environments,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/environmentsprojectkeyenvironmentkey-patch-openapi.md
- name: Launch Darkly Get a list of statuses for all feature flags
  x-api-slug: launch-darkly
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flag-statuses/{projectKey}/{environmentKey}
  tags: Flag-statuses,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly Get a list of statuses for all feature flags
  x-api-slug: launch-darkly
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flag-statuses/{projectKey}/{environmentKey}/{featureFlagKey}
  tags: Flag-statuses,Projects,Keys,EnvironmentKey,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-openapi.md
- name: Launch Darkly Get a list of all features in the given project.
  x-api-slug: launch-darkly
  description: Get a list of all features in the given project..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flags/{projectKey}
  tags: Flags,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkey-get-openapi.md
- name: Launch Darkly Create a feature flag
  x-api-slug: launch-darkly
  description: Create a feature flag.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flags/{projectKey}
  tags: Flags,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkey-post-openapi.md
- name: Launch Darkly Delete a feature flag by ID
  x-api-slug: launch-darkly
  description: Delete a feature flag by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flags/{projectKey}/{featureFlagKey}
  tags: Flags,Projects,Keys,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-delete-openapi.md
- name: Launch Darkly Get a single feature flag by key.
  x-api-slug: launch-darkly
  description: Get a single feature flag by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flags/{projectKey}/{featureFlagKey}
  tags: Flags,Projects,Keys,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-get-openapi.md
- name: Launch Darkly Modify a feature flag by ID
  x-api-slug: launch-darkly
  description: Modify a feature flag by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//flags/{projectKey}/{featureFlagKey}
  tags: Flags,Projects,Keys,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-patch-openapi.md
- name: Launch Darkly Returns a list of all projects in the account.
  x-api-slug: launch-darkly
  description: Returns a list of all projects in the account..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projects-get-openapi.md
- name: Launch Darkly Create a project
  x-api-slug: launch-darkly
  description: Create a project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projects-post-openapi.md
- name: Launch Darkly Delete a project by ID
  x-api-slug: launch-darkly
  description: Delete a project by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//projects/{projectKey}
  tags: Projects,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-delete-openapi.md
- name: Launch Darkly Get a project by key.
  x-api-slug: launch-darkly
  description: Get a project by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//projects/{projectKey}
  tags: Projects,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-get-openapi.md
- name: Launch Darkly Modify a project by ID
  x-api-slug: launch-darkly
  description: Modify a project by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//projects/{projectKey}
  tags: Projects,Projects,Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/projectsprojectkey-patch-openapi.md
- name: Launch Darkly Search users in LaunchDarkly based on their last active date,
    or a search query.
  x-api-slug: launch-darkly
  description: Search users in launchdarkly based on their last active date, or a
    search query..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//user-search/{projectKey}/{environmentKey}
  tags: User-search,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersearchprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersearchprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly List all users in the environment.
  x-api-slug: launch-darkly
  description: List all users in the environment..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}
  tags: Users,Projects,Keys,EnvironmentKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly Delete a user by ID
  x-api-slug: launch-darkly
  description: Delete a user by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}/{userKey}
  tags: Users,Projects,Keys,EnvironmentKey,UserKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkey-delete-openapi.md
- name: Launch Darkly Get a user by key.
  x-api-slug: launch-darkly
  description: Get a user by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}/{userKey}
  tags: Users,Projects,Keys,EnvironmentKey,UserKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkey-get-openapi.md
- name: Launch Darkly Lists the current flag settings for a given user.
  x-api-slug: launch-darkly
  description: Lists the current flag settings for a given user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}/{userKey}/flags
  tags: Users,Projects,Keys,EnvironmentKey,UserKey,Flags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflags-get-openapi.md
- name: Launch Darkly Get a user by key.
  x-api-slug: launch-darkly
  description: Get a user by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}/{userKey}/flags/{featureFlagKey}
  tags: Users,Projects,Keys,EnvironmentKey,UserKey,Flags,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get-openapi.md
- name: Launch Darkly Specifically enable or disable a feature flag for a user based
    on their key.
  x-api-slug: launch-darkly
  description: Specifically enable or disable a feature flag for a user based on their
    key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//users/{projectKey}/{environmentKey}/{userKey}/flags/{featureFlagKey}
  tags: Users,Projects,Keys,EnvironmentKey,UserKey,Flags,FeatureFlagKey
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put-openapi.md
- name: Launch Darkly Fetch a list of all webhooks
  x-api-slug: launch-darkly
  description: Fetch a list of all webhooks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooks-get-openapi.md
- name: Launch Darkly Create a webhook
  x-api-slug: launch-darkly
  description: Create a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooks-post-openapi.md
- name: Launch Darkly Delete a webhook by ID
  x-api-slug: launch-darkly
  description: Delete a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-delete-openapi.md
- name: Launch Darkly Get a webhook by ID
  x-api-slug: launch-darkly
  description: Get a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-get-openapi.md
- name: Launch Darkly Modify a webhook by ID
  x-api-slug: launch-darkly
  description: Modify a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/webhooksresourceid-patch-openapi.md
- name: Launch Darkly
  x-api-slug: launch-darkly
  description: Our vision is to eliminate risk for developers and operations teams
    from the software development cycle. As companies transition to a world built
    on software, there is an increasing requirement to move quickly&mdash;but that
    often comes with the desire to maintain control. LaunchDarkly is the feature management
    platform that enables dev and ops teams to control the whole feature lifecycle,
    from concept to launch to value. Feature flagging is an industry best practice
    of wrapping a new or risky section of code or infrastructure change with a flag.
    Each flag can easily be turned on/off independent of code deployment (aka &rdquo;dark
    launching&rdquo;). Equipping businesses with the ability to move at the speed
    of every deploy allows an entire company to learn rapidly, deliver value to their
    customers faster, and produce more value. Developers can build, marketing can
    launch, product can iterate, and sales can sell.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: LaunchDarkly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/launchdarkly/master/_listings/launchdarkly/openapi.md
x-common:
- type: x-website
  url: http://www.launchdarkly.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/launchdarkly
- type: x-email
  url: sales@launchdarkly.com
- type: x-email
  url: privacy@launchdarkly.com
- type: x-email
  url: security@launchdarkly.com
- type: x-github
  url: https://github.com/launchdarkly
- type: x-curated-source
  url: http://launchdarkly.com/blog/stripe-webhook-event-processing-best-practices/
- type: x-website
  url: http://launchdarkly.com
- type: x-twitter
  url: https://twitter.com/LaunchDarkly
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---