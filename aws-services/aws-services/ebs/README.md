# AWS EBS – Elastic Block Store

## 1. Project Overview

**Service:** Amazon Elastic Block Store (EBS)  
**AWS Region:** Asia Pacific (Mumbai) – `ap-south-1`  
**Availability Zone:** `ap-south-1a`  
**EC2 Instance:** `aws-devops-web-server-1`  
**Instance ID:** `i-06b7afd43d88eacdb`

### Objective

To create an encrypted EBS volume, attach it to an EC2 instance, format it with the ext4 filesystem, mount it permanently, verify read/write operations, and create an EBS snapshot.

## 2. EBS Configuration

| Configuration | Value |
|---|---|
| Volume ID | `vol-0f8df23c08b5287c3` |
| Volume Type | gp3 |
| Volume Size | 5 GiB |
| IOPS | 3000 |
| Throughput | 125 MiB/s |
| Availability Zone | ap-south-1a |
| Encryption | Enabled |
| Filesystem | ext4 |
| EC2 Device Name | `/dev/sdf` |
| Linux Device Name | `/dev/nvme1n1` |
| Mount Point | `/data` |

## 3. Create EBS Volume

1.
