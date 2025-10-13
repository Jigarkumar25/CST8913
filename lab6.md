# Lab-6:Cloud Resource Comparison Across AWS, Azure, and Google Cloud
## **Student:** Jigarkumar Patel <br>
## Cloud Resource Descriptions and Comparison Table:

| #  | Description | AWS (Service Name) | Azure (Service Name) | Google Cloud (Service Name) |
|----|-------------|--------------------|----------------------|----------------------------|
| 1  | A compute service that provides scalable virtual machines for running applications. | EC2 (Elastic Compute Cloud) | Virtual Machines | Compute Engine |
| 2  | An object storage service used to store and retrieve data, commonly used for backups and static website content. | S3 (Simple Storage Service) | Blob Storage | Cloud Storage |
| 3  | A managed relational database service that supports multiple database engines like MySQL, PostgreSQL, and SQL Server. | RDS (Relational Database Service) | Azure SQL Database | Cloud SQL |
| 4  | A serverless compute service that allows you to run code in response to events without provisioning or managing servers. | Lambda | Azure Functions | Cloud Functions |
| 5  | A virtual private network service that allows you to create isolated networks within the cloud provider's infrastructure. | VPC (Virtual Private Cloud) | Virtual Network (VNet) | VPC (Virtual Private Cloud) |
| 6  | A content delivery network (CDN) service that delivers data, videos, applications, and APIs to customers around the world with low latency. | CloudFront | Azure CDN | Cloud CDN |
| 7  | A managed NoSQL database service designed for low-latency, high-scale applications. | DynamoDB | Cosmos DB | Firestore / Cloud Bigtable |
| 8  | A block storage service for use with virtual machines, offering persistent storage for data. | EBS (Elastic Block Store) | Managed Disks | Persistent Disks |
| 9  | A managed container orchestration service based on Kubernetes. | EKS (Elastic Kubernetes Service) | AKS (Azure Kubernetes Service) | GKE (Google Kubernetes Engine) |
| 10 | A service for managing user access and encryption keys to secure cloud resources. | KMS (Key Management Service) | Key Vault | Cloud KMS |
| 11 | A platform that automates application deployment and scaling without needing to manage infrastructure. | Elastic Beanstalk | App Service | App Engine |
| 12 | A service that provides monitoring and logging of applications and infrastructure, offering insights into resource usage and performance. | CloudWatch | Azure Monitor | Cloud Operations (Stackdriver) |
| 13 | A domain name system (DNS) service that routes traffic globally and translates domain names to IP addresses. | Route 53 | Azure DNS | Cloud DNS |
| 14 | A load balancing service that distributes incoming network traffic across multiple targets, improving application availability. | Elastic Load Balancing (ELB/ALB/NLB) | Azure Load Balancer / Application Gateway | Cloud Load Balancing |
| 15 | A service that automatically scales your cloud infrastructure based on demand, ensuring resources are available as needed. | Auto Scaling | VM Scale Sets | Autoscaler |
| 16 | A message queuing service that enables applications to send and receive messages between different components. | SQS (Simple Queue Service) | Azure Queue Storage / Service Bus | Pub/Sub |
| 17 | A managed real-time data streaming service that collects and processes large amounts of data from various sources. | Kinesis | Event Hubs | Pub/Sub / Dataflow |
| 18 | A fully managed, highly scalable data warehouse service optimized for analytics and large-scale queries. | Redshift | Synapse Analytics | BigQuery |
| 19 | A service that automates the execution of workflows and allows the integration of different cloud services in a sequence of steps. | Step Functions | Logic Apps | Cloud Composer / Workflows |
| 20 | A service that integrates multiple data sources and enables data migration, transformation, and movement across platforms. | AWS Glue / Data Pipeline | Data Factory | Dataflow |
| 21 | A data catalog and governance service that helps manage metadata across your data estate, supporting compliance and security. | Glue Data Catalog | Purview | Data Catalog |
| 22 | A set of machine learning and AI services that provide pre-built models, APIs, and tools for developers to easily implement AI in their apps. | SageMaker | Azure Machine Learning | Vertex AI |
| 23 | A service that allows you to define and deploy infrastructure using code, automating the management of cloud resources. | CloudFormation | ARM Templates / Bicep | Deployment Manager / Terraform |
| 24 | A fully managed CI/CD service that automates the building, testing, and deployment of applications to production environments. | CodePipeline | Azure DevOps / GitHub Actions | Cloud Build |
| 25 | A desktop as a service (DaaS) offering that allows you to deploy virtual desktops in the cloud and access them remotely. | WorkSpaces | Azure Virtual Desktop | Workspaces / AppStream |
| 26 | A backup and disaster recovery service that helps to protect your data by creating backups and replicas of your cloud resources. | AWS Backup | Azure Backup / Site Recovery | Backup and DR Service |
| 27 | A service designed for big data analytics, allowing organizations to store, process, and analyze large datasets in real time. | EMR (Elastic MapReduce) | HDInsight / Synapse | Dataproc / BigQuery |
| 28 | A file storage service for storing and sharing files with users, typically used in shared file systems across applications. | EFS (Elastic File System) / FSx | Azure Files | Filestore |
| 29 | A service that helps you transcode, process, and stream media content such as video and audio. | Elastic Transcoder / MediaConvert | Media Services | Transcoder API |
| 30 | A real-time communication service used for sending notifications, emails, and text messages to users and devices. | SNS (Simple Notification Service) | Notification Hubs | Firebase Cloud Messaging (FCM) |


