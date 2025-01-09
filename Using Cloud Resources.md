[[ICCA-Questions]]
[[Cloud-Basics]]
[[Manage-Cloud-Resources-LAB-1]]
[[Manage-Cloud-Resources-LAB-2]]
[[Manage-Cloud-Resources-LAB-3]]
[[Limitations-Cloud-INE-LABS]]
[[Cloud-Cost-Management-Google]]
[[Cloud-Cost-Management-Azure-Lab]]
[[Cloud-Cost-Management-AWS-Lab]]
[[Provision-a-Compute-Instance-AWS-Lab]]
[[Provision-an-Azure-Virtual-Machine-Lab]]
[[Provision-a-GCP-Virtual-Machine-Lab]]
### Cloud Infrastructure Services

- Infrastructure as service
- Cloud networking
- Cloud Compute
- Cloud Storage
- IaaS - Infrastructure as a Service

![[2025-01-06_10-20.png]]

![[Pasted image 20250106103025.png]]
#### Virtual Network

![[Pasted image 20250106104729.png]]

	VN, subnets, IP ranges, Network security group/ Access control, routing, 
	VN/  VPC level --> DNS, 
	gateways --> VPN gateway, private circuit gateway
	Load balancers
	Firewall - F5
### Firewalls

- **F5 firewall** is a type of network security device that helps protect your network by monitoring and controlling incoming and outgoing network traffic based on predetermined security rules. F5 offers several types of firewalls, including **Next-Generation Firewalls (NGFW)** and **Web Application Firewalls (WAF)**.

- **Policy-Based Access Control**: F5 firewalls provide policy-based access control to and from address and port pairs, both inside and outside your network.

- **Advanced Threat Protection**: They include capabilities like intrusion prevention systems (IPS) and URL filtering to block incoming threats such as malware.

- **Application Layer Security**: F5 firewalls can inspect traffic at the application layer, allowing them to detect and block sophisticated attacks targeting specific applications.

- **High Availability and Scalability**: F5 firewalls are designed to be highly available and scalable, ensuring consistent performance even under heavy network traffic.

- **Integration with Other Security Solutions**: They can be integrated with other security solutions to provide comprehensive protection in today's complex cyber threat landscape.

![[Pasted image 20250106105930.png]]
	Image --> Windows, Linux (Linux has different variations)
	Software --> LAMP Stack
- The **LAMP stack** is a popular set of open-source software commonly used to build dynamic websites and web applications. LAMP is an acronym that stands for:
  
1. **Linux**: The operating system that provides the foundation for the stack.
2. **Apache**: The web server software that handles requests and serves web pages to users.
3. **MySQL**: The relational database management system used to store and manage the data for the website or application.
4. **PHP** (or sometimes Python/Perl): The programming language used to create dynamic content that interacts with the database and generates the web pages.

- Custom Images 
- Storage
- Security and Access

### Cloud Storage

![[Pasted image 20250106110906.png]]
##### AWS
- **Amazon S3 (Simple Storage Service)**:
  *Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It's designed to store and retrieve any amount of data from anywhere on the web2. S3 is highly durable, with 99.999999999% (11 nines) of data durability and 99.99% availability.*
  
- **Amazon EFS (Elastic File System)**:
  *Amazon EFS provides a simple, scalable, fully managed elastic NFS (network file system) file system for use with AWS cloud services and on-premises resources. It automatically grows and shrinks as you add and remove files, making it easy to manage storage capacity3. EFS is designed for applications that require shared file storage, such as content management systems, home directories, and big data analytics.*

- **Amazon EBS (Elastic Block Store):**
  *Amazon EBS provides block-level storage volumes for use with Amazon EC2 instances. EBS volumes are highly available and reliable, with options for SSD-backed storage for transactional workloads and HDD-backed storage for throughput-intensive workloads5. EBS volumes can be used as primary storage for instances, and they support snapshots for backup and recovery.*

### Cloud Platform Services

- Platform as a Service
- Application Hosting
- Data Hosting
- Other Services

![[Pasted image 20250106143425.png]]

![[Pasted image 20250106143640.png]]
 ![[Pasted image 20250106143722.png]]
 
#### Other Services
- Authentication and Identity services
- Security services
- Media services
- Migration Services
- Archiving Services
- Machine Learning 
- Cognitive Services
- IoT Services
- More ....

### Application Hosting Demo

```
go to AWS management console
RDS ---> create a relational database
Standard Create ---> MySQL
Templates --> production/ free tire [Choose One]
DB-Instance Size ---> Standard Classes --> db.m6g.large
Storage Type ---> Provisioned IOPs
Allocate Storage ---> 100 GiB
Provisioned IOPS ---> 3000
Enable Autoscaling
Database Authentication ---> IAM database authentication

```

![[Pasted image 20250108161734.png]]

```
go to AWS Console ----> Lambda 
Create a Funtion
Set ---> Name , Runtime as Python<version>
Click Create

Go to the Function
Designer ---> Add a Trigger
(Trigger Configuration)
---> API Gateway
```

![[Pasted image 20250108163836.png]]

![[Pasted image 20250108164216.png]]
![[Pasted image 20250108164416.png]]

### AWS Fargate

**AWS Fargate** is a serverless compute engine for running containers. It eliminates the need to manage servers or clusters1. You just need to specify the CPU and memory requirements, and Fargate handles the rest. It integrates seamlessly with Amazon ECS and EKS1.

### Google Cloud Run

**Google Cloud Run** is a managed compute platform that allows you to run containers directly on Google's infrastructure. It's serverless, meaning you don't need to manage infrastructure3. You can deploy code in any language, and Cloud Run handles scaling, load balancing, and security.

### Amazon Lightsail

**Amazon Lightsail** is an easy-to-use virtual private server (VPS) service. It includes everything you need to launch a project quickly, such as instances, managed databases, storage, and networking5. It's designed for simplicity and cost-effectiveness, making it great for beginners.

### Google Kubernetes Engine (GKE)

**Google Kubernetes Engine (GKE)** is a managed environment for deploying, managing, and scaling containerized applications using Kubernetes. It simplifies the process of running Kubernetes clusters, handling upgrades, and providing high availability6.

## Software as a Service

![[Pasted image 20250108165606.png]]

**Salesforce** is a leading customer relationship management (CRM) platform that helps organizations manage and analyze customer interactions and data throughout the customer lifecycle. It aims to improve business relationships, streamline processes, and enhance customer service.

Salesforce offers a variety of applications for different business functions, including:

- **Sales Cloud**: Tools for managing sales processes, tracking leads, and closing deals.
    
- **Service Cloud**: Solutions for delivering customer service and support.
    
- **Marketing Cloud**: Platforms for creating and managing marketing campaigns.
    
- **Commerce Cloud**: Tools for building and managing e-commerce websites.
    
- **IT Service Management**: Applications for managing IT services and support.

### Service Providers

- **Salesforce**
- **Microsoft 365**
- **G Suite**
![[Pasted image 20250109110333.png]]

![[Pasted image 20250109110409.png]]

### Scalability and Availability


