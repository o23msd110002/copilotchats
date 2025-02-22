# Azure Architect Exam Syllabus

## Exam AZ-303: Microsoft Azure Architect Technologies

### Implement and Monitor an Azure Infrastructure (50-55%)
#### Implement Cloud Infrastructure Monitoring
- Monitor security
- Monitor performance
- Monitor health and availability
- Monitor cost
- Configure advanced logging
- Initiate automated responses by using Action Groups
- Configure and manage advanced alerts

#### Implement Storage Accounts
- Select storage account options based on a use case
- Configure Azure Files and Azure Blob storage
- Configure network access to the storage account
- Implement Shared Access Signatures and access policies
- Implement Azure AD authentication for storage
- Manage access keys
- Implement Azure storage replication
- Implement Azure storage account failover

#### Implement VMs for Windows and Linux
- Configure high availability
- Configure storage for VMs
- Select virtual machine size
- Implement Azure Dedicated Hosts
- Deploy and configure Virtual Machine Scale Sets
- Configure managed disk encryption

#### Automate Deployment and Configuration of Resources
- Save a deployment as an Azure Resource Manager template
- Modify Azure Resource Manager template (JSON and Bicep)
- Evaluate location of new resources
- Configure a VHD image
- Deploy from an image
- Manage an image library
- Create and execute an Azure Automation runbook

#### Implement Virtual Networking
- Implement VNet to VNet connections
- Implement VNet peering

#### Implement Azure Active Directory
- Add custom domains
- Configure Azure AD Identity Protection
- Implement self-service password reset
- Implement Conditional Access including MFA
- Configure fraud alerts
- Configure verification methods
- Implement and manage guest accounts
- Manage multiple directories

#### Implement and Manage Hybrid Identities
- Install and configure Azure AD Connect
- Identity synchronization options
- Configure and manage password sync and password writeback
- Configure single sign-on
- Configure Azure AD Connect cloud sync
- Use Azure AD Connect Health

### Implement Management and Security Solutions (25-30%)
#### Manage Workloads in Azure
- Migrate workloads using Azure Migrate
- Implement Azure Backup for Azure workloads
- Implement disaster recovery
- Implement Azure Automation Update Management

#### Implement Load Balancing and Network Security
- Implement Azure Load Balancer
- Implement an Azure Application Gateway
- Implement Web Application Firewall
- Implement Azure Firewall
- Implement Azure Firewall Manager
- Implement Azure Front Door
- Implement Azure Traffic Manager
- Implement Network Security Groups and Application Security Groups
- Implement Bastion

#### Implement and Manage Azure Governance Solutions
- Create and manage hierarchical structure that contains management groups, subscriptions, and resource groups
- Assign RBAC roles
- Create a custom RBAC role
- Configure access to Azure resources by assigning roles
- Configure management access to Azure
- Interpret effective permissions
- Set up and perform an access review
- Implement and configure Azure Policy
- Implement and configure Azure Blueprints

#### Manage Security for Applications
- Implement and configure Key Vault
- Implement and configure managed identities
- Register and manage applications in Azure AD

### Implement Solutions for Apps (10-15%)
#### Implement an Application Infrastructure
- Create and configure Azure App Service
- Create an App Service Web App for Containers
- Create and configure an App Service plan
- Configure App Service
- Configure networking for App Service
- Create and manage deployment slots
- Implement Logic Apps
- Implement Azure Functions

#### Implement Container-Based Applications
- Create a container image
- Configure Azure Kubernetes Service
- Push container images
- Deploy a solution on an Azure Container Instance

### Implement and Manage Data Platforms (10-15%)
#### Implement NoSQL Databases
- Configure Azure Storage tables
- Select appropriate Cosmos DB APIs
- Set up replicas in Cosmos DB

#### Implement Azure SQL Databases
- Configure Azure SQL database settings
- Implement Azure SQL managed instances
- Configure HA for an Azure SQL database
- Deploy an Azure SQL database

## Exam AZ-304: Microsoft Azure Architect Design

### Design Monitoring (10-15%)
#### Design for Cost Optimization
- Recommend a solution for cost management and cost reporting
- Recommend solutions to minimize costs

