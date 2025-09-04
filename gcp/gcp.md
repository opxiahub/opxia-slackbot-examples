# GCP OpxiaBot Prompt Examples

This document contains example prompts for interacting with Google Cloud Platform (GCP) resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## 🔵 Security & Compliance

### Cloud Storage Security
```
@opxiabot Find all Cloud Storage buckets in GCP with public access
@opxiabot List all Cloud Storage buckets in GCP without uniform bucket-level access
@opxiabot Show me all Cloud Storage buckets in GCP with legacy ACLs enabled
@opxiabot Find all Cloud Storage buckets in GCP without encryption at rest
```

### Compute Engine Security
```
@opxiabot List all Compute instances in GCP with firewall rules allowing SSH from 0.0.0.0/0
@opxiabot Find all Compute instances in GCP with serial port access enabled
@opxiabot Show me all Compute instances in GCP without OS Login enabled
@opxiabot List all Compute instances in GCP with deprecated machine types
```

### IAM Security
```
@opxiabot Show me all service accounts in GCP with owner role
@opxiabot Find all service accounts in GCP with keys older than 90 days
@opxiabot List all IAM bindings in GCP with overly broad permissions
@opxiabot Show me all users in GCP with primitive roles assigned
```

### Database Security
```
@opxiabot Find all Cloud SQL instances in GCP without SSL required
@opxiabot List all Cloud SQL instances in GCP with public IP addresses
@opxiabot Show me all Firestore databases in GCP with security rules issues
@opxiabot Find all BigQuery datasets in GCP with public access
```

### Network Security
```
@opxiabot List all unattached external IPs in GCP incurring charges
@opxiabot Find all VPC firewall rules in GCP allowing traffic from 0.0.0.0/0
@opxiabot Show me all load balancers in GCP without SSL certificates
@opxiabot List all VPC networks in GCP with legacy networking enabled
```

## 💰 Cost Optimization

### Compute Optimization
```
@opxiabot Show me all unattached persistent disks in GCP
@opxiabot Find all Compute instances in GCP running over 30 days with CPU usage below 5%
@opxiabot List all preemptible instances in GCP that could be sustained instances
@opxiabot Show me all custom machine types in GCP that are oversized
```

### Storage Optimization
```
@opxiabot List all disk snapshots in GCP older than 60 days
@opxiabot Find all Cloud Storage buckets in GCP without lifecycle policies
@opxiabot Show me all persistent disks in GCP with low IOPS utilization
@opxiabot List all Cloud Storage objects in GCP in wrong storage class
```

### Database Optimization
```
@opxiabot Show me all stopped instances in GCP with attached persistent disks
@opxiabot Find all Cloud SQL instances in GCP with less than 10% connection usage
@opxiabot List all BigQuery datasets in GCP with high storage costs
@opxiabot Show me all Cloud SQL instances in GCP that are oversized
```

### Network Optimization
```
@opxiabot Find all Cloud NAT gateways in GCP with low traffic
@opxiabot Show me all VPN tunnels in GCP with zero traffic
@opxiabot List all Cloud Load Balancers in GCP with no backend traffic
@opxiabot Find all external IP addresses in GCP that are unused
```

## 📊 Operations & Monitoring

### Load Balancer Operations
```
@opxiabot List all load balancers in GCP with unhealthy backend services
@opxiabot Show me all load balancers in GCP with high error rates
@opxiabot Find all load balancers in GCP with SSL certificate expiring soon
@opxiabot List all load balancers in GCP with backend capacity issues
```

### Compute Operations
```
@opxiabot Show me all Compute instances in GCP with high CPU utilization
@opxiabot Find all Compute instances in GCP with disk space above 80%
@opxiabot List all Compute instances in GCP with available OS patches
@opxiabot Show me all Compute instances in GCP with network connectivity issues
```

### Database Operations
```
@opxiabot Find all Cloud SQL instances in GCP with high CPU usage
@opxiabot Show me all Cloud SQL instances in GCP with storage above 80%
@opxiabot List all BigQuery jobs in GCP with high slot usage
@opxiabot Find all Firestore operations in GCP with high read costs
```

