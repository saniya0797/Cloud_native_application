# Cloud-Native Backend Development Workflow



## __Overview__
This repository is dedicated to showcasing a comprehensive backend development workflow, simulating a real-world project environment. The project revolves around building a Java spring-boot application, deploying it on AWS, and managing its infrastructure through 
Infrastructure as Code (IaC) practices. The project spans across multiple repositories, each catering to specific aspects of the development lifecycle, including serverless functions, web application development, and cloud infrastructure management.

## __Project Scope__

### Web Application (Java spring-boot): 
A dynamic, CRUD-capable application interfacing with MySql for data management.
Cloud Deployment: Utilizing AWS services such as EC2, RDS, VPC, IAM, and Route53 for deployment and operational purposes.
Serverless Architecture: AWS Lambda functions are employed for handling specific backend processes, enhancing the application's scalability and efficiency.
### CI/CD Pipelines:
Integrated within GitHub Actions to automate testing and deployment phases.
### IaC with Pulumi: 
Managing and provisioning cloud resources in an automated and replicable manner.
### Logging and Monitoring:
Leveraging AWS CloudWatch for real-time monitoring and logging of the application.
Load Balancing & Autoscaling: Ensuring high availability and optimal resource usage through AWS load balancers and auto-scaling groups.

## __Repositories__

### **Serverless:** 
Contains AWS Lambda functions for asynchronous tasks and event handling.
### **Webapp:**
The Java spring-boot  web application with detailed setup and deployment instructions.
### **IaC-Pulumi:**
Scripts and configurations for cloud resource management using Pulumi.
