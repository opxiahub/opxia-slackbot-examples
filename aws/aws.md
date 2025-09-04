# AWS OpxiaBot Prompt Examples

This document contains example prompts for interacting with AWS resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## Security & Compliance

### S3 Security
```
@opxiabot Find all S3 buckets in AWS with public read access enabled
@opxiabot List all S3 buckets in AWS with versioning disabled
@opxiabot Show me all S3 buckets in AWS without server-side encryption
@opxiabot Find all S3 buckets in AWS with public write access
```

### EC2 Security
```
@opxiabot List all EC2 instances in AWS with security groups allowing SSH from 0.0.0.0/0
@opxiabot Find all EC2 instances in AWS with security groups allowing RDP from anywhere
@opxiabot Show me all EC2 instances in AWS without key pairs assigned
@opxiabot List all security groups in AWS with overly permissive rules
```

### IAM Security
```
@opxiabot Show me all IAM users in AWS with access keys older than 90 days
@opxiabot Find all IAM users in AWS with administrative privileges
@opxiabot List all IAM roles in AWS with overly broad permissions
@opxiabot Show me all unused IAM access keys in AWS
```

### Database Security
```
@opxiabot Find all RDS instances in AWS without encryption enabled
@opxiabot List all RDS instances in AWS with public accessibility enabled
@opxiabot Show me all DynamoDB tables in AWS without encryption at rest
@opxiabot Find all RDS instances in AWS without automated backups enabled
```

### Network Security
```
@opxiabot List all unused Elastic IPs in AWS that are incurring charges
@opxiabot Find all VPCs in AWS with default security groups having inbound rules
@opxiabot Show me all subnets in AWS that are publicly accessible
@opxiabot List all NACLs in AWS with allow-all rules
```

## Cost Optimization

### Storage Optimization
```
@opxiabot Show me all unattached EBS volumes in AWS
@opxiabot List all EBS snapshots in AWS older than 60 days
@opxiabot Find all EBS volumes in AWS with low IOPS utilization
@opxiabot Show me all S3 buckets in AWS with lifecycle policies not configured
```

### Compute Optimization
```
@opxiabot Find all EC2 instances in AWS running for over 30 days with CPU usage below 5%
@opxiabot Show me all stopped EC2 instances in AWS still incurring storage costs
@opxiabot List all EC2 instances in AWS that can be right-sized
@opxiabot Find all Reserved Instances in AWS that are underutilized
```

### Network Optimization
```
@opxiabot Find all NAT gateways in AWS with zero traffic in the last 7 days
@opxiabot Show me all Elastic Load Balancers in AWS with low traffic
@opxiabot List all VPC endpoints in AWS that are unused
@opxiabot Find all Data Transfer costs in AWS exceeding $100 this month
```

### Service-Specific Optimization
```
@opxiabot Show me all Lambda functions in AWS with low invocation rates
@opxiabot Find all RDS instances in AWS that are oversized
@opxiabot List all CloudWatch logs in AWS with retention period over 30 days
@opxiabot Show me all unused Auto Scaling groups in AWS
```

## Operations & Monitoring

### Load Balancer Operations
```
@opxiabot List all ALB/NLB load balancers in AWS with no healthy targets
@opxiabot Show me all load balancers in AWS with SSL certificate expiring in 30 days
@opxiabot Find all target groups in AWS with unhealthy targets
@opxiabot List all load balancers in AWS with high error rates
```

### Lambda Operations
```
@opxiabot Show me all Lambda functions in AWS with error rate above 1% in last hour
@opxiabot Find all Lambda functions in AWS with timeout issues
@opxiabot List all Lambda functions in AWS with memory usage above 80%
@opxiabot Show me all Lambda functions in AWS with cold start issues
```

### Database Operations
```
@opxiabot Find all RDS instances in AWS with storage above 80% capacity
@opxiabot Show me all RDS instances in AWS with high CPU utilization
@opxiabot List all DynamoDB tables in AWS with throttling events
@opxiabot Find all database connections in AWS exceeding connection limits
```

### Monitoring & Alerting
```
@opxiabot List all EC2 instances in AWS without CloudWatch monitoring enabled
@opxiabot Show me all CloudWatch alarms in AWS that are in ALARM state
@opxiabot Find all resources in AWS without proper tagging
@opxiabot List all SNS topics in AWS with failed message deliveries
```

### Auto Scaling Operations
```
@opxiabot Show me all AWS Auto Scaling groups at maximum capacity
@opxiabot Find all Auto Scaling groups in AWS with scaling policies not triggered
@opxiabot List all EC2 instances in AWS that failed auto scaling launches
@opxiabot Show me all Auto Scaling groups in AWS with unhealthy instances
```

### Backup & Recovery
```
@opxiabot List all EBS volumes in AWS without recent snapshots
@opxiabot Show me all RDS instances in AWS with failed backup jobs
@opxiabot Find all S3 buckets in AWS without Cross-Region Replication
@opxiabot List all resources in AWS missing disaster recovery configuration
```

## Resource Management

### Inventory Management
```
@opxiabot Show me all resources in AWS by region
@opxiabot List all resources in AWS by cost center tag
@opxiabot Find all orphaned resources in AWS across all services
@opxiabot Show me all resources in AWS created in the last 24 hours
```

### Tag Management
```
@opxiabot Find all resources in AWS missing required tags
@opxiabot Show me all resources in AWS with inconsistent tag values
@opxiabot List all resources in AWS tagged for deletion
@opxiabot Find all resources in AWS with cost center tag missing
```

### Lifecycle Management
```
@opxiabot Show me all resources in AWS scheduled for retirement
@opxiabot Find all AMIs in AWS that are no longer used
@opxiabot List all EBS snapshots in AWS that can be safely deleted
@opxiabot Show me all CloudFormation stacks in AWS that failed to deploy
```