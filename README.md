# aws-cdk-samples
Samples apps and pipelines to use the aws-cdk Codefresh plugin

[![TypeScript build status]( https://g.codefresh.io/api/badges/pipeline/cf-support/AWS-CDK%2Faws-cdk-typescriptTest?type=cf-2&key=eyJhbGciOiJIUzI1NiJ9.NWY4ZGIwN2I0ZTZiYTcxYTlkNmE0YmRi.yLwabvNEULlRNqg3JE79RV_snKflnzkoS8wI50pXfEw)]( https://g.codefresh.io/pipelines/edit/new/builds?id=6067a9f3cefd7137179747f5&pipeline=aws-cdk-typescriptTest&projects=AWS-CDK&projectId=605b50f338440b464b5557e7)


There are two pipelines to show an end-to-end pipeline using the aws-cdk typed step.

cf-aws-cdk-python.yml is an example (lambda-cron) for the TypeScript language.

cf-aws-cdk-python.yml is an example (dynamodb-lamba) for the Pythin language.

**Note:** the default version for CDK is currently 1.94.1 but we plan to release new images as new versions are released so the cdk_version argument will allow to override the default version without forcing us to release a new version of the plugin.
