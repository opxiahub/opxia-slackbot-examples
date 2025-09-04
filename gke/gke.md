# GKE OpxiaBot Prompt Examples

This document contains example prompts for interacting with Google Kubernetes Engine (GKE) resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## GKE Cluster Management

### Cluster Health & Status
```
@opxiabot Show me all GKE clusters in GCP with unhealthy nodes
@opxiabot List all GKE clusters in GCP with deprecated Kubernetes versions
@opxiabot Find all GKE clusters in GCP with master upgrade available
@opxiabot Show me all GKE clusters in GCP with control plane issues
```

### Node Pool Operations
```
@opxiabot List all GKE node pools in GCP with nodes in NotReady state
@opxiabot Show me all GKE node pools in GCP with high resource utilization
@opxiabot Find all GKE node pools in GCP with autoscaling problems
@opxiabot List all GKE node pools in GCP with preemptible instance failures
```

### Cluster Autoscaling
```
@opxiabot Show me all GKE clusters in GCP with cluster autoscaler errors
@opxiabot Find all GKE clusters in GCP with horizontal pod autoscaler issues
@opxiabot List all GKE clusters in GCP with vertical pod autoscaler recommendations
@opxiabot Show me all GKE clusters in GCP with node pool scaling events
```

### GKE Autopilot vs Standard
```
@opxiabot List all standard GKE clusters in GCP eligible for Autopilot migration
@opxiabot Show me all GKE Autopilot clusters in GCP with resource optimization opportunities
@opxiabot Find all workloads in GKE incompatible with Autopilot mode
@opxiabot List all GKE clusters in GCP with mixed node pool configurations
```

## Security & Compliance

### Workload Security
```
@opxiabot Find all pods in GKE running with privileged containers
@opxiabot Show me all pods in GKE without security context constraints
@opxiabot List all pods in GKE with hostNetwork or hostPID enabled
@opxiabot Find all containers in GKE running as root user
```

### GKE Binary Authorization
```
@opxiabot Show me all GKE clusters in GCP without Binary Authorization enabled
@opxiabot List all container images in GKE that failed attestation
@opxiabot Find all pods in GKE with unsigned container images
@opxiabot Show me all Binary Authorization policies in GKE with violations
```

### Workload Identity & IAM
```
@opxiabot List all service accounts in GKE without Workload Identity enabled
@opxiabot Show me all pods in GKE using Google Cloud service account keys
@opxiabot Find all Kubernetes service accounts in GKE with overly broad IAM bindings
@opxiabot List all workloads in GKE with direct GCP API access
```

### Network Security
```
@opxiabot Show me all GKE clusters in GCP without private nodes enabled
@opxiabot Find all services in GKE exposing LoadBalancer to public internet
@opxiabot List all GKE clusters in GCP without authorized networks configured
@opxiabot Show me all Istio service mesh policies in GKE with misconfigurations
```

## Cost Optimization

### Compute Optimization
```
@opxiabot Show me all GKE node pools in GCP using only standard instances
@opxiabot Find all GKE clusters in GCP with underutilized nodes
@opxiabot List all workloads in GKE suitable for preemptible instances
@opxiabot Show me all GKE clusters in GCP with oversized machine types
```

### Storage Cost Management
```
@opxiabot List all persistent disks in GKE using standard SSD unnecessarily
@opxiabot Show me all persistent volumes in GKE with overprovisioned storage
@opxiabot Find all GKE clusters in GCP with unused persistent volumes
@opxiabot List all regional persistent disks in GKE with low availability requirements
```

### Network Cost Optimization
```
@opxiabot Show me all GKE clusters in GCP with high egress costs
@opxiabot Find all services in GKE using expensive load balancer types
@opxiabot List all GKE clusters in GCP with cross-zone traffic optimization opportunities
@opxiabot Show me all Cloud NAT usage in GKE with cost implications
```

### Right-sizing & Resource Optimization
```
@opxiabot Find all deployments in GKE with resource requests exceeding actual usage
@opxiabot Show me all pods in GKE with high memory requests but low usage
@opxiabot List all namespaces in GKE with resource quota underutilization
@opxiabot Find all workloads in GKE suitable for Spot VM migration
```

## Monitoring & Operations

### GKE Monitoring Integration
```
@opxiabot Show me all GKE clusters in GCP without Google Cloud Monitoring enabled
@opxiabot Find all GKE clusters in GCP with logging configuration issues
@opxiabot List all custom metrics in GKE with collection problems
@opxiabot Show me all GKE clusters in GCP with monitoring alerting gaps
```

### Container & Pod Health
```
@opxiabot List all pods in GKE with high CPU throttling
@opxiabot Show me all containers in GKE with frequent restarts
@opxiabot Find all pods in GKE stuck in pending or unknown state
@opxiabot List all deployments in GKE with readiness probe failures
```

### Performance Monitoring
```
@opxiabot Show me all services in GKE with high latency metrics
@opxiabot Find all ingress controllers in GKE with error rate spikes
@opxiabot List all horizontal pod autoscalers in GKE with scaling delays
@opxiabot Show me all persistent volumes in GKE with I/O performance issues
```

### Cluster Operations
```
@opxiabot List all GKE clusters in GCP with DNS resolution problems
@opxiabot Show me all GKE clusters in GCP with network connectivity issues
@opxiabot Find all add-ons in GKE with upgrade or configuration problems
@opxiabot List all GKE clusters in GCP with certificate expiration warnings
```

## Workload Management

### Application Deployment
```
@opxiabot Show me all deployments in GKE using deprecated API versions
@opxiabot Find all deployments in GKE with image pull policy issues
@opxiabot List all rolling updates in GKE that are stuck or failed
@opxiabot Show me all deployments in GKE without proper health checks
```

### StatefulSet Management
```
@opxiabot List all StatefulSets in GKE with persistent volume issues
@opxiabot Show me all StatefulSets in GKE with pod management problems
@opxiabot Find all StatefulSets in GKE with headless service configuration errors
@opxiabot List all StatefulSets in GKE with storage class compatibility issues
```

### Job & CronJob Operations
```
@opxiabot Show me all failed jobs in GKE from the past week
@opxiabot Find all CronJobs in GKE with missed execution schedules
@opxiabot List all jobs in GKE with resource limit exceeded errors
@opxiabot Show me all CronJobs in GKE with suspend or cleanup issues
```

### DaemonSet Operations
```
@opxiabot List all DaemonSets in GKE not running on all required nodes
@opxiabot Show me all DaemonSets in GKE with node affinity conflicts
@opxiabot Find all DaemonSets in GKE with update strategy problems
@opxiabot List all DaemonSets in GKE with resource constraint violations
```

## Google Cloud Integration

### Load Balancer Integration
```
@opxiabot Show me all Google Cloud Load Balancers for GKE with backend failures
@opxiabot Find all ingress resources in GKE with SSL certificate issues
@opxiabot List all services in GKE with load balancer provisioning errors
@opxiabot Show me all Cloud Armor policies in GKE with configuration problems
```

### Persistent Storage
```
@opxiabot List all Compute Engine persistent disks in GKE with attachment errors
@opxiabot Show me all Filestore instances in GKE with connectivity issues
@opxiabot Find all persistent volume claims in GKE with provisioning failures
@opxiabot List all storage classes in GKE with deprecated parameters
```

### Networking & VPC
```
@opxiabot Show me all VPC-native GKE clusters with IP address exhaustion
@opxiabot Find all GKE clusters in GCP with VPC firewall rule conflicts
@opxiabot List all Private Google Access configurations in GKE with issues
@opxiabot Show me all subnet secondary ranges in GKE approaching capacity
```

### Container Registry Integration
```
@opxiabot List all container images in GKE pulled from unsecured registries
@opxiabot Show me all Artifact Registry repositories in GKE with access issues
@opxiabot Find all pods in GKE with image pull secrets configuration problems
@opxiabot List all container images in GKE with vulnerability scan failures
```

## Advanced GKE Features

### GKE Enterprise (Anthos)
```
@opxiabot Show me all Anthos clusters in GCP with fleet management issues
@opxiabot Find all Anthos Service Mesh configurations in GKE with problems
@opxiabot List all Anthos Config Management policies in GKE with sync failures
@opxiabot Show me all multi-cluster services in GKE with endpoint discovery issues
```

### Istio Service Mesh
```
@opxiabot List all Istio sidecar injections in GKE with failures
@opxiabot Show me all virtual services in GKE with traffic routing problems
@opxiabot Find all destination rules in GKE with load balancing issues
@opxiabot List all Istio gateways in GKE with certificate or TLS problems
```

### Config Connector
```
@opxiabot Show me all Config Connector resources in GKE with reconciliation errors
@opxiabot Find all Google Cloud resources managed by Config Connector with drift
@opxiabot List all Config Connector CRDs in GKE with version compatibility issues
@opxiabot Show me all IAM policies managed by Config Connector with violations
```

### Backup for GKE
```
@opxiabot List all GKE clusters in GCP without backup plans configured
@opxiabot Show me all Backup for GKE jobs with recent failures
@opxiabot Find all persistent volumes in GKE without backup coverage
@opxiabot List all backup restore operations in GKE with errors
```