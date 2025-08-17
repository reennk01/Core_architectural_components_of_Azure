
## 🌐 Describe the Core Architectural Components of Azure

This module provides an in-depth understanding of how Microsoft Azure is structured, both physically and logically. It introduces the key architectural elements that form the backbone of the Azure cloud platform:

### 🏢 Physical Infrastructure
- **Azure Regions**: Geographical areas where Microsoft has data centers. Each region comprises multiple data centers interconnected by a low-latency network.
- **Availability Zones**: Physically separate locations within a region. They offer high availability and fault tolerance for mission-critical applications.
- **Region Pairs**: Each Azure region is paired with another within the same geography to support disaster recovery and data residency requirements.

### 🗂️ Management Infrastructure
- **Subscriptions**: Containers that hold related Azure resources and define billing boundaries.
- **Management Groups**: Help manage access, policies, and compliance across multiple Azure subscriptions.
- **Resource Groups**: Logical containers for grouping related resources like VMs, databases, and storage accounts for easier management and automation.

### ⚙️ Azure Resource Manager (ARM)
- The deployment and management service that enables you to work with resources as a group, apply templates (ARM templates), and define infrastructure as code.

### 🧪 Hands-On Experience
- The module includes interactive exercises where you create and organize resources in the Azure portal, helping reinforce the structure and relationships between Azure components.

## ☁️ Describe Azure Compute and Networking Services

In this module, I explored the core compute and networking services offered by Microsoft Azure. It helped me understand how to deploy, manage, and connect applications efficiently and securely in the cloud.

### 🖥️ What I Learned

- **Compute Services**  
  I learned about various compute options available in Azure, including **Virtual Machines**, **Containers**, and **Azure Functions**.  
  I also explored:
  - **VM Scale Sets** for autoscaling
  - **Availability Sets** for high availability
  - **Azure Virtual Desktop** for remote access solutions  
  These services allow you to pick the right compute model depending on performance, cost, and deployment needs.

- **App Hosting**  
  I discovered different ways to host applications using Azure — whether on VMs, through container instances, or using **Azure App Services**. This helps in selecting the best approach for different workloads.

- **Networking Essentials**  
  I got hands-on with:
  - **Azure Virtual Networks (VNets)** and **Subnets** for resource segmentation
  - **VNet Peering** to enable private communication between VNets
  - **Azure DNS** for name resolution
  - **VPN Gateway** and **ExpressRoute** for secure on-prem to cloud connections
  - Public and private endpoints for securing access to resources

### 🧪 Hands-On Practice

Throughout the module, I practiced:
- Creating and managing Virtual Machines
- Setting up virtual networks and subnets

## 🗂️ Describe Azure Storage Services

I recently completed the **"Describe Azure Storage Services"** module, where I deepened my understanding of how different Azure storage offerings work together to build resilient and efficient data solutions.

###  What I Learned

- **Core Concepts & Objectives**  
  I learned to compare the different Azure storage services, understand storage tiers (like hot, cool, archive), and recognize redundancy options to ensure data durability and availability

- **Storage Account Types & Services**  
  I explored multiple storage services:
  - **Blob Storage** (for unstructured text and binary data, with analytics support via Data Lake Storage)  
  - **Azure Files** (fully managed file shares compatible with SMB/NFS protocols)  
  - **Azure Elastic SAN** (iSCSI‑based high-performance storage)  
  - **Azure Queues** (message queuing service)  
  - **Azure Tables** (schemaless NoSQL storage)  
  - **Managed Disks**, **Azure Container Storage**, **Azure NetApp Files**, and **Managed Lustre** for specialized scenarios

- **Data Movement & Migration Tools**  
  I learned about tools to move and migrate data:
  - **AzCopy**, **Azure Storage Explorer**, **Azure File Sync** for file transfers  
  - **Azure Migrate** and **Azure Data Box** for larger-scale migrations 

- **Resilience Through Redundancy**  
  The module helped me understand redundancy options (LRS, ZRS, GRS, etc.) that safeguard data across hardware failures and geographic disruptions

- **Hands-On Practice**  
  I completed an interactive task to create a storage blob, which reinforced my working knowledge of Azure Storage fundamentals 

## 🔒 Describe Azure Identity, Access, and Security

I recently completed the **"Describe Azure Identity, Access, and Security"** module, which gave me a foundational understanding of how Azure handles identity, access control, and cloud security.

###  What I Learned

- **Azure Directory Services**  
  I explored key directory services in Azure, including **Microsoft Entra ID** (formerly Azure AD) and **Microsoft Entra Domain Services**.

- **Authentication Methods**  
  I learned about multiple authentication approaches, including **Single Sign-On (SSO)**, **Multi-Factor Authentication (MFA)**, and **passwordless** methods.

- **External Identities & Guest Access**  
  I discovered how to manage identities beyond the organization by leveraging **external identities** and enabling **guest user access**.

- **Conditional Access & RBAC**  
  I gained insights into **Microsoft Entra Conditional Access** and **Azure Role-Based Access Control (RBAC)** for enforcing dynamic and fine-grained permissions.

- **Security Models**  
  I studied the **Zero Trust** security principle and the **defense-in-depth** model, both critical for building secure, resilient cloud infrastructure.

- **Microsoft Defender for Cloud**  
  I learned how **Microsoft Defender for Cloud** rounds out Azure’s security stack by providing protection across resources and workloads.

###  Why It’s Valuable

This module helped me connect the dots between identity services, authentication controls, and access governance—laying the groundwork for securing Azure environments effectively. It also introduced me to core security best practices like conditional access and defense-in-depth strategies.


