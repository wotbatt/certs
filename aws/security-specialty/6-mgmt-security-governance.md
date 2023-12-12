# Domain 6 - Management and Security Governance

This section covers domain 6 of the AWS Security Specialty certification.

## Task Statement 6.1: Develop a strategy to centrally deploy and manage AWS accounts

**Knowledge of:**

- Multi-account strategies :white_check_mark:
- Managed services that allow delegated administration :white_check_mark:
- Policy-defined guardrails :white_check_mark:
- Root account best practices :white_check_mark:
- Cross-account roles :white_check_mark:

**Skills in:**

- Deploying and configuring AWS Organizations :white_check_mark:
- Determining when and how to deploy AWS Control Tower (for example, which services must be deactivated for successful deployment) :large_orange_diamond:
- Implementing SCPs as a technical solution to enforce a policy (for example, limitations on the use of a root account, implementation of controls in AWS Control Tower) :white_check_mark:
- Centrally managing security services and aggregating findings (for example,
by using delegated administration and AWS Config aggregators) :white_check_mark:
- Securing AWS account root user credentials :white_check_mark:

## Task Statement 6.2: Implement a secure and consistent deployment strategy for cloud resources

**Knowledge of:**

- Deployment best practices with infrastructure as code (IaC) (for example, AWS CloudFormation template hardening and drift detection) :white_check_mark:
- Best practices for tagging :white_check_mark:
- Centralized management, deployment, and versioning of AWS services :white_check_mark:
- Visibility and control over AWS infrastructure :white_check_mark:

**Skills in:**

- Using CloudFormation to deploy cloud resources consistently and securely :white_check_mark:
- Implementing and enforcing multi-account tagging strategies :large_orange_diamond:
- Configuring and deploying portfolios of approved AWS services (for example, by using AWS Service Catalog) :large_orange_diamond:
- Organizing AWS resources into different groups for management :large_orange_diamond:
- Deploying Firewall Manager to enforce policies :white_check_mark:
- Securely sharing resources across AWS accounts (for example, by using AWS Resource Access Manager [AWS RAM]) :large_orange_diamond:

## Task Statement 6.3: Evaluate the compliance of AWS resources

**Knowledge of:**

- Data classification by using AWS services :white_check_mark:
- How to assess, audit, and evaluate the configurations of AWS resources (for example, by using AWS Config) :white_check_mark:

**Skills in:**

- Identifying sensitive data by using Macie :white_check_mark:
- Creating AWS Config rules for detection of noncompliant AWS resources :white_check_mark:
- Collecting and organizing evidence by using Security Hub and AWS Audit Manager :white_check_mark:

## Task Statement 6.4: Identify security gaps through architectural reviews and cost analysis

**Knowledge of:**

- AWS cost and usage for anomaly identification :white_check_mark:
- Strategies to reduce attack surfaces :white_check_mark:
- AWS Well-Architected Framework :large_orange_diamond:

**Skills in:**

- Identifying anomalies based on resource utilization and trends :white_check_mark:
- Identifying unused resources by using AWS services and tools (for example, AWS Trusted Advisor, AWS Cost Explorer) :white_check_mark:
- Using the AWS Well-Architected Tool to identify security gaps :large_orange_diamond:

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
