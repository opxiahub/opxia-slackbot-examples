# GKE OpxiaBot Prompt Examples

This document contains example prompts for interacting with Kubernetes resources inside GKE clusters using OpxiaBot. All prompts start with `@opxiabot` followed by your request. These operations are performed using kubectl and focus on resources within the cluster.

## Pod Management

### Pod Health & Status
```
@opxiabot Show me all pods with high CPU throttling in GKE cluster
@opxiabot Find all containers with frequent restarts in GKE cluster
@opxiabot List all pods stuck in pending or unknown state in GKE cluster
@opxiabot Show me all pods with readiness probe failures in GKE cluster
@opxiabot Find all pods without resource limits defined in GKE cluster
@opxiabot List all pods running as root user in GKE cluster
```

### Workload Security
```
@opxiabot Find all pods running with privileged containers in GKE cluster
@opxiabot Show me all pods without security context constraints in GKE cluster
@opxiabot List all pods with hostNetwork or hostPID enabled in GKE cluster
@opxiabot Find all containers running as root user in GKE cluster
@opxiabot Show me all pods using Google Cloud service account keys in GKE cluster
@opxiabot List all pods without Workload Identity enabled in GKE cluster
```

## Workload Management

### Application Deployment
```
@opxiabot Show me all deployments using deprecated API versions in GKE cluster
@opxiabot Find all deployments with image pull policy issues in GKE cluster
@opxiabot List all rolling updates that are stuck or failed in GKE cluster
@opxiabot Show me all deployments without proper health checks in GKE cluster
@opxiabot Find all deployments with zero replicas in GKE cluster
@opxiabot List all deployments with image vulnerabilities in GKE cluster
```

### StatefulSet Management
```
@opxiabot List all StatefulSets with persistent volume issues in GKE cluster
@opxiabot Show me all StatefulSets with pod management problems in GKE cluster
@opxiabot Find all StatefulSets with headless service configuration errors in GKE cluster
@opxiabot List all StatefulSets with storage class compatibility issues in GKE cluster
@opxiabot Show me all StatefulSets with backup failures in GKE cluster
```

### Job & CronJob Operations
```
@opxiabot Show me all failed jobs from the past week in GKE cluster
@opxiabot Find all CronJobs with missed execution schedules in GKE cluster
@opxiabot List all jobs with resource limit exceeded errors in GKE cluster
@opxiabot Show me all CronJobs with suspend or cleanup issues in GKE cluster
@opxiabot Find all jobs exceeding execution time limits in GKE cluster
```

### DaemonSet Operations
```
@opxiabot List all DaemonSets not running on all required nodes in GKE cluster
@opxiabot Show me all DaemonSets with node affinity conflicts in GKE cluster
@opxiabot Find all DaemonSets with update strategy problems in GKE cluster
@opxiabot List all DaemonSets with resource constraint violations in GKE cluster
```

## Services & Networking

### Service Operations
```
@opxiabot Show me all services with high latency metrics in GKE cluster
@opxiabot Find all services with endpoint readiness issues in GKE cluster
@opxiabot List all services with load balancer provisioning errors in GKE cluster
@opxiabot Show me all headless services with endpoint registration issues in GKE cluster
@opxiabot Find all services exposing LoadBalancer to public internet in GKE cluster
```

### Ingress & Load Balancing
```
@opxiabot Find all ingress resources with SSL certificate issues in GKE cluster
@opxiabot Show me all ingress controllers with high error rates in GKE cluster
@opxiabot List all ingress resources with backend service failures in GKE cluster
@opxiabot Find all ingress controllers with certificate or TLS problems in GKE cluster
```

### Network Policies
```
@opxiabot Show me all pods without network policies applied in GKE cluster
@opxiabot Find all network policies that allow all traffic in GKE cluster
@opxiabot List all services with unrestricted network access in GKE cluster
```

## Storage & Persistent Volumes

### Persistent Storage
```
@opxiabot List all persistent volume claims with provisioning failures in GKE cluster
@opxiabot Show me all persistent volumes with I/O performance issues in GKE cluster
@opxiabot Find all persistent volume claims with resize operations pending in GKE cluster
@opxiabot List all storage classes with deprecated parameters in GKE cluster
@opxiabot Show me all persistent volume claims with overprovisioned storage in GKE cluster
```

### Storage Optimization
```
@opxiabot Find all persistent volumes using standard SSD unnecessarily in GKE cluster
@opxiabot Show me all regional persistent disks with low availability requirements in GKE cluster
@opxiabot List all persistent volumes with expensive storage classes in GKE cluster
```

## ConfigMaps & Secrets

### Configuration Management
```
@opxiabot Show me all ConfigMaps not mounted by any pods in GKE cluster
@opxiabot Find all ConfigMaps containing sensitive information in GKE cluster
@opxiabot List all pods with configuration drift issues in GKE cluster
@opxiabot Show me all ConfigMaps with large sizes affecting pod startup in GKE cluster
```

