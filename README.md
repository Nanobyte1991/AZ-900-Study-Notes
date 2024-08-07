# AZ-900 Study Notes

## Additional Learning Resources

### Microsoft Learn
- **SC-900 Microsoft Security, Compliance, and Identity Fundamentals**
  - **Time to Complete:** 6 hours
  - **Link:** [Microsoft Learn SC-900](https://learn.microsoft.com/en-us/credentials/certifications/sc-900)

### Udemy
- **SC-900 Exam Prep**
  - **Time to Complete:** 5 hours
  - **Link:** [Udemy SC-900 Exam Prep](https://www.udemy.com/course/az900-azure/?couponCode=ST10MT8624)

### YouTube
- **SC-900 Exam Preparation**
  - **Time to Complete:** 6 hours
  - **Links:**
    - [Video 1](https://www.youtube.com/watch?v=tQp1YkB2Tgs)

## Table of Contents
1. [Cloud Responsibilities](#cloud-responsibilities)
2. [Cloud Deployments](#cloud-deployments)
3. [Cost Management](#cost-management)
4. [Cloud Architecture Terms](#cloud-architecture-terms)
5. [High Availability and Scalability](#high-availability-and-scalability)
6. [Service Types](#service-types)
7. [Regions and Geographies](#regions-and-geographies)
8. [Compute Services](#compute-services)
9. [Storage Services](#storage-services)
10. [Database Services](#database-services)
11. [Application Integration Services](#application-integration-services)
12. [Developer and Mobile Tools](#developer-and-mobile-tools)
13. [Networking](#networking)
14. [Security and Compliance](#security-and-compliance)

## Cloud Responsibilities

### IAAS (Infrastructure as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Runtime, Middleware, OS
- **Example:** Azure Virtual Machines

### PAAS (Platform as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Runtime, Middleware, OS
- **Example:** Azure App Services

### SaaS (Software as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Everything else
- **Example:** Microsoft 365

## Cloud Deployments

### Public Cloud
- **Description:** All resources are hosted in the cloud provider’s infrastructure.
- **Example:** Azure

### Private Cloud
- **Description:** All resources are hosted within an organization's own data center.
- **Example:** On-premises data center

### Hybrid Cloud
- **Description:** Combines public and private clouds, allowing data and applications to be shared between them.
- **Example:** Azure Stack

### Cross-Cloud
- **Description:** Integrates multiple cloud services from different providers.
- **Example:** Azure Arc

## Cost Management

### CapEx (Capital Expenditure)
- **Description:** Upfront costs associated with purchasing and owning hardware.
- **Pros:** Generally more cost-effective for licenses.
- **Cons:** Higher upfront costs, less flexibility.

### OpEx (Operational Expenditure)
- **Description:** Ongoing costs associated with cloud services.
- **Pros:** Lower initial costs, better scalability and flexibility.
- **Cons:** Higher ongoing costs for licenses.

## Cloud Architecture Terms

### Availability
- **Definition:** Ensuring services remain online and functional.
- **Example:** High Availability (HA) using multiple availability zones.

### Scalability
- **Definition:** Ability to increase or decrease resources based on demand.
- **Types:**
  - **Vertical Scaling:** Increasing the size of a single resource (e.g., larger VM).
  - **Horizontal Scaling:** Adding more resources (e.g., more VMs).

### Elasticity
- **Definition:** Automatically adjusting resources based on demand.
- **Example:** Azure Scale Sets

### Fault Tolerance
- **Definition:** Ability to continue operating in the event of a failure.
- **Example:** Using load balancers and multiple availability zones.

### Disaster Recovery (DR)
- **Definition:** Strategies to recover from unexpected failures.
- **Example:** Geo-redundant storage and backup solutions.

## High Availability and Scalability

### High Availability
- **Description:** Ensures no single point of failure and maintains performance.
- **Implementation:** Use load balancers and deploy across multiple availability zones.

### High Scalability
- **Description:** Ability to increase capacity based on demand.
- **Scaling Methods:**
  - **Vertical Scaling:** Upgrade existing resources.
  - **Horizontal Scaling:** Add more resources.

### High Elasticity
- **Description:** Automatically adjusts resources based on real-time demand.
- **Example:** Azure Scale Sets

### High Durability
- **Description:** Ensures data is reliably stored and recoverable.
- **Considerations:** Backup strategies, recovery time objectives (RTO), and testing.

## Service Types

### Virtual Machines (VMs)
- **Description:** Provides scalable virtualized computing resources.
- **Example:** Azure Virtual Machines

### Containers
- **Description:** Lightweight, portable, and efficient environment for running applications.
- **Tool:** Docker Daemon
- **Example:** Azure Container Instances

### Functions
- **Description:** Serverless compute service that executes code in response to events.
- **Example:** Azure Functions

## Storage Services

### Blob Storage
- **Description:** Scalable object storage for unstructured data.
- **Example:** Azure Blob Storage

### Disk Storage
- **Description:** Persistent storage attached to VMs.
- **Features:** Encryption by default.

### File Storage
- **Description:** Managed file shares accessible over SMB.
- **Example:** Azure Files

### Queue Storage
- **Description:** Messaging queue for communication between application components.
- **Example:** Azure Queue Storage

### Table Storage
- **Description:** NoSQL key-value store for structured data.
- **Example:** Azure Table Storage

### Data Lake Storage
- **Description:** Store large volumes of data in a scalable manner.
- **Example:** Azure Data Lake Storage

## Database Services

### Cosmos DB
- **Description:** Fully managed NoSQL database with global distribution.
- **Features:** 99.999% availability, multi-model support.
- **Example:** Azure Cosmos DB

### SQL Database
- **Description:** Managed relational database service.
- **Example:** Azure SQL Database

### Database for MySQL
- **Description:** Managed MySQL database service.
- **Example:** Azure Database for MySQL

### SQL Servers on VMs
- **Description:** Host SQL Server on virtual machines.
- **Example:** Azure SQL Server VMs

### Synapse Analytics
- **Description:** Analytics service for large-scale data warehousing.
- **Example:** Azure Synapse Analytics

### Cache for Redis
- **Description:** In-memory data structure store for caching.
- **Example:** Azure Cache for Redis

## Application Integration Services

### Notification Hub
- **Description:** Send notifications to various platforms.
- **Example:** Azure Notification Hubs

### API Apps
- **Description:** Create and manage APIs quickly.
- **Example:** Azure API Management

### Service Bus
- **Description:** Messaging service for reliable communication between applications.
- **Example:** Azure Service Bus

### Stream Analytics
- **Description:** Real-time analytics on streaming data.
- **Example:** Azure Stream Analytics

### Logic Apps
- **Description:** Automate workflows and integrate services.
- **Example:** Azure Logic Apps

## Developer and Mobile Tools

### Azure SignalR Service
- **Description:** Real-time messaging for web applications.
- **Example:** Azure SignalR Service

### App Service
- **Description:** Host web applications and APIs.
- **Example:** Azure App Services

### Visual Studio
- **Description:** Integrated development environment for coding.
- **Example:** Visual Studio Code

### Xamarin
- **Description:** Framework for building mobile applications.
- **Example:** Xamarin

## Networking

### Virtual Networks (vNet)
- **Description:** Isolated network section to launch resources.
- **Example:** Azure Virtual Network

### Subnets
- **Description:** Smaller network segments within a vNet.
- **Types:**
  - **Public:** Accessible from the internet.
  - **Private:** Not accessible from the internet.

### Front Door
- **Description:** Secure point for fast delivery of applications.
- **Example:** Azure Front Door

### ExpressRoute
- **Description:** Fast, private connection from on-premises to Azure.
- **Example:** Azure ExpressRoute

### VPN Gateway
- **Description:** Site-to-site VPN connection.
- **Example:** Azure VPN Gateway

### Traffic Manager
- **Description:** DNS-based traffic load balancer.
- **Example:** Azure Traffic Manager

### Azure DNS
- **Description:** Manage DNS records and domains.
- **Example:** Hosting domain names on Azure.

### Azure Load Balancer
- **Description:** Distributes incoming network traffic across multiple servers.
- **Types:**
  - **Public Load Balancer:** Distributes traffic from the internet.
  - **Internal Load Balancer:** Distributes traffic within a virtual network.

## Security and Compliance

### Key Vault
- **Description:** Securely manage and store cryptographic keys and secrets.
- **Features:** Secrets management, certificate management, hardware security.

### Azure DDoS Protection
- **Description:** Protection against distributed denial-of-service attacks.
- **Tiers:** Basic (free), Standard (paid).

### Azure Firewall
- **Description:** Managed, cloud-based network security service.
- **Features:** Threat intelligence, logging, and policy management.

### Information Protection (AIP)
- **Description:** Protect sensitive information using encryption.
- **Example:** Azure Information Protection

### Application Gateway
- **Description:** Web application firewall and load balancer.
- **Features:** Application-level security, SSL termination.
