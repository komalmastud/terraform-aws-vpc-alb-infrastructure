# Terraform AWS Infrastructure

Terraform AWS VPC ALB Infrastructure
This project uses Terraform to provision and manage AWS infrastructure components such as a VPC, EC2 instances, an Application Load Balancer (ALB), a Target Group, and an S3 bucket. It demonstrates a modular approach to infrastructure as code (IaC).

Features
Creates a custom Virtual Private Cloud (VPC)

Launches EC2 instances in public/private subnets

Sets up an Application Load Balancer (ALB) with Target Group

Defines security groups and routing tables

Provisions an S3 bucket

Organizes code using separate files for provider, variables, and configuration

Project Structure
bash
Copy
Edit
TerraformAWS_Recovered/
├── main.tf         # Core infrastructure (VPC, EC2, ALB, etc.)
├── provider.tf     # AWS provider configuration
├── variables.tf    # Input variables
├── outputs.tf      # Output values after deployment
Prerequisites
Terraform v1.0 or later

AWS account and CLI configured with credentials

Basic knowledge of AWS services

Usage
Clone this repository:
git clone https://github.com/komalmastud/terraform-aws-vpc-alb-infrastructure.git
cd terraform-aws-vpc-alb-infrastructure

Initialize Terraform:
terraform init

Preview the execution plan:
terraform plan

Apply the changes to deploy:
terraform apply

To destroy the infrastructure:
terraform destroy

Author
Komal Mastud
