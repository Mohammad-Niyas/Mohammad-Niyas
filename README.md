<h1 align="center">Mohammad Niyas</h1>
<h3 align="center">Backend Engineer — Go · PostgreSQL · Redis · Distributed Systems</h3>

<p align="center">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mohammadniyas662@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://leetcode.com/YOUR-LEETCODE"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white"></a>
</p>

---

### About

Backend engineer specializing in Go, PostgreSQL, Redis, and distributed systems.
Built concurrent booking infrastructure with Redis distributed locking and PostgreSQL
transactions, and deployed containerized gRPC microservices to AWS EKS. Commerce
graduate turned backend engineer — 6 deployed Go projects in 18 months.

- 🔭 Currently building **BookMyVenue** — a Go venue booking engine with Redis-based slot holds
- 🌱 Deep in Go concurrency patterns, event-driven architecture, and clean architecture
- 📫 Reach me at **mohammadniyas662@gmail.com**

---

### Tech Stack

**Language & Core**
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Backend**
![Gin](https://img.shields.io/badge/-Gin-00ADD8?style=flat-square)
![gRPC](https://img.shields.io/badge/-gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![REST](https://img.shields.io/badge/-REST%20APIs-informational?style=flat-square)
![WebSockets](https://img.shields.io/badge/-WebSockets-informational?style=flat-square)

**Databases & Cache**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Message Queues**
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Cloud & DevOps**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![NGINX](https://img.shields.io/badge/-NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

### Featured Projects

#### 🔗 [BookMyVenue — Venue Booking System](https://github.com/Mohammad-Niyas/REPO-NAME)
Production-grade venue booking engine in Go, built on strict Clean Architecture
(Handler → Service → Repository).
- BookMyShow-style 10-minute temporary slot hold using **Redis SET NX + TTL** to
  prevent race conditions on concurrent bookings
- AWS S3 presigned-URL uploads for direct client-to-cloud image transfer
- Shadow-copy draft system so venue owners can submit edits for admin review
  without touching live data
- Atomic slot replacement via `gorm.Transaction`; RabbitMQ producers wired for
  async booking notifications

`Go` `PostgreSQL` `Redis` `RabbitMQ` `AWS S3`

#### 🔗 [VogueLuxe — E-Commerce Microservices Platform](https://github.com/Mohammad-Niyas/REPO-NAME)
E-commerce backend with JWT auth, transactional wallet, and Razorpay integration.
- Extracted Wallet and Wishlist out of a monolith into independent **gRPC
  microservices** behind an API Gateway
- Containerized with Docker, deployed to **AWS EKS** via GitHub Actions CI/CD

`Go` `PostgreSQL` `MongoDB` `gRPC` `Docker` `Kubernetes`

---

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Mohammad-Niyas&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohammad-Niyas&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Mohammad-Niyas&theme=tokyonight&hide_border=true" />
</p>
