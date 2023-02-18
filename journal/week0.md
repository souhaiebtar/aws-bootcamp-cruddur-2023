# Week 0 — Billing and Architecture

## Required Homework/Tasks

### Install aws cli

as  i'm working on Linux ( ubuntu more exactly ), i did use the snippet in the Linux instruction to install aws cli on my machine, of the page [Installing or updating the latest version of the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html), there was also the possibility to install it using Homebrew (yes, now it does also support linux ) using `brew install awscli` but i did prefer the official way.

![install-aws-cli][awscliSetupImage]

### Generate Aws credentials 
after that i did setup my credentials (Access key ID,Secret access key) that i generated in the `IAM`,
the setup was made using the command `aws configure` , the picture below is the result of the command `aws configure list` 

![AwsCredentialsSetup][awsConfigureList]

### Create a Billing Alarm

after watch [chirag video][chirag video], i did setup a billing alarm for 25$ using *CloudWatch* like shown in 

![AwsBillingAlert][awsBillingAlertOnCloudWatch]

### Create a budget

i created the budget using the information from [chirag video][chirag video], the picture below show the result which is set to equal to 25$ or greater, the 

![awsBudgetSetup][awsBudgetSetup]

### Recreate Logical Architectural Design

![cruddurLogicalDiagram][logicalDiagram]

[lucid Chart share link][lucidChartLinkLogicalDiagram]

### Recreate Conceptual Architectural Design

![cruddurConceptualDiagram][conceptualDiagram]

[lucid Chart share link][lucidChartLinkConceptualDiagram]


## Homework Challenges



[awscliSetupImage]: assets/proofAwsCliInstalledWithCredentialApplied.png

[awsConfigureList]: assets/awsConfigureList.png

[awsBudgetSetup]: assets/awsBudgetSetup.png

[awsBillingAlertOnCloudWatch]: assets/awsBillingAlertOnCloudWatch.png

[chirag video]: https://www.youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=13

[conceptualDiagram]: assets/crudderConceptualDiagram.png

[logicalDiagram]: assets/CruddurLogicalDiagram.png

[lucidChartLinkLogicalDiagram]: https://lucid.app/lucidchart/35ddc8ec-09ea-4d12-8e41-ca5e82112a73/edit?viewport_loc=216%2C41%2C2017%2C1108%2C0_0&invitationId=inv_a4738964-b448-4803-a759-091d8df55e56

[lucidChartLinkConceptualDiagram]: https://lucid.app/lucidchart/ea7cac01-5bb9-4a97-b6e2-4b545bf0aca6/edit?viewport_loc=-963%2C-453%2C2473%2C1358%2C0_0&invitationId=inv_b622e53f-09aa-482d-bbf0-513169b20c70