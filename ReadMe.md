# Secure Enterprise VPC Architecture on AWS

## Project Overview

Designed and deployed a secure enterprise-grade AWS cloud networking architecture using Amazon VPC services. The project simulates a real-world enterprise infrastructure with public/private subnet segmentation, bastion host access, NAT Gateway configuration, VPC peering, monitoring, and secure internal communication.

---

# Architecture Components

- Custom VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Bastion Host
- Private EC2 Instances
- Route Tables
- Security Groups
- VPC Peering
- CloudWatch Monitoring
- VPC Flow Logs
- SNS Alerts

---

# Architecture Diagram
## Architecture Diagram

![Architecture Diagram](architecture.png)

---

# Services Used

- Amazon VPC
- Amazon EC2
- AWS IAM
- Amazon CloudWatch
- Amazon SNS
- VPC Flow Logs
- NAT Gateway
- Internet Gateway

---

# Key Features Implemented

## Networking
- Created custom VPC with CIDR block planning
- Configured public and private subnet architecture
- Implemented Internet Gateway and NAT Gateway routing

## Security
- Bastion host for secure SSH access
- Security Group-based traffic control
- Private EC2 isolation
- VPC-level segmentation

## Enterprise Connectivity
- Configured VPC Peering between two VPCs
- Enabled private cross-VPC communication
- Updated route tables for peering traffic

## Monitoring & Logging
- CloudWatch alarms
- SNS email notifications
- VPC Flow Logs monitoring
- Billing alerts

---

# Project Workflow

1. Created custom VPC infrastructure
2. Configured subnet segmentation
3. Attached Internet Gateway
4. Created NAT Gateway for private outbound internet
5. Launched Bastion Host in public subnet
6. Launched Private EC2 in private subnet
7. Configured secure SSH access
8. Created second VPC
9. Configured VPC Peering
10. Enabled CloudWatch monitoring and alerts

---

# Testing Performed

- SSH from Bastion Host to Private EC2
- Internet access verification through NAT Gateway
- Cross-VPC private ping testing
- CloudWatch CPU alarm testing

---

# Skills Demonstrated

- AWS Cloud Networking
- VPC Architecture
- Security Group Management
- Route Table Configuration
- Linux SSH Administration
- Cloud Monitoring
- Infrastructure Troubleshooting
- Enterprise Cloud Security

---

# Author

Rishab Anand
AWS Cloud & Networking Enthusiast