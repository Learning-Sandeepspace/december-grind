# AWS VPC – Production Grade Setup (Day 1)

## Architecture
- 1 VPC (10.0.0.0/16)
- 2 Public Subnets (Multi-AZ)
- 2 Private Subnets (Multi-AZ)
- 1 Internet Gateway
- 1 NAT Gateway
- 2 Route Tables
- Bastion Host in Public Subnet
- Private EC2 connected via NAT

## Learnings
- Difference b/w public and private subnets
- Why NAT gateway is needed
- How routing works in AWS
- How companies secure EC2 instances

## Commands Used
sudo yum update -y
