
<div align="center">

# ☁️ AWS 3-Tier Application Deployment

### Designing and Deploying a Scalable, Highly Available Cloud Architecture on AWS

<p>
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws" />
  <img src="https://img.shields.io/badge/Region-ap--south--1-blue" />
  <img src="https://img.shields.io/badge/Architecture-3--Tier-success" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
</p>

**A production-style cloud infrastructure project demonstrating AWS networking, compute, database management, security, scalability and monitoring.**

</div>

---

## 📌 Project Overview

This project focuses on designing and deploying a **three-tier web application architecture** using Amazon Web Services (AWS).

The architecture separates the application into three independent layers — Presentation, Application and Database — to achieve better scalability, security, availability and maintainability.

The infrastructure is being implemented in the **AWS Mumbai Region (`ap-south-1`)**, using multiple Availability Zones to demonstrate high availability and fault tolerance.

## 🎯 Project Objectives

- Design a production-style AWS 3-tier architecture.
- Configure a custom Virtual Private Cloud (VPC).
- Implement public and private subnet segmentation.
- Deploy application servers using Amazon EC2.
- Distribute incoming traffic through an Application Load Balancer.
- Configure Auto Scaling for application availability.
- Integrate Amazon RDS for managed database services.
- Implement IAM-based access control and network security.
- Configure monitoring and alerts using Amazon CloudWatch.
- Explore event-driven workflows using Lambda, SQS and SNS.

---

## 🏗️ Architecture Overview

<div align="center">

### AWS 3-Tier Architecture

<!-- Replace this image with your actual architecture diagram -->
<img src="architecture/aws-3-tier-architecture.png" alt="AWS 3-Tier Architecture" width="100%" />

</div>

### Architecture Layers

| Layer | AWS Services | Responsibility |
|---|---|---|
| Presentation | Application Load Balancer | Receives and distributes incoming traffic |
| Application | EC2, Auto Scaling | Processes application requests |
| Database | Amazon RDS | Stores and manages application data |

### Network Design

- Custom VPC for isolated networking.
- Public subnets for internet-facing resources.
- Private subnets for application and database resources.
- Internet Gateway for public internet connectivity.
- Route Tables for network traffic management.
- Security Groups for controlled inbound and outbound access.
- Multiple Availability Zones for improved availability.

---

## 🛠️ AWS Services & Technologies

| Service | Purpose |
|---|---|
| Amazon VPC | Network isolation |
| Subnets | Network segmentation |
| Internet Gateway | Internet connectivity |
| Route Tables | Traffic routing |
| Amazon EC2 | Application hosting |
| Application Load Balancer | Traffic distribution |
| EC2 Auto Scaling | Dynamic capacity management |
| Amazon RDS | Managed relational database |
| AWS IAM | Identity and access management |
| Security Groups | Instance-level network security |
| Amazon CloudWatch | Monitoring and alerting |
| AWS Lambda | Serverless execution |
| Amazon SQS | Message queuing |
| Amazon SNS | Notifications and messaging |

---

## 🔐 Security Implementation

Security is considered throughout the infrastructure design.

- IAM roles and least-privilege permissions.
- Multi-Factor Authentication (MFA).
- Restricted Security Group rules.
- Private application and database subnets.
- No direct public database access.
- Secure application configuration.
- Controlled administrative access.

---

## 📊 High Availability & Scalability

The architecture incorporates the following design considerations:

- Deployment across multiple Availability Zones.
- Application Load Balancer health checks.
- EC2 Auto Scaling based on defined policies.
- Database backup and recovery considerations.
- CloudWatch metrics and alarms.
- Separation of application and database layers.

---

## 📁 Repository Structure

```text
AWS-3-Tier-Application-Deployment/
│
├── README.md
│
├── architecture/
│   ├── aws-3-tier-architecture.png
│   └── architecture-flow.md
│
├── docs/
│   ├── project-overview.md
│   ├── networking.md
│   ├── security.md
│   └── troubleshooting.md
│
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── application/
│
├── screenshots/
│
└── .gitignore
```

---

## 🚀 Implementation Roadmap

| Phase | Implementation | Status |
|---|---|---|
| 01 | GitHub & Project Documentation | 🟡 In Progress |
| 02 | AWS Account & Security Setup | ⬜ Pending |
| 03 | VPC & Subnet Configuration | ⬜ Pending |
| 04 | Internet Gateway & Route Tables | ⬜ Pending |
| 05 | Security Groups | ⬜ Pending |
| 06 | EC2 Application Deployment | ⬜ Pending |
| 07 | Application Load Balancer | ⬜ Pending |
| 08 | Auto Scaling Configuration | ⬜ Pending |
| 09 | Amazon RDS Integration | ⬜ Pending |
| 10 | CloudWatch Monitoring & Alarms | ⬜ Pending |
| 11 | Lambda, SQS & SNS Integration | ⬜ Pending |
| 12 | Testing & Troubleshooting | ⬜ Pending |
| 13 | Final Documentation | ⬜ Pending |

---

## 💰 Cost Optimization

Cost management considerations include:

- Selecting appropriately sized EC2 instances.
- Monitoring AWS resource utilization.
- Configuring AWS Budgets and billing alerts.
- Cleaning up unused resources after testing.
- Reviewing NAT Gateway, storage and data transfer costs.
- Evaluating RDS instance sizing and backup requirements.

---

## 🧠 Key Learning Outcomes

This project is designed to demonstrate practical understanding of:

- AWS Cloud Infrastructure.
- VPC and Network Architecture.
- High Availability and Fault Tolerance.
- Load Balancing and Auto Scaling.
- Database Management.
- IAM and Cloud Security.
- Infrastructure Monitoring.
- Troubleshooting and Cost Optimization.
- Event-Driven Architecture.

---

## 📸 Project Implementation

Screenshots, architecture diagrams, deployment evidence and configuration documentation will be added as each implementation phase is completed.

---

## 👨‍💻 Project Information

| Detail | Information |
|---|---|
| Project | AWS 3-Tier Application Deployment |
| Cloud Provider | Amazon Web Services |
| AWS Region | Asia Pacific (Mumbai) |
| Region Code | `ap-south-1` |
| Project Category | Cloud Infrastructure |
| Learning Platform | PaperLive Learning |
| Status | In Progress |

---

<div align="center">

### ☁️ Building Scalable Infrastructure, One Layer at a Time.

**Designed & Implemented as a Hands-on Cloud Engineering Project**

</div>
