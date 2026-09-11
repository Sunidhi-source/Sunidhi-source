<h1 align="center">Hi, I'm Sunidhi Sharma 👋</h1>
<h3 align="center">Full-Stack Software Engineer | Distributed Systems & Real-Time Infrastructure</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/sunidhisharma1208/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sunidhisharma1208@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### 🚀 About Me

I'm a B.Tech Computer Science student at Guru Nanak Dev University, Amritsar (Class of 2027), who builds and ships production systems end-to-end — from database schema to deployed, monitored code.

I've independently designed, built, and deployed **7 production applications**, including a live algorithmic trading system with **70+ active users** and a **130%+ six-month return**, and a distributed rate-limiting middleware **load-tested at 11,000+ requests**. I care about the hard parts underneath the UI: race conditions, atomic operations, multi-tenant security, and systems that stay correct under load.

- 🔭 Currently freelancing as a Full-Stack & Systems Developer for independent clients
- 🌱 Deep in distributed systems — Redis internals, CRDTs, and real-time infrastructure
- 💡 300+ DSA problems solved in Java
- 📸 Award-winning photographer on the side (1st place, technical execution & visual storytelling)
- ⚡ Fun fact: I run production infrastructure for a live trading system while still in school

---

### 🛠️ Tech Stack

**Languages & Fundamentals**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MQL5](https://img.shields.io/badge/MQL5-1E88E5?style=flat-square&logo=metatrader&logoColor=white)

**Backend & Distributed Systems**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Databases & Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Auth & Payments**

![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-3C4043?style=flat-square&logo=auth0&logoColor=white)

---

### 🌟 Featured Projects

**[Sentinel — Distributed Rate-Limiting & API Gateway Middleware](https://github.com/Sunidhi-source/Sentinel-project)** · [Live Demo](https://sentinel-project-ngmp.onrender.com/sentinel/dashboard)
Reusable Express middleware using atomic Redis Lua scripts (EVALSHA) to eliminate race conditions in distributed rate limiting. Load-tested across 3 concurrent instances and 11,000+ requests, holding within 10% of the configured shared limit — versus the ~3x over-admission a naive per-instance limiter allows. Ships 3 rate-limiting algorithms, sub-3ms p50 overhead, and a real-time WebSocket + Prometheus dashboard.
`Node.js` `Express.js` `Redis (Lua/EVALSHA)` `WebSockets` `Docker` `Prometheus`

**[NoteSlack — Real-Time Collaboration Platform](https://github.com/Sunidhi-source/noteSlack)** · [Live Demo](https://note-slack.vercel.app/)
A CRDT-based concurrent editing engine (Y.js) supporting 10 simultaneous collaborators with live cursors and zero merge conflicts. Backed by a 3-tier multi-tenant RBAC system using Supabase Row-Level Security and Clerk auth, enforcing access control at the database layer — not just the API layer.
`Next.js` `Supabase` `Clerk` `TypeScript` `Y.js (CRDT)` `WebSockets` `RBAC`

**Algorithmic Trading Engine** *(private client project)*
Live automated trading system built in MQL5/MetaTrader 5, currently serving 70+ active users with a 130%+ cumulative return over a 6-month live track record. Includes a fail-closed remote licensing and kill-switch system, and a fault-tolerant order-management layer that mirrors take-profit targets as broker-side order properties to guarantee exits through terminal disconnects.

---

### 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/sunidhisharma1208/">LinkedIn</a> ·
  <a href="mailto:sunidhisharma1208@gmail.com">Email</a> ·
  Amritsar, Punjab, India
</p>
