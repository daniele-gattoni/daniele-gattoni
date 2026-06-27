# Daniele Gattoni | Cloud Systems Engineer

I'm an **MSc Computer and Robotics Engineer** with a background in **Industrial Automation** and **Embedded Systems** transitioning to **Cloud Computing**. Infrastructures as **Amazon Web Services (AWS)** offer the perfect intersection for my interests in core software development, automated physical devices, and remote control systems. I'm currently working on modern serverless architectures to run new and existing software developed with different languages seamlessly in the cloud, and hybrid pipelines from physical hardware to scalable cloud solutions, focusing on **IoT**, **IIoT** and **Edge Computing**, linking Operational Technology (OT) and Information Technology (IT) in the cloud. All infrastructure deployment is via **Infrastructure as Code (IaC)** through **Terraform**.

## Featured Projects

### Resilient Multi-Tier Web Platform (In Development)  
A highly-available, multi-tier full-stack web platform.  

<img width="2808" height="2187" alt="image" src="https://github.com/user-attachments/assets/30224040-584c-45d2-90aa-e770de797af3" />

**Networking & Protection**: Multi-AZ architecture with strict network isolation using custom VPC subnets and NAT Gateway.  
**Front-End Ecosystem**: Responsive React (TypeScript) dashboard deployed globally via Amazon CloudFront CDN, using Route 53 for DNS.  
**Back-End**: Containerized Node.js/Python API in Docker deployed through AWS ECS running on Fargate.  
**Data Tier**: Fully managed Amazon RDS MySQL database securely isolated inside private subnets with dynamic multi-AZ storage replication.  
**Repository**: [resilient-multi-tier-web-platform](https://github.com/daniele-gattoni/resilient-multi-tier-web-platform)  

### Hybrid IIoT Edge Computing System (In Development)
An architecture focused on Edge Computing for industrial scenarios, ensuring low-latency data processing and operational continuity.

<img width="1476" height="2362" alt="image" src="https://github.com/user-attachments/assets/b964868e-aae0-41cc-a821-868f1b280ae8" />

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [hybrid-iiot-edge-computing-system](https://github.com/daniele-gattoni/hybrid-iiot-edge-computing-system)  

### Corporate Web Application with CI/CD (Planned)
A production-ready, highly available three-tier web infrastructure on AWS built entirely via Terraform. Features multi-AZ EC2 Auto Scaling, secure private subnets, RDS failover, and a GitHub Actions CI/CD pipeline using Packer. 

**Repository**: [corporate-web-application-with-ci-cd](https://github.com/daniele-gattoni/corporate-web-application-with-ci-cd)  

### Automated Secure OTA Firmware Delivery System (Planned)
Make use of AWS Security services to build a secure embedded C++/Python client-side firmware update logic.

**Repository**: [automated-secure-ota-firmware-delivery-system](https://github.com/daniele-gattoni/automated-secure-ota-firmware-delivery-system)  

### Predictive Maintenance Event-Driven Platform (Planned)  
Fully Event-Driven Serverless architecture using AWS messaging and notification services. Custom coding to implement predictive maintenance models.

**Repository**: [predictive-maintenance-event-driven-platform](https://github.com/daniele-gattoni/predictive-maintenance-event-driven-platform)  

---

