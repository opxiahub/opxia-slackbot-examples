# EKS Opxia Slackbot Prompt Examples

This document contains example prompts for interacting with Kubernetes resources inside EKS clusters using Opxia Slackbot. All prompts start with `@opxiabot` followed by your request. These operations are performed using kubectl and focus on resources within the cluster.

## Pod Management

### Pod Health & Status
```
@opxiabot Show me all pods with high memory consumption in EKS cluster
@opxiabot Find all containers with restart count above 10 in EKS cluster
@opxiabot List all pods stuck in CrashLoopBackOff state in EKS cluster
@opxiabot Show me all pods with image pull errors in EKS cluster
@opxiabot Find all pods with pending state for over 5 minutes in EKS cluster
@opxiabot List all pods without resource limits defined in EKS cluster
```

### Pod Security Standards
```
@opxiabot Find all pods running with privileged security context in EKS cluster
@opxiabot Show me all pods without security context defined in EKS cluster
@opxiabot List all pods running as root user in EKS cluster
@opxiabot Find all pods with hostNetwork enabled in EKS cluster
@opxiabot Show me all pods mounting AWS credentials as volumes in EKS cluster
@opxiabot List all pods using default service account in EKS cluster
```

## Workload Management

### Deployment Management
```
@opxiabot Show me all deployments with image vulnerabilities in EKS cluster
@opxiabot Find all deployments using images without tags in EKS cluster
@opxiabot List all deployments with missing health checks in EKS cluster
@opxiabot Show me all deployments with zero downtime deployment issues in EKS cluster
@opxiabot Find all deployments with rolling update timeouts in EKS cluster
@opxiabot List all deployments with mismatched desired and actual replicas in EKS cluster
```

### StatefulSet Operations
```
@opxiabot List all StatefulSets with persistent volume claim errors in EKS cluster
@opxiabot Show me all StatefulSets with pod ordering issues in EKS cluster
@opxiabot Find all StatefulSets with storage expansion problems in EKS cluster
@opxiabot List all StatefulSets with backup failures in EKS cluster
@opxiabot Show me all StatefulSets with headless service configuration errors in EKS cluster
```

### Job & CronJob Management
```
@opxiabot Show me all failed jobs from the last 7 days in EKS cluster
@opxiabot Find all CronJobs with schedule conflicts in EKS cluster
@opxiabot List all jobs exceeding execution time limits in EKS cluster
@opxiabot Show me all CronJobs with cleanup policy issues in EKS cluster
@opxiabot Find all jobs with resource constraint issues in EKS cluster
```

### DaemonSet Operations
```
@opxiabot List all DaemonSets with pods not running on all nodes in EKS cluster
@opxiabot Show me all DaemonSets with update strategy problems in EKS cluster
@opxiabot Find all DaemonSets with resource constraint issues in EKS cluster
@opxiabot List all DaemonSets with node selector conflicts in EKS cluster
```

## Services & Networking

### Service Operations
```
@opxiabot Show me all services with unhealthy endpoints in EKS cluster
@opxiabot Find all services with LoadBalancer type exposed publicly in EKS cluster
@opxiabot List all headless services with endpoint discovery problems in EKS cluster
@opxiabot Show me all services with endpoint readiness issues in EKS cluster
```

### Ingress & Load Balancing
```
@opxiabot List all ingress resources with AWS Load Balancer Controller errors in EKS cluster
@opxiabot Show me all ingress controllers with high error rates in EKS cluster
@opxiabot Find all ingress resources with SSL certificate issues in EKS cluster
@opxiabot List all ingress controllers with certificate problems in EKS cluster
```

### Network Policies
```
@opxiabot Show me all pods without network policies applied in EKS cluster
@opxiabot Find all network policies that allow all traffic in EKS cluster
@opxiabot List all services with unrestricted network access in EKS cluster
```

## Storage & Persistent Volumes

### Persistent Volume Claims
```
@opxiabot List all persistent volume claims with pending status in EKS cluster
@opxiabot Show me all persistent volume claims with resize operations pending in EKS cluster
@opxiabot Find all persistent volumes with EBS attachment failures in EKS cluster
@opxiabot List all storage classes with EBS CSI provisioning errors in EKS cluster
@opxiabot Show me all persistent volume claims with overprovisioned storage in EKS cluster
```

