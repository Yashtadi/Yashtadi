<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=Yash%20Tadi&fontSize=40&fontColor=fff&fontAlignY=35&desc=CSE%20%40%20PES%20University%20%7C%20Backend%20%26%20Systems%20%7C%20ML%20for%20Battery%20Diagnostics&descAlignY=55&descSize=16" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/yash-tadi">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:yashtadi17046@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
</div>

## About Me

Third-year CSE student at PES University, Bengaluru. I'm drawn to the parts of a system that decide whether it survives contact with the real world — the retry logic, the write-ahead log, the concurrency control. Most of my projects are backend- or systems-heavy for that reason.

Currently a **Research Intern at PESU Research Foundation**, building a self-healing ML framework for battery health prediction — combining equivalent-circuit physics (ECM/EIS) with drift detection and adaptive retraining on a 228-cell, 1.1M+ measurement dataset.

- Backend: Node.js/Express, FastAPI, REST design, PostgreSQL/Redis
- Systems: Linux namespaces, asyncio, WAL, concurrency control
- Learning: DSA in C++, weekend competitive programming

## Featured Projects

| Project | Stack | What it does |
|---|---|---|
| **Revio** | FastAPI · Redis · PostgreSQL/pgvector | AI code-review service for GitHub PRs. Signature-verified webhooks with a Redis queue and background worker to stay inside GitHub's 10s window; RAG over the repo (pgvector) so reviews reflect the wider codebase; idempotent, retry-safe event handling. |
| **Linux Multi-Container Runtime** | C · Namespaces · pthreads | User-space container runtime isolating processes via PID/mount/UTS namespaces with `clone()` and chroot-based rootfs. Custom kernel module (ioctl) tracks per-container memory and enforces limits; pthread bounded buffers stream logs concurrently. |
| **Distributed Reservation System** | Python · asyncio · TCP · WAL | Train-reservation server with a custom TCP/JSON protocol and per-seat locking to prevent double-booking. Durability via WAL (fsync) and primary–backup replication with automatic failover; validated with a 50-client stress harness. |
| **PlantHub** | MERN · JWT | Full-stack e-commerce app — catalog, cart, checkout, and order management, with JWT auth, bcrypt, email password reset, and image uploads. |

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-web-services&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

## GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Yashtadi&show_icons=true&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashtadi&layout=compact&hide_border=true&langs_count=8" />
</div>

## Beyond Code

- **Student Body Head, Maaya 2026** — leading 50+ volunteers across logistics, sponsorships, and technical operations for a 500+ participant event
- **Tech Head, Nexus AWS Champs Club** — running technical infrastructure for cloud workshops (EC2, S3, IAM)
