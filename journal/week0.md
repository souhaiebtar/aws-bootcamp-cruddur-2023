# Week 0 — Billing and Architecture

## Required Homework/Tasks

### Install aws cli

as  i'm working on Linux ( ubuntu more exactly ), i did use the snippet in the Linux instruction to install aws cli on my machine, of the page [Installing or updating the latest version of the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html), there was also the possibility to install it using Homebrew (yes, now it does also support linux ) using `brew install awscli` but i did prefer the official way.

![install-aws-cli][awscliSetupImage]

### Generate Aws credentials and 
after that i did setup my credentials (Access key ID,Secret access key) that i generated in the `IAM`,
the setup was made using the command `aws configure` , the picture below is the result of the command `aws configure list` 

![AwsCredentialsSetup][awsConfigureList]

### Create a Billing Alarm

after watch [chirag video][chirag video], i did setup a billing alarm using *CloudWatch* like shown in 

![AwsBillingAlert][awsBillingAlertOnCloudWatch]

### Creating a budget

i created the budget using the information from [chirag video][chirag video], the picture [awsBudgetSetup][awsBudgetSetup] show the result


[awscliSetupImage]: assets/proofAwsCliInstalledWithCredentialApplied.png

[awsConfigureList]: assets/awsConfigureList.png

[awsBudgetSetup]: assets/awsBudgetSetup.png

[awsBillingAlertOnCloudWatch]: assets/awsBillingAlertOnCloudWatch.png

[chirag video]: https://www.youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=13