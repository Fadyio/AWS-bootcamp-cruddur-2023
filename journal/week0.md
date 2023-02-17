# Week 0 — Billing and Architecture

### Pre-Requisite and Homework For week 0
 - [X] [Generate Github rebo](#generate-github-rebo)
 - [X] [Create a budget](#create-a-budget)
 - [X] [set up a billing alarm](#set-up-a-billing-alarm)
 - [X] [secure the root account in aws and Enable AWS multi-factor authentication](#secure-the-root-account-in-aws-and-enable-aws-multi-factor-authentication)
 - [X] [Create an administrative user and Enable AWS multi-factor authentication](#create-an-administrative-user-and-enable-aws-multi-factor-authentication)
 - [X] [Napkin Diagram](#napkin-diagram)
 - [X] [Recreate Logical Architectual Diagram in Lucid Charts](#recreate-logical-architectual-diagram-in-lucid-charts)
 - [ ] [Use CloudShell](#use-cloudshell)
 - [ ] [Generate AWS Credentials](#generate-aws-credentials)
 - [ ] [Installed AWS CLI](#installed-aws-cli)

###  Homework Challenges For week 0
 - [X] [Destroy your root account credentials, Set MFA, IAM role](#destroy-your-root-account-credentials-set-mfa-iam-role)
 - [ ] [Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.](#use-eventbridge-to-hookup-health-dashboard-to-sns-and-send-notification-when-there-is-a-service-health-issue.)
 - [ ] [Review all the questions of each pillars in the Well Architected Tool](#review-all-the-questions-of-each-pillars-in-the-well-architected-tool)
 - [ ] [Create an architectural diagram the CI/CD logical pipeline in Lucid Charts](#create-an-architectural-diagram-the-ci-cd-logical-pipeline-in-lucid-charts)
 - [ ] [Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility.](#research-the-technical-and-service-limits-of-specific-services-and-how-they-could-impact-the-technical-path-for-technical-flexibility.)
- [ ] [Open a support ticket and request a service limit](#open-a-support-ticket-and-request-a-service-limit)

#### Generate Github rebo
- Generate a new Github Repository from this [template](https://github.com/ExamProCo/aws-bootcamp-cruddur-2023).
- For more Information you can read [the Github doc](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
![The GitHub repo](/journal/Img/week0/github-repo.png)

#### Create a budget
- Creating a billing alarm to make sure to not exceed the aws free tier.
- [For more info on how to Creating a budget in AWS](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-create.html)
![Budget](/journal/Img/week0/budget-alarm.png)
#### Set up a billing alarm
- Creating a billing alarm to monitor your estimated AWS charges
- [For more info on how to Creating a billing alarm in AWS](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)
![Billing](/journal/Img/week0/billing-alerts.png)
#### secure the root account in aws and Enable AWS multi-factor authentication
- Enable MFA on the Root account
- [For more info on how to Enable MFA in AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html)
![MFA](/journal/Img/week0/MFA.png)
#### Create an administrative user and Enable AWS multi-factor authentication
- Create an admin user to minimize root user access to your account [Following Amazon best practices for securing my AWS account and its resources](https://aws.amazon.com/premiumsupport/knowledge-center/security-best-practices/)
- Attach the administratoraccess policy to the admin user we just created.
![Admin](/journal/Img/week0/IAM-Admin.png)
#### Napkin Diagram
![Napkin](/journal/Img/week0/napkin.jpg)
#### Recreate Logical Architectual Diagram in Lucid Charts
- [The Lucid Charts Link to The Diagram](https://lucid.app/lucidchart/1a6c5bc1-dda4-46a9-9b86-701cabf15d58/edit?viewport_loc=-108%2C216%2C2208%2C1004%2C0_0&invitationId=inv_4097ab4a-18ea-454a-b1cf-c127b8afb91e)
- Used two availability zones for improving the availability and resilience of the applications and infrastructure.
- Created public subnet and private subnet for securing the database and the backend and isolate them from the internet and other publicly accessible networks,This can help reduce the risk of attacks and unauthorized access.
![The Diagram](/journal/Img/week0/Diagram.png)
#### Use CloudShell

#### Generate AWS Credentials

#### Installed AWS CLI

#### Destroy your root account credentials Set MFA IAM role

#### Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.

#### Review all the questions of each pillars in the Well Architected Tool

#### Create an architectural diagram the CI-CD logical pipeline in Lucid Charts

#### Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility.

#### Open a support ticket and request a service limit