#### Design a Solution for Logging and Monitoring
- Determine levels and storage locations for logs
- Plan for integration with monitoring tools including Azure Monitor and Azure Sentinel
- Recommend appropriate monitoring tool(s) for a solution
- Choose a mechanism for event routing and escalation
- Recommend a logging solution for compliance requirements

### Design Identity and Security (25-30%)
#### Design Authentication
- Recommend a solution for single-sign on
- Recommend a solution for authentication
- Recommend a solution for Conditional Access, including multi-factor authentication
- Recommend a solution for network access authentication
- Recommend a solution for a hybrid identity including Azure AD Connect, Azure AD Connect cloud sync, and Azure AD Connect Health
- Recommend a solution for user self-service
- Recommend and implement a solution for B2B integration

#### Design Authorization
- Choose an authorization approach
- Recommend a hierarchical structure that includes management groups, subscriptions, and resource groups
- Recommend an access management solution including RBAC policies, access reviews, role assignments, Privileged Identity Management (PIM), Azure AD Identity Protection, Just In Time (JIT) access

#### Design Governance
- Recommend a strategy for tagging
- Recommend a solution for using Azure Policy
- Recommend a solution for using Azure Blueprints
- Recommend a solution that leverages Azure Resource Graph

#### Design Security for Applications
- Recommend a solution that includes Key Vault
- Recommend a solution that includes managed identities
- Recommend a solution for integrating applications into Azure AD

### Design Data Storage (15-20%)
#### Design a Solution for Databases
- Select an appropriate data platform based on requirements
- Recommend database service tier sizing
- Recommend a solution for database scalability
- Recommend a solution for encrypting data at rest, data in transmission, and data in use

#### Design Data Integration
- Recommend a data flow to meet business requirements
- Recommend a solution for data integration, including Azure Data Factory, Azure Databricks, Azure Data Lake, Azure Synapse Analytics

#### Select an Appropriate Storage Account
- Choose between storage tiers
- Recommend a storage access solution
- Recommend storage management tools

### Design Business Continuity (10-15%)
#### Design a Solution for Backup and Recovery
- Recommend a recovery solution for Azure hybrid and on-premises workloads that meets recovery objectives (RTO, RLO, RPO)
- Design an Azure Site Recovery solution
- Recommend a solution for recovery in different regions
- Recommend a solution for geo-redundancy of workloads
- Recommend a solution for Azure Backup management
- Design a solution for data archiving and retention

#### Design for High Availability
- Recommend a solution for application and workload redundancy, including compute, database, and storage
- Recommend a solution for autoscaling
- Identify resources that require high availability
- Identify storage types for high availability

### Design Infrastructure (25-30%)
#### Design a Compute Solution
- Recommend a solution for compute provisioning
- Determine appropriate compute technologies, including virtual machines, App Services, Service Fabric, Azure Functions, Azure Virtual Desktop, Batch, HPC, and containers
- Recommend a solution for containers
- Recommend a solution for automating compute management

#### Design a Network Solution
- Recommend a network architecture (hub and spoke, Virtual WAN)
- Recommend a solution for network addressing and name resolution
- Recommend a solution for network provisioning
- Recommend a solution for network security including Private Link, firewalls, gateways, network segmentation (perimeter networks/DMZs/NVAs)
- Recommend a solution for network connectivity to the Internet, on-premises networks, and other Azure virtual networks
- Recommend a solution for automating network management
- Recommend a solution for load balancing and traffic routing

#### Design an Application Architecture
- Recommend a microservices architecture including Event Grid, Event Hubs, Service Bus, Azure Queue Storage, Logic Apps, Azure Functions, Service Fabric, AKS, Azure App Configuration, and webhooks
- Recommend an orchestration solution for deployment and maintenance of applications including ARM templates, Azure Automation, Azure Pipelines, Logic Apps, or Azure Functions
- Recommend a solution for API integration

#### Design Migrations
- Assess and interpret on-premises servers, data, and applications for migration
- Recommend a solution for migrating applications and VMs
- Recommend a solution for migration of databases
- Determine migration scope, including redundant, related, trivial, and outdated data
- Recommend a solution for migrating data (Storage Migration Service, Azure Data Box, Azure File Sync-based migration to hybrid file server)