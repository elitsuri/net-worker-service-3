# .NET Worker Service 3

> Background worker service with .NET, queues, and health checks

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
.NET, C#, ASP.NET Core, PostgreSQL, EF Core, Docker

## 🏗️ Architecture
Backend service with .NET, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/.net-worker-service-3
cd .net-worker-service-3

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
