# Daniele Gattoni | Cloud DevOps Engineer

I'm an MSc Computer and Robotics Engineer with a background in Industrial Automation and Embedded Systems transitioning to Cloud Computing. Infrastructures as Amazon Web Services (AWS) offer the perfect intersection for my interests in core software development, automated physical devices, and remote control systems. I'm currently working on modern serverless architectures to run new and existing software developed with different languages seamlessly in the cloud, and hybrid pipelines from physical hardware to scalable cloud solutions, focusing on IoT and Edge Computing. All infrastructure deployment is via Infrastructure as Code (IaC) through Terraform.

## Featured Projects

### AWS Enterprise Multi-Tier Web Platform (Status - Ready)  
A highly-available, multi-tier full-stack web platform.  

<img width="2808" height="2167" alt="image" src="https://github.com/user-attachments/assets/c9286620-4892-4f66-b21d-30c790a76d1a" />

**Networking & Protection**: Multi-AZ architecture with strict network isolation using custom VPC subnets and NAT Gateway.  
**Front-End Ecosystem**: Responsive React (TypeScript) dashboard deployed globally via Amazon CloudFront CDN, using Route 53 for DNS.  
**Back-End**: Containerized Node.js/Python API in Docker deployed through AWS ECS running on Fargate.  
**Data Tier**: Fully managed Amazon RDS MySQL database securely isolated inside private subnets with dynamic multi-AZ storage replication.  
**Repository**: [aws-enterprise-multi-tier-web-platform](https://github.com/daniele-gattoni/aws-enterprise-multi-tier-web-platform)  

### Hybrid IIoT Edge Computing System (Planned)
An architecture focused on Edge Computing for industrial scenarios, ensuring low-latency data processing and operational continuity.

<img width="1476" height="2362" alt="image" src="https://github.com/user-attachments/assets/b964868e-aae0-41cc-a821-868f1b280ae8" />

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [hybrid-iiot-edge-computing-system](https://github.com/daniele-gattoni/hybrid-iiot-edge-computing-system)  

---

