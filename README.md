# AWS Lift and Shift Project – vProfile

## Project Overview
This project demonstrates how to deploy a Java-based application on AWS using a scalable and production-like architecture.

## Architecture
User → Load Balancer → Target Group → Auto Scaling EC2 → Backend Services

## AWS Services Used
- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- Amazon S3
- Route53
- IAM

## Tools Used
- Apache Maven
- AWS CLI
- Apache Tomcat
- Git

## Deployment Workflow
1. Build application using Maven
2. Upload WAR artifact to S3
3. Launch EC2 instances
4. Deploy application to Tomcat
5. Configure Target Group
6. Configure Load Balancer
7. Create AMI
8. Create Launch Template
9. Configure Auto Scaling Group

## Learning Outcomes
- Understanding AWS infrastructure
- Implementing scalable architecture
- Managing application deployment on cloud
- Using IAM roles for secure access
