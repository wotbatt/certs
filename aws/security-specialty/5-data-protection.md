# Domain 5 - Data Protection

This section covers domain 5 of the AWS Security Specialty certification.

## Task Statement 5.1: Design and implement controls that provide confidentiality and integrity for data in transit

**Knowledge of:**

- TLS concepts :white_check_mark:
- VPN concepts (for example, IPsec) :white_check_mark:
- Secure remote access methods (for example, SSH, RDP over Systems Manager Session Manager) :white_check_mark:
- Systems Manager Session Manager concepts :white_check_mark:
- How TLS certificates work with various network services and resources (for example, CloudFront, load balancers) :white_check_mark:

**Skills in:**

- Designing secure connectivity between AWS and on-premises networks (for example, by using Direct Connect and VPN gateways) :white_check_mark:
- Designing mechanisms to require encryption when connecting to resources (for example, Amazon RDS, Amazon Redshift, CloudFront, Amazon S3, Amazon DynamoDB, load balancers, Amazon Elastic File System [Amazon EFS], Amazon API Gateway) :white_check_mark:
- Requiring TLS for AWS API calls (for example, with Amazon S3) :white_check_mark:
- Designing mechanisms to forward traffic over secure connections (for example, by using Systems Manager and EC2 Instance Connect) :white_check_mark:
- Designing cross-Region networking by using private VIFs and public VIFs :white_check_mark:

## Task Statement 5.2: Design and implement controls that provide confidentiality and integrity for data at rest

**Knowledge of:**

- Encryption technique selection (for example, client-side, server-side, symmetric, asymmetric) :white_check_mark:
- Integrity-checking techniques (for example, hashing algorithms, digital signatures) :white_check_mark:
- Resource policies (for example, for DynamoDB, Amazon S3, and AWS Key Management Service [AWS KMS]) :white_check_mark:
- IAM roles and policies :white_check_mark:

**Skills in:**

- Designing resource policies to restrict access to authorized users (for example, S3 bucket policies, DynamoDB policies) :white_check_mark:
- Designing mechanisms to prevent unauthorized public access (for example, S3 Block Public Access, prevention of public snapshots and public AMIs) :white_check_mark:
- Configuring services to activate encryption of data at rest (for example, Amazon S3, Amazon RDS, DynamoDB, Amazon Simple Queue Service [Amazon SQS], Amazon EBS, Amazon EFS) :white_check_mark:
- Designing mechanisms to protect data integrity by preventing modifications (for example, by using S3 Object Lock, KMS key policies, S3 Glacier Vault Lock, and AWS Backup Vault Lock) :white_check_mark:
- Designing encryption at rest by using AWS CloudHSM for relational databases (for example, Amazon RDS, RDS Custom, databases on EC2 instances) :white_check_mark:
- Choosing encryption techniques based on business requirements :white_check_mark:

## Task Statement 5.3: Design and implement controls to manage the lifecycle of data at rest

**Knowledge of:**

- Lifecycle policies :white_check_mark:
- Data retention standards :white_check_mark:

**Skills in:**

- Designing S3 Lifecycle mechanisms to retain data for required retention periods (for example, S3 Object Lock, S3 Glacier Vault Lock, S3 Lifecycle policy) :white_check_mark:
- Designing automatic lifecycle management for AWS services and resources (for example, Amazon S3, EBS volume snapshots, RDS volume snapshots, AMIs, container images, CloudWatch log groups, Amazon Data Lifecycle Manager) :large_orange_diamond:
- Establishing schedules and retention for AWS Backup across AWS services :large_orange_diamond:

## Task Statement 5.4: Design and implement controls to protect credentials, secrets, and cryptographic key materials

**Knowledge of:**

- Secrets Manager :white_check_mark:
- Systems Manager Parameter Store :large_orange_diamond:
- Usage and management of symmetric keys and asymmetric keys (for example, AWS KMS) :white_check_mark:

**Skills in:**

- Designing management and rotation of secrets for workloads (for example, database access credentials, API keys, IAM access keys, AWS KMS customer managed keys) :white_check_mark:
- Designing KMS key policies to limit key usage to authorized users :white_check_mark:
- Establishing mechanisms to import and remove customer-provided key
material :white_check_mark:

## KMS

