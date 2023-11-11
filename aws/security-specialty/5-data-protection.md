# Domain 5 - Data Protection

This section covers domain 5 of the AWS Security Specialty certification.

## Task Statement 5.1: Design and implement controls that provide confidentiality and integrity for data in transit

**Knowledge of:**

- TLS concepts
- VPN concepts (for example, IPsec)
- Secure remote access methods (for example, SSH, RDP over Systems Manager Session Manager)
- Systems Manager Session Manager concepts
- How TLS certificates work with various network services and resources (for example, CloudFront, load balancers)

**Skills in:**

- Designing secure connectivity between AWS and on-premises networks (for example, by using Direct Connect and VPN gateways)
- Designing mechanisms to require encryption when connecting to resources (for example, Amazon RDS, Amazon Redshift, CloudFront, Amazon S3, Amazon DynamoDB, load balancers, Amazon Elastic File System [Amazon EFS], Amazon API Gateway)
- Requiring TLS for AWS API calls (for example, with Amazon S3)
- Designing mechanisms to forward traffic over secure connections (for example, by using Systems Manager and EC2 Instance Connect)
- Designing cross-Region networking by using private VIFs and public VIFs

## Task Statement 5.2: Design and implement controls that provide confidentiality and integrity for data at rest

**Knowledge of:**

- Encryption technique selection (for example, client-side, server-side, symmetric, asymmetric)
- Integrity-checking techniques (for example, hashing algorithms, digital signatures)
- Resource policies (for example, for DynamoDB, Amazon S3, and AWS Key Management Service [AWS KMS])
- IAM roles and policies

**Skills in:**

- Designing resource policies to restrict access to authorized users (for example, S3 bucket policies, DynamoDB policies)
- Designing mechanisms to prevent unauthorized public access (for example, S3 Block Public Access, prevention of public snapshots and public AMIs)
- Configuring services to activate encryption of data at rest (for example, Amazon S3, Amazon RDS, DynamoDB, Amazon Simple Queue Service [Amazon SQS], Amazon EBS, Amazon EFS)
- Designing mechanisms to protect data integrity by preventing modifications (for example, by using S3 Object Lock, KMS key policies, S3 Glacier Vault Lock, and AWS Backup Vault Lock)
- Designing encryption at rest by using AWS CloudHSM for relational databases (for example, Amazon RDS, RDS Custom, databases on EC2 instances)
- Choosing encryption techniques based on business requirements

## Task Statement 5.3: Design and implement controls to manage the lifecycle of data at rest

**Knowledge of:**

- Lifecycle policies
- Data retention standards

**Skills in:**

- Designing S3 Lifecycle mechanisms to retain data for required retention periods (for example, S3 Object Lock, S3 Glacier Vault Lock, S3 Lifecycle policy)
- Designing automatic lifecycle management for AWS services and resources (for example, Amazon S3, EBS volume snapshots, RDS volume snapshots, AMIs, container images, CloudWatch log groups, Amazon Data Lifecycle Manager)
- Establishing schedules and retention for AWS Backup across AWS services

## Task Statement 5.4: Design and implement controls to protect credentials, secrets, and cryptographic key materials

**Knowledge of:**

- Secrets Manager
- Systems Manager Parameter Store
- Usage and management of symmetric keys and asymmetric keys (for example, AWS KMS)

**Skills in:**

- Designing management and rotation of secrets for workloads (for example, database access credentials, API keys, IAM access keys, AWS KMS customer managed keys)
- Designing KMS key policies to limit key usage to authorized users
- Establishing mechanisms to import and remove customer-provided key
material
