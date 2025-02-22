# Exam AZ-303: Microsoft Azure Architect Technologies

## Implement and Monitor an Azure Infrastructure (50-55%)

### Implement Cloud Infrastructure Monitoring
- **Monitor security**
  - Implement security alerts and policies.
  - Utilize Azure Security Center.
- **Monitor performance**
  - Use Azure Monitor to track performance metrics.
  - Implement Application Insights.
- **Monitor health and availability**
  - Set up Azure Service Health alerts.
  - Monitor VM health using Azure Monitor.
- **Monitor cost**
  - Use Azure Cost Management and Billing.
  - Set up cost alerts and budgets.
- **Configure advanced logging**
  - Implement Azure Monitor logs.
  - Use Log Analytics for detailed insights.
- **Initiate automated responses by using Action Groups**
  - Create and configure Action Groups.
  - Set up automated notifications and responses.
- **Configure and manage advanced alerts**
  - Implement metric alerts.
  - Configure log alerts.

### Implement Storage Accounts
- **Select storage account options based on a use case**
  - Choose between Standard and Premium storage.
  - Decide on storage redundancy options (LRS, GRS, ZRS).
- **Configure Azure Files and Azure Blob storage**
  - Create and manage Azure File Shares.
  - Configure Blob containers and access tiers.
- **Configure network access to the storage account**
  - Set up Virtual Network service endpoints.
  - Implement Private Link for secure access.
- **Implement Shared Access Signatures and access policies**
  - Generate SAS tokens with appropriate permissions.
  - Configure stored access policies.
- **Implement Azure AD authentication for storage**
  - Enable Azure AD DS authentication for Azure Files.
  - Set up Azure AD integration for Blob storage.
- **Manage access keys**
  - Rotate and regenerate access keys.
  - Implement Key Vault for key management.
- **Implement Azure storage replication**
  - Configure replication options (LRS, GRS, RA-GRS).
  - Implement geo-replication.
- **Implement Azure storage account failover**
  - Set up account failover.
  - Test failover procedures.

### Implement VMs for Windows and Linux
- **Configure high availability**
  - Implement Availability Sets.
  - Configure Availability Zones.
- **Configure storage for VMs**
  - Attach and manage data disks.
  - Implement Managed Disks.
- **Select virtual machine size**
  - Choose VM sizes based on workload requirements.
  - Optimize VM performance and cost.
- **Implement Azure Dedicated Hosts**
  - Set up dedicated hosts for compliance.
  - Allocate VMs to dedicated hosts.
- **Deploy and configure Virtual Machine Scale Sets**
  - Create and manage scale sets.
  - Configure autoscaling rules.
- **Configure managed disk encryption**
  - Enable Azure Disk Encryption.
  - Configure encryption keys in Key Vault.

### Automate Deployment and Configuration of Resources
- **Save a deployment as an Azure Resource Manager template**
  - Export templates from the Azure portal.
  - Save templates for reuse.
- **Modify Azure Resource Manager template (JSON and Bicep)**
  - Edit templates using Visual Studio Code.
  - Convert JSON templates to Bicep.
- **Evaluate location of new resources**
  - Determine optimal regions for deployment.
  - Consider compliance and latency requirements.
- **Configure a VHD image**
  - Create and manage custom VHD images.
  - Upload VHDs to Azure.
- **Deploy from an image**
  - Use Azure Image Gallery for image management.
  - Deploy VMs from custom images.
- **Manage an image library**
  - Maintain a library of VM images.
  - Update and version images.
- **Create and execute an Azure Automation runbook**
  - Develop runbooks using PowerShell or Python.
  - Schedule and monitor runbook execution.

### Implement Virtual Networking
- **Implement VNet to VNet connections**
  - Set up VNet peering.
  - Configure VPN Gateway connections.
- **Implement VNet peering**
  - Establish peering between VNets.
  - Configure routing and firewall rules.

### Implement Azure Active Directory
- **Add custom domains**
  - Verify and add custom domains in Azure AD.
  - Configure DNS settings.
- **Configure Azure AD Identity Protection**
  - Set up risk policies for sign-ins.
  - Monitor and respond to identity risks.
- **Implement self-service password reset**
  - Enable and configure password reset options.
  - Integrate with on-premises AD.
- **Implement Conditional Access including MFA**
  - Create and manage Conditional Access policies.
  - Configure multi-factor authentication settings.
- **Configure fraud alerts**
  - Enable fraud alerts for MFA.
  - Review and respond to fraud reports.
- **Configure verification methods**
  - Set up phone, email, and app-based verification.
  - Manage user verification options.
- **Implement and manage guest accounts**
  - Invite and manage B2B guest users.
  - Configure access policies for guest accounts.
- **Manage multiple directories**
  - Handle multiple Azure AD tenants.
  - Set up directory synchronization.

### Implement and Manage Hybrid Identities
- **Install and configure Azure AD Connect**
  - Set up synchronization between on-premises AD and Azure AD.
  - Configure user and group synchronization.
- **Identity synchronization options**
  - Choose between password hash sync, pass-through authentication, and federation.
  - Configure synchronization settings.
- **Configure and manage password sync and password writeback**
  - Enable password hash synchronization.
  - Set up password writeback.
- **Configure single sign-on**
  - Implement SSO with Azure AD.
  - Configure application SSO settings.
- **Configure Azure AD Connect cloud sync**
  - Set up cloud sync for lightweight directory synchronization.
  - Monitor and troubleshoot cloud sync.
- **Use Azure AD Connect Health**
  - Monitor synchronization health.
  - Configure alerts for sync issues.

## Implement Management and Security Solutions (25-30%)

### Manage Workloads in Azure
- **Migrate workloads using Azure Migrate**
  - Assess on-premises workloads.
  - Plan and execute migration strategies.
- **Implement Azure Backup for Azure workloads**
  - Configure backup policies.
  - Monitor and manage backups.
- **Implement disaster recovery**
  - Set up Azure Site Recovery.
  - Test and validate disaster recovery plans.
- **Implement Azure Automation Update Management**
  - Enable Update Management for VMs.
  - Schedule and monitor updates.

### Implement Load Balancing and Network Security
- **Implement Azure Load Balancer**
  - Configure public and internal load balancers.
  - Set up load balancing rules and health probes.
- **Implement an Azure Application Gateway**
  - Configure Application Gateway for web traffic.
  - Set up URL-based routing and SSL termination.
- **Implement Web Application Firewall**
  - Enable WAF on Application Gateway.
  - Configure WAF policies and rules.
- **Implement Azure Firewall**
  - Deploy and configure Azure Firewall.
  - Set up network rules and application rules.
- **Implement Azure Firewall Manager**
  - Centralize firewall management.
  - Configure policies across multiple firewalls.
- **Implement Azure Front Door**
  - Set up global load balancing.
  - Configure routing rules and SSL offloading.
- **Implement Azure Traffic Manager**
  - Configure traffic routing methods.
  - Set up endpoint monitoring.
- **Implement Network Security Groups and Application Security Groups**
  - Create and manage NSGs.
  - Configure ASGs for fine-grained network security.
- **Implement Bastion**
  - Deploy Azure Bastion for secure VM access.
  - Configure Bastion settings and policies.

### Implement and Manage Azure Governance Solutions
- **Create and manage hierarchical structure that contains management groups, subscriptions, and resource groups**
  - Set up management groups.
  - Organize subscriptions and resource groups.
- **Assign RBAC roles**
  - Assign built-in and custom roles.
  - Manage role assignments.
- **Create a custom RBAC role**
  - Define custom roles using JSON.
  - Assign custom roles to users and groups.
- **Configure access to Azure resources by assigning roles**
  - Implement role-based access control.
  - Manage access permissions.
- **Configure management access to Azure**
  - Set up Azure AD Privileged Identity Management (PIM).
  - Manage administrative roles and access.
- **Interpret effective permissions**
  - Analyze effective permissions for users and groups.
  - Resolve permission conflicts.
- **Set up and perform an access review**
  - Configure access reviews for RBAC roles.
  - Monitor and take action on access review results.
- **Implement and configure Azure Policy**
  - Create and assign policies.
  - Monitor policy compliance.
- **Implement and configure Azure Blueprints**
  - Define and deploy blueprints.
  - Manage blueprint versions and assignments.

### Manage Security for Applications
- **Implement and configure Key Vault**
  - Store and manage secrets, keys, and certificates.
  - Implement access policies for Key Vault.
- **Implement and configure managed identities**
  - Enable system-assigned and user-assigned managed identities.
  - Configure access for managed identities.
- **Register and manage applications in Azure AD**
  - Register applications for Azure AD authentication.
  - Manage application permissions and roles.

## Implement Solutions for Apps (10-15%)

### Implement an Application Infrastructure
- **Create and configure Azure App Service**
  - Set up web apps, API apps, and mobile apps.
  - Configure app settings and scaling.
- **Create an App Service Web App for Containers**
  - Deploy containerized web apps.
  - Manage container configuration and scaling.
- **Create and configure an App Service plan**
  - Choose appropriate pricing tiers.
  - Configure scaling options.
- **Configure App Service**
  - Set up custom domains and SSL.
  - Configure authentication and authorization.
- **Configure networking for App Service**
  - Set up VNet integration.
  - Configure hybrid connections.
- **Create and manage deployment slots**
  - Set up staging environments.
  - Swap deployment slots.
- **Implement Logic Apps**
  - Create and manage workflows.
  - Integrate with other Azure services.
- **Implement Azure Functions**
  - Develop and deploy serverless functions.
  - Configure triggers and bindings.

### Implement Container-Based Applications
- **Create a container image**
  - Build container images using Docker.
  - Store images in Azure Container Registry.
- **Configure Azure Kubernetes Service**
  - Deploy and manage Kubernetes clusters.
  - Configure scaling and networking.
- **Push container images**
  - Push images to Azure Container Registry.
  - Automate image deployment.
- **Deploy a solution on an Azure Container Instance**
  - Create and manage container instances.
  - Configure networking and storage.

## Implement and Manage Data Platforms (10-15%)

### Implement NoSQL Databases
- **Configure Azure Storage tables**
  - Create and manage table storage.
  - Implement access policies.
- **Select appropriate Cosmos DB APIs**
  - Choose between SQL, MongoDB, Cassandra, Gremlin, and Table APIs.
  - Configure API settings and scaling.
- **Set up replicas in Cosmos DB**
  - Configure global distribution.
  - Manage consistency levels.

### Implement Azure SQL Databases
- **Configure Azure SQL database settings**
  - Set up performance and security settings.
  - Configure backup and retention policies.
- **Implement Azure SQL managed instances**
  - Deploy managed instances.
  - Configure instance settings and scaling.
- **Configure HA for an Azure SQL database**
  - Set up geo-replication.
  - Implement failover groups.
- **Deploy an Azure SQL database**
  - Create single databases and elastic pools.
  - Configure database settings.