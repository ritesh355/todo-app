
# ✅ Dockerized To-Do App

A **full-stack To-Do List application** built using:

- 🖥️ Node.js & Express (Backend API)
- 📦 MongoDB (Database)
- 🌐 Nginx (Frontend Server)
- 🐳 Docker & Docker Compose (Containerization)

> Developed as part of my [100 Days of DevOps](https://github.com/ritesh355/Devops-journal) challenge.

---

## 📌 Features

- Add, list, update, and delete todos (CRUD)
- RESTful API powered by Express.js
- MongoDB for persistent storage
- Nginx serves static frontend
- All services run using Docker Compose

---

## 🧱 Architecture

```mermaid
graph TD
  User[🧑 User] -->|Access via browser| Nginx[🌐 Nginx (Frontend)]
  Nginx --> API[🔗 Express.js API]
  API --> DB[(🗄️ MongoDB Database)]
