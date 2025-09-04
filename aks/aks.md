# AKS OpxiaBot Prompt Examples

This document contains example prompts for interacting with Azure Kubernetes Service (AKS) resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## AKS Cluster Management

### Cluster Health & Status
```
@opxiabot Show me all AKS clusters in Azure with unhealthy nodes
@opxiabot List all AKS clusters in Azure with deprecated Kubernetes versions
@opxiabot Find all AKS clusters in Azure with node upgrade available
@opxiabot Show me all AKS clusters in Azure with system pod failures
```

### Node Pool Operations
```
@opxiabot List all AKS node pools in Azure with high CPU utilization
@opxiabot Show me all AKS node pools in Azure with nodes in NotReady state
@opxiabot Find all AKS node pools in Azure with autoscaling disabled
@opxiabot List all AKS node pools in Azure approaching maximum node count
```

### Cluster Scaling & Performance
```
@opxiabot Show me all AKS clusters in Azure with cluster autoscaler issues
@opxiabot Find all AKS clusters in Azure with horizontal pod autoscaler failures
@opxiabot List all AKS clusters in Azure with resource quota exceeded
@opxiabot Show me all AKS clusters in Azure with pod eviction events
```

### Cluster Configuration
```
@opxiabot List all AKS clusters in Azure without Azure Active Directory integration
@opxiabot Show me all AKS clusters in Azure without network policies enabled
@opxiabot Find all AKS clusters in Azure with public API server endpoint
@opxiabot List all AKS clusters in Azure without Azure Policy add-on enabled
```

## Security & Compliance

### Pod Security
```
@opxiabot Find all pods in AKS running with privileged mode enabled
@opxiabot Show me all pods in AKS without resource limits defined
@opxiabot List all pods in AKS running as root user
@opxiabot Find all pods in AKS with hostNetwork or hostPID enabled
```

### RBAC & Access Control
```
@opxiabot Show me all service accounts in AKS with cluster-admin role binding
@opxiabot List all RBAC policies in AKS with overly broad permissions
@opxiabot Find all users in AKS with direct cluster access
@opxiabot Show me all pods in AKS using default service account
```

### Network Security
```
@opxiabot List all services in AKS with LoadBalancer type exposed to internet
@opxiabot Show me all ingress controllers in AKS without TLS configuration
@opxiabot Find all network policies in AKS that allow all traffic
@opxiabot List all pods in AKS with unrestricted network access
```

### Secret & Config Management
```
@opxiabot Show me all secrets in AKS that are base64 encoded only
@opxiabot Find all ConfigMaps in AKS containing sensitive information
@opxiabot List all pods in AKS mounting secrets as environment variables
@opxiabot Show me all Azure Key Vault integrations in AKS with access issues
```

## Cost Optimization

### Resource Utilization
```
@opxiabot Show me all AKS node pools in Azure with low utilization
@opxiabot Find all AKS clusters in Azure with overprovisioned nodes
@opxiabot List all pods in AKS with high resource requests but low usage
@opxiabot Show me all AKS clusters in Azure with unused node pools
```

### Right-sizing Opportunities
```
@opxiabot Find all deployments in AKS that can be right-sized
@opxiabot Show me all StatefulSets in AKS with oversized persistent volumes
@opxiabot List all services in AKS with expensive load balancer types
@opxiabot Find all AKS clusters in Azure using premium storage unnecessarily
```

### Spot Instance Optimization
```
@opxiabot Show me all AKS node pools in Azure eligible for spot instances
@opxiabot List all AKS clusters in Azure not using spot instances for non-critical workloads
@opxiabot Find all workloads in AKS that can tolerate interruptions
@opxiabot Show me all node pools in AKS with mixed pricing models
```

### Storage Cost Optimization
```
@opxiabot List all persistent volumes in AKS with premium storage
@opxiabot Show me all persistent volume claims in AKS with overprovisioned storage
@opxiabot Find all AKS clusters in Azure with unused persistent volumes
@opxiabot List all storage classes in AKS with expensive replication settings
```

## Monitoring & Operations

### Pod & Container Monitoring
```
@opxiabot Show me all pods in AKS with high memory usage
@opxiabot Find all containers in AKS with restart count above 5
@opxiabot List all pods in AKS with CrashLoopBackOff status
@opxiabot Show me all pods in AKS with pending state for over 5 minutes
```

### Application Performance
```
@opxiabot List all deployments in AKS with rolling update failures
@opxiabot Show me all services in AKS with endpoint readiness issues
@opxiabot Find all ingress resources in AKS with 5xx error rates above 1%
@opxiabot List all horizontal pod autoscalers in AKS with scaling events
```

### Cluster Monitoring
```
@opxiabot Show me all AKS clusters in Azure with API server latency issues
@opxiabot Find all AKS clusters in Azure with etcd performance problems
@opxiabot List all AKS clusters in Azure with DNS resolution failures
@opxiabot Show me all AKS clusters in Azure with kubelet issues
```

### Log & Metrics Analysis
```
@opxiabot List all containers in AKS with high log volume
@opxiabot Show me all pods in AKS with error logs in last hour
@opxiabot Find all AKS clusters in Azure with Container Insights disabled
@opxiabot List all custom metrics in AKS with missing data points
```

## Workload Management

### Deployment Operations
```
@opxiabot Show me all deployments in AKS with zero replicas
@opxiabot Find all deployments in AKS with mismatched desired and actual replicas
@opxiabot List all deployments in AKS with image pull errors
@opxiabot Show me all deployments in AKS using latest image tag
```

### StatefulSet Operations
```
@opxiabot List all StatefulSets in AKS with pod management policy issues
@opxiabot Show me all StatefulSets in AKS with persistent volume claim problems
@opxiabot Find all StatefulSets in AKS with rolling update stuck
@opxiabot List all StatefulSets in AKS with headless service issues
```

### Job & CronJob Operations
```
@opxiabot Show me all failed jobs in AKS from last 24 hours
@opxiabot Find all CronJobs in AKS with missed schedules
@opxiabot List all jobs in AKS with long completion times
@opxiabot Show me all CronJobs in AKS with overlapping executions
```

### Service Mesh Operations
```
@opxiabot List all Istio sidecars in AKS with injection failures
@opxiabot Show me all service mesh policies in AKS with configuration errors
@opxiabot Find all virtual services in AKS with routing issues
@opxiabot List all destination rules in AKS with load balancing problems
```

## Infrastructure & Networking

### Load Balancer Operations
```
@opxiabot Show me all Azure Load Balancers for AKS with unhealthy backend pools
@opxiabot Find all Application Gateway integrations in AKS with SSL issues
@opxiabot List all AKS services with Azure Load Balancer annotation issues
@opxiabot Show me all ingress controllers in AKS with certificate problems
```

### DNS & Service Discovery
```
@opxiabot List all CoreDNS pods in AKS with performance issues
@opxiabot Show me all services in AKS with endpoint discovery problems
@opxiabot Find all ExternalDNS configurations in AKS with sync failures
@opxiabot List all headless services in AKS with endpoint registration issues
```

### Storage Operations
```
@opxiabot Show me all Azure Disk attachments in AKS with mount failures
@opxiabot Find all Azure File shares in AKS with permission issues
@opxiabot List all persistent volume claims in AKS with pending status
@opxiabot Show me all storage classes in AKS with provisioning errors
```

### Backup & Disaster Recovery
```
@opxiabot List all AKS clusters in Azure without backup solutions
@opxiabot Show me all Velero backup jobs in AKS with failures
@opxiabot Find all persistent volumes in AKS without snapshot policies
@opxiabot List all AKS clusters in Azure missing disaster recovery setup
```