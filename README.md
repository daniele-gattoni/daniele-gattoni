# Daniele Gattoni | Cloud DevOps Engineer 

Cloud DevOps Engineer | AWS Certified Solutions Architect | M.Sc. Computer and Robotics Engineer  

Cloud DevOps Engineer with three years of independent contracting experience and more than five years foundational background as a Software Engineer. Hardened experience in automating infrastructure deployment, orchestrating containers, building CI/CD pipelines and troubleshooting production issues. Specialized in IoT and Edge Computing to connect OT systems with IT cloud architectures.

*The technical stack*  
▪	Amazon AWS, Microsoft Azure, Google Cloud Platform (GCP)  
▪	Docker, Kubernetes, Helm; Amazon RDS, Aurora, SQL, DynamoDB  
▪	GitHub Actions, Terraform, Argo CD, Ansible, Python, Bash  
▪	OpenTelemetry, Prometheus, Grafana, ELK/EFK, Amazon CloudWatch  
▪	AWS IAM, KMS, Secrets Manager, SCPs, HashiCorp Vault, Checkov, Trivy  
▪	OPC-UA, Siemens PLCs, IIoT, Edge Computing, MQTT, Modbus, C/C++, RTOS  

*Let's connect*  
I'll take care of your cloud infrastructure, handling the structural work, maintaining the building, and securing the perimeter - so your developers can focus entirely on building value.  
Email: daniele.gattoni@outlook.com  
Linkedin: [linkedin.com](https://www.linkedin.com/in/daniele-gattoni)  
Engagement model: B2B contracts  
Availability: remote or hybrid (EU, I live around CEE/SE) 

## Cloud-Native Infrastructure and DevOps Implementations

### AWS Enterprise Multi-Tier Web Platform  
A highly-available, multi-tier full-stack web platform.  
<img width="2808" height="2167" alt="image" src="https://github.com/user-attachments/assets/c9286620-4892-4f66-b21d-30c790a76d1a" />  

**Networking & Protection**: Multi-AZ architecture with strict network isolation using custom VPC subnets and NAT Gateway.  
**Front-End Ecosystem**: Responsive React (TypeScript) dashboard deployed globally via Amazon CloudFront CDN, using Route 53 for DNS.  
**Back-End**: Containerized Node.js/Python API in Docker deployed through AWS ECS running on Fargate.  
**Data Tier**: Fully managed Amazon RDS MySQL database securely isolated inside private subnets with dynamic multi-AZ storage replication.  
**Repository**: [aws-enterprise-multi-tier-web-platform](https://github.com/daniele-gattoni/aws-enterprise-multi-tier-web-platform)  

---

### Kubernetes CI/CD Pipeline
Production-grade AWS EKS GitOps pipeline automated via Terraform and GitHub Actions, secured with OIDC, Checkov, and Trivy, orchestrated by Argo CD.

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [eks-gitops-devsecops-pipeline](https://github.com/daniele-gattoni/eks-gitops-devsecops-pipeline)  

---

### IaaS Telemetry Traditional Architecture
Enterprise traditional IaaS framework provisioning AWS EC2 environments via Terraform, automating Linux configurations through Ansible, monitored via Prometheus & Grafana.

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [hybrid-iiot-edge-computing-system](https://github.com/daniele-gattoni/hybrid-iiot-edge-computing-system) 

---


### AWS Multi-Account Governance Landing Zone

**Enterprise Governance**: Multi-account AWS Organizations landing zone structured under AWS Control Tower guardrails, isolating corporate workloads across distinct Development, Production, and Shared-Services accounts  
**Cross-Account Resource Sharing**: Centralized high-availability networking topology utilizing AWS RAM (Resource Access Manager) to securely share VPC subnets and infrastructure resources from the Shared-Services hub to downstream environments, optimizing network topology and cutting data transfer overhead.  
**Strict Cloud Compliance**: Implementation of infrastructure-level Service Control Policies (SCPs) to enforce mandatory multi-factor authentication (MFA), strict geographical region-locking, and tamper-proof CloudTrail auditing across the entire organization.  
**Automated Identity Federation**: Centralized access management and least-privilege permission boundary orchestration leveraging AWS IAM Identity Center (AWS SSO) for programmatic cross-account assuming roles.  
**Repository**: [aws-multiaccount-governance-landing-zone](https://github.com/daniele-gattoni/aws-multiaccount-governance-landing-zone)  

---

### Hybrid IIoT Edge Computing System 
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

### Automated Secure OTA Firmware Delivery System 
//  

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [hybrid-iiot-edge-computing-system](https://github.com/daniele-gattoni/hybrid-iiot-edge-computing-system)

---

### Predictive Maintenance Event-Driven Platform 
//  

**Industrial Edge**: Python-based OPC UA simulator generating telemetry ingested locally by AWS IoT Greengrass V2 with offline caching.  
**Secure Ingestion**: Bidirectional mTLS communication via AWS IoT Core handling device synchronization using Named Device Shadows.  
**Data Processing**: Event-driven AWS IoT Rules Engine routing raw payloads instantly into AWS Lambda parsing functions.  
**Dual-Engine Storage**: Real-time telemetry routed to Amazon Timestream and machine lifecycle states stored in Amazon DynamoDB.  
**Serverless Backend**: Secure, scalable Amazon API Gateway layer fetching sub-second analytical metrics using on-demand AWS Lambda queries.  
**Global Frontend**: Single-page React (TypeScript) web application hosted on Amazon S3 and accelerated via Amazon CloudFront CDN.  
**Repository**: [hybrid-iiot-edge-computing-system](https://github.com/daniele-gattoni/hybrid-iiot-edge-computing-system)

---

## Extra 

### MantaCore: Distributed Edge IoT and SCADA Platform for Maritime Operations
MantaCore is a simulated end-to-end industrial control platform (ICS) for cargo ships or isolated critical installations. 
It's a SCADA shipboard system inspired by distributed automation systems and the responsive CLI of classic 90s systems, but implemented with cloud-native enterprise logic.
Distributed Edge IoT & SCADA platform for maritime workloads, leveraging AWS IoT Core (MQTT), Amazon DynamoDB state storage, and unified CloudWatch/Grafana telemetry.

**Edge Control Simulation**: Python-based event-driven industrial simulator replicating maritime/facility hardware states (bulkheads, sensors, actuators) with automated local file-trigger feedback loops.  
**Containerized Host**: Lightweight multi-stage Docker environment isolating the Python runtime execution and core dependencies to guarantee micro-service portability.  
**Secure Event Brokerage**: Real-time bidirectional telemetry ingestion via AWS IoT Core MQTT protocol, handling remote commands and status synchronization under low-bandwidth network constraints.  
**Serverless State Storage**: On-demand Amazon DynamoDB architecture mapping and preserving the live analytical state of distributed infrastructure components with zero maintenance overhead.  
**Unified Observability**: Complete telemetry monitoring and alerting infrastructure leveraging native Amazon CloudWatch Alarms combined with custom Prometheus metrics and central Grafana dashboards.  
**Dual-Mode Interface**: Secure, low-latency operator control plane featuring a unified Web UI alongside a retro-inspired, high-privilege raw interactive CLI Terminal for system override commands.  
**Repository**: [manta-core-shipboard-scada](https://github.com/daniele-gattoni/manta-core-shipboard-scada)
