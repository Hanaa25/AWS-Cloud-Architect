# ☁️ AWS Project 1 — Highly Available & Scalable Web Application

A practical AWS Cloud project demonstrating the design and deployment of a **highly available, scalable, secure, and cost-effective web application** using AWS services and following the principles of the **AWS Well-Architected Framework**.

---

## 🚀 Project Overview

This project demonstrates the design and deployment of a **highly available, scalable, secure, and cost-effective web application on AWS**.

The application manages **student records** and allows users to:

* View student records
* Add student records
* Modify student records
* Delete student records

The architecture is designed to improve **availability, scalability, security, performance, and cost efficiency**.

---

## 🏗️ AWS Architecture

![AWS Infrastructure](./Diagram.png)

The architecture uses multiple AWS services working together to provide a reliable and secure application environment.

### Architecture Components

* **Amazon VPC** — Provides an isolated network environment.
* **Amazon EC2** — Hosts the web application.
* **Application Load Balancer** — Distributes incoming traffic across EC2 instances.
* **Auto Scaling** — Automatically adjusts EC2 capacity based on demand.
* **Amazon RDS** — Provides a managed relational database for student records.
* **AWS Secrets Manager** — Securely stores sensitive database credentials.
* **Security Groups** — Control network traffic between AWS resources.

---

## 🔄 Application Flow

```text
Users
  │
  ▼
Application Load Balancer
  │
  ▼
EC2 Instances
  │
  ▼
Amazon RDS
```

The Application Load Balancer distributes incoming requests across the available EC2 instances.

The EC2 instances communicate with Amazon RDS to store and retrieve student records.

AWS Secrets Manager is used to securely manage sensitive credentials, while Security Groups control network access between resources.

---

## 🧩 AWS Services Used

| AWS Service               | Purpose                              |
| ------------------------- | ------------------------------------ |
| Amazon VPC                | Network isolation and infrastructure |
| Amazon EC2                | Application hosting                  |
| Application Load Balancer | Traffic distribution                 |
| Auto Scaling              | Automatic scaling of EC2 instances   |
| Amazon RDS                | Managed relational database          |
| AWS Secrets Manager       | Secure credential management         |
| Security Groups           | Network traffic control              |

---

## 🎯 Key Concepts Demonstrated

### High Availability

The architecture is designed to minimize single points of failure and maintain application availability.

### Scalability

EC2 Auto Scaling allows the infrastructure to automatically adjust compute capacity according to workload requirements.

### Load Balancing

The Application Load Balancer distributes incoming traffic across available EC2 instances.

### Secure Database Architecture

Amazon RDS is used as the managed database layer, while network access is controlled using Security Groups.

### Network Security

Security Groups restrict inbound and outbound traffic between the different components of the architecture.

### Secrets Management

AWS Secrets Manager securely stores sensitive credentials instead of exposing them directly in application code.

### Cost Optimization

The architecture considers resource utilization and cost while maintaining the required availability, security, and performance.

---

## 🔐 Security

Security is implemented through multiple layers:

* **Amazon VPC** for network isolation
* **Security Groups** for access control
* **AWS Secrets Manager** for sensitive credentials
* Separation between the application and database layers
* Restricted communication between infrastructure components

---

## 📈 Scalability & Availability

The architecture supports scalability and availability through:

* Application Load Balancer
* EC2 Auto Scaling
* Multiple EC2 application instances
* Amazon RDS
* VPC-based network architecture

This allows the application to handle changing workloads while improving reliability and performance.

---

## 💰 Cost Optimization

Cost considerations are included as part of the project design.

The architecture aims to balance:

* High Availability
* Scalability
* Security
* Performance
* Cost Optimization

A detailed cost estimation is included in the project documentation.

---

## 📄 Project Documentation

The complete project documentation contains:

* Detailed implementation steps
* AWS configuration
* Architecture
* Screenshots
* Testing
* Security configuration
* Cost estimation

📄 **[Open Project 1 Documentation](./project1.pdf)**

---

## 📸 Architecture Diagram

![AWS Infrastructure](./Diagram.png)

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* AWS Cloud Architecture
* Amazon VPC
* Amazon EC2
* Amazon RDS
* Application Load Balancer
* EC2 Auto Scaling
* AWS Secrets Manager
* Security Groups
* High Availability
* Scalability
* Load Balancing
* Network Security
* Cost Optimization
* AWS Well-Architected Framework

---

## 📁 Repository Structure

```text
AWS-Cloud-Projects/
│
├── README.md
├── project1.pdf
└── Diagram.png
```

---

## 🏆 Project Summary

This project demonstrates the practical design of a **secure, highly available, scalable, and cost-effective web application architecture on AWS**.

It combines networking, compute, database, security, load balancing, and auto-scaling services into a complete AWS cloud solution following cloud architecture best practices.
