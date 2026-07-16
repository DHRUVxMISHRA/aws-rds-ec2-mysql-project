# Create RDS Security Group

## Objective

Create a dedicated Security Group for the Amazon RDS MySQL instance that allows database access only from the EC2 instance.

---

## Configuration

| Setting | Value |
|---------|-------|
| Security Group Name | student-rds-sg |
| Description | Security group for Amazon RDS MySQL instance |
| VPC | Default VPC |
| Inbound Rule | MySQL/Aurora |
| Port | 3306 |
| Source | student-ec2-sg |
| Outbound Rule | All Traffic (Default) |

---

## Why a Separate Security Group?

Using a dedicated Security Group for the RDS instance follows AWS security best practices by isolating database access.

Instead of exposing the database to the internet, only the EC2 instance is allowed to communicate with the RDS instance over port **3306**.

This minimizes the attack surface and improves overall security.

---

## Result

- Created a dedicated Security Group for Amazon RDS.
- Allowed MySQL traffic only from the EC2 Security Group.
- Followed the principle of least privilege for database access.

---

## Screenshots

Refer to:

```text
screenshots/02-create-rds-security-group/
```

- 01-basic-details.png
- 02-inbound-rule.png
- 03-security-group-created.png
