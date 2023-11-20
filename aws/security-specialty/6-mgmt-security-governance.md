# Domain 6 - Management and Security Governance

This section covers domain 6 of the AWS Security Specialty certification.

## Task Statement 6.1: Develop a strategy to centrally deploy and manage AWS accounts

**Knowledge of:**

- Multi-account strategies
- Managed services that allow delegated administration
- Policy-defined guardrails
- Root account best practices
- Cross-account roles

**Skills in:**

- Deploying and configuring AWS Organizations
- Determining when and how to deploy AWS Control Tower (for example, which services must be deactivated for successful deployment)
- Implementing SCPs as a technical solution to enforce a policy (for example, limitations on the use of a root account, implementation of controls in AWS Control Tower)
- Centrally managing security services and aggregating findings (for example,
by using delegated administration and AWS Config aggregators)
- Securing AWS account root user credentials

## Task Statement 6.2: Implement a secure and consistent deployment strategy for cloud resources

**Knowledge of:**

- Deployment best practices with infrastructure as code (IaC) (for example, AWS CloudFormation template hardening and drift detection)
- Best practices for tagging
- Centralized management, deployment, and versioning of AWS services
- Visibility and control over AWS infrastructure

**Skills in:**

- Using CloudFormation to deploy cloud resources consistently and securely
- Implementing and enforcing multi-account tagging strategies
- Configuring and deploying portfolios of approved AWS services (for example, by using AWS Service Catalog)
- Organizing AWS resources into different groups for management
- Deploying Firewall Manager to enforce policies
- Securely sharing resources across AWS accounts (for example, by using AWS Resource Access Manager [AWS RAM])

## Task Statement 6.3: Evaluate the compliance of AWS resources

**Knowledge of:**

- Data classification by using AWS services
- How to assess, audit, and evaluate the configurations of AWS resources (for example, by using AWS Config)

**Skills in:**

- Identifying sensitive data by using Macie
- Creating AWS Config rules for detection of noncompliant AWS resources
- Collecting and organizing evidence by using Security Hub and AWS Audit Manager

## Task Statement 6.4: Identify security gaps through architectural reviews and cost analysis

**Knowledge of:**

- AWS cost and usage for anomaly identification
- Strategies to reduce attack surfaces
- AWS Well-Architected Framework

**Skills in:**

- Identifying anomalies based on resource utilization and trends
- Identifying unused resources by using AWS services and tools (for example, AWS Trusted Advisor, AWS Cost Explorer)
- Using the AWS Well-Architected Tool to identify security gaps

## OUs 

- [Managing organizational units](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_ous.html)

## IAM

- [SCIM profile and SAML 2.0 implementation](https://docs.aws.amazon.com/singlesignon/latest/userguide/scim-profile-saml.html)

## DNS - ACM & Route 53

- [Why is the CNAME record not resolving for my ACM issued certificate and the DNS validation status is still pending validation?](https://repost.aws/knowledge-center/acm-certificate-pending-validation)
- [TD Route 53 cheat sheet](https://tutorialsdojo.com/amazon-route-53/)
- [Configuring DNSSEC signing in Amazon Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-configuring-dnssec.html)
- [Enabling DNSSEC signing and establishing a chain of trust](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-configuring-dnssec-enable-signing.html)
- [Route53 DS record has wrong keytag](https://repost.aws/pt/questions/QUnoNwU3yIS66WSWfuH2H35Q/route53-ds-record-has-wrong-keytag)

## AWS Config

- [How to Monitor AWS Account Configuration Changes and API Calls to Amazon EC2 Security Groups](https://aws.amazon.com/blogs/security/how-to-monitor-aws-account-configuration-changes-and-api-calls-to-amazon-ec2-security-groups/)
- [Example AWS Lambda Functions for AWS Config Rules (Node.js)](https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config_develop-rules_nodejs-sample.html)

## CloudFormation

- [Intrinsic function reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)