<img width="1536" height="1024" alt="aws lift and shift diag" src="https://github.com/user-attachments/assets/c7cdabb2-81ef-4920-966d-9537a931054d" />
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
