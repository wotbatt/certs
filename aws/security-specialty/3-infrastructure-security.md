# Domain 3 - Infrastructure Security

This section covers domain 3 of the AWS Security Specialty certification.

## Task Statement 3.1: Design and implement security controls for edge services

**Knowledge of:**

- Security features on edge services (for example, AWS WAF, load balancers,Amazon Route 53, Amazon CloudFront, AWS Shield) :red_circle:
- Common attacks, threats, and exploits (for example, Open Web Application Security Project [OWASP] Top 10, DDoS) :white_check_mark:
- Layered web application architecture :white_check_mark:

**Skills in:**

- Defining edge security strategies for common use cases (for example, public website, serverless app, mobile app backend) :white_check_mark:
- Selecting appropriate edge services based on anticipated threats and attacks (for example, OWASP Top 10, DDoS) :white_check_mark:
- Selecting appropriate protections based on anticipated vulnerabilities and risks (for example, vulnerable software, applications, libraries) :white_check_mark:
- Defining layers of defense by combining edge security services (for example, CloudFront with AWS WAF and load balancers) :white_check_mark:
- Applying restrictions at the edge based on various criteria (for example, geography, geolocation, rate limit) :large_orange_diamond:
- Activating logs, metrics, and monitoring around edge services to indicate attacks :large_orange_diamond:

## Task Statement 3.2: Design and implement network security controls

**Knowledge of:**

- VPC security mechanisms (for example, security groups, network ACLs, AWS Network Firewall) :large_orange_diamond:
- Inter-VPC connectivity (for example, AWS Transit Gateway, VPC endpoints) :large_orange_diamond:
- Security telemetry sources (for example, Traffic Mirroring, VPC Flow Logs) :large_orange_diamond:
- VPN technology, terminology, and usage :white_check_mark:
- On-premises connectivity options (for example, AWS VPN, AWS Direct Connect) :white_check_mark:

**Skills in:**

- Implementing network segmentation based on security requirements (for example, public subnets, private subnets, sensitive VPCs, on-premises connectivity) :white_check_mark:
- Designing network controls to permit or prevent network traffic as required (for example, by using security groups, network ACLs, and Network Firewall) :white_check_mark:
- Designing network flows to keep data off the public internet (for example, by using Transit Gateway, VPC endpoints, and Lambda in VPCs) :large_orange_diamond:
- Determining which telemetry sources to monitor based on network design, threats, and attacks (for example, load balancer logs, VPC Flow Logs, Traffic Mirroring) :large_orange_diamond:

## Task Statement 3.3: Design and implement security controls for compute workloads

**Knowledge of:**

- Provisioning and maintenance of EC2 instances (for example, patching, inspecting, creation of snapshots and AMIs, use of EC2 Image Builder) :red_circle:
- IAM instance roles and IAM service roles :large_orange_diamond:
- Services that scan for vulnerabilities in compute workloads (for example, Amazon Inspector, Amazon Elastic Container Registry [Amazon ECR]) :white_check_mark:
- Host-based security (for example, firewalls, hardening) :white_check_mark:

**Skills in:**

- Creating hardened EC2 AMIs :red_circle:
- Applying instance roles and service roles as appropriate to authorize compute workloads :white_check_mark:
- Scanning EC2 instances and container images for known vulnerabilities :white_check_mark:
- Applying patches across a fleet of EC2 instances or container images :red_circle:
- Activating host-based security mechanisms (for example, host-based firewalls) :large_orange_diamond:
- Analyzing Amazon Inspector findings and determining appropriate mitigation techniques :white_check_mark:
- Passing secrets and credentials securely to compute workloads :red_circle:

## Task Statement 3.4: Troubleshoot network security

**Knowledge of:**

- How to analyze reachability (for example, by using VPC Reachability Analyzer and Amazon Inspector) :red_circle:
- Fundamental TCP/IP networking concepts (for example, UDP compared with TCP, ports, Open Systems Interconnection [OSI] model, network operating system utilities) :white_check_mark:
- How to read relevant log sources (for example, Route 53 logs, AWS WAF logs, VPC Flow Logs) :large_orange_diamond:

**Skills in:**

- Identifying, interpreting, and prioritizing problems in network connectivity (for example, by using Amazon Inspector Network Reachability) :red_circle:
- Determining solutions to produce desired network behavior :red_circle:
- Analyzing log sources to identify problems :large_orange_diamond:
- Capturing traffic samples for problem analysis (for example, by using Traffic Mirroring) :red_circle:

## EC2

- [Work with instance metadata](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ExamplePolicies_EC2.html#iam-example-instance-metadata)
- [How the IMDSv2 works](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/instance-metadata-v2-how-it-works.html)
- [Infrastructure security in Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/infrastructure-security.html   )

## VPC IDS/IPS

- [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering/)
- [Intrusion Detection Systems and Intrusion Prevention Systems for EC2 Instances](https://d1.awsstatic.com/Marketplace/scenarios/security/SEC_01_TSB_Final.pdf)

## AWS Config

- [How to Use AWS Config to Monitor for and Respond to Amazon S3 Buckets Allowing Public Access](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-monitor-for-and-respond-to-amazon-s3-buckets-allowing-public-access/)

## ELB

- [Elastic Load Balancing – Perfect Forward Secrecy and Other Security Enhancements](https://aws.amazon.com/blogs/aws/elastic-load-balancing-perfect-forward-secrecy-and-other-security-enhancements/)
  - To begin using Perfect Forward Secrecy, configure your load balancer with the newly added Elliptic Curve Cryptography (ECDHE) cipher suites.
- [ALB Adds New Security Policies Including Policy for Forward Secrecy](https://aws.amazon.com/about-aws/whats-new/2018/06/application-load-balancer-adds-new-security-policies-including-policy-for-forward-secrecy/)
  - **ELBSecurityPolicy-FS-2018-06** implements ciphers that ensure Forward Secrecy. Customers now have a policy that prevents out-of-band decryption if someone records the traffic and later compromises the server’s private key.
  - [ALB Security policies](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/create-https-listener.html#describe-ssl-policies)

## AWS Network Firewall

- [Deployment models for AWS Network Firewall](https://aws.amazon.com/blogs/networking-and-content-delivery/deployment-models-for-aws-network-firewall/)

## CloudFront

- [Authorization@Edge using cookies: Protect your Amazon CloudFront content from being downloaded by unauthenticated users](https://aws.amazon.com/blogs/networking-and-content-delivery/authorizationedge-using-cookies-protect-your-amazon-cloudfront-content-from-being-downloaded-by-unauthenticated-users/)
- [Using the managed response headers policies](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/using-managed-response-headers-policies.html#managed-response-headers-policies-security)
