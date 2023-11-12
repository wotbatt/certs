# Domain 4 - Identity and Access Management

This section covers domain 4 of the AWS Security Specialty certification.

## Task Statement 4.1: Design, implement, and troubleshoot authentication for AWS resources

**Knowledge of:**

- Methods and services for creating and managing identities (for example, federation, identity providers, AWS IAM Identity Center [AWS Single Sign-On], Amazon Cognito)
- Long-term and temporary credentialing mechanisms
- How to troubleshoot authentication issues (for example, by using CloudTrail, IAM Access Advisor, and IAM policy simulator)

**Skills in:**

- Establishing identity through an authentication system, based on
requirements
- Setting up multi-factor authentication (MFA)
- Determining when to use AWS Security Token Service (AWS STS) to issue temporary credentials

## Task Statement 4.2: Design, implement, and troubleshoot authorization for AWS resources

**Knowledge of:**

- Different IAM policies (for example, managed policies, inline policies, identity-based policies, resource-based policies, session control policies)
- Components and impact of a policy (for example, Principal, Action, Resource, Condition)
- How to troubleshoot authorization issues (for example, by using CloudTrail, IAM Access Advisor, and IAM policy simulator)

**Skills in:**

- Constructing attribute-based access control (ABAC) and role-based access control (RBAC) strategies
- Evaluating IAM policy types for given requirements and workloads
- Interpreting an IAM policy’s effect on environments and workloads
- Applying the principle of least privilege across an environment
- Enforcing proper separation of duties
- Analyzing access or authorization errors to determine cause or effect
- Investigating unintended permissions, authorization, or privileges granted to a resource, service, or entity

## AWS Managed Active Directory

- [AWS Federated Authentication with Active Directory Federation Services (AD FS)](https://aws.amazon.com/blogs/security/aws-federated-authentication-with-active-directory-federation-services-ad-fs/)
- [TD AWS Directory Service cheat sheet](https://tutorialsdojo.com/aws-directory-service/)
- [Tutorial: Create a trust relationship between your AWS Managed Microsoft AD and your self-managed Active Directory domain](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_tutorial_setup_trust.html)
- [Creating a trust relationship](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_setup_trust.html)
- [Use Case 1: Sign in to AWS applications and services with Active Directory credentials](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/usecase1.html)
- [Use Case 5: Extend your on-premises Active Directory to the AWS Cloud](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/usecase5.html)
- [How trust relationships work for forests in Active Directory](https://learn.microsoft.com/en-us/entra/identity/domain-services/concepts-forest-trust)

## AWS Cognito

- [Using Amazon Cognito user pools security features](https://docs.aws.amazon.com/cognito/latest/developerguide/managing-security.html)
- [What's the difference between Amazon Cognito user pools and identity pools?](https://repost.aws/knowledge-center/cognito-user-pools-identity-pools)
- [Getting started with Amazon Cognito identity pools (federated identities)](https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-with-identity-pools.html)
- [Adding groups to a user pool](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pools-user-groups.html)
- [Building fine-grained authorization using Amazon Cognito User Pools groups](https://aws.amazon.com/blogs/mobile/building-fine-grained-authorization-using-amazon-cognito-user-pools-groups/)

## AWS Access Policies - IAM / SCP

- [TD AWS IAM cheat sheet](https://tutorialsdojo.com/aws-identity-and-access-management-iam/)
- [TD Service Control Policies (SCP) vs IAM Policies](https://tutorialsdojo.com/service-control-policies-scp-vs-iam-policies/)
- [Bucket policy examples](https://docs.aws.amazon.com/AmazonS3/latest/userguide/example-bucket-policies.html)
- [How to Audit Cross-Account Roles Using AWS CloudTrail and Amazon CloudWatch Events](https://aws.amazon.com/blogs/security/how-to-audit-cross-account-roles-using-aws-cloudtrail-and-amazon-cloudwatch-events/)
- [How to use an external ID when granting access to your AWS resources to a third party](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_create_for-user_externalid.html)
- [Security best practices in IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [Service control policies (SCPs)](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps.html)

## AWS S3 Security

- [How to Use Bucket Policies and Apply Defense-in-Depth to Help Secure Your Amazon S3 Data](https://aws.amazon.com/blogs/security/how-to-use-bucket-policies-and-apply-defense-in-depth-to-help-secure-your-amazon-s3-data/)
- [How to restrict Amazon S3 bucket access to a specific IAM role](https://aws.amazon.com/blogs/security/how-to-restrict-amazon-s3-bucket-access-to-a-specific-iam-role/)
- [Amazon S3: Restrict management to a specific S3 bucket](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_s3_deny-except-bucket.html)

## CloudWatch 

- [TD CloudWatch cheat sheet](https://tutorialsdojo.com/amazon-cloudwatch/)
- [Amazon CloudWatch permissions reference](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/permissions-reference-cw.html)
