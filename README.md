# AZ-900 Study Notes

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
13. [Azure DevOps Services](#azure-devops-services)
14. [Networking](#networking)
15. [Security and Compliance](#security-and-compliance)

## Cloud Responsibilities

### IAAS (Infrastructure as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Runtime, Middleware, OS
- **Example:** [Azure Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

### PAAS (Platform as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Runtime, Middleware, OS
- **Example:** [Azure App Services](https://azure.microsoft.com/en-us/services/app-service/)

### SaaS (Software as a Service)
- **Customer Responsibilities:** Applications, Data
- **Cloud Provider Responsibilities:** Everything else
- **Example:** [Microsoft 365](https://www.microsoft.com/en-us/microsoft-365)

## Cloud Deployments

### Public Cloud
- **Description:** All resources are hosted in the cloud provider’s infrastructure.
- **Example:** [Azure](https://azure.microsoft.com/)

### Private Cloud
- **Description:** All resources are hosted within an organization's own data center.
- **Example:** On-premises data center

### Hybrid Cloud
- **Description:** Combines public and private clouds, allowing data and applications to be shared between them.
- **Example:** [Azure Stack](https://azure.microsoft.com/en-us/services/azure-stack/)

### Cross-Cloud
- **Description:** Integrates multiple cloud services from different providers.
- **Example:** [Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/)

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
- **Example:** [Azure Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/)

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
- **Example:** [Azure Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/)

### High Durability
- **Description:** Ensures data is reliably stored and recoverable.
- **Considerations:** Backup strategies, recovery time objectives (RTO), and testing.

## Service Types

### Virtual Machines (VMs)
- **Description:** Provides scalable virtualized computing resources.
- **Example:** [Azure Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

### Containers
- **Description:** Lightweight, portable, and efficient environment for running applications.
- **Tool:** Docker Daemon
- **Example:** [Azure Container Instances](https://azure.microsoft.com/en-us/services/container-instances/)

### Functions
- **Description:** Serverless compute service that executes code in response to events.
- **Example:** [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)

## Storage Services

### Blob Storage
- **Description:** Scalable object storage for unstructured data.
- **Example:** [Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/)

### Disk Storage
- **Description:** Persistent storage attached to VMs.
- **Features:** Encryption by default.

### File Storage
- **Description:** Managed file shares accessible over SMB.
- **Example:** [Azure Files](https://azure.microsoft.com/en-us/services/storage/files/)

### Queue Storage
- **Description:** Messaging queue for communication between application components.
- **Example:** [Azure Queue Storage](https://azure.microsoft.com/en-us/services/storage/queues/)

### Table Storage
- **Description:** NoSQL key-value store for structured data.
- **Example:** [Azure Table Storage](https://azure.microsoft.com/en-us/services/storage/tables/)

### Data Lake Storage
- **Description:** Store large volumes of data in a scalable manner.
- **Example:** [Azure Data Lake Storage](https://azure.microsoft.com/en-us/services/storage/data-lake-storage/)

## Database Services

### Cosmos DB
- **Description:** Fully managed NoSQL database with global distribution.
- **Features:** 99.999% availability, multi-model support.
- **Example:** [Azure Cosmos DB](https://azure.microsoft.com/en-us/services/cosmos-db/)

### SQL Database
- **Description:** Managed relational database service.
- **Example:** [Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)

### Database for MySQL
- **Description:** Managed MySQL database service.
- **Example:** [Azure Database for MySQL](https://azure.microsoft.com/en-us/services/mysql/)

### SQL Servers on VMs
- **Description:** Host SQL Server on virtual machines.
- **Example:** [Azure SQL Server VMs](https://azure.microsoft.com/en-us/services/sql-server/)

### Synapse Analytics
- **Description:** Analytics service for large-scale data warehousing.
- **Example:** [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/)

### Cache for Redis
- **Description:** In-memory data structure store for caching.
- **Example:** [Azure Cache for Redis](https://azure.microsoft.com/en-us/services/cache/)

## Application Integration Services

### Notification Hub
- **Description:** Send notifications to various platforms.
- **Example:** [Azure Notification Hubs](https://azure.microsoft.com/en-us/services/notification-hubs/)

### API Apps
- **Description:** Create and manage APIs quickly.
- **Example:** [Azure API Management](https://azure.microsoft.com/en-us/services/api-management/)

### Service Bus
- **Description:** Messaging service for reliable communication between applications.
- **Example:** [Azure Service Bus](https://azure.microsoft.com/en-us/services/service-bus/)

### Stream Analytics
- **Description:** Real-time analytics on streaming data.
- **Example:** [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/)

### Logic Apps
- **Description:** Automate workflows and integrate services.
- **Example:** [Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/)

## Developer and Mobile Tools

### Azure SignalR Service
- **Description:** Real-time messaging for web applications.
- **Example:** [Azure SignalR Service](https://azure.microsoft.com/en-us/services/signalr/)

### App Service
- **Description:** Host web applications and APIs.
- **Example:** [Azure App Services](https://azure.microsoft.com/en-us/services/app-service/)

### Visual Studio
- **Description:** Integrated development environment for coding.
- **Example:** [Visual Studio Code](https://code.visualstudio.com/)

### Xamarin
- **Description:** Framework for building mobile applications.
- **Example:** [Xamarin](https://dotnet.microsoft.com/apps/xamarin)

## Azure DevOps Services

### Boards
- **Description:** Agile project management tools.
- **Example:** [Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/)

### Pipelines
- **Description:** CI/CD service for building, testing, and deploying code.
- **Example:** [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/)

### Repos
- **Description:** Source control with private Git repositories.
- **Example:** [Azure Repos](https://azure.microsoft.com/en-us/services
