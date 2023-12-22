# Domain 1 - Monitoring, Logging, and Remediation

## Task Statement 1.1: Implement metrics, alarms, and filters by using AWS monitoring and logging services

- Identify, collect, analyze, and export logs (for example, Amazon CloudWatch Logs, CloudWatch Logs Insights, AWS CloudTrail logs). :white_check_mark:
- Collect metrics and logs by using the CloudWatch agent. :large_orange_diamond:
- Create CloudWatch alarms. :large_orange_diamond:
- Create metric filters. :large_orange_diamond:
- Create CloudWatch dashboards. :red_circle:
- Configure notifications (for example, Amazon Simple Notification Service [Amazon SNS], Service Quotas, CloudWatch alarms, AWS Health events). :red_circle:

## Task Statement 1.2: Remediate issues based on monitoring and availability metrics

- Troubleshoot or take corrective actions based on notifications and alarms. :white_check_mark:
- Configure Amazon EventBridge rules to invoke actions. :red_circle:
- Use AWS Systems Manager Automation runbooks to take action based on AWS Config rules. :red_circle:

## EventBridge

- [Monitoring AWS Health events with Amazon EventBridge](https://docs.aws.amazon.com/health/latest/ug/cloudwatch-events-health.html)
- [Amazon EventBridge rules](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-rules.html)

## KMS

- [Determining past usage of a KMS key](https://docs.aws.amazon.com/kms/latest/developerguide/deleting-keys-determining-usage.html)
- [Deleting AWS KMS keys](https://docs.aws.amazon.com/kms/latest/developerguide/deleting-keys.html)

## Route 53

- [Types of Amazon Route 53 health checks](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/health-checks-types.html)

## Auto scaling

- [Using Amazon Aurora Auto Scaling with Aurora Replicas](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Integrating.AutoScaling.html)
- [Step and simple scaling policies for Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scaling-simple-step.html#as-step-scaling-warmup)
- [How can I troubleshoot Application Load Balancer session stickiness issues?](https://repost.aws/knowledge-center/elb-alb-stickiness)
- [Sticky sessions for your Application Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/sticky-sessions.html)
- [What is Amazon EC2 Auto Scaling?](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- [Troubleshoot Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/CHAP_Troubleshooting.html)

## AWS Config

- [How AWS Config works](https://docs.aws.amazon.com/config/latest/developerguide/how-does-config-work.html)

## AWS Systems Manager

- [AWS Systems Manager Automation](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-automation.html)
- [Query for the latest Amazon Linux AMI IDs using AWS Systems Manager Parameter Store](https://aws.amazon.com/blogs/compute/query-for-the-latest-amazon-linux-ami-ids-using-aws-systems-manager-parameter-store/)

## CloudWatch Agent

- [Metrics collected by the CloudWatch agent](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/metrics-collected-by-CloudWatch-agent.html)
- [Collect metrics, logs, and traces with the CloudWatch agent](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Install-CloudWatch-Agent.html)
- [List the available CloudWatch metrics for your instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/viewing_metrics_with_cloudwatch.html)
- [Publish custom metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/publishingMetrics.html)
- [Amazon CloudWatch Agent Adds Support for Procstat Plugin and Multiple Configuration Files](https://aws.amazon.com/about-aws/whats-new/2019/01/amazon-cloudwatch-agent-adds-support-for-procstat-plugin-and-multiple-configuration-files/)
- [Collect process metrics with the procstat plugin](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Agent-procstat-process-metrics.html)

## CloudWatch Logs

- [Monitoring OS metrics with Enhanced Monitoring](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Monitoring.OS.html#USER_Monitoring.OS.CloudWatchLogs)
- [Overview of monitoring metrics in Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/MonitoringOverview.html#monitoring-cloudwatch)

## AWS Health

- [Getting started with your AWS Health Dashboard – Your account health](https://docs.aws.amazon.com/health/latest/ug/getting-started-health-dashboard.html)

## CloudFront

- [CloudFront reports in the console](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/reports.html)
- [Monitor resource usage and send notifications when approaching quotas](https://docs.aws.amazon.com/solutions/latest/quota-monitor-for-aws/solution-overview.html)

## ELBs

- [Access logs for your Application Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-access-logs.html)
- [Access Logs for Elastic Load Balancers](https://aws.amazon.com/blogs/aws/access-logs-for-elastic-load-balancers/)
