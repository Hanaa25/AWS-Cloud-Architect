# ☁️ AWS Project 1 — Highly Available & Scalable Web Application

A practical AWS cloud project demonstrating the design and deployment of a **highly available, scalable, secure, and cost-effective web application** using AWS services and following the principles of the **AWS Well-Architected Framework**.

---

## 🚀 Project Overview

The goal of this project is to build a reliable web application infrastructure on AWS that can handle increasing traffic while maintaining **high availability, security, scalability, and performance**.

The application manages **student records** and allows users to:

* View student records
* Add student records
* Modify student records
* Delete student records

The infrastructure is designed to distribute application traffic, automatically scale compute resources, and securely connect the application layer with the database.

---

## 🏗️ AWS Architecture

![AWS Infrastructure](Diagram.png)

The architecture uses multiple AWS services working together to provide a secure and highly available application environment.

### Architecture Components

* **Amazon VPC** — Provides an isolated network environment.
* **Amazon EC2** — Hosts the web application.
* **Application Load Balancer** — Distributes incoming traffic across EC2 instances.
* **Auto Scaling** — Automatically adjusts the number of EC2 instances according to demand.
* **Amazon RDS** — Provides a managed relational database for student records.
* **AWS Secrets Manager** — Securely stores database credentials and sensitive information.
* **Security Groups** — Control inbound and outbound network traffic between resources.

---

## 🔄 Application Flow

The application follows this general traffic flow:

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

Sensitive credentials are securely managed using **AWS Secrets Manager**, while **Security Groups** restrict communication between the different application components.

---

## 🧩 AWS Services Used

| AWS Service               | Purpose                            |
| ------------------------- | ---------------------------------- |
| Amazon VPC                | Network isolation and architecture |
| Amazon EC2                | Application hosting                |
| Application Load Balancer | Traffic distribution               |
| Auto Scaling              | Automatic scaling of EC2 instances |
| Amazon RDS                | Managed relational database        |
| AWS Secrets Manager       | Secure credential management       |
| Security Groups           | Network access control             |

---

## 🎯 Key Concepts Demonstrated

### High Availability

The architecture is designed to reduce single points of failure and maintain application availability.

### Scalability

Auto Scaling allows the application environment to automatically increase or decrease compute capacity according to workload requirements.

### Load Balancing

The Application Load Balancer distributes incoming requests across available EC2 instances.

### Database Architecture

Amazon RDS provides a managed relational database for storing and managing student records.

### Network Security

Security Groups control which resources can communicate with each other and which traffic is allowed.

### Secrets Management

AWS Secrets Manager is used to securely manage sensitive database credentials instead of storing them directly in application code.

### Cost Optimization

The architecture considers resource utilization and AWS cost optimization while maintaining the required availability and performance.

---

## 🔐 Security

Security was considered at multiple layers of the architecture:

* Network isolation using **Amazon VPC**
* Controlled access using **Security Groups**
* Secure storage of credentials using **AWS Secrets Manager**
* Separation between application and database resources
* Restricted communication between infrastructure components

---

## 📈 Scalability & Availability

The architecture supports scalability through:

* Application Load Balancer
* EC2 Auto Scaling
* Distributed application instances
* Managed Amazon RDS database
* VPC-based network architecture

This allows the application to handle changing workloads while improving reliability and availability.

---

## 📄 Project Documentation

The complete project documentation contains the detailed implementation process, configuration steps, screenshots, architecture, testing, and cost estimation.

📄 **[Open Project 1 Documentation](project1.pdf)**

---

## 📸 Project Screenshots

Additional screenshots and implementation evidence are included in the project documentation PDF.

---

## 💰 Cost Considerations

The project also includes a cost estimation section covering the AWS resources used in the architecture.

The design aims to balance:

* Availability
* Scalability
* Security
* Performance
* Cost

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Designing AWS cloud architectures
* Building VPC-based infrastructures
* Deploying applications on Amazon EC2
* Configuring Application Load Balancers
* Implementing EC2 Auto Scaling
* Working with Amazon RDS
* Managing secrets with AWS Secrets Manager
* Configuring Security Groups
* Designing highly available architectures
* Applying cloud security principles
* Considering AWS cost optimization

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

It combines networking, compute, database, security, load balancing, and auto-scaling services into a complete cloud solution based on AWS architectural best practices.
