# Terraform AWS Static Website

This repository contains a Terraform configuration for hosting a static website on Amazon S3. It simplifies the process of setting up an S3 bucket for static website hosting and retrieving the website's endpoint.

## Repository Structure

- **main.tf**: Main configuration for creating the S3 bucket and enabling website hosting.
- **provider.tf**: Specifies the AWS provider and sets the required region.
- **variables.tf**: Defines input variables, including the S3 bucket name.
- **output.tf**: Outputs the website hosting endpoint after resource creation.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html)
- [AWS CLI](https://aws.amazon.com/cli/) (for managing AWS credentials)
- An AWS account with IAM permissions to create S3 resources.

## Configuration Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sharonkynu/terraform-aws-static-website.git
   cd terraform-aws-static-website


2. **Configure AWS CLI**:
   ```bash
   aws configure

3. **Initialize the Terraform configuration**:
   ```bash
   terraform init
4. **Create an execution plan**:
   ```bash
   terraform plan
5. **Apply the configuration**:
   ```bash
   terraform apply
6. **Output values**:
   ```bash
   terraform output