### Secret Management
```
@opxiabot Find all secrets not being used by any pods in GKE cluster
@opxiabot Show me all pods mounting secrets as environment variables in GKE cluster
@opxiabot List all external-secrets operators with sync failures in GKE cluster
@opxiabot Find all secrets without proper rotation policies in GKE cluster
```

## Resource Optimization

### Resource Usage Analysis
```
@opxiabot Find all deployments with resource requests exceeding actual usage in GKE cluster
@opxiabot Show me all pods with high memory requests but low usage in GKE cluster
@opxiabot List all namespaces with resource quota underutilization in GKE cluster
@opxiabot Find all workloads suitable for Spot VM migration in GKE cluster
```

### Horizontal Pod Autoscaler
```
@opxiabot List all horizontal pod autoscalers with scaling delays in GKE cluster
@opxiabot Show me all horizontal pod autoscalers with metric collection problems in GKE cluster
@opxiabot Find all horizontal pod autoscalers with scaling failures in GKE cluster
@opxiabot List all horizontal pod autoscalers with custom metrics issues in GKE cluster
```

### Vertical Pod Autoscaler
```
@opxiabot Show me all vertical pod autoscaler recommendations in GKE cluster
@opxiabot Find all workloads with VPA optimization opportunities in GKE cluster
@opxiabot List all pods with VPA policy violations in GKE cluster
```

## RBAC & Security

### Workload Identity & IAM
```
@opxiabot List all service accounts without Workload Identity enabled in GKE cluster
@opxiabot Find all Kubernetes service accounts with overly broad IAM bindings in GKE cluster
@opxiabot Show me all workloads with direct GCP API access in GKE cluster
@opxiabot List all pods using service account keys instead of Workload Identity in GKE cluster
```

### Role-Based Access Control
```
@opxiabot Show me all role bindings with overly broad permissions in GKE cluster
@opxiabot Find all cluster role bindings with unnecessary access in GKE cluster
@opxiabot List all service accounts with cluster-admin privileges in GKE cluster
@opxiabot Show me all users with direct cluster access in GKE cluster
```

## Monitoring & Observability

### Container Performance
```
@opxiabot Show me all containers with high memory usage in GKE cluster
@opxiabot Find all pods with disk space above 80% in GKE cluster
@opxiabot List all pods with memory pressure warnings in GKE cluster
@opxiabot Show me all containers with frequent OOMKilled events in GKE cluster
```

### Application Health
```
@opxiabot List all deployments with readiness probe failures in GKE cluster
@opxiabot Show me all pods with liveness probe failures in GKE cluster
@opxiabot Find all applications with startup probe issues in GKE cluster
@opxiabot List all services with health check failures in GKE cluster
```

### Logging & Metrics
```
@opxiabot List all containers with high log volume in GKE cluster
@opxiabot Show me all pods with error logs in last hour in GKE cluster
@opxiabot Find all containers with logging configuration issues in GKE cluster
@opxiabot List all custom metrics with collection problems in GKE cluster
```

## Advanced GKE Features

### Binary Authorization
```
@opxiabot List all container images that failed attestation in GKE cluster
@opxiabot Show me all pods with unsigned container images in GKE cluster
@opxiabot Find all Binary Authorization policy violations in GKE cluster
```

### Istio Service Mesh
```
@opxiabot List all Istio sidecar injections with failures in GKE cluster
@opxiabot Show me all virtual services with traffic routing problems in GKE cluster
@opxiabot Find all destination rules with load balancing issues in GKE cluster
@opxiabot List all Istio gateways with certificate or TLS problems in GKE cluster
```

### Config Connector
```
@opxiabot Show me all Config Connector resources with reconciliation errors in GKE cluster
@opxiabot Find all Google Cloud resources managed by Config Connector with drift in GKE cluster
@opxiabot List all Config Connector CRDs with version compatibility issues in GKE cluster
```

### Anthos Service Mesh
```
@opxiabot Show me all Anthos Service Mesh configurations with problems in GKE cluster
@opxiabot Find all multi-cluster services with endpoint discovery issues in GKE cluster
@opxiabot List all Anthos Config Management policies with sync failures in GKE cluster
```

## GitOps & CI/CD

### GitOps Operations
```
@opxiabot Show me all GitOps applications with sync failures in GKE cluster
@opxiabot Find all GitOps repositories with authentication issues in GKE cluster
@opxiabot List all GitOps applications with drift detection in GKE cluster
```

### Container Registry
```
@opxiabot Show me all pods pulling images from unsecured registries in GKE cluster
@opxiabot Find all image pull secrets with expired credentials in GKE cluster
@opxiabot List all container images with vulnerability scan failures in GKE cluster
@opxiabot Show me all pods with image pull policy issues in GKE cluster
```