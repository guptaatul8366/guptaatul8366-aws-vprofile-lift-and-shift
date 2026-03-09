# Deployment Steps

1. Create security groups for ELB, application, and backend servers.
2. Launch backend servers (MySQL, Memcache, RabbitMQ).
3. Configure private DNS records using Route53.
4. Launch application EC2 instance.
5. Create IAM role for S3 access.
6. Build application using Maven.
7. Upload WAR file to S3 bucket.
8. SSH into EC2 instance and install AWS CLI.
9. Download artifact from S3.
10. Deploy WAR file to Apache Tomcat.
11. Create Target Group with port 8080.
12. Create Application Load Balancer.
13. Create AMI from configured instance.
14. Create Launch Template.
15. Configure Auto Scaling Group.
