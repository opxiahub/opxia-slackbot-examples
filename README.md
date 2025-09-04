# OpxiaBot Prompt Examples

Welcome to the comprehensive collection of prompt examples for **OpxiaBot** - your AI-powered DevOps and Cloud management assistant for Slack. This repository contains organized examples and templates to help you effectively interact with your cloud infrastructure across multiple platforms.

## About OpxiaBot

OpxiaBot is an intelligent Slack bot designed to streamline your DevOps and cloud management workflows. With natural language processing capabilities, OpxiaBot helps you monitor, optimize, and manage your cloud resources across AWS, Azure, GCP, and Kubernetes platforms.

### Key Features
- **Multi-Cloud Support**: AWS, Azure, GCP, and Kubernetes (EKS, AKS, GKE)
- **Natural Language Interface**: Simple `@opxiabot` commands
- **Real-time Monitoring**: Get instant insights into your infrastructure
- **Cost Optimization**: Identify and resolve cost inefficiencies
- **Security Compliance**: Monitor security posture and compliance violations
- **Operational Excellence**: Streamline day-to-day operations and incident response

### Getting Started
- **Setup & Installation**: [Install OpxiaBot](https://slackbot.opxia.ai/) in your Slack workspace
- **Documentation**: [Learn how to use OpxiaBot](https://slackbot.opxia.ai/doc.html) - Complete setup and usage guide

## Documentation Structure

This repository is organized by cloud platform and service type. Each section contains carefully crafted prompt examples categorized by use case:

### Cloud Platforms

#### 🟠 [Amazon Web Services (AWS)](./aws/aws.md)
Comprehensive prompts for AWS services including EC2, S3, RDS, Lambda, and more.
- **Security & Compliance**: IAM, Security Groups, Encryption, Access Control
- **Cost Optimization**: Resource utilization, Reserved Instances, Storage optimization
- **Operations & Monitoring**: CloudWatch, Auto Scaling, Load Balancers
- **Resource Management**: Tagging, Lifecycle, Inventory management

#### 🔷 [Microsoft Azure](./azure/azure.md)
Complete Azure resource management prompts covering VMs, Storage Accounts, SQL Database, and Key Vault.
- **Security & Compliance**: NSGs, Key Vault, Encryption, Access policies
- **Cost Optimization**: VM sizing, Storage tiers, Reserved capacity
- **Operations & Monitoring**: Azure Monitor, Application Gateway, Service health
- **Infrastructure as Code**: ARM templates, Policy compliance, DevOps integration

#### 🔵 [Google Cloud Platform (GCP)](./gcp/gcp.md)
Detailed GCP prompts for Compute Engine, Cloud Storage, BigQuery, and Cloud Functions.
- **Security & Compliance**: IAM, Firewall rules, Security Command Center
- **Cost Optimization**: Machine types, Storage classes, BigQuery optimization
- **Operations & Monitoring**: Stackdriver, Load balancers, Performance monitoring
- **DevOps Integration**: Cloud Build, Deployment Manager, Traffic management

### Kubernetes Platforms

#### 🟠 [Amazon Elastic Kubernetes Service (EKS)](./eks/eks.md)
EKS-specific prompts for cluster management, workload operations, and AWS integrations.
- **Cluster Management**: Node groups, Autoscaling, Control plane operations
- **Security & Compliance**: IRSA, Pod security, Network policies, Secret management
- **Cost Optimization**: Spot instances, Right-sizing, Storage optimization
- **AWS Integration**: Load Balancer Controller, EBS CSI, VPC CNI

#### 🔷 [Azure Kubernetes Service (AKS)](./aks/aks.md)
AKS-focused prompts covering cluster operations, security, and Azure-specific features.
- **Cluster Management**: Node pools, Scaling operations, Upgrade management
- **Security & Compliance**: Azure AD integration, Pod security, RBAC
- **Cost Optimization**: Node utilization, Storage management, Spot instances
- **Azure Integration**: Application Gateway, Azure Monitor, Key Vault CSI

#### 🔵 [Google Kubernetes Engine (GKE)](./gke/gke.md)
GKE prompts including Autopilot, Standard clusters, and Google Cloud integrations.
- **Cluster Management**: Autopilot vs Standard, Node pools, Autoscaling
- **Security & Compliance**: Binary Authorization, Workload Identity, Private clusters
- **Cost Optimization**: Preemptible instances, Resource optimization, Storage management
- **Advanced Features**: Anthos, Istio Service Mesh, Config Connector

## How to Use This Repository

### 1. **Choose Your Platform**
Navigate to the appropriate folder based on your cloud platform or Kubernetes service.

### 2. **Browse by Category**
Each document is organized by functional categories:
- **Security & Compliance**
- **Cost Optimization** 
- **Operations & Monitoring**
- **Resource Management**

### 3. **Copy and Customize**
Copy the relevant prompts and customize them for your specific environment and requirements.

### 4. **Use in Slack**
Execute the prompts in your Slack workspace by mentioning `@opxiabot` followed by the command.

## Example Usage

```
@opxiabot Show me all my VMs on Azure that are stopped but still incurring charges
@opxiabot Find all S3 buckets in AWS with public read access enabled
@opxiabot List all GKE clusters in GCP with deprecated Kubernetes versions
@opxiabot Show me all EKS clusters in AWS with unhealthy nodes
```

## Best Practices

### Command Structure
- Always start with `@opxiabot`
- Use clear, specific language
- Include relevant filters (time periods, resource types, etc.)
- Be explicit about the cloud platform when managing multi-cloud environments

### Optimization Tips
- Use category-specific commands for faster results
- Combine multiple related queries for comprehensive analysis
- Leverage tagging in prompts for better resource organization
- Set up regular monitoring commands for proactive management

## 🤝 Contributing

We welcome contributions to expand and improve these prompt examples. Please feel free to:
- Submit additional prompt examples
- Improve existing documentation
- Report issues or suggest enhancements
- Share your use cases and best practices

📞 Support

For technical support, feature requests, or questions about OpxiaBot:
- [Visit our documentation](https://slackbot.opxia.ai/doc.html)
- [Setup and Installation Guide](https://slackbot.opxia.ai/)
- Contact our support team
- Join our community discussions

---

*OpxiaBot - Transforming DevOps and Cloud Management through Intelligent Automation*