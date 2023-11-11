# Domain 3 - Infrastructure Security

This section covers domain 3 of the AWS Security Specialty certification.

## Task Statement 3.1: Design and implement security controls for edge services

**Knowledge of:**

- Security features on edge services (for example, AWS WAF, load balancers,Amazon Route 53, Amazon CloudFront, AWS Shield)
- Common attacks, threats, and exploits (for example, Open Web Application Security Project [OWASP] Top 10, DDoS)
- Layered web application architecture

**Skills in:**

- Defining edge security strategies for common use cases (for example, public website, serverless app, mobile app backend)
- Selecting appropriate edge services based on anticipated threats and attacks (for example, OWASP Top 10, DDoS)
- Selecting appropriate protections based on anticipated vulnerabilities and risks (for example, vulnerable software, applications, libraries)
- Defining layers of defense by combining edge security services (for example, CloudFront with AWS WAF and load balancers)
- Applying restrictions at the edge based on various criteria (for example, geography, geolocation, rate limit)
- Activating logs, metrics, and monitoring around edge services to indicate attacks

## Task Statement 3.2: Design and implement network security controls

**Knowledge of:**

- VPC security mechanisms (for example, security groups, network ACLs, AWS Network Firewall)
- Inter-VPC connectivity (for example, AWS Transit Gateway, VPC endpoints)
- Security telemetry sources (for example, Traffic Mirroring, VPC Flow Logs)
- VPN technology, terminology, and usage
- On-premises connectivity options (for example, AWS VPN, AWS Direct Connect)

**Skills in:**

- Implementing network segmentation based on security requirements (for example, public subnets, private subnets, sensitive VPCs, on-premises connectivity)
- Designing network controls to permit or prevent network traffic as required (for example, by using security groups, network ACLs, and Network Firewall)
- Designing network flows to keep data off the public internet (for example, by using Transit Gateway, VPC endpoints, and Lambda in VPCs)
- Determining which telemetry sources to monitor based on network design, threats, and attacks (for example, load balancer logs, VPC Flow Logs, Traffic
Mirroring)

## Task Statement 3.3: Design and implement security controls for compute workloads

**Knowledge of:**

- Provisioning and maintenance of EC2 instances (for example, patching, inspecting, creation of snapshots and AMIs, use of EC2 Image Builder)
- IAM instance roles and IAM service roles
- Services that scan for vulnerabilities in compute workloads (for example, Amazon Inspector, Amazon Elastic Container Registry [Amazon ECR])
- Host-based security (for example, firewalls, hardening)

**Skills in:**

- Creating hardened EC2 AMIs
- Applying instance roles and service roles as appropriate to authorize compute workloads
- Scanning EC2 instances and container images for known vulnerabilities
- Applying patches across a fleet of EC2 instances or container images
- Activating host-based security mechanisms (for example, host-based firewalls)
- Analyzing Amazon Inspector findings and determining appropriate mitigation techniques
- Passing secrets and credentials securely to compute workloads

## Task Statement 3.4: Troubleshoot network security

**Knowledge of:**

- How to analyze reachability (for example, by using VPC Reachability Analyzer and Amazon Inspector)
- Fundamental TCP/IP networking concepts (for example, UDP compared with TCP, ports, Open Systems Interconnection [OSI] model, network operating system utilities)
- How to read relevant log sources (for example, Route 53 logs, AWS WAF logs, VPC Flow Logs)

**Skills in:**

- Identifying, interpreting, and prioritizing problems in network connectivity (for example, by using Amazon Inspector Network Reachability)
- Determining solutions to produce desired network behavior
- Analyzing log sources to identify problems
- Capturing traffic samples for problem analysis (for example, by using Traffic Mirroring)

## VPC IDS/IPS

- [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering/)
- [Intrusion Detection Systems and Intrusion Prevention Systems for EC2 Instances](https://d1.awsstatic.com/Marketplace/scenarios/security/SEC_01_TSB_Final.pdf)

## AWS Config

- [How to Use AWS Config to Monitor for and Respond to Amazon S3 Buckets Allowing Public Access](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-monitor-for-and-respond-to-amazon-s3-buckets-allowing-public-access/)
