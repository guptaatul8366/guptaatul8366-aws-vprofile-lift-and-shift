![AWS](https://github.com/user-attachments/assets/f6a46826-d606-4c75-a9bf-e24cb04bf77a)
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
