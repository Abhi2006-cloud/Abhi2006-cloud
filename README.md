<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F766E,100:16324F&text=Abhi%20Suryawanshi&fontSize=48&fontColor=FFFFFF&fontAlignY=38&desc=Backend%20Engineer%20%7C%20Scalable%20Systems%20%7C%20Applied%20AI&descSize=18&descColor=E6F4F1&descAlignY=60" alt="Abhi Suryawanshi" width="100%" />

<a href="https://github.com/Abhi2006-cloud"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=0F766E&center=true&vCenter=true&width=640&lines=I+build+multi-tenant+backends;I+ship+RAG+apps+with+traceable+answers;I+connect+hardware+sensors+to+ML+pipelines" alt="Typing animation" /></a>

<br/>

<a href="https://www.linkedin.com/in/abhi-suryawanshi-531b3a324/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:workforabhi1314@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://feisty-vitality-production-0f8b.up.railway.app/"><img src="https://img.shields.io/badge/Live%20Demo-Document%20Copilot-0F766E?style=for-the-badge&logo=railway&logoColor=white" alt="Live demo" /></a>

</div>

---

## 👋 About Me

```python
class Abhi:
    name      = "Abhi Suryawanshi"
    education = "B.Tech ECE @ IIIT Bhagalpur (2024–2028)"
    focus     = ["Backend Engineering", "Applied AI / RAG", "System Design"]
    stack     = ["Python", "FastAPI", "PostgreSQL", "Redis", "React + TypeScript"]
    learning  = ["DSA in C++", "Scalable System Design"]
    open_to   = "Backend / AI engineering internships"
```

I build backend systems that are **secure, tenant-aware and production-shaped**, and AI applications whose answers you can **trace back to a source**. I also like the hardware end: sensors, telemetry and ML on real data.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="33%" valign="top">

### 🏢 FastAPI-Tenant
**Multi-tenant AI Workspace SaaS backend**

Organization-scoped access, JWT + RBAC, invitations, file management, audit logs and background jobs.

`FastAPI` `PostgreSQL` `SQLAlchemy` `Redis` `Docker`

[**View repo →**](https://github.com/Abhi2006-cloud/FastAPI-Tenant)

</td>
<td width="33%" valign="top">

### 📄 Document Copilot
**AI research assistant for SEC 10-K filings** · 🟢 *Live*

Hybrid retrieval (vectors + full-text with RRF), citations validated against source passages, streamed answers.

`PydanticAI` `pgvector` `Supabase` `SSE` `React`

[**Live demo →**](https://feisty-vitality-production-0f8b.up.railway.app/) · [**Code →**](https://github.com/Abhi2006-cloud/document-copilot)

</td>
<td width="33%" valign="top">

### ⛏️ Terra Sense
**Mine subsidence early-warning system** · IoT + ML

ESP32 sensor nodes → edge gateway → FastAPI. Anomaly detection and risk scoring with live alerts on a GIS map.

`ESP32` `scikit-learn` `WebSockets` `Leaflet` `React`

[**View repo →**](https://github.com/Abhi2006-cloud/sih-backend)

</td>
</tr>
</table>

---

### 1️⃣ [FastAPI-Tenant — Multi-Tenant AI Workspace SaaS](https://github.com/Abhi2006-cloud/FastAPI-Tenant)

> One backend, many organizations, with data isolation built in from the start.

- **Tenant-aware request handling** with organization-scoped data access.
- **JWT authentication and role-based access control** for organization membership.
- **Modular services** for organizations, invitations, file management, audit logs and background jobs.
- **Async data layer** using SQLAlchemy with PostgreSQL, plus Redis-backed infrastructure.
- **React + TypeScript dashboard**, with Docker and GitHub Actions workflows.

**Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · Redis · React · TypeScript · Docker

---

### 2️⃣ [Document Copilot — AI Financial Research Assistant](https://github.com/Abhi2006-cloud/document-copilot)

> Ask questions about 10-K filings and get answers you can verify.

- **Hybrid retrieval:** dense vector search combined with PostgreSQL full-text search using Reciprocal Rank Fusion (RRF).
- **Agent workflow** built with PydanticAI to answer questions over indexed filings.
- **Real-time streaming** of agent progress and answer events to the UI via Server-Sent Events.
- **Citation validation:** answer citations are checked against retrieved passages and linked to filing evidence.
- **Secure data layer** on Supabase PostgreSQL with pgvector and Row-Level Security.

<a href="https://feisty-vitality-production-0f8b.up.railway.app/"><img src="https://img.shields.io/badge/▶%20Try%20the%20Live%20Demo-0F766E?style=for-the-badge&logo=railway&logoColor=white" alt="Live demo" /></a>
<a href="https://github.com/Abhi2006-cloud/document-copilot"><img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source" /></a>

**Stack:** Python · FastAPI · PydanticAI · PostgreSQL · pgvector · Supabase · React · TypeScript · SSE

---

### 3️⃣ [Terra Sense — Mine Subsidence Monitoring & Early Warning](https://github.com/Abhi2006-cloud/sih-backend)

> Built for Smart India Hackathon. Hardware readings in, risk alerts out.

- **End-to-end IoT pipeline:** ESP32/NodeMCU sensor nodes and an edge gateway feeding a FastAPI backend.
- **Telemetry processing** of tilt and vibration data, with derived features for anomaly and risk analysis.
- **Layered ML:** Isolation Forest for anomaly detection, Gradient Boosting for risk scoring, and deterministic fallback rules.
- **Live alerts** over WebSockets, with GIS-based risk visualization in a React dashboard.
- **Honest demo design:** physical-hardware readings are kept separate from simulated telemetry in the dashboard.

**Stack:** Python · FastAPI · scikit-learn · ESP32 · C++ · React · TypeScript · WebSockets · Leaflet · PostgreSQL · Redis

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**AI, Frontend & Embedded**

![PydanticAI](https://img.shields.io/badge/PydanticAI-E92063?style=flat-square&logo=pydantic&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Arduino](https://img.shields.io/badge/ESP32%20%2F%20Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

---

## 📊 GitHub Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Abhi2006-cloud&show_icons=true&hide_border=true&include_all_commits=true&bg_color=FFFFFF&title_color=0F766E&text_color=334155&icon_color=0F766E" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhi2006-cloud&layout=compact&langs_count=8&hide_border=true&bg_color=FFFFFF&title_color=0F766E&text_color=334155" alt="Top languages" />
</div>

---

<div align="center">

### 📬 Let's build something together

<a href="https://www.linkedin.com/in/abhi-suryawanshi-531b3a324/">LinkedIn</a> · <a href="mailto:workforabhi1314@gmail.com">workforabhi1314@gmail.com</a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:16324F,100:0F766E&section=footer" width="100%" alt="" />

</div>
