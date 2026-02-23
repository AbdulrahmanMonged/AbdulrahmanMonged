# Abdulrahman Monged

**Backend Engineer** — FastAPI · Flask · Redis · Socket.IO · PostgreSQL

[![Portfolio](https://img.shields.io/badge/Portfolio-abdulrahman--monged.com-000000?style=flat-square&logo=About.me&logoColor=white)](https://abdulrahman-monged.com/)
[![CV](https://img.shields.io/badge/CV-Download-0077B5?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://abdulrahman-monged.com/cv.pdf)
[![Email](https://img.shields.io/badge/Email-abdoomonged231@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abdoomonged231@gmail.com)

---

## About

I build scalable backend systems and real-time applications with modern Python frameworks. Currently focused on distributed systems, async architecture, and production-grade API design.

- Solving algorithmic problems on LeetCode in spare time

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Databases & Caching**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-grey?style=flat-square)

---

## Featured Projects

### [CodeBlack System](https://github.com/AbdulrahmanMonged/codeblack-system) — Production · Live at [thunder-project.xyz](https://thunder-project.xyz/)

A full-stack guild management platform built around a Discord bot, a FastAPI backend, and a React SPA — all sharing a single PostgreSQL schema.

**Architecture highlights**
- Bot-to-backend IPC via Redis Streams (ACK-based, persistent) and Redis Pub/Sub
- Full RBAC permission system with domain-level policy enforcement
- 17 REST route modules covering auth, admin, recruitment, voting, blacklist, config registry, and more
- 11 Discord cogs with activity monitoring, player management, forum watching, and event handling
- Cloudflare bypass layer with Capsolver integration and session management
- Async-first throughout — SQLAlchemy 2.0 async, asyncpg, Celery workers
- Observability: request correlation IDs, metrics endpoints, structured logging

**Stack:** Python 3.12 · FastAPI · discord.py · PostgreSQL · Redis · Celery · SQLAlchemy 2.0 · Pydantic v2 · React 19 · Redux Toolkit · Tailwind CSS v4 · Framer Motion

---

### [host4cit](https://github.com/AbdulrahmanMonged/host4cit)

A music hosting and streaming service with async download pipelines, CDN delivery, and a React SPA dashboard.

**Architecture highlights**
- Pluggable download strategy pattern (yt-dlp) with separate metadata fetchers (Spotify, yt-dlp)
- Celery workers for async download and cleanup tasks
- Idempotency layer on write endpoints to prevent duplicate operations
- Token-bucket rate limiting middleware with per-user tracking
- Membership tiers with permission-based access control
- Full E2E, integration, and unit test suite
- Alembic migrations with role/permission seeding

**Stack:** Python · FastAPI · PostgreSQL · Redis · Celery · SQLAlchemy · Socket.IO · React · Vite · Redux Toolkit

---


## Other Projects

| Project | Stack | Description |
|---|---|---|
| [blog-api-demo](https://github.com/AbdulrahmanMonged/blog-api-demo) | FastAPI · PostgreSQL | RESTful blog API with auth and CRUD |
| [Flask-Portfolio](https://github.com/AbdulrahmanMonged/Flask-Portfolio) | Flask · HTML · CSS | Personal portfolio site |
| [DS & Algorithms](https://github.com/AbdulrahmanMonged/DS---Algorithm-Python--LEETCODE-QUESTIONS-) | Python | LeetCode solutions and algorithm practice |
