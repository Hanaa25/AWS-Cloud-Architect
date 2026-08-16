# ☁️ AWS Cloud Projects

This repository contains AWS Cloud projects demonstrating practical skills in cloud architecture, networking, security, scalability, high availability, and cost optimization.

---

# 🚀 Project 1: Building a Highly Available, Scalable Web Application

📄 **Project Documentation:** [Open project1.pdf](project1.pdf)

🖼️ **Project Architecture:**

![AWS Infrastructure](Diagram.png)

## 🧩 Project Overview

The project focuses on planning, designing, building, and deploying a highly available and scalable web application on AWS following the **AWS Well-Architected Framework** best practices.

The application manages **student records**, allowing users to:

* View student records
* Add student records
* Modify student records
* Delete student records

The architecture is designed to support **thousands of users during peak admission periods**.

## 🎯 Key Requirements

* **Highly Available** – Minimal downtime if a server becomes unavailable.
* **Scalable** – Automatically scales according to demand.
* **Load Balanced** – Distributes traffic across multiple web servers.
* **Secure** – Protects the database and credentials.
* **High Performing** – Supports fast application operations.
* **Cost Optimized** – Minimizes unnecessary operational costs.

## 🏗️ AWS Architecture

The solution includes:

* Amazon VPC
* Public and Private Subnets
* Amazon EC2
* Application Load Balancer
* Auto Scaling Group
* Amazon RDS
* AWS Secrets Manager
* Security Groups

## 🗂️ Project Phases

### Phase 1 – Planning & Cost Estimation

* Designed the AWS architecture.
* Created an architectural diagram.
* Estimated the project cost over three years.

### Phase 2 – Basic Web Application

* Created a VPC named `project_app`.
* Launched an EC2 instance named `web1`.
* Deployed and tested the web application.

### Phase 3 – Decoupling Application Components

* Created an Amazon RDS database named `database1`.
* Connected the web application to RDS.
* Stored database credentials securely using AWS Secrets Manager.
* Created a second web server named `web2`.
* Tested connectivity between the web servers and database.

### Phase 4 – High Availability & Scalability

* Created a Target Group named `web-TG`.
* Created an Application Load Balancer named `WEB-LB`.
* Created a Launch Template named `template-web`.
* Created an Auto Scaling Group named `web-auto`.
* Configured automatic scaling based on application demand.

## ✅ Expected Outcome

The final architecture provides a:

* Highly available application
* Scalable web tier
* Load-balanced environment
* Secure database architecture
* High-performing application
* Cost-optimized AWS solution

---

# 🚀 Project 2

📄 **Project Documentation:** [Open project2.pdf](project2.pdf)

The second project is documented separately in **project2.pdf**.

---

## 📚 AWS Skills Demonstrated

Through these projects, I practiced:

* AWS VPC and networking
* Amazon EC2
* Amazon RDS
* Application Load Balancer
* Auto Scaling
* AWS Secrets Manager
* Security Groups
* High Availability
* Scalability
* Load Balancing
* AWS Well-Architected Framework
* Cost Optimization
* Cloud Architecture

---

## 📁 Repository Structure

```text
AWS-Cloud-Projects/
│
├── README.md
├── project1.pdf
├── project2.pdf
└── Diagram.png
```

---

## 🎓 Learning Outcome

These projects demonstrate practical experience in designing and deploying **secure, highly available, scalable, and cost-effective AWS architectures**.
