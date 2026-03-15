# AWS ECS Node.js Container Deployment

This project demonstrates deploying a Dockerized Node.js application on AWS using ECS and ECR with monitoring through CloudWatch.

## Architecture

![Architecture]((https://github.com/PROTIKPATRA/aws-ecs-nodejs-container-deployment/tree/main/Snapshots/architecture))

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
![ECS](screenshots/ecs-cluster.png)

### ECR Repository
![ECR](screenshots/ecr-repo.png)

### CloudWatch Dashboard
![CloudWatch](screenshots/cloudwatch-dashboard.png)

### Running Container
![Task](screenshots/ecs-task.png)

## Tech Stack

- Node.js
- Docker
- AWS ECS
- AWS ECR
- AWS CloudWatch
- Linux
