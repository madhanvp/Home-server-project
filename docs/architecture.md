# 🧱 Architecture

## Current Setup
Mobile / Laptop
->
AFFiNE App
->
PostgreSQL
->
Redis

---

## Explanation

### Client
User accesses application from browser

### AFFiNE App
Main application (UI + Backend)

### PostgreSQL
Stores data like notes and users

### Redis
Used for caching and performance

---

## Flow

1. User sends request
2. AFFiNE processes request
3. Data stored in PostgreSQL
4. Redis speeds up responses
