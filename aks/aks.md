# AKS OpxiaBot Prompt Examples

This document contains example prompts for interacting with Kubernetes resources inside AKS clusters using OpxiaBot. All prompts start with `@opxiabot` followed by your request. These operations are performed using kubectl and focus on resources within the cluster.

## Pod Management

### Pod Health & Status
```
@opxiabot Show me all pods with high memory usage in AKS cluster
@opxiabot Find all containers with restart count above 5 in AKS cluster
@opxiabot List all pods stuck in CrashLoopBackOff state in AKS cluster
@opxiabot Show me all pods with pending state for over 5 minutes in AKS cluster
@opxiabot Find all pods without resource limits defined in AKS cluster
@opxiabot List all pods running as root user in AKS cluster
```

### Pod Security
```
@opxiabot Find all pods running with privileged mode enabled in AKS cluster
@opxiabot Show me all pods with hostNetwork or hostPID enabled in AKS cluster
@opxiabot List all pods using default service account in AKS cluster
@opxiabot Find all pods mounting secrets as environment variables in AKS cluster
@opxiabot Show me all pods without security context defined in AKS cluster
```

## Workload Management

### Deployments
```
@opxiabot Show me all deployments with zero replicas in AKS cluster
@opxiabot Find all deployments with mismatched desired and actual replicas in AKS cluster
@opxiabot List all deployments with image pull errors in AKS cluster
@opxiabot Show me all deployments using latest image tag in AKS cluster
@opxiabot Find all deployments with rolling update failures in AKS cluster
@opxiabot List all deployments without proper health checks in AKS cluster
```

### StatefulSets
```
@opxiabot List all StatefulSets with pod management policy issues in AKS cluster
@opxiabot Show me all StatefulSets with persistent volume claim problems in AKS cluster
@opxiabot Find all StatefulSets with rolling update stuck in AKS cluster
@opxiabot List all StatefulSets with headless service issues in AKS cluster
@opxiabot Show me all StatefulSets with oversized persistent volumes in AKS cluster
```

### DaemonSets
```
@opxiabot List all DaemonSets not running on all required nodes in AKS cluster
@opxiabot Show me all DaemonSets with update strategy problems in AKS cluster
@opxiabot Find all DaemonSets with resource constraint issues in AKS cluster
@opxiabot List all DaemonSets with node selector conflicts in AKS cluster
```

## Jobs & CronJobs

### Job Operations
```
@opxiabot Show me all failed jobs from last 24 hours in AKS cluster
@opxiabot Find all jobs with long completion times in AKS cluster
@opxiabot List all jobs exceeding execution time limits in AKS cluster
@opxiabot Show me all jobs with resource limit exceeded errors in AKS cluster
```

### CronJob Operations
```
@opxiabot Find all CronJobs with missed schedules in AKS cluster
@opxiabot List all CronJobs with overlapping executions in AKS cluster
@opxiabot Show me all CronJobs with cleanup policy issues in AKS cluster
@opxiabot Find all CronJobs with suspend or cleanup issues in AKS cluster
```

## Services & Networking

### Service Operations
```
@opxiabot List all services with endpoint readiness issues in AKS cluster
@opxiabot Show me all services with LoadBalancer type exposed to internet in AKS cluster
@opxiabot Find all headless services with endpoint registration issues in AKS cluster
@opxiabot List all services with unhealthy endpoints in AKS cluster
```

### Ingress & Network Policies
```
@opxiabot Show me all ingress controllers without TLS configuration in AKS cluster
@opxiabot Find all ingress resources with 5xx error rates above 1% in AKS cluster
@opxiabot List all network policies that allow all traffic in AKS cluster
@opxiabot Show me all pods without network policies applied in AKS cluster
```

## Storage & Persistent Volumes

### Persistent Volume Claims
```
@opxiabot List all persistent volume claims with pending status in AKS cluster
@opxiabot Show me all persistent volume claims with overprovisioned storage in AKS cluster
@opxiabot Find all persistent volume claims with resize operations pending in AKS cluster
@opxiabot List all persistent volumes without recent snapshots in AKS cluster
```

### Storage Classes
```
@opxiabot Show me all storage classes with expensive replication settings in AKS cluster
@opxiabot Find all storage classes with provisioning errors in AKS cluster
@opxiabot List all persistent volumes using premium storage unnecessarily in AKS cluster
```

## ConfigMaps & Secrets

### Configuration Management
```
@opxiabot Show me all secrets that are base64 encoded only in AKS cluster
@opxiabot Find all ConfigMaps containing sensitive information in AKS cluster
@opxiabot List all secrets not being used by any pods in AKS cluster
@opxiabot Show me all ConfigMaps not mounted by any pods in AKS cluster
```

## Resource Optimization

### Resource Usage
```
@opxiabot Find all pods with high resource requests but low usage in AKS cluster
@opxiabot Show me all pods with CPU requests exceeding usage by 50% in AKS cluster
@opxiabot List all namespaces with resource quota underutilization in AKS cluster
@opxiabot Find all deployments that can be right-sized in AKS cluster
```

### Horizontal Pod Autoscaler
```
@opxiabot List all horizontal pod autoscalers with scaling events in AKS cluster
@opxiabot Show me all horizontal pod autoscalers with scaling failures in AKS cluster
@opxiabot Find all horizontal pod autoscalers with scaling delays in AKS cluster
@opxiabot List all horizontal pod autoscalers with metric collection issues in AKS cluster
```

## RBAC & Security

### Role-Based Access Control
```
@opxiabot Show me all service accounts with cluster-admin role binding in AKS cluster
@opxiabot List all RBAC policies with overly broad permissions in AKS cluster
@opxiabot Find all users with direct cluster access in AKS cluster
@opxiabot Show me all role bindings with unnecessary permissions in AKS cluster
```

## Monitoring & Logs

### Container Logs
```
@opxiabot List all containers with high log volume in AKS cluster
@opxiabot Show me all pods with error logs in last hour in AKS cluster
@opxiabot Find all containers with logging configuration issues in AKS cluster
@opxiabot List all pods without log rotation configured in AKS cluster
```

### Resource Monitoring
```
@opxiabot Show me all pods with high CPU throttling in AKS cluster
@opxiabot Find all nodes with disk space above 80% in AKS cluster
@opxiabot List all pods with memory pressure warnings in AKS cluster
@opxiabot Show me all containers with frequent OOMKilled events in AKS cluster
```