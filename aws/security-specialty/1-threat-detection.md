# Threat Detection and Incident Response

- [AWS Certified Security – Specialty SCS-C01 SCS-C02 Exam Guide Study Path](https://tutorialsdojo.com/aws-certified-security-specialty-exam-guide-study-path-scs-c01-scs-c02/)
- [Threat detection and incident response](#threat-detection-and-incident-response)
  - [IAM](#iam)
    - [Automate rotation of access keys](#automate-rotation-of-access-keys)
  - [GuardDuty](#guardduty)
  - [Secrets Manager](#secrets-manager)
  - [SSM Parameter Store](#ssm-parameter-store)

## Task Statement 1.1: Design and implement an incident response plan

**Knowledge of:**

- AWS best practices for incident response :white_check_mark:
- Cloud incidents :white_check_mark:
- Roles and responsibilities in the incident response plan :white_check_mark:
- AWS Security Finding Format (ASFF) :large_orange_diamond: :white_check_mark:

**Skills in:**

- Implementing credential invalidation and rotation strategies in response to compromises (for example, by using AWS Identity and Access Management [IAM] and AWS Secrets Manager)
- Isolating AWS resources :large_orange_diamond:
- Designing and implementing playbooks and runbooks for responses to security incidents :large_orange_diamond:
- Deploying security services (for example, AWS Security Hub, Amazon Macie, Amazon GuardDuty, Amazon Inspector, AWS Config, Amazon Detective, AWS Identity and Access Management Access Analyzer) :white_check_mark:
- Configuring integrations with native AWS services and third-party services (for example, by using Amazon EventBridge and the ASFF) :red_circle:

## Task Statement 1.2: Detect security threats and anomalies by using AWS services

**Knowledge of:**

- AWS managed security services that detect threats :white_check_mark:
- Anomaly and correlation techniques to join data across services :red_circle:
- Visualizations to identify anomalies :red_circle:
- Strategies to centralize security findings :large_orange_diamond:

**Skills in:**

- Evaluating findings from security services (for example, GuardDuty, Security Hub, Macie, AWS Config, IAM Access Analyzer) :white_check_mark:
- Searching and correlating security threats across AWS services (for example, by using Detective) :large_orange_diamond:
- Performing queries to validate security events (for example, by using Amazon Athena) :large_orange_diamond:
- Creating metric filters and dashboards to detect anomalous activity (for example, by using Amazon CloudWatch) :large_orange_diamond:

## Task Statement 1.3: Respond to compromised resources and workloads

**Knowledge of:**

- AWS Security Incident Response Guide :large_orange_diamond:
- Resource isolation mechanisms :large_orange_diamond:
- Techniques for root cause analysis :large_orange_diamond:
- Data capture mechanisms :large_orange_diamond:
- Log analysis for event validation :large_orange_diamond:

**Skills in:**

- Automating remediation by using AWS services (for example, AWS Lambda, AWS Step Functions, EventBridge, AWS Systems Manager runbooks, Security Hub, AWS Config) :red_circle:
- Responding to compromised resources (for example, by isolating Amazon EC2 instances) :red_circle:
- Investigating and analyzing to conduct root cause analysis (for example, by using Detective) :red_circle:
- Capturing relevant forensics data from a compromised resource (for example, Amazon Elastic Block Store [Amazon EBS] volume snapshots, memory dump) :red_circle:
- Querying logs in Amazon S3 for contextual information related to security events (for example, by using Athena) :red_circle:
- Protecting and preserving forensic artifacts (for example, by using S3 Object Lock, isolated forensic accounts, S3 Lifecycle, and S3 replication) :large_orange_diamond:
- Preparing services for incidents and recovering services after incidents :red_circle:

## IAM

### Automate rotation of access keys

- Develop a Lambda function that calls the [GenerateCredentialReport](https://docs.aws.amazon.com/IAM/latest/APIReference/API_GenerateCredentialReport.html) API to generate the credential report.
- Configure the function to use GetCredentialReport API to download the report, parse the CSV file and check the keys with a [access_key_1_last_rotated](https://docs.aws.amazon.com/config/latest/developerguide/access-keys-rotated.html) of more than 90 days.
- Disable the old access keys using the [UpdateAccessKey](https://docs.aws.amazon.com/IAM/latest/APIReference/API_UpdateAccessKey.html) API.

## GuardDuty

Amazon GuardDuty can generate findings based on suspicious activities such as requests coming from known malicious IP addresses, changing of bucket policies/ACLs to expose an S3 bucket publicly, or suspicious API call patterns that attempt to discover misconfigured bucket permissions.

- [New – Using Amazon GuardDuty to Protect Your S3 Buckets](https://aws.amazon.com/blogs/aws/new-using-amazon-guardduty-to-protect-your-s3-buckets/)
- [How can I configure an EventBridge rule for GuardDuty to send custom SNS notifications for specific AWS service event types?](https://repost.aws/knowledge-center/guardduty-eventbridge-sns-rule)
- [Creating custom responses to GuardDuty findings with Amazon CloudWatch Events](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_findings_cloudwatch.html)

## Secrets Manager

- [AWS Secrets Manager Cheat Sheet](https://tutorialsdojo.com/aws-secrets-manager/)
- [What is AWS Secrets Manager](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
- [Rotate AWS Secrets Manager secrets](https://docs.aws.amazon.com/secretsmanager/latest/userguide/rotating-secrets.html)

## SSM Parameter Store

- [AWS Systems Manager Parameter Store Overview](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
- [Sharing Secrets with AWS Lambda Using AWS Systems Manager Parameter Store](https://aws.amazon.com/blogs/compute/sharing-secrets-with-aws-lambda-using-aws-systems-manager-parameter-store/)
