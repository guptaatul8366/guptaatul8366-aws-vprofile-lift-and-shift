# Architecture Overview

User
 │
 ▼
Application Load Balancer
 │
 ▼
Target Group
 │
 ▼
Auto Scaling Group
 │
 ├── EC2 App Server
 │
 ▼
Backend Services
 ├── MySQL
 ├── Memcache
 └── RabbitMQ
