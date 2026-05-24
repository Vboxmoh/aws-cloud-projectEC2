# AWS Cloud Project - EC2 & Linux

## Project Overview
This project demonstrates the creation and configuration of an AWS EC2 instance running Ubuntu 24.04 LTS, along with basic Linux file system operations.

## Architecture
- VPC with one public subnet and one private subnet
- Internet Gateway attached to the public subnet
- NAT Gateway for the private subnet
- Security Group with SSH, HTTP, HTTPS and SMTP rules

## Steps Completed

### 1. VPC Architecture Design
Designed a VPC architecture including public and private subnets, route tables, Internet Gateway and NAT Gateway.

### 2. Security Group
Created a security group allowing inbound traffic for SSH (22), HTTP (80), HTTPS (443) and SMTP (25).

### 3. EC2 Instance
Launched an EC2 instance using Ubuntu 24.04 LTS on a t3.micro free tier instance.

### 4. Directory Structure
Created a project directory with src and docs subdirectories containing main.py and README.md files.

### 5. File Permissions
- Made main.py executable using chmod +x
- Set README.md to read-only using chmod 444

### 6. Bash Script
Created and executed run.sh which prints Hello, World! to the terminal.

### 7. Archive and Compression
Archived the project directory into project.tar and compressed it to project.tar.gz.

### 8. File Editing with Nano
Added content to README.md using the nano editor.

## Screenshots
All screenshots are available in the screenshots folder.

## Technologies Used
- AWS EC2
- Ubuntu 24.04 LTS
- Bash
- Linux CLI
