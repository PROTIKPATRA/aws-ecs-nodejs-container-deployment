# AWS ECS Node.js Container Deployment

This project demonstrates deploying a Dockerized Node.js application on AWS using ECS and ECR with monitoring through CloudWatch.

## Architecture

## AWS Services Used

- Amazon EC2
- Amazon ECR
- Amazon ECS
- AWS IAM
- Amazon CloudWatch

## Deployment Workflow

1. Created an EC2 instance and connected via SSH.
2. Installed Docker and AWS CLI.
3. Configured AWS credentials.
4. Created IAM user with ECR permissions.
5. Built Docker image using Dockerfile.
6. Pushed Docker image to Amazon ECR private repository.
7. Created ECS cluster and task definition.
8. Deployed container using ECS.
9. Verified logs and monitoring using CloudWatch.

## Screenshots

### ECS Cluster

### ECR Repository

### CloudWatch Dashboard


### Running Container


## Tech Stack

- Node.js
- Docker
- AWS ECS
- AWS ECR
- AWS CloudWatch
- Linux
