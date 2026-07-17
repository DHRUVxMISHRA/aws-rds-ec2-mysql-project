# 🚀 AWS RDS + EC2 MySQL Project

![AWS](https://img.shields.io/badge/AWS-RDS-orange)
![Amazon EC2](https://img.shields.io/badge/Amazon-EC2-orange)
![MySQL](https://img.shields.io/badge/MySQL-8.4-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-success)

> **A hands-on AWS project demonstrating the deployment of a private Amazon RDS MySQL database and its secure integration with an Amazon EC2 instance using VPC networking, Security Groups, and SQL database operations.**

---

# 📖 About This Project

This repository documents my hands-on journey of deploying a **private MySQL database on Amazon RDS** and securely connecting it with an **Amazon EC2 instance** using AWS networking services.

Rather than simply following deployment steps, I focused on understanding **why each AWS service is required**, **how AWS resources communicate**, and **how they work together to build a secure cloud architecture**.

Every milestone in this project is documented with explanations, screenshots, and implementation notes to strengthen both my practical AWS knowledge and documentation skills.

---

# 📊 Project Information

| Property | Value |
|----------|-------|
| **Project Type** | Hands-on AWS Cloud Project |
| **Difficulty** | Beginner → Intermediate |
| **AWS Region** | ap-south-1 (Mumbai) |
| **Primary Services** | Amazon EC2, Amazon RDS, Amazon VPC |
| **Database Engine** | MySQL 8.4 |
| **Documentation** | 6 Detailed Milestones |
| **Status** | ✅ Completed |

---

# 🎯 Why I Built This Project

I created this project to gain practical experience with deploying and managing relational databases on AWS.

My primary learning goals were to understand:

- How Amazon EC2 communicates with Amazon RDS
- Why Security Groups are essential for secure communication
- The purpose of DB Subnet Groups
- How private databases improve cloud security
- How to connect and manage a MySQL database hosted on Amazon RDS
- How AWS networking components work together

Instead of only learning AWS concepts theoretically, I wanted to implement everything in a real AWS environment.

---

# 🏗️ Project Architecture

![Project Architecture](architecture/aws-rds-ec2-architecture.png)

---

# ☁️ AWS Services Used

- Amazon EC2
- Amazon RDS
- Amazon VPC
- Security Groups
- DB Subnet Group

---

# 🛠️ Technologies & Tools

### Operating System

- Amazon Linux 2023

### Database

- MySQL 8.4

### Tools

- AWS Management Console
- SSH
- MySQL Client (MariaDB Client)

---

# 📚 What I Learned

Through this project, I gained practical experience with:

- Launching and managing Amazon EC2 instances
- Deploying Amazon RDS MySQL databases
- Configuring Security Groups
- Understanding Amazon VPC networking
- Creating DB Subnet Groups
- Connecting EC2 with private Amazon RDS instances
- Installing and using the MySQL client
- Performing SQL database operations
- Understanding secure communication between AWS resources
- Documenting cloud projects professionally using GitHub

---

# 🗺️ Project Roadmap

| Milestone | Description |
|------------|-------------|
| ✅ Milestone 1 | Launched an Amazon EC2 instance and explored its networking configuration. |
| ✅ Milestone 2 | Configured Security Groups to securely allow communication between AWS resources. |
| ✅ Milestone 3 | Created a DB Subnet Group and understood its role in Amazon RDS deployment. |
| ✅ Milestone 4 | Deployed a private Amazon RDS MySQL instance. |
| ✅ Milestone 5 | Connected the EC2 instance to Amazon RDS using the MySQL client. |
| ✅ Milestone 6 | Performed SQL database operations including database creation, table creation, record insertion, updates, deletion, and queries. |

---

# 🧠 Key Concepts Learned

Throughout this project, I explored several important AWS concepts, including:

- Amazon VPC Networking
- Public vs Private Resources
- Security Groups
- Stateful Firewalls
- DB Subnet Groups
- Amazon RDS Architecture
- EC2 to RDS Communication
- MySQL Connectivity
- SQL CRUD Operations

---

# 📂 Repository Structure

```
aws-rds-ec2-mysql-project
│
├── architecture/
│   └── aws-rds-ec2-architecture.png
│
├── docs/
│   ├── 01-launch-ec2.md
│   ├── 02-security-groups.md
│   ├── 03-db-subnet-group.md
│   ├── 04-launch-rds-instance.md
│   ├── 05-connect-ec2-to-rds.md
│   └── 06-database-operations.md
│
├── screenshots/
│   ├── 01-launch-ec2/
│   ├── 02-security-groups/
│   ├── 03-db-subnet-group/
│   ├── 04-launch-rds-instance/
│   ├── 05-connect-rds/
│   └── 06-database-operations/
│
├── LICENSE
└── README.md
```

---

# 📖 Documentation

This repository contains detailed documentation for every implementation milestone.

| Document | Description |
|----------|-------------|
| 01 | Launch Amazon EC2 |
| 02 | Configure Security Groups |
| 03 | Create DB Subnet Group |
| 04 | Launch Amazon RDS |
| 05 | Connect EC2 to Amazon RDS |
| 06 | Perform MySQL Database Operations |

---

# ⭐ Key Features

- Deploy a private Amazon RDS MySQL database
- Secure EC2-to-RDS communication using Security Groups
- Configure a DB Subnet Group across multiple Availability Zones
- Perform SQL database operations from an EC2 instance
- Maintain structured documentation with milestone-based explanations
- Include organized screenshots for every implementation stage
- Follow AWS security best practices throughout the project

---

# 📸 Project Gallery

Some key stages of the implementation include:

- Amazon EC2 Instance Deployment
- Security Group Configuration
- DB Subnet Group Creation
- Amazon RDS MySQL Deployment
- Successful EC2 → RDS Connection
- SQL Database Operations

> 📁 Complete screenshots are available in the **screenshots/** directory.

---

# 💪 Challenges I Faced

During this project, I encountered and resolved several practical AWS challenges, including:

- Understanding how Security Groups communicate with each other
- Connecting a private Amazon RDS instance from an EC2 instance
- Installing and configuring the MySQL client on Amazon Linux
- Understanding the purpose of DB Subnet Groups
- Writing and executing SQL commands on Amazon RDS

Overcoming these challenges strengthened my understanding of AWS networking, cloud infrastructure, and relational database management.

---

# 🎓 Skills Demonstrated

This project demonstrates practical experience with:

- AWS Cloud Fundamentals
- Amazon EC2
- Amazon RDS
- Amazon VPC
- Security Groups
- MySQL Administration
- SQL Database Operations
- Linux Command Line
- Cloud Troubleshooting
- Technical Documentation

---

# 🚀 How to Reproduce This Project

1. Launch an Amazon EC2 instance.
2. Configure Security Groups.
3. Create a DB Subnet Group.
4. Deploy a private Amazon RDS MySQL instance.
5. Install the MySQL client on EC2.
6. Connect to the RDS endpoint.
7. Create a database and perform SQL operations.

---

# 🌱 Future Improvements

In future iterations, I plan to enhance this project by:

- Deploying the infrastructure inside a custom VPC
- Configuring Multi-AZ RDS deployments
- Enabling automated backups and monitoring
- Connecting a web application to Amazon RDS
- Deploying a sample CRUD application using the RDS database
- Automating infrastructure provisioning using Terraform
- Recreating the project using AWS CloudFormation

---

# 🙏 Acknowledgements

This project was completed as part of my AWS Cloud learning journey to strengthen my understanding of cloud infrastructure, networking, and database services through hands-on implementation.

---

# 👨‍💻 Author

**Dhruv Mishra**

Computer Science Student passionate about Cloud Computing, AWS, and Backend Infrastructure.

I enjoy building practical cloud projects and documenting every implementation step to strengthen both my technical skills and my understanding of AWS services.

---

# 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project helpful or interesting, consider giving the repository a **Star**.
