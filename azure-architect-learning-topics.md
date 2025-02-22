# Azure Architect Learning Topics

## 1. Foundation Phase
### 1.1 Azure Fundamentals
- Introduction to Azure
- Azure Services Overview
- Azure Core Solutions and Management Tools
- General security and network security features
- Identity, governance, privacy, and compliance features
- Azure cost management and Service Level Agreements (SLAs)

## 2. AZ-303: Microsoft Azure Architect Technologies
### 2.1 Implement and Monitor an Azure Infrastructure
#### 2.1.1 Implement Cloud Infrastructure Monitoring
- Monitor security
  - Implement security alerts and policies
  - Utilize Azure Security Center
- Monitor performance
  - Use Azure Monitor to track performance metrics
  - Implement Application Insights
- Monitor health and availability
  - Set up Azure Service Health alerts
  - Monitor VM health using Azure Monitor
- Monitor cost
  - Use Azure Cost Management and Billing
  - Set up cost alerts and budgets
- Configure advanced logging
  - Implement Azure Monitor logs
  - Use Log Analytics for detailed insights
- Initiate automated responses by using Action Groups
  - Create and configure Action Groups
  - Set up automated notifications and responses
- Configure and manage advanced alerts
  - Implement metric alerts
  - Configure log alerts

#### 2.1.2 Implement Storage Accounts
- Select storage account options based on a use case
  - Choose between Standard and Premium storage
  - Decide on storage redundancy options (LRS, GRS, ZRS)
- Configure Azure Files and Azure Blob storage
  - Create and manage Azure File Shares
  - Configure Blob containers and access tiers
- Configure network access to the storage account
  - Set up Virtual Network service endpoints
  - Implement Private Link for secure access
- Implement Shared Access Signatures and access policies
  - Generate SAS tokens with appropriate permissions
  - Configure stored access policies
- Implement Azure AD authentication for storage
  - Enable Azure AD DS authentication for Azure Files
  - Set up Azure AD integration for Blob storage
- Manage access keys
  - Rotate and regenerate access keys
  - Implement Key Vault for key management
- Implement Azure storage replication
  - Configure replication options (LRS, GRS, RA-GRS)
  - Implement geo-replication
- Implement Azure storage account failover
  - Set up account failover
  - Test failover procedures

#### 2.1.3 Implement VMs for Windows and Linux
- Configure high availability
  - Implement Availability Sets
  - Configure Availability Zones
- Configure storage for VMs
  - Attach and manage data disks
  - Implement Managed Disks
- Select virtual machine size
  - Choose VM sizes based on workload requirements
  - Optimize VM performance and cost
- Implement Azure Dedicated Hosts
  - Set up dedicated hosts for compliance
  - Allocate VMs to dedicated hosts
- Deploy and configure Virtual Machine Scale Sets
  - Create and manage scale sets
  - Configure autoscaling rules
- Configure managed disk encryption
  - Enable Azure Disk Encryption
  - Configure encryption keys in Key Vault

#### 2.1.4 Automate Deployment and Configuration of Resources
- Save a deployment as an Azure Resource Manager template
  - Export templates from the Azure portal
  - Save templates for reuse
- Modify Azure Resource Manager template (JSON and Bicep)
  - Edit templates using Visual Studio Code
  - Convert JSON templates to Bicep
- Evaluate location of new resources
  - Determine optimal regions for deployment
  - Consider compliance and latency requirements
- Configure a VHD image
  - Create and manage custom VHD images
  - Upload VHDs to Azure
- Deploy from an image
  - Use Azure Image Gallery for image management
  - Deploy VMs from custom images
- Manage an image library
  - Maintain a library of VM images
  - Update and version images
- Create and execute an Azure Automation runbook
  - Develop runbooks using PowerShell or Python
  - Schedule and monitor runbook execution

#### 2.1.5 Implement Virtual Networking
- Implement VNet to VNet connections
  - Set up VNet peering
  - Configure VPN Gateway connections
- Implement VNet peering
  - Establish peering between VNets
  - Configure routing and firewall rules

#### 2.1.6 Implement Azure Active Directory
- Add custom domains
  - Verify and add custom domains in Azure AD
  - Configure DNS settings
- Configure Azure AD Identity Protection
  - Set up risk policies for sign-ins
  - Monitor and respond to identity risks
- Implement self-service password reset
  - Enable and configure password reset options
  - Integrate with on-premises AD
- Implement Conditional Access including MFA
  - Create and manage Conditional Access policies
  - Configure multi-factor authentication settings
- Configure fraud alerts
  - Enable fraud alerts for MFA
  - Review and respond to fraud reports
- Configure verification methods
  - Set up phone, email, and app-based verification
  - Manage user verification options
- Implement and manage guest accounts
  - Invite and manage B2B guest users
  - Configure access policies for guest accounts
- Manage multiple directories
  - Handle multiple Azure AD tenants
  - Set up directory synchronization

#### 2.1.7 Implement and Manage Hybrid Identities
- Install and configure Azure AD Connect
  - Set up synchronization between on-premises AD and Azure AD
  - Configure user and group synchronization
- Identity synchronization options
  - Choose between password hash sync, pass-through authentication, and federation
  - Configure synchronization settings
- Configure and manage password sync and password writeback
  - Enable password hash synchronization
  - Set up password writeback
- Configure single sign-on
  - Implement SSO with Azure AD
  - Configure application SSO settings
- Configure Azure AD Connect cloud sync
  - Set up cloud sync for lightweight directory synchronization
  - Monitor and troubleshoot cloud sync
- Use Azure AD Connect Health
  - Monitor synchronization health
  - Configure alerts for sync issues

### 2.2 Implement Management and Security Solutions
#### 2.2.1 Manage Workloads in Azure
- Migrate workloads using Azure Migrate
  - Assess on-premises workloads
  - Plan and execute migration strategies
- Implement Azure Backup for Azure workloads
  - Configure backup policies
  - Monitor and manage backups
- Implement disaster recovery
  - Set up Azure Site Recovery
  - Test and validate disaster recovery plans
- Implement Azure Automation Update Management
  - Enable Update Management for VMs
  - Schedule and monitor updates

#### 2.2.2 Implement Load Balancing and Network Security
- Implement Azure Load Balancer
  - Configure public and internal load balancers
  - Set up load balancing rules and health probes
- Implement an Azure Application Gateway
  - Configure Application Gateway for web traffic
  - Set up URL-based routing and SSL termination
- Implement Web Application Firewall
  - Enable WAF on Application Gateway
  - Configure WAF policies and rules
- Implement Azure Firewall
  - Deploy and configure Azure Firewall
  - Set up network rules and application rules
- Implement Azure Firewall Manager
  - Centralize firewall management
  - Configure policies across multiple firewalls
- Implement Azure Front Door
  - Set up global load balancing
  - Configure routing rules and SSL offloading
- Implement Azure Traffic Manager
  - Configure traffic routing methods
  - Set up endpoint monitoring
- Implement Network Security Groups and Application Security Groups
  - Create and manage NSGs
  - Configure ASGs for fine-grained network security
- Implement Bastion
  - Deploy Azure Bastion for secure VM access
  - Configure Bastion settings and policies

#### 2.2.3 Implement and Manage Azure Governance Solutions
- Create and manage hierarchical structure that contains management groups, subscriptions, and resource groups
  - Set up management groups
  - Organize subscriptions and resource groups
- Assign RBAC roles
  - Assign built-in and custom roles
  - Manage role assignments
- Create a custom RBAC role
  - Define custom roles using JSON
  - Assign custom roles to users and groups
- Configure access to Azure resources by assigning roles
  - Implement role-based access control
  - Manage access permissions
- Configure management access to Azure
  - Set up Azure AD Privileged Identity Management (PIM)
  - Manage administrative roles and access
- Interpret effective permissions
  - Analyze effective permissions for users and groups
  - Resolve permission conflicts
- Set up and perform an access review
  - Configure access reviews for RBAC roles
  - Monitor and take action on access review results
- Implement and configure Azure Policy
  - Create and assign policies
  - Monitor policy compliance
- Implement and configure Azure Blueprints
  - Define and deploy blueprints
  - Manage blueprint versions and assignments

#### 2.2.4 Manage Security for Applications
- Implement and configure Key Vault
  - Store and manage secrets, keys, and certificates
  - Implement access policies for Key Vault
- Implement and configure managed identities
  - Enable system-assigned and user-assigned managed identities
  - Configure access for managed identities
- Register and manage applications in Azure AD
  - Register applications for Azure AD authentication
  - Manage application permissions and roles

### 2.3 Implement Solutions for Apps
#### 2.3.1 Implement an Application Infrastructure
- Create and configure Azure App Service
  - Set up web apps, API apps, and mobile apps
  - Configure app settings and scaling
- Create an App Service Web App for Containers
  - Deploy containerized web apps
  - Manage container configuration and scaling
- Create and configure an App Service plan
  - Choose appropriate pricing tiers
  - Configure scaling options
- Configure App Service
  - Set up custom domains and SSL
  - Configure authentication and authorization
- Configure networking for App Service
  - Set up VNet integration
  - Configure hybrid connections
- Create and manage deployment slots
  - Set up staging environments
  - Swap deployment slots
- Implement Logic Apps
  - Create and manage workflows
  - Integrate with other Azure services
- Implement Azure Functions
  - Develop and deploy serverless functions
  - Configure triggers and bindings

#### 2.3.2 Implement Container-Based Applications
- Create a container image
  - Build container images using Docker
  - Store images in Azure Container Registry
- Configure Azure Kubernetes Service
  - Deploy and manage Kubernetes clusters
  - Configure scaling and networking
- Push container images
  - Push images to Azure Container Registry
  - Automate image deployment
- Deploy a solution on an Azure Container Instance
  - Create and manage container instances
  - Configure networking and storage

### 2.4 Implement and Manage Data Platforms
#### 2.4.1 Implement NoSQL Databases
- Configure Azure Storage tables
  - Create and manage table storage
  - Implement access policies
- Select appropriate Cosmos DB APIs
  - Choose between SQL, MongoDB, Cassandra, Gremlin, and Table APIs
  - Configure API settings and scaling
- Set up replicas in Cosmos DB
  - Configure global distribution
  - Manage consistency levels

#### 2.4.2 Implement Azure SQL Databases
- Configure Azure SQL database settings
  - Set up performance and security settings
  - Configure backup and retention policies
- Implement Azure SQL managed instances
  - Deploy managed instances
  - Configure instance settings and scaling
- Configure HA for an Azure SQL database
  - Set up geo-replication
  - Implement failover groups
- Deploy an Azure SQL database
  - Create single databases and elastic pools
  - Configure database settings

## 3. AZ-305: Designing Microsoft Azure Infrastructure Solutions
### 3.1 Design Identity, Governance, and Monitoring Solutions
#### 3.1.1 Design a solution for logging and monitoring
- Design a log routing solution
  - Determine log routing requirements
  - Implement log routing using Azure Monitor and Event Hubs
- Recommend an appropriate level of logging
  - Evaluate logging needs based on application requirements
  - Set up appropriate log levels
- Recommend monitoring tools for a solution
  - Choose suitable monitoring tools like Azure Monitor, Log Analytics, and Application Insights
  - Integrate with third-party monitoring tools if necessary
- Design a logging solution for compliance requirements
  - Ensure logging meets regulatory compliance
  - Implement secure log storage

#### 3.1.2 Design authentication and authorization solutions
- Recommend a solution for securing resources with role-based access control
  - Implement RBAC for Azure resources
  - Configure custom roles and assignments
- Recommend an identity management solution
  - Choose between Azure AD, Azure AD B2C, and third-party identity providers
  - Implement identity management best practices
- Recommend a solution for securing identities
  - Implement multi-factor authentication (MFA)
  - Use Azure AD Identity Protection

#### 3.1.3 Design governance
- Recommend an organizational and hierarchical structure for Azure resources
  - Design a management group and subscription hierarchy
  - Implement resource organization strategies
- Recommend a solution for enforcing and auditing compliance
  - Implement Azure Policy for compliance
  - Set up auditing using Azure Monitor and Azure Security Center

#### 3.1.4 Design identities and access for applications
- Recommend solutions to allow applications to access Azure resources
  - Implement managed identities for Azure resources
  - Configure application permissions
- Recommend a solution that securely stores passwords and secrets
  - Use Azure Key Vault for secret management
  - Implement access policies for Key Vault
- Recommend a solution for integrating applications into Azure AD
  - Register applications in Azure AD
  - Manage application permissions and roles
- Recommend a user consent solution for applications
  - Implement user consent flows in Azure AD
  - Configure consent settings and policies

### 3.2 Design Data Storage Solutions
#### 3.2.1 Design a data storage solution for relational data
- Recommend database service tier sizing
  - Evaluate workload requirements
  - Choose appropriate service tiers for Azure SQL Database and other relational databases
- Recommend a solution for database scalability
  - Implement vertical and horizontal scaling
  - Use sharding and partitioning techniques
- Recommend a solution for encrypting data at rest, data in transmission, and data in use
  - Implement Transparent Data Encryption (TDE)
  - Use Always Encrypted and SSL/TLS

#### 3.2.2 Design data integration
- Recommend a solution for data integration
  - Use Azure Data Factory for ETL processes
  - Implement data integration workflows
- Recommend a solution for data analysis
  - Choose appropriate tools like Azure Synapse Analytics, Databricks, and Power BI
  - Implement data analysis pipelines

#### 3.2.3 Recommend a data storage solution
- Recommend a solution for storing relational data
  - Evaluate requirements for SQL databases
  - Choose suitable Azure SQL Database configurations
- Recommend a solution for storing semi-structured data
  - Use Azure Cosmos DB for semi-structured data
  - Implement appropriate API configurations
- Recommend a solution for storing non-relational data
  - Use Azure Table Storage and Blob Storage for non-relational data
  - Implement access and performance optimizations

#### 3.2.4 Design a data storage solution for non-relational data
- Recommend access control solutions to data storage
  - Implement access policies for storage accounts
  - Use Azure AD authentication for storage access
- Recommend a data storage solution to balance features, performance, and cost
  - Evaluate storage options based on performance and cost
  - Choose appropriate storage tiers and configurations
- Design a data solution for protection and durability
  - Implement geo-redundant storage
  - Configure backup and disaster recovery solutions

### 3.3 Design Business Continuity Solutions
#### 3.3.1 Design a solution for backup and disaster recovery
- Recommend a recovery solution for Azure, hybrid, and on-premises workloads that meets recovery objectives (RTO, RLO, RPO)
  - Implement Azure Backup and Site Recovery
  - Configure backup and recovery policies
- Understand the recovery solutions for containers
  - Implement backup and recovery for containerized workloads
  - Use Azure Kubernetes Service (AKS) for disaster recovery
- Recommend a backup and recovery solution for compute
  - Configure VM backups using Azure Backup
  - Implement recovery strategies for compute workloads
- Recommend a backup and recovery solution for databases
  - Use Azure SQL Database backup features
  - Implement point-in-time restore and geo-redundant backups
- Recommend a backup and recovery solution for unstructured data
  - Implement Azure Blob Storage and Azure Files backup solutions
  - Configure data retention policies

#### 3.3.2 Design for high availability
- Identify the availability requirements of Azure resources
  - Determine SLAs for critical workloads
  - Implement availability strategies
- Recommend a high availability solution for compute
  - Use Availability Sets and Availability Zones
  - Implement VM scale sets for high availability
- Recommend a high availability solution for non-relational data storage
  - Implement geo-replication for Azure Cosmos DB
  - Configure high availability for Azure Table Storage and Blob Storage
- Recommend a high availability solution for relational data storage
  - Implement failover groups for Azure SQL Database
  - Configure replication and geo-redundancy

### 3.4 Design Infrastructure Solutions
#### 3.4.1 Design a compute solution
- Recommend a virtual machine–based compute solution
  - Choose appropriate VM sizes and configurations
  - Implement VM scaling strategies
- Recommend an appropriately sized compute solution based on workload requirements
  - Assess workload needs
  - Optimize compute resources for performance and cost
- Recommend a container-based compute solution
  - Use Azure Kubernetes Service (AKS) for container orchestration
  - Implement Azure Container Instances for lightweight workloads
- Recommend a serverless-based compute solution
  - Use Azure Functions and Logic Apps for serverless computing
  - Implement event-driven architectures

#### 3.4.2 Design an application architecture
- Recommend a caching solution for applications
  - Use Azure Cache for Redis
  - Implement caching strategies to improve performance
- Recommend a messaging architecture
  - Implement Azure Service Bus and Event Grid
  - Use Azure Queue Storage for messaging solutions
- Recommend an event-driven architecture
  - Use Azure Event Grid and Event Hubs
  - Implement event-driven design patterns
- Recommend an automated deployment solution for your applications
  - Use Azure DevOps and GitHub Actions for CI/CD pipelines
  - Implement infrastructure as code with ARM templates and Terraform
- Recommend an application configuration management solution
  - Use Azure App Configuration and Key Vault
  - Implement configuration management best practices
- Recommend a solution for API integration
  - Use Azure API Management
  - Implement API gateways and security

#### 3.4.3 Design migrations
- Evaluate a migration solution that leverages the Cloud Adoption Framework for Azure
  - Assess on-premises workloads for migration
  - Use the Cloud Adoption Framework for planning
- Assess and interpret on-premises servers, data, and applications for migration
  - Perform a detailed assessment of existing infrastructure
  - Identify migration priorities
- Recommend a solution for migrating applications and virtual machines
  - Use Azure Migrate for VM migration
  - Implement migration strategies for applications
- Recommend a solution for migrating databases
  - Evaluate database migration options
  - Use Azure Database Migration Service (DMS)
  - Implement database migration strategies
- Recommend a solution for migrating unstructured data
  - Assess unstructured data migration requirements
  - Use Azure Data Box and Azure File Sync
  - Implement strategies for unstructured data migration

#### 3.4.4 Design network solutions
- Recommend a network architecture solution based on workload requirements
  - Design network topologies for scalability and security
  - Implement hub and spoke or Virtual WAN architectures
- Recommend a connectivity solution that connects Azure resources to the internet
  - Use Azure Front Door and Application Gateway
  - Implement secure internet connectivity
- Recommend a connectivity solution that connects Azure resources to on-premises networks
  - Implement VPN Gateway and ExpressRoute
  - Configure hybrid connectivity solutions
- Optimize network performance for applications
  - Use Azure Traffic Manager and Load Balancer
  - Implement network performance optimizations
- Recommend a solution to optimize network security
  - Implement Azure Firewall and Network Security Groups
  - Use Azure DDoS Protection
- Recommend a load balancing and routing solution
  - Use Azure Load Balancer and Application Gateway
  - Implement traffic routing with Azure Traffic Manager