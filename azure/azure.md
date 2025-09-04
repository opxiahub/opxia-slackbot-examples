# Azure OpxiaBot Prompt Examples

This document contains example prompts for interacting with Microsoft Azure resources using OpxiaBot. All prompts start with `@opxiabot` followed by your request.

## Security & Compliance

### Storage Security
```
@opxiabot Find all Storage Accounts in Azure with public blob access enabled
@opxiabot List all Storage Accounts in Azure without secure transfer required
@opxiabot Show me all Storage Accounts in Azure with shared access signature tokens
@opxiabot Find all Storage Accounts in Azure without firewall rules configured
```

### Virtual Machine Security
```
@opxiabot List all VMs in Azure with NSG rules allowing RDP from any source
@opxiabot Find all VMs in Azure with NSG rules allowing SSH from 0.0.0.0/0
@opxiabot Show me all VMs in Azure without Azure Security Center agent installed
@opxiabot List all VMs in Azure with outdated OS versions
```

### Key Management Security
```
@opxiabot Show me all Key Vaults in Azure without soft delete enabled
@opxiabot Find all Key Vaults in Azure with keys nearing expiration
@opxiabot List all Key Vaults in Azure without access policies properly configured
@opxiabot Show me all certificates in Azure Key Vault expiring in 30 days
```

### Database Security
```
@opxiabot Find all SQL Databases in Azure without transparent data encryption
@opxiabot List all SQL Databases in Azure with firewall allowing all Azure services
@opxiabot Show me all Cosmos DB accounts in Azure without encryption at rest
@opxiabot Find all SQL Databases in Azure without Advanced Threat Protection
```

### Network Security
```
@opxiabot List all Public IPs in Azure not associated with any resource
@opxiabot Find all Network Security Groups in Azure with default allow rules
@opxiabot Show me all VNets in Azure without DDoS protection enabled
@opxiabot List all Application Gateways in Azure with SSL policy issues
```

## Cost Optimization

### Compute Optimization
```
@opxiabot Show me all unattached Managed Disks in Azure
@opxiabot Find all VMs in Azure that are stopped but still incurring charges
@opxiabot List all VMs in Azure with low CPU utilization over 30 days
@opxiabot Show me all oversized VMs in Azure based on usage patterns
```

### Storage Optimization
```
@opxiabot List all snapshots in Azure older than 60 days
@opxiabot Find all Storage Accounts in Azure with hot tier data accessed infrequently
@opxiabot Show me all unattached Premium SSD disks in Azure
@opxiabot List all blob containers in Azure with lifecycle policies not configured
```

### Service Optimization
```
@opxiabot Show me all App Service Plans in Azure with zero apps
@opxiabot Find all SQL Databases in Azure using DTUs below 10% capacity
@opxiabot List all Azure Functions in Azure with low execution rates
@opxiabot Show me all Load Balancers in Azure with no backend pools
```

### Reserved Instance Optimization
```
@opxiabot Find all VMs in Azure that could benefit from Reserved Instances
@opxiabot Show me all unused Reserved Instances in Azure
@opxiabot List all expiring Reserved Instances in Azure
@opxiabot Find all SQL Databases in Azure eligible for reserved capacity
```

## Operations & Monitoring

### Application Gateway Operations
```
@opxiabot List all Application Gateways in Azure with unhealthy backend pools
@opxiabot Show me all Application Gateways in Azure with high error rates
@opxiabot Find all Application Gateways in Azure with SSL certificate issues
@opxiabot List all Application Gateways in Azure with WAF policy violations
```

### Virtual Machine Operations
```
@opxiabot Show me all VMs in Azure without Azure Monitor agent installed
@opxiabot Find all VMs in Azure with available OS updates
@opxiabot List all VMs in Azure with disk space above 80%
@opxiabot Show me all VMs in Azure with high memory utilization
```

### Storage Operations
```
@opxiabot Find all Storage Accounts in Azure approaching transaction limits
@opxiabot Show me all Storage Accounts in Azure with replication issues
@opxiabot List all Storage Accounts in Azure with backup job failures
@opxiabot Find all blob containers in Azure with access tier optimization opportunities
```

### Database Operations
```
@opxiabot Show me all SQL Databases in Azure with DTU usage above 80%
@opxiabot Find all Cosmos DB collections in Azure with throttling events
@opxiabot List all SQL Databases in Azure with long-running queries
@opxiabot Show me all database connections in Azure approaching connection limits
```

### Key Vault Operations
```
@opxiabot List all expired certificates in Azure Key Vault
@opxiabot Show me all Key Vaults in Azure with audit log issues
@opxiabot Find all secrets in Azure Key Vault that haven't been accessed in 90 days
@opxiabot List all Key Vaults in Azure with failed access attempts
```

### Service Health & Alerts
```
@opxiabot Show me all Azure services with active service health alerts
@opxiabot Find all resources in Azure with critical alerts
@opxiabot List all Action Groups in Azure with failed notifications
@opxiabot Show me all Log Analytics workspaces in Azure with high ingestion rates
```

## Resource Management

### Resource Group Management
```
@opxiabot Show me all empty Resource Groups in Azure
@opxiabot List all Resource Groups in Azure by cost
@opxiabot Find all Resource Groups in Azure missing required tags
@opxiabot Show me all Resource Groups in Azure with resources in different regions
```

### Subscription Management
```
@opxiabot List all subscriptions in Azure approaching spending limits
@opxiabot Show me all subscriptions in Azure with unused credits
@opxiabot Find all subscriptions in Azure with policy compliance issues
@opxiabot List all management groups in Azure with inconsistent policies
```

### Backup & Recovery
```
@opxiabot Show me all VMs in Azure without backup configured
@opxiabot Find all Recovery Services Vaults in Azure with failed backup jobs
@opxiabot List all VMs in Azure with backup retention policy violations
@opxiabot Show me all Site Recovery replications in Azure with issues
```

### Networking Operations
```
@opxiabot List all VNets in Azure with unused subnets
@opxiabot Show me all ExpressRoute circuits in Azure with low utilization
@opxiabot Find all VPN Gateways in Azure with connection issues
@opxiabot List all Traffic Manager profiles in Azure with unhealthy endpoints
```

## Infrastructure as Code

### ARM Template Operations
```
@opxiabot Show me all ARM template deployments in Azure that failed
@opxiabot Find all Resource Groups in Azure created from ARM templates
@opxiabot List all ARM templates in Azure with outdated API versions
@opxiabot Show me all custom ARM template functions in Azure
```

### Policy & Governance
```
@opxiabot List all Azure Policy assignments with non-compliant resources
@opxiabot Show me all resources in Azure violating naming conventions
@opxiabot Find all Azure Blueprints in Azure with assignment issues
@opxiabot List all management groups in Azure with policy exemptions
```

### DevOps Integration
```
@opxiabot Show me all Azure DevOps pipelines with recent failures
@opxiabot Find all App Services in Azure with deployment slot issues
@opxiabot List all Container Registries in Azure with vulnerability scans
@opxiabot Show me all AKS clusters in Azure with upgrade recommendations
```