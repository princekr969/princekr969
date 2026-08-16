<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Prince+Kumar;Final+Year+CS+@+ABV-IIITM+Gwalior;Full-Stack+Engineer+%7C+Systems+Builder;Open+to+New+Grad+%26+SDE+Roles+2027" alt="Typing SVG" />
</h1>

<h3 align="center">Building distributed systems & real-time platforms from the ground up</h3>

<p align="center">
  <a href="mailto:princekr969@outlook.com"><img src="https://img.shields.io/badge/Email-princekr969%40outlook.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/princekr969"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/princekr969"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://portfolio-prince-rajs-projects-7e326db3.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-2ea44f?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>

---

## 🎓 Student · 💻 Builder · 🚀 Engineer

I'm a **final-year Computer Science undergrad at ABV-IIITM Gwalior** (Batch 2023–2027) who treats every project like a production system. While I maintain a strong academic foundation in **DSA, OS, DBMS, Networks, and Compiler Design**, I spend most of my time architecting real-world platforms — from distributed query engines to real-time collaborative infrastructure.

**Currently seeking:** New Graduate / Software Engineer roles starting **2027** | Summer internships 2026

---

## What I've Shipped

### [QueryForge](https://github.com/princekr969/QueryForge-) — Distributed Parallel SQL Engine
> *Because single-node analytics shouldn't be the bottleneck*

A **cloud-native, distributed SQL query engine** built from scratch to handle analytical workloads at scale.
- **3 worker nodes** orchestrated via **gRPC server-side streaming** with MapReduce-style partial aggregation and predicate pushdown
- Achieved **1.7× speedup** on **2M+ row datasets** vs. single-node baseline
- **Fault-tolerant scheduler**: 5s heartbeats, 15s dead-node detection, automatic partition reassignment (max 3 retries)
- Full observability: **OpenTelemetry** spans, **Prometheus** metrics, **Grafana** dashboards across **9 containerized services**
- Analytical SQL over partitioned datasets in **MinIO** (S3-compatible)

**Stack:** `Node.js` `TypeScript` `gRPC` `Docker` `PostgreSQL` `MinIO` `Prometheus` `Grafana`

---

### [Code-Buddy](https://github.com/princekr969/Code-Buddy) — Real-Time Collaborative Code Editor
> *Google Docs meets VS Code, with 25+ language execution*

A **production-grade collaborative IDE** with conflict-free synchronization and in-browser code execution.
- **Live cursor tracking** and conflict-free sync using **Yjs CRDT** + **Socket.IO**
- **Monaco Editor** integration with multi-file tabs, syntax highlighting, and unsaved-change indicators
- In-browser code execution across **25+ languages** via JDoodle API
- **JWT auth**, MongoDB persistence, real-time presence panel, and in-editor chat

**Stack:** `React.js` `Node.js` `Express` `Socket.IO` `Yjs` `MongoDB` `JWT` `Monaco Editor`

---

## 💼 Experience

**Software Developer (Summer Colloquium)** @ SLDC Odisha Project, ABV-IIITM Gwalior  
*May 2026 – Aug 2026*
- Architected a **centralized API abstraction layer** decoupling data-fetching logic from UI, reducing redundant service calls across **10+ modules**
- Replaced fixed month/year report downloads with **flexible custom date-range selection** for arbitrary range generation
- Built a **Node.js/TypeScript integration layer** consuming real-time **SCADA APIs** across **5 grid zones** for sub-minute power-demand monitoring
- Designed a **dual-source data pipeline** (SCADA + Open-Meteo API) with **Drizzle ORM** → PostgreSQL, powering an **Hour-Ahead Load Forecasting** model

**Web Developer** @ Sangillence (Startup)  
*Jan 2026 – Mar 2026*
- Delivered a **full-stack platform** for the Open Book Olympiad serving **500+ students** (Class 3–10) end-to-end
- Engineered **secure student registration** with live photo capture + on-site identity verification for tamper-proof validation
- Shipped independently from design to deployment in **14 weeks** for a real client

---

## 🛠️ Tech Stack

**Languages:**  
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend:**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend & Systems:**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat&logo=grpc&logoColor=white)

**Data & DevOps:**  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## 📊 GitHub Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=princekr969&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=princekr969&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=princekr969&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=princekr969&theme=tokyo-night&hide_border=true" alt="Activity Graph" />
</p>

---

## 🏆 Achievements & Leadership

- **Design Lead**, Inter-IIITM Sports Meet & Aurora — Led visual design for two major college fests, producing **20+ posters and digital creatives**
- Built **2 production-grade systems** independently from system design to deployment
- Strong foundation in **DSA, OOP, DBMS, OS, Computer Networks, Software Engineering, Compiler Design, and System Design**

---

## 📫 Let's Connect

<p align="center">
  <a href="mailto:princekr969@outlook.com">
    <img src="https://img.shields.io/badge/📧_princekr969@outlook.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>I'm always open to discussing systems design, distributed architectures, or potential opportunities.</i><br>
  <b>Looking for New Grad / SDE roles for 2027 🎯</b>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=princekr969&label=Profile%20Views&color=58A6FF&style=flat" alt="Profile Views" />
</p>