### EFS Integration
```
@opxiabot List all EFS access points with connection issues in EKS cluster
@opxiabot Show me all persistent volumes using EFS with performance problems in EKS cluster
@opxiabot Find all EFS CSI driver issues in EKS cluster
```

## ConfigMaps & Secrets

### Secret Management
```
@opxiabot Show me all secrets stored as plain text in EKS cluster
@opxiabot Find all pods mounting AWS credentials as volumes in EKS cluster
@opxiabot List all external-secrets operators with sync failures in EKS cluster
@opxiabot Show me all secrets not being used by any pods in EKS cluster
```

### Configuration Management
```
@opxiabot Find all ConfigMaps containing sensitive information in EKS cluster
@opxiabot Show me all ConfigMaps not mounted by any pods in EKS cluster
@opxiabot List all pods with configuration drift issues in EKS cluster
```

## Resource Optimization

### Resource Usage Analysis
```
@opxiabot Find all deployments with high resource requests but low usage in EKS cluster
@opxiabot Show me all pods with CPU requests exceeding usage by 50% in EKS cluster
@opxiabot List all namespaces with resource quota underutilization in EKS cluster
@opxiabot Find all workloads suitable for Fargate migration in EKS cluster
```

### Horizontal Pod Autoscaler
```
@opxiabot List all horizontal pod autoscalers with scaling failures in EKS cluster
@opxiabot Show me all horizontal pod autoscalers with scaling events in EKS cluster
@opxiabot Find all horizontal pod autoscalers with metric collection issues in EKS cluster
@opxiabot List all horizontal pod autoscalers with scaling delays in EKS cluster
```

### Vertical Pod Autoscaler
```
@opxiabot Show me all vertical pod autoscaler recommendations in EKS cluster
@opxiabot Find all workloads with VPA recommendations in EKS cluster
@opxiabot List all pods with VPA policy violations in EKS cluster
```

## RBAC & Security

### AWS IAM & RBAC
```
@opxiabot Show me all service accounts with IAM roles for service accounts (IRSA) issues in EKS cluster
@opxiabot Find all RBAC policies with cluster-admin permissions in EKS cluster
@opxiabot List all service accounts without proper IAM role binding in EKS cluster
@opxiabot Show me all pods using AWS credentials directly in EKS cluster
```

### Role-Based Access Control
```
@opxiabot List all role bindings with overly broad permissions in EKS cluster
@opxiabot Show me all cluster role bindings with unnecessary access in EKS cluster
@opxiabot Find all users with direct cluster access in EKS cluster
```

## Monitoring & Observability

### Container Monitoring
```
@opxiabot Show me all pods with high CPU throttling in EKS cluster
@opxiabot Find all containers with frequent restarts in EKS cluster
@opxiabot List all pods with memory pressure warnings in EKS cluster
@opxiabot Show me all containers with OOMKilled events in EKS cluster
```

### Application Performance
```
@opxiabot List all services with high latency metrics in EKS cluster
@opxiabot Show me all pods with readiness probe failures in EKS cluster
@opxiabot Find all pods with liveness probe failures in EKS cluster
@opxiabot List all applications with startup probe issues in EKS cluster
```

### Logging
```
@opxiabot List all containers with high log volume in EKS cluster
@opxiabot Show me all pods with error logs in last hour in EKS cluster
@opxiabot Find all containers with logging driver issues in EKS cluster
@opxiabot List all pods without log rotation configured in EKS cluster
```

## GitOps & CI/CD

### ArgoCD Operations
```
@opxiabot Show me all ArgoCD applications with sync failures in EKS cluster
@opxiabot Find all ArgoCD applications with drift detection in EKS cluster
@opxiabot List all ArgoCD applications with out-of-sync resources in EKS cluster
@opxiabot Show me all ArgoCD projects with RBAC issues in EKS cluster
```

### Flux Operations
```
@opxiabot List all Flux GitRepositories with sync errors in EKS cluster
@opxiabot Show me all Flux Kustomizations with reconciliation failures in EKS cluster
@opxiabot Find all Flux Helm releases with deployment issues in EKS cluster
@opxiabot List all Flux sources with authentication problems in EKS cluster
```

### Container Registry
```
@opxiabot Show me all pods pulling images from public registries in EKS cluster
@opxiabot Find all image pull secrets with expired credentials in EKS cluster
@opxiabot List all container images with known vulnerabilities in EKS cluster
@opxiabot Show me all pods with image pull policy issues in EKS cluster
```