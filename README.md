# AWS Fargate for Containerized Applications

## Overview
AWS Fargate is a serverless compute engine for containers that allows you to run containers without managing the underlying infrastructure. It works with both Amazon ECS and EKS.

## Key Features
- **No Server Management**: Deploy containers without managing EC2 instances.
- **Seamless Scaling**: Automatically scales based on workload demands.
- **Security & Isolation**: Each task runs in its own isolated environment.
- **Cost Optimization**: Pay for vCPU and memory used by running tasks.

## How to Use AWS Fargate
1. Create an **Amazon ECS Cluster** with Fargate as the launch type.
2. Define a **Task Definition** specifying the container image, CPU, and memory requirements.
3. Deploy and manage tasks/services using the ECS console, CLI, or AWS SDK.

## Useful Resources
- [AWS Fargate Documentation](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html)
- [Getting Started with AWS Fargate](https://aws.amazon.com/fargate/)
