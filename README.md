# High Availability Web App with Terraform

This project deploys a highly available, load-balanced web application on AWS using:
- EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Terraform (Infrastructure as Code)

## Architecture

- Public Subnets in multiple AZs
- ALB to distribute traffic
- Launch Template with EC2
- Auto Scaling Group with min=1, max=3

## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/high-availability-webapp-terraform.git
   cd high-availability-webapp-terraform
