# High Availability Web App with Terraform

This project deploys a highly available, load-balanced web application on AWS using:
- EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Terraform (Infrastructure as Code)

## 🔹What I have build
- An EC2 Auto Scaling Group (ASG) that automatically adds or removes servers based on traffic
- An Application Load Balancer (ALB) that routes traffic to healthy servers.
- Security rules to control network access.
- A simple web app that returns “Hello, World”.

## 🔹Architecture

- Public Subnets in multiple AZs
- ALB to distribute traffic
- Launch Template with EC2
- Auto Scaling Group with min=1, max=3

## 🔹Architecture Diagram
<img width="867" height="510" alt="image" src="https://github.com/user-attachments/assets/afededd4-210e-4092-b45a-e2fa49cf468e" />

## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/high-availability-webapp-terraform.git
   cd high-availability-webapp-terraform