### GKE Operations
```
@opxiabot Show me all GKE clusters in GCP with node upgrade available
@opxiabot Find all GKE clusters in GCP with unhealthy nodes
@opxiabot List all GKE clusters in GCP with deprecated Kubernetes versions
@opxiabot Show me all GKE clusters in GCP with autoscaling issues
```

### Cloud Function Operations
```
@opxiabot List all Cloud Functions in GCP with high error rates
@opxiabot Show me all Cloud Functions in GCP with high memory usage
@opxiabot Find all Cloud Functions in GCP with cold start latency issues
@opxiabot List all Cloud Functions in GCP with timeout errors
```

### App Engine Operations
```
@opxiabot Show me all App Engine services in GCP with high latency
@opxiabot Find all App Engine versions in GCP consuming traffic
@opxiabot List all App Engine applications in GCP with quota exceeded errors
@opxiabot Show me all App Engine services in GCP with instance scaling issues
```

## 🔄 Resource Management

### Project Management
```
@opxiabot Show me all projects in GCP by resource usage
@opxiabot List all projects in GCP with billing issues
@opxiabot Find all projects in GCP missing required labels
@opxiabot Show me all projects in GCP with inactive resources
```

### Organization Management
```
@opxiabot List all folders in GCP with inconsistent policies
@opxiabot Show me all organization policies in GCP with violations
@opxiabot Find all projects in GCP not following naming conventions
@opxiabot List all billing accounts in GCP with budget alerts
```

### Resource Inventory
```
@opxiabot Show me all resources in GCP by region
@opxiabot Find all resources in GCP created in the last 24 hours
@opxiabot List all resources in GCP by cost center
@opxiabot Show me all orphaned resources in GCP
```

### Backup & Recovery
```
@opxiabot List all Compute instances in GCP without snapshot schedules
@opxiabot Show me all persistent disks in GCP without recent snapshots
@opxiabot Find all Cloud SQL instances in GCP with backup failures
@opxiabot List all resources in GCP missing disaster recovery setup
```

## 🛡️ Security Center & Compliance

### Security Command Center
```
@opxiabot Show me all high-severity findings in GCP Security Command Center
@opxiabot Find all open security findings in GCP from last 7 days
@opxiabot List all assets in GCP with security violations
@opxiabot Show me all compliance violations in GCP Security Command Center
```

### Cloud Asset Inventory
```
@opxiabot List all resources in GCP with public access
@opxiabot Show me all resources in GCP without proper IAM policies
@opxiabot Find all resources in GCP with overprivileged service accounts
@opxiabot List all resources in GCP violating organization policies
```

### Audit Logging
```
@opxiabot Show me all admin activity logs in GCP with suspicious actions
@opxiabot Find all data access logs in GCP for sensitive resources
@opxiabot List all Cloud Logging sinks in GCP with configuration issues
@opxiabot Show me all audit logs in GCP with authentication failures
```

## 🏗️ Infrastructure & DevOps

### Cloud Build Operations
```
@opxiabot Show me all Cloud Build triggers in GCP with recent failures
@opxiabot Find all Cloud Build builds in GCP with long execution times
@opxiabot List all Cloud Build triggers in GCP with outdated configurations
@opxiabot Show me all Container Registry images in GCP with vulnerabilities
```

### Deployment Manager
```
@opxiabot List all Deployment Manager deployments in GCP with failures
@opxiabot Show me all Deployment Manager templates in GCP with deprecated resources
@opxiabot Find all deployments in GCP with configuration drift
@opxiabot List all Deployment Manager previews in GCP that failed validation
```

### Traffic & Performance
```
@opxiabot Show me all CDN cache hit ratios in GCP below 80%
@opxiabot Find all Cloud Endpoints in GCP with high latency
@opxiabot List all Global Load Balancers in GCP with geographic routing issues
@opxiabot Show me all Cloud Interconnect connections in GCP with utilization above 80%
```