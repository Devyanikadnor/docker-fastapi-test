# 🚀 Dockerized FastAPI Application

## 📌 Overview

- This is a simple FastAPI application containerized using Docker and managed with docker-compose.

---

## ✨ Features

- **GET /** → Returns hello message  
- **GET /users** → Fetch all users  
- **POST /users** → Add new user  
- Data stored in JSON file  
- Persistent storage using Docker volumes  

---

## ▶️ How to Run

```bash
git clone <your-repo-link>
cd docker-fastapi-test
docker-compose up --build
http://<public_IP>:8000
