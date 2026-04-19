# dj-store-stack

Full-stack modern e-commerce platform built with Django, designed to simulate a real-world production architecture with scalable backend patterns, caching strategies, and asynchronous processing.

---

## 🚀 Overview

This project is an end-to-end e-commerce system that handles:

- Product management
- User authentication
- Shopping cart and checkout flow
- Order processing

The goal is not just to build a working store, but to progressively evolve the architecture by introducing performance optimizations and distributed system patterns.

---

## 🧱 Tech Stack

| Layer      | Technology        |
|------------|------------------|
| Frontend   | Tailwind CSS     |
| Backend    | Django (Python)  |
| Database   | PostgreSQL       |
| Cache      | Redis            |
| Async Jobs | Celery           |

---

## 🏗️ Architecture

```txt
Client (Browser)
      ↓
Django (Views / API)
      ↓
PostgreSQL (Primary Data Store)
      ↓
Redis (Cache & Message Broker)
      ↓
Celery Workers (Async Tasks)