### Cloud Service Comparison: AWS vs Azure vs Google Cloud

Cloud computing platforms from Amazon, Microsoft, and Google provide similar capabilities under different names and ecosystems. While the core functions compute, storage, networking, databases, and AI are conceptually the same, each vendor differentiates itself with unique integrations, pricing models, and management tools.
1) Core Infrastructure Similarities<br> 
All three providers offer comparable foundational services:<br>
**Compute:** AWS EC2, Azure VMs, and GCP Compute Engine deliver scalable virtual machines.<br>
**Storage:** Object storage (S3, Blob, Cloud Storage) forms the backbone for data backups and static content delivery.<br>
**Networking:** Each uses isolated virtual networks VPC or VNet for secure communication between cloud resources.<br>

2) Data and Databases<br>
All platforms provide both relational (RDS, SQL Database, Cloud SQL) and NoSQL (DynamoDB, Cosmos DB, Firestore) options. Azure Cosmos DB stands out for global distribution and multi-model APIs, while AWS RDS supports the widest range of database engines.

3) Application and Serverless Computing<br>
AWS Lambda, Azure Functions, and Cloud Functions all allow event-driven execution without server management. PaaS solutions like Elastic Beanstalk, App Service, and App Engine simplify web-app deployment, but AWS integrates more tightly with developer pipelines, while Google focuses on simplicity and automatic scaling.

4) Analytics and Big Data<br>
Big data ecosystems overlap: AWS Redshift + EMR, Azure Synapse + HDInsight, and Google BigQuery + Dataproc. Google’s stack is the most serverless and analytics-oriented, while AWS offers granular control.<br>

5) Security and IAM<br>
Security tools such as AWS KMS, Azure Key Vault, and Cloud KMS all support encryption key lifecycle management. Identity and access control integrate with each cloud’s IAM framework.<br>

6) DevOps and Automation<br>
Each platform provides infrastructure-as-code (CloudFormation, ARM/Bicep, Deployment Manager) and CI/CD (CodePipeline, Azure DevOps, Cloud Build). Azure benefits from tight GitHub integration, while AWS offers broader service automation coverage.<br>

7) AI and Emerging Technologies<br>
All three emphasize AI SageMaker, Azure ML, and Vertex AI but Google leads in pretrained APIs for speech, vision, and translation due to its AI heritage.<br>

8) Key Differences<br>
**Ecosystem:** AWS offers the largest breadth of services.<br>
**Hybrid/Enterprise focus:** Azure aligns best with Microsoft enterprise tools.<br>
**Data & AI:** Google Cloud is strongest in analytics and machine learning.

### Conclusion
While naming and interface design differ, the three cloud providers share equivalent offerings across almost every domain. The best choice depends on an organization’s priorities AWS for scale and maturity, Azure for enterprise integration, and Google Cloud for data analytics innovation.