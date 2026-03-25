# aws-waf-security-lab

### Description
This lab showcases how to design and secure a cloud-based web application using AWS services. It focuses on implementing AWS WAF (Web Application Firewall) to control and filter HTTP traffic based on defined security rules.

### Technologies Implemented
- AWS VPC
- EC2
- Application Load Balancer
- AWS WAF
- AWS CloudWatch Logs

### Features
- Created a custom VPC
- Configured public subnets across multiple availability zones
- Deployed an EC2 instance running a web server
- Implemented an ALB
- Configured an AWS WAF to allow and block traffic based on IP rules
- Verified security rules using HTTP responses
- Enabled logging with cloudwatch

### How It Works
- Created a VPC and configured networking
- Deployed EC2 instance with Apache web server
- Set up a load balancer for traffic distribution
- Attached a AWS WAF to filter incoming request
- Used CloudWatch to monitor traffic and logs
