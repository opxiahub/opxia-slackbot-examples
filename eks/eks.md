# EKS OpxiaBot Prompt Examples

This document contains example prompts for interacting with Amazon Elastic Kubernetes Service (EKS) resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## 🟠 EKS Cluster Management

### Cluster Health & Status
```
@opxiabot Show me all EKS clusters in AWS with unhealthy nodes
@opxiabot List all EKS clusters in AWS with deprecated Kubernetes versions
@opxiabot Find all EKS clusters in AWS with control plane upgrade available
@opxiabot Show me all EKS clusters in AWS with API server issues
```

### Node Group Operations
```
@opxiabot List all EKS node groups in AWS with nodes in NotReady state
@opxiabot Show me all EKS node groups in AWS with high CPU utilization
@opxiabot Find all EKS node groups in AWS with autoscaling issues
@opxiabot List all EKS node groups in AWS approaching maximum capacity
```

### Cluster Scaling & Performance
```
@opxiabot Show me all EKS clusters in AWS with cluster autoscaler failures
@opxiabot Find all EKS clusters in AWS with horizontal pod autoscaler issues
@opxiabot List all EKS clusters in AWS with resource constraints
@opxiabot Show me all EKS clusters in AWS with pod scheduling failures
```

### Cluster Configuration
```
@opxiabot List all EKS clusters in AWS without private endpoint enabled
@opxiabot Show me all EKS clusters in AWS without logging enabled
@opxiabot Find all EKS clusters in AWS without encryption at rest
@opxiabot List all EKS clusters in AWS with public API server access from 0.0.0.0/0
```

## 🔐 Security & Compliance

### Pod Security Standards
```
@opxiabot Find all pods in EKS running with privileged security context
@opxiabot Show me all pods in EKS without security context defined
@opxiabot List all pods in EKS running as root user
@opxiabot Find all pods in EKS with hostNetwork enabled
```

### AWS IAM & RBAC
```
@opxiabot Show me all service accounts in EKS with IAM roles for service accounts (IRSA) issues
@opxiabot List all EKS clusters in AWS with overly permissive IAM roles
@opxiabot Find all RBAC policies in EKS with cluster-admin permissions
@opxiabot Show me all pods in EKS using AWS credentials directly
```

### Network Security
```
@opxiabot List all services in EKS with LoadBalancer type exposed publicly
@opxiabot Show me all security groups in EKS with overly permissive rules
@opxiabot Find all Network Load Balancers in EKS without SSL termination
@opxiabot List all pods in EKS without network policies applied
```

### Secret Management
```
@opxiabot Show me all secrets in EKS stored as plain text
@opxiabot Find all pods in EKS mounting AWS credentials as volumes
@opxiabot List all EKS clusters in AWS without AWS Secrets Manager integration
@opxiabot Show me all external-secrets operators in EKS with sync failures
```

## 💰 Cost Optimization

### EC2 Instance Optimization
```
@opxiabot Show me all EKS node groups in AWS using on-demand instances only
@opxiabot Find all EKS clusters in AWS with underutilized EC2 instances
@opxiabot List all EKS node groups in AWS eligible for Spot instances
@opxiabot Show me all EKS clusters in AWS with oversized instance types
```

### Storage Cost Optimization
```
@opxiabot List all EBS volumes in EKS with gp2 storage type
@opxiabot Show me all persistent volumes in EKS with overprovisioned storage
@opxiabot Find all EKS clusters in AWS with unused EBS volumes
@opxiabot List all storage classes in EKS using expensive volume types
```

### Load Balancer Optimization
```
@opxiabot Show me all Classic Load Balancers in EKS that can be migrated to ALB
@opxiabot Find all Network Load Balancers in EKS with low traffic
@opxiabot List all Application Load Balancers in EKS with unused target groups
@opxiabot Show me all EKS services using multiple load balancers unnecessarily
```

### Right-sizing Opportunities
```
@opxiabot Find all deployments in EKS with high resource requests but low usage
@opxiabot Show me all pods in EKS with CPU requests exceeding usage by 50%
@opxiabot List all namespaces in EKS with resource quota underutilization
@opxiabot Find all workloads in EKS suitable for Fargate migration
```

## 📊 Monitoring & Operations

### Container & Pod Monitoring
```
@opxiabot Show me all pods in EKS with high memory consumption
@opxiabot Find all containers in EKS with restart count above 10
@opxiabot List all pods in EKS stuck in CrashLoopBackOff state
@opxiabot Show me all pods in EKS with image pull errors
```

