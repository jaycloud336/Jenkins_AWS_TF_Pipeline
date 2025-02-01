# Prerequisites for Setting Up Jenkins Pipeline with Terraform and AWS

Before starting the setup for Jenkins pipeline with Terraform and AWS, ensure the following prerequisites are met:

## 1. **Docker Desktop Installed and Running**
   - You should have **Docker Desktop** installed on your machine and it should be running.
   - Docker will be used to run Jenkins in a container, so ensure Docker is properly configured and operational.

## 2. **Running Jenkins Instance in Docker Container**
   - A **Jenkins instance** should be running inside a Docker container. You can use the official Jenkins Docker image for this.
   - You will interact with Jenkins through the web interface, which is typically accessible on port `8080` of your local machine.

## 3. **Active AWS Account with IAM User**
   - Ensure you have an **AWS account** with an active IAM user.
   - The IAM user must have sufficient permissions to interact with AWS resources like EC2, S3, etc.
   - You will need to obtain the IAM user's **Access Key ID** and **Secret Access Key** in order to authenticate Jenkins with AWS.

## 4. **GitHub Repository with Terraform Code**
   - You should have a **GitHub repository** that contains the Terraform code to manage your infrastructure.
   - The repository should be accessible to Jenkins for pulling the code and running the pipeline.

---

Once these prerequisites are in place, you can proceed with setting up the Jenkins pipeline to deploy Terraform code and interact with AWS services.
