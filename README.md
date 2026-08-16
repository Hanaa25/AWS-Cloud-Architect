# ☁️ AWS Project 1 — Highly Available & Scalable Web Application

This project demonstrates the design and deployment of a **highly available, scalable, secure, and cost-effective web application on AWS**, following AWS architectural best practices.

---

## 🚀 Project Overview

The application manages **student records** and allows users to:

* View student records
* Add student records
* Modify student records
* Delete student records

The architecture is designed to provide:

* High Availability
* Scalability
* Security
* Load Balancing
* Network Security
* Cost Optimization

---

## 🏗️ AWS Architecture

![AWS Infrastructure](./Diagram.png)

---

## 🧩 AWS Services

* **Amazon VPC** — Network isolation and infrastructure
* **Amazon EC2** — Application hosting
* **Application Load Balancer** — Traffic distribution
* **Auto Scaling** — Automatic scaling of EC2 instances
* **Amazon RDS** — Managed relational database
* **AWS Secrets Manager** — Secure credential management
* **Security Groups** — Network access control

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

---

## 🔐 Security

The project implements security through:

* Amazon VPC
* Security Groups
* AWS Secrets Manager
* Controlled communication between application and database layers
* Secure database access

---

## 📈 Scalability & High Availability

The architecture uses:

* Application Load Balancer
* EC2 Auto Scaling
* Multiple application instances
* Amazon RDS
* VPC networking

These components help the application handle changing workloads while maintaining availability and reliability.

---

## 💰 Cost Optimization

The architecture considers AWS cost optimization while maintaining the required:

* Availability
* Scalability
* Security
* Performance

Detailed cost estimation is included in the project documentation.

---

## 📄 Project Documentation

The complete implementation, configuration steps, screenshots, testing, architecture details, and cost estimation are available in the PDF.

👉 **[Open Project 1 Documentation](./project1.pdf)**

---

## 🎓 Skills Demonstrated

* AWS Cloud Architecture
* Amazon VPC
* Amazon EC2
* Amazon RDS
* Application Load Balancer
* Auto Scaling
* AWS Secrets Manager
* Security Groups
* High Availability
* Scalability
* Load Balancing
* Network Security
* Cost Optimization

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

A practical AWS Cloud project demonstrating the design of a **secure, highly available, scalable, and cost-effective web application** using AWS networking, compute, database, load balancing, auto scaling, and security services.
