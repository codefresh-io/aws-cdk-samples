# aws-cdk-samples
Samples apps and pipelines to use the aws-cdk Codefresh plugin

| --- | --- |
| TypeScript build status: | [![Codefresh build status]( https://g.codefresh.io/api/badges/pipeline/cf-support/AWS-CDK%2Faws-cdk-typescriptTest?type=cf-2&key=eyJhbGciOiJIUzI1NiJ9.NWY4ZGIwN2I0ZTZiYTcxYTlkNmE0YmRi.yLwabvNEULlRNqg3JE79RV_snKflnzkoS8wI50pXfEw)]( https://g.codefresh.io/pipelines/edit/new/builds?id=6067a9f3cefd7137179747f5&pipeline=aws-cdk-typescriptTest&projects=AWS-CDK&projectId=605b50f338440b464b5557e7) |
| Python build status: | [![Codefresh build status]( https://g.codefresh.io/api/badges/pipeline/cf-support/AWS-CDK%2Faws-cdk-python-test?type=cf-2&key=eyJhbGciOiJIUzI1NiJ9.NWY4ZGIwN2I0ZTZiYTcxYTlkNmE0YmRi.yLwabvNEULlRNqg3JE79RV_snKflnzkoS8wI50pXfEw)]( https://g.codefresh.io/pipelines/edit/new/builds?id=6067af00654fe3b1348e4dae&pipeline=aws-cdk-python-test&projects=AWS-CDK&projectId=605b50f338440b464b5557e7) |

yo will find in this repo some CDK apps using different lanagues. Those apps were lifted from [https://github.com/aws-samples/aws-cdk-examples/](https://github.com/aws-samples/aws-cdk-examples/).

Each language has its own pipeline to demosrate how to build the pplication and use it with CDK.

| Language | Pipeline | Application |
| --- | --- | --- |
| TypeScript | [cf-aws-cdk-typescript.yml](f-aws-cdk-typescript.yml) | [lambda-cron](lambda-cron) |
| Python | [cf-aws-cdk-python.yml](cf-aws-cdk-python.yml) | [dynamodb-lamba](dynamodb-lamba) |


**Note:** the default version for CDK is currently 1.94.1 but we plan to release new images as new versions are released so the cdk_version argument will allow to override the default version without forcing us to release a new version of the plugin.
