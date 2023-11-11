# Practice test - Tutorial Dojo

- [AWS Certified Security – Specialty SCS-C01 SCS-C02 Exam Guide Study Path](https://tutorialsdojo.com/aws-certified-security-specialty-exam-guide-study-path-scs-c01-scs-c02/)
- [Practice test - Tutorial Dojo](#practice-test---tutorial-dojo)
  - [IAM](#iam)
    - [Automate rotation of access keys](#automate-rotation-of-access-keys)
  - [GuardDuty](#guardduty)
  - [Secrets Manager](#secrets-manager)
  - [SSM Parameter Store](#ssm-parameter-store)

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

## VPC IDS/IPS

- [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering/)
- [Intrusion Detection Systems and Intrusion Prevention Systems for EC2 Instances](https://d1.awsstatic.com/Marketplace/scenarios/security/SEC_01_TSB_Final.pdf)

## AWS Config

- [How to Use AWS Config to Monitor for and Respond to Amazon S3 Buckets Allowing Public Access](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-monitor-for-and-respond-to-amazon-s3-buckets-allowing-public-access/)
 