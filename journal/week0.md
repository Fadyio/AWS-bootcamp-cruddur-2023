# Week 0 — Billing and Architecture

### Pre-Requisite and Homework For week 0
 - [X] [Generate Github rebo](#generate-github-rebo)
 - [X] [Create a budget](#create-a-budget)
 - [X] [set up a billing alarm](#set-up-a-billing-alarm)
 - [X] [secure the root account in aws and Enable AWS multi-factor authentication (MFA)](#secure-the-root-account-in-aws-and-enable-aws-multi-factor-authentication-(mfa))
 - [X] [Create an administrative user and Enable AWS multi-factor authentication (MFA)](#create-an-administrative-user-and-enable-aws-multi-factor-authentication-(mfa))
 - [ ] [Napkin Diagram](#napkin-diagram)
 - [ ] [Recreate Logical Architectual Diagram in Lucid Charts](#recreate-logical-architectual-diagram-in-lucid-charts)
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
#### secure the root account in aws and Enable AWS multi-factor authentication (MFA)
- Enable MFA on the Root account
- [For more info on how to Enable MFA in AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html)
![MFA](/journal/Img/week0/MFA.png)
#### Create an administrative user and Enable AWS multi-factor authentication (MFA)
- Create an admin user to minimize root user access to your account [Following Amazon best practices for securing my AWS account and its resources](https://aws.amazon.com/premiumsupport/knowledge-center/security-best-practices/)
- Attach the administratoraccess policy to the admin user we just created.
![Admin](/journal/Img/week0/IAM-Admin.png)
#### Napkin Diagram
-

#### Recreate Logical Architectual Diagram in Lucid Charts

#### Use CloudShell

#### Generate AWS Credentials

#### Installed AWS CLI

#### Destroy your root account credentials Set MFA IAM role

#### Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.

#### Review all the questions of each pillars in the Well Architected Tool

#### Create an architectural diagram the CI-CD logical pipeline in Lucid Charts

#### Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility.

#### Open a support ticket and request a service limit
