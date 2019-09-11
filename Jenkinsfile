@Library('pipelines') _

javaFullPipeline(appName: params.APP_NAME, baseImage: params.BASE_IMAGE, 
                 gitBranch: params.GIT_BRANCH, gitCredentials: params.GIT_CREDENTIALS, 
                 gitUrl: params.GIT_URL, buildProject: params.BUILD_PROJECT, 
                 buildTag: params.BUILD_TAG, deployTag: params.DEPLOY_TAG,
                 testStrategy: params.TEST_STRATEGY, testCollectionUrl: params.TEST_COLLECTION_URL,
                 testEnvironmentDefinitionUrlForBuild: params.TEST_ENVIRONMENT_DEF_URL_FOR_BUILD,
                 promotedProject: params.PROMOTED_PROJECT, promotedTag: params.PROMOTED_TAG,
                 testEnvironmentDefinitionUrlForPromoted: params.TEST_ENVIRONMENT_DEF_URL_FOR_PROMOTED )
