# Installation Guide

Follow these steps to install **Splunk** on an **Ubuntu 20.04 EC2 instance**.

### Step 1: Launch an EC2 Instance
- Follow the steps to launch an EC2 instance running **Ubuntu 20.04** from the [AWS Console](https://aws.amazon.com/console/).
- Make sure your security group allows inbound traffic on ports **22** (SSH), **80** (HTTP), and **8000** (Splunk Web UI).

### Step 2: SSH into the EC2 Instance
Use the following command to SSH into your EC2 instance:
```bash
ssh -i your_key.pem ubuntu@<Elastic-IP>
