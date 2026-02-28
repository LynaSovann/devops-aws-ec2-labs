# devops-aws-ec2-labs

Hands-on AWS labs demonstrating infrastructure provisioning, automation, and production-style deployment practices.

---

<img src="./ec2-img.png" alt="aws ec2">

---

## What is Amazon EC2?

**Amazon Elastic Compute Cloud** (EC2) is a scalable virtual server service that allows you to launch and manage compute instances in the cloud. It provides full control over the operating system, networking, and installed software.

EC2 is commonly used for:

- Hosting web applications
- Running backend service
- Deploying development and test environments
- Infrastructure automation

---

## Core EC2 Features

- On-demand virtual servers
- Multiple instance types (CPU / Memory optimized)
- Elastic IP addressing
- Security Groups (firewall rules)
- Key Pair authentication (SSH access)
- User Data for automated provisioning
- Integration with other AWS services

---

## EC2 Instance Creation

1. Select AMI (e.g., Ubuntu, Amazon Linux, ...)
2. Choose instance type
3. Configure networking (VPC, Subnet)
4. Create or select Key Pair
5. Configure Security Group
6. Add User Data script (optional automation)
7. Launch instance

---

## Requirement Gathering Before Deployment

Before launching an EC2 instance, define:

- Purpose (web server, backend, testing, etc.)
- Expected traffic/load
- Required ports (HTTP, HTTPS, SSH)
- Storage requirements
- Automation needs (User Data / scripts)
- Security considerations

---

## Lab Objective

This repository focuses on:

- Manual EC2 provisioning
- Security Group configuration
- SSH access using Key Pairs
- Automated setup using User Data scripts
- Production-style service deployment (Apache, NGINX, etc.)
- Basic cloud architecture principles
  Each lab branch demonstrates a specific real-world EC2 scenario.

---

## Branch Structure

```bash
lab/<topic-name>
```

Example:

```bash
lab/ec2-apache-portfolio-deploy
lab/ec2-wordpress-auto-deploy
lab/ec2-static-nginx
```

**Switch branches to explore each scenario.**