- [TD AWS KMS Cheat Sheet](https://tutorialsdojo.com/aws-key-management-service-aws-kms/)
- [AWS KMS Concepts](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#customer-cmk)
- [How to Protect the Integrity of Your Encrypted Data by Using AWS Key Management Service and EncryptionContext](https://aws.amazon.com/blogs/security/how-to-protect-the-integrity-of-your-encrypted-data-by-using-aws-key-management-service-and-encryptioncontext/)
- [Grants in AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/grants.html)
- [Condition keys for AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/policy-conditions.html)
- [Why can’t I upload a large file to Amazon S3 with AWS KMS key encryption?](https://repost.aws/knowledge-center/s3-large-file-encryption-kms-key)
- [Rotating AWS KMS keys](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-keys.html#rotate-keys-how-it-works)
- [Security best practices for AWS Key Management Service](https://docs.aws.amazon.com/kms/latest/developerguide/best-practices.html)
- [Importing key material for AWS KMS keys](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys.html)
- [Key policies in AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/key-policies.html#key-policy-default)
- [How can I prevent IAM policies from allowing a user or role to access a KMS key in AWS KMS?](https://repost.aws/knowledge-center/kms-prevent-access)
- [Envelope encryption](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#enveloping)
- [Encrypting CloudTrail log files with AWS KMS keys (SSE-KMS)](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/encrypting-cloudtrail-log-files-with-aws-kms.html)
- [Create data keys](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#data-keys)
- [GenerateDataKeyWithoutPlaintext API reference](https://docs.aws.amazon.com/kms/latest/APIReference/API_GenerateDataKeyWithoutPlaintext.html)
- [Protecting data by using client-side encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingClientSideEncryption.html)
- [Importing key material](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys.html)
- [Creating a CloudWatch alarm for expiration of imported key material](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys.html)
  - This alarm uses the **SecondsUntilKeyMaterialExpires** metric that AWS KMS publishes to CloudWatch for KMS keys with imported key material that expires. Each alarm uses this metric to monitor the imported key material for a particular KMS key. You cannot create a single alarm for all KMS keys with expiring key material or an alarm for KMS keys that you might create in the future.

## Simple Email Service (SES)

- [Security in AWS SES](https://docs.aws.amazon.com/ses/latest/dg/security.html)

## AWS Systems Manager - Parameter Store

- [Sharing Secrets with AWS Lambda Using AWS Systems Manager Parameter Store](https://aws.amazon.com/blogs/compute/sharing-secrets-with-aws-lambda-using-aws-systems-manager-parameter-store/)
- [AWS Systems Manager Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
- [Managing Parameter Tiers](https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-advanced-parameters.html)
- [How Parameter Store uses KMS](https://docs.aws.amazon.com/kms/latest/developerguide/services-parameter-store.html)

## AWS EBS

- [Migrate data between encrypted and unencrypted volumes](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSEncryption.html#migrate-data-encrypted-unencrypted)

## S3

- [S3 Glacier Vault Lock Overview](https://docs.aws.amazon.com/amazonglacier/latest/dev/vault-lock.html#vault-lock-overview)
- [Initiate Vault Lock (POST lock-policy)](https://docs.aws.amazon.com/amazonglacier/latest/dev/api-InitiateVaultLock.html)
- [Protecting data with encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingEncryption.html)
- [Data protection in Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/DataDurability.html)
- [Reducing the cost of SSE-KMS with Amazon S3 Bucket Keys](https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-key.html)

## CloudTrail

- [Security best practices for CloudTrail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/best-practices-security.html)

## Amazon Kinesis

- [Data Protection in Amazon Kinesis Data Analytics for SQL Applications](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/data-protection.html)
- [TD Amazon Kinesis cheat sheet](https://tutorialsdojo.com/amazon-kinesis/)

## DynamoDB

- [What is the AWS Database Encryption SDK?](https://docs.aws.amazon.com/database-encryption-sdk/latest/devguide/what-is-database-encryption-sdk.html)
- [AWS Database Encryption SDK for DynamoDB](https://docs.aws.amazon.com/database-encryption-sdk/latest/devguide/dynamodb-encryption-client.html)

## Lambda

- [Configuring code signing for Lambda](https://docs.aws.amazon.com/lambda/latest/dg/configuration-codesigning.html)