### Application Performance Monitoring
```
@opxiabot List all deployments in EKS with rolling update timeouts
@opxiabot Show me all services in EKS with unhealthy endpoints
@opxiabot Find all ingress controllers in EKS with high error rates
@opxiabot List all horizontal pod autoscalers in EKS with scaling failures
```

### CloudWatch Integration
```
@opxiabot Show me all EKS clusters in AWS without Container Insights enabled
@opxiabot Find all EKS clusters in AWS with high CloudWatch Logs costs
@opxiabot List all custom metrics in EKS with missing data points
@opxiabot Show me all CloudWatch alarms in EKS that are in ALARM state
```

### Cluster Observability
```
@opxiabot List all EKS clusters in AWS with CoreDNS performance issues
@opxiabot Show me all EKS clusters in AWS with kube-proxy problems
@opxiabot Find all EKS clusters in AWS with CNI plugin failures
@opxiabot List all add-ons in EKS with update failures
```

## 🔄 Workload Management

### Deployment Management
```
@opxiabot Show me all deployments in EKS with image vulnerabilities
@opxiabot Find all deployments in EKS using images without tags
@opxiabot List all deployments in EKS with missing health checks
@opxiabot Show me all deployments in EKS with zero downtime deployment issues
```

### StatefulSet Operations
```
@opxiabot List all StatefulSets in EKS with persistent volume claim errors
@opxiabot Show me all StatefulSets in EKS with pod ordering issues
@opxiabot Find all StatefulSets in EKS with storage expansion problems
@opxiabot List all StatefulSets in EKS with backup failures
```

### Job & CronJob Management
```
@opxiabot Show me all failed jobs in EKS from the last 7 days
@opxiabot Find all CronJobs in EKS with schedule conflicts
@opxiabot List all jobs in EKS exceeding execution time limits
@opxiabot Show me all CronJobs in EKS with cleanup policy issues
```

### DaemonSet Operations
```
@opxiabot List all DaemonSets in EKS with pods not running on all nodes
@opxiabot Show me all DaemonSets in EKS with update strategy problems
@opxiabot Find all DaemonSets in EKS with resource constraint issues
@opxiabot List all DaemonSets in EKS with node selector conflicts
```

## 🏗️ AWS Integration & Networking

### AWS Load Balancer Controller
```
@opxiabot Show me all Application Load Balancers in EKS with SSL certificate issues
@opxiabot Find all Network Load Balancers in EKS with target group health problems
@opxiabot List all ingress resources in EKS with AWS Load Balancer Controller errors
@opxiabot Show me all target groups in EKS with unhealthy targets
```

### VPC & Networking
```
@opxiabot List all EKS clusters in AWS with VPC CNI IP exhaustion
@opxiabot Show me all subnets in EKS with insufficient IP addresses
@opxiabot Find all security groups in EKS with conflicting rules
@opxiabot List all EKS clusters in AWS with cross-AZ traffic costs
```

### EBS CSI Driver
```
@opxiabot Show me all persistent volumes in EKS with EBS attachment failures
@opxiabot Find all storage classes in EKS with EBS CSI provisioning errors
@opxiabot List all persistent volume claims in EKS with resize operations pending
@opxiabot Show me all EBS snapshots in EKS with backup policy violations
```

### EFS Integration
```
@opxiabot List all EFS access points in EKS with connection issues
@opxiabot Show me all persistent volumes in EKS using EFS with performance problems
@opxiabot Find all EFS file systems in EKS with throughput limitations
@opxiabot List all EFS CSI driver issues in EKS clusters
```

## 🚀 CI/CD & GitOps

### ArgoCD Operations
```
@opxiabot Show me all ArgoCD applications in EKS with sync failures
@opxiabot Find all ArgoCD repositories in EKS with authentication issues
@opxiabot List all ArgoCD applications in EKS with drift detection
@opxiabot Show me all ArgoCD projects in EKS with RBAC issues
```

### Flux Operations
```
@opxiabot List all Flux GitRepositories in EKS with sync errors
@opxiabot Show me all Flux Kustomizations in EKS with reconciliation failures
@opxiabot Find all Flux Helm releases in EKS with deployment issues
@opxiabot List all Flux sources in EKS with authentication problems
```

### Image Registry Integration
```
@opxiabot Show me all pods in EKS pulling images from public registries
@opxiabot Find all ECR repositories in EKS with vulnerability scan failures
@opxiabot List all image pull secrets in EKS with expired credentials
@opxiabot Show me all container images in EKS with known vulnerabilities
```