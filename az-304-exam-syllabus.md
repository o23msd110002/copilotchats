# Exam AZ-304: Microsoft Azure Architect Design

## Design Monitoring (10-15%)

### Design for Cost Optimization
- **Recommend a solution for cost management and cost reporting**
  - Use Azure Cost Management and Billing.
  - Implement cost-saving strategies.
- **Recommend solutions to minimize costs**
  - Optimize resource usage.
  - Implement Reserved Instances and Spot VMs.

### Design a Solution for Logging and Monitoring
- **Determine levels and storage locations for logs**
  - Choose appropriate log retention policies.
  - Decide on storage solutions for logs.
- **Plan for integration with monitoring tools including Azure Monitor and Azure Sentinel**
  - Set up integration with third-party tools.
  - Configure monitoring solutions.
- **Recommend appropriate monitoring tool(s) for a solution**
  - Choose the right monitoring tools based on requirements.
  - Implement Application Insights, Log Analytics, and Azure Monitor.
- **Choose a mechanism for event routing and escalation**
  - Set up Action Groups and alerts.
  - Configure event routing to appropriate teams.
- **Recommend a logging solution for compliance requirements**
  - Ensure logging meets regulatory compliance.
  - Implement secure log storage.

## Design Identity and Security (25-30%)

### Design Authentication
- **Recommend a solution for single-sign on**
  - Implement Azure AD SSO.
  - Configure SAML and OAuth authentication.
- **Recommend a solution for authentication**
  - Use Azure Multi-Factor Authentication (MFA).
  - Implement conditional access policies.
- **Recommend a solution for Conditional Access, including multi-factor authentication**
  - Set up and manage conditional access policies.
  - Configure MFA requirements.
- **Recommend a solution for network access authentication**
  - Implement Network Access Control (NAC).
  - Configure VPN and ExpressRoute authentication.
- **Recommend a solution for a hybrid identity including Azure AD Connect, Azure AD Connect cloud sync, and Azure AD Connect Health**
  - Set up hybrid identity solutions.
  - Monitor and maintain hybrid identity health.
- **Recommend a solution for user self-service**
  - Implement self-service password reset.
  - Enable self-service group management.
- **Recommend and implement a solution for B2B integration**
  - Configure Azure AD B2B.
  - Manage guest user access.

### Design Authorization
- **Choose an authorization approach**
  - Implement RBAC and ABAC.
  - Configure access policies.
- **Recommend a hierarchical structure that includes management groups, subscriptions, and resource groups**
  - Organize resources for governance.
  - Implement management groups and policies.
- **Recommend an access management solution including RBAC policies, access reviews, role assignments, Privileged Identity Management (PIM), Azure AD Identity Protection, Just In Time (JIT) access**
  - Configure RBAC and PIM.
  - Set up access reviews and JIT access.

### Design Governance
- **Recommend a strategy for tagging**
  - Implement a tagging policy.
  - Use tags for resource organization and cost management.
- **Recommend a solution for using Azure Policy**
  - Create and assign policies.
  - Monitor policy compliance.
- **Recommend a solution for using Azure Blueprints**
  - Define and deploy blueprints.
  - Manage blueprint versions and assignments.
- **Recommend a solution that leverages Azure Resource Graph**
  - Query resources using Azure Resource Graph.
  - Use Resource Graph Explorer.

### Design Security for Applications
- **Recommend a solution that includes Key Vault**
  - Store and manage secrets, keys, and certificates.
  - Implement access policies for Key Vault.
- **Recommend a solution that includes managed identities**
  - Enable system-assigned and user-assigned managed identities.
  - Configure access for managed identities.
- **Recommend a solution for integrating applications into Azure AD**
  - Register applications for Azure AD authentication.
  - Manage application permissions and roles.

## Design Data Storage (15-20%)

### Design a Solution for Databases
- **Select an appropriate data platform based on requirements**
  - Choose between SQL and NoSQL options.
  - Select managed services like Azure SQL Database and Cosmos DB.
- **Recommend database service tier sizing**
  - Determine appropriate service tiers.
  - Optimize for performance and cost.
- **Recommend a solution for database scalability**
  - Implement vertical and horizontal scaling.
  - Use sharding and partitioning.
- **Recommend a solution for encrypting data at rest, data in transmission, and data in use**
  - Implement Transparent Data Encryption (TDE).
  - Use Always Encrypted and SSL/TLS.

### Design Data Integration
- **Recommend a data flow to meet business requirements**
  - Design ETL/ELT processes.
  - Use Azure Data Factory for data integration.
- **Recommend a solution for data integration, including Azure Data Factory, Azure Databricks, Azure Data Lake, Azure Synapse Analytics**
  - Choose appropriate tools for data integration and analysis.
  - Implement data pipelines and workflows.

### Select an Appropriate Storage Account
- **Choose between storage tiers**
  - Select Hot, Cool, or Archive tiers.
  - Optimize for access patterns and cost.
- **Recommend a storage access solution**
  - Implement Shared Access Signatures (SAS).
  - Use Azure AD for authentication.
- **Recommend storage management tools**
  - Use Storage Explorer and Azure Portal.
  - Implement lifecycle management policies.

## Design Business Continuity (10-15%)

### Design a Solution for Backup and Recovery
- **Recommend a recovery solution for Azure hybrid and on-premises workloads that meets recovery objectives (RTO, RLO, RPO)**
  - Implement Azure Backup and Site Recovery.
  - Configure backup policies and recovery plans.
- **Design an Azure Site Recovery solution**
  - Set up replication and failover.
  - Test disaster recovery scenarios.
- **Recommend a solution for recovery in different regions**
  - Implement geo-redundant storage.
  - Configure cross-region replication.
- **Recommend a solution for geo-redundancy of workloads**
  - Set up global load balancing and failover.
  - Implement multi-region deployments.
- **Recommend a solution for Azure Backup management**
  - Monitor and manage backup jobs.
  - Configure alerts and reporting.
- **Design a solution for data archiving and retention**
  - Implement long-term data retention policies.
  - Use Azure Archive Storage.

### Design for High Availability
- **Recommend a solution for application and workload redundancy, including compute, database, and storage**
  - Implement load balancing and failover solutions.
  - Configure high availability for databases and storage.
- **Recommend a solution for autoscaling**
  - Set up autoscale rules for VMs and App Services.
  - Monitor and adjust scaling settings.
- **Identify resources that require high availability**
  - Determine SLAs for critical workloads.
  - Implement redundancy and failover strategies.
- **Identify storage types for high availability**
  - Choose appropriate storage options for HA.
  - Implement replication and backup solutions.

## Design Infrastructure (25-30%)

### Design a Compute Solution
- **Recommend a solution for compute provisioning**
  - Choose between VMs, App Services, and containers.
  - Optimize compute resources for performance and cost.
- **Determine appropriate compute technologies, including virtual machines, App Services, Service Fabric, Azure Functions, Azure Virtual Desktop, Batch, HPC, and containers**
  - Select the best compute options based on workload requirements.
  - Implement hybrid and multi-cloud solutions.
- **Recommend a solution for containers**
  - Use Azure Kubernetes Service (AKS) for orchestration.
  - Implement Azure Container Instances for lightweight workloads.
- **Recommend a solution for automating compute management**
  - Use ARM templates, Terraform, and Azure Automation.
  - Implement CI/CD pipelines for infrastructure as code.

### Design a Network Solution
- **Recommend a network architecture (hub and spoke, Virtual WAN)**
  - Design network topologies for scalability and security.
  - Implement hub and spoke or Virtual WAN architectures.
- **Recommend a solution for