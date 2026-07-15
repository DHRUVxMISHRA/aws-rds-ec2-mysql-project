# 📖 Project Overview

## 📌 About This Project

This project demonstrates how to deploy a **private MySQL Amazon RDS database** and securely connect it with an **Amazon EC2 instance** inside an AWS Virtual Private Cloud (VPC).

The primary objective of this project is to understand how AWS manages relational databases while following security best practices. Instead of exposing the database to the internet, only the EC2 instance is allowed to communicate with the RDS instance through Security Groups over **MySQL Port (3306)**.

Throughout this project, I implemented the complete workflow from infrastructure setup to database connectivity and SQL operations.

---

# 🎯 Project Objectives

The main objectives of this project were to:

- 🚀 Launch an Amazon EC2 instance
- 🔒 Configure Security Groups for secure communication
- 🌐 Create an RDS Subnet Group
- 🗄️ Deploy a MySQL Amazon RDS instance
- 🔗 Connect EC2 to the RDS database
- 📂 Create a sample database and table
- 💾 Insert and retrieve sample data
- 🧹 Clean up AWS resources after completion

---

# 🏗️ Project Architecture

The infrastructure implemented in this project consists of:

- Amazon EC2
- Amazon RDS (MySQL)
- Amazon VPC
- RDS Subnet Group
- EC2 Security Group
- RDS Security Group

Architecture Diagram:

```
architecture/architecture-diagram.png
```

---

# ⚙️ Project Workflow

```
Launch EC2 Instance
        │
        ▼
Create RDS Security Group
        │
        ▼
Create RDS Subnet Group
        │
        ▼
Deploy MySQL RDS
        │
        ▼
Connect EC2 → RDS
        │
        ▼
Create Database
        │
        ▼
Create Table
        │
        ▼
Insert Sample Data
        │
        ▼
Verify Database Connection
```

---

# 🛠️ AWS Services Used

| AWS Service | Purpose |
|-------------|---------|
| Amazon EC2 | Client machine used to connect to the database |
| Amazon RDS | Managed MySQL database service |
| Amazon VPC | Provides isolated networking |
| Security Groups | Controls traffic between EC2 and RDS |
| RDS Subnet Group | Defines subnets where RDS is deployed |
| MySQL Client | Used to execute SQL commands from EC2 |

---

# 📂 Project Structure

```
aws-rds-ec2-mysql-project/
│
├── README.md
├── LICENSE
│
├── architecture/
│   └── architecture-diagram.png
│
├── docs/
│   ├── 01-project-overview.md
│   ├── 02-launch-ec2.md
│   ├── 03-create-rds-security-group.md
│   ├── 04-create-rds-subnet-group.md
│   ├── 05-launch-rds-instance.md
│   ├── 06-connect-ec2-to-rds.md
│   ├── 07-create-database-table.md
│   └── 08-cleanup.md
│
├── screenshots/
│   ├── 01-ec2-instance.png
│   ├── 02-rds-security-group.png
│   ├── 03-rds-subnet-group.png
│   ├── 04-rds-instance.png
│   ├── 05-rds-endpoint.png
│   ├── 06-mysql-connection.png
│   ├── 07-create-database.png
│   ├── 08-create-table.png
│   └── 09-query-results.png
│
└── sql/
    └── studentdb.sql
```

---

# 🎓 Skills Demonstrated

This project demonstrates practical experience with:

- ☁️ Amazon EC2
- 🗄️ Amazon RDS (MySQL)
- 🌐 Amazon VPC
- 🔒 AWS Security Groups
- 📡 Database Networking
- 💻 Linux Command Line
- 📝 MySQL Administration
- 🔗 Secure AWS Service Integration

---

# ✅ Project Outcome

After completing this project, I successfully:

- ✔️ Deployed a private MySQL database using Amazon RDS.
- ✔️ Configured secure communication between EC2 and RDS.
- ✔️ Connected to the database using the MySQL client.
- ✔️ Created a sample database and table.
- ✔️ Inserted and retrieved sample records.
- ✔️ Followed AWS security best practices by keeping the database private.

---

# 🚀 What's Next?

The next step is to launch an Amazon EC2 instance, which will act as the client machine used throughout the remainder of the project.

---

## 📖 Next Section

➡️ **Next:** [02 - Launch EC2 Instance](02-launch-ec2.md)
