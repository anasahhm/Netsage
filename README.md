***NetSage*** - Professional Router Management & Monitoring Platform
An application for managing and monitoring network routers with real-time analytics, automated data collection, and multi-user support.

# Features

🔐 Multi-user Support - Secure authentication with JWT & data isolation
📊 Real-Time Monitoring - Live bandwidth, CPU, and memory usage tracking
🤖 Automated Collection - Scheduled data collection every 5 minutes via SSH
📈 Interactive Charts - Beautiful visualizations with historical data
🌐 Multi-Vendor Support - Cisco, Juniper, Arista, and more
⚡ Scalable Architecture - Celery workers for parallel data collection

# Tech Stack
**Backend**

FastAPI (Python 3.11)
MongoDB
Redis + Celery
Netmiko (SSH automation)

**Frontend**

Next.js 14 + TypeScript
Tailwind CSS
Recharts

# Prerequisites

Docker & Docker Compose (recommended)
OR: Python 3.11+, Node.js 18+, MongoDB 7.0+, Redis 7.0+

# Security

Bcrypt password hashing
JWT authentication with 24-hour expiration
Company data isolation
Encrypted router credentials (production)







# I HAVE ADDED ONLY README NAD CONTRIBUTING GUIDELINES RN , WILL BE PUSHING ENTIRE CODE IN 2 DAYS 

## 🤝 Contributing

This repository uses a collaborator-based workflow.

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before making any changes.

