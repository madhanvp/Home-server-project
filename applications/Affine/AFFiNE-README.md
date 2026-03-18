# 📝 AFFiNE Deployment (Docker)

## 📌 Overview
AFFiNE is a self-hosted productivity and note-taking application.

In this setup, it is deployed using Docker Compose with a multi-container architecture.

---

## 🧱 Services Used

- **AFFiNE** → Main application  
- **PostgreSQL** → Database  
- **Redis** → Cache  

---

## ⚙️ Architecture

```

AFFiNE App
↓
PostgreSQL
↓
Redis

````

---

## 🚀 How to Run

Start all services:

```bash
docker compose up -d
````

---

Stop services:

```bash
docker compose down
```

---

## 🌐 Access

Open in browser:

```
http://localhost:3010
```

---

## 🐞 Debugging Commands

Check running containers:

```bash
docker ps
```

View logs:

```bash
docker logs affine_server
```

---

## 📁 Files

* `docker-compose.yml` → Defines all services
* `.env.example` → Environment variables template

---

## ✅ Result

* Successfully deployed a multi-container application
* Learned how services communicate (App → DB → Cache)
* Gained hands-on experience with Docker Compose

```
