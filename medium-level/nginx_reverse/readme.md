# 🐳 Docker Compose: Flask Backend with Nginx Reverse Proxy

This project demonstrates how to use **Docker Compose** to orchestrate a **Flask backend** and an **Nginx reverse proxy**.

Nginx handles incoming HTTP traffic and routes requests to the Flask service using Docker’s **internal service network**, not `localhost`. This mirrors real-world production architectures where backend services remain isolated.

## 📌 Overview

- 🧱 Multi-container setup using Docker Compose
- 🌐 Nginx acts as a reverse proxy
- 🐍 Flask runs as a backend service
- 🔒 Backend is not exposed directly to the host
- 🔁 Inter-service communication via Docker’s internal network

## 🛠 Tech Stack

- 🐳 Docker & Docker Compose
- 🌐 Nginx (Reverse Proxy)
- 🐍 Flask (Python Backend)

## 📂 Project Structure

├── docker-compose.yml
├── nginx
│ └── nginx.conf
├── backend
│ ├── app.py
│ └── Dockerfile
└── README.md


