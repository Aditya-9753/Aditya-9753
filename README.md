<!--
  NOTE (Aditya ke liye, GitHub pe dikhega nahi):
  "How I Build" aur project highlights me jo practices likhi hain (tests, CI, Swagger docs, etc.),
  sirf wahi rakhna jo repo me sach me hai. Recruiter repo khol ke check karte hain —
  jo claim repo me match kare wahi trust banata hai.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,100:8B5CF6&height=200&section=header&text=Aditya%20Tiwari&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20MERN%20%26%20Python%20%7C%20Applied%20AI&descAlignY=55&descSize=18" width="100%" alt="Aditya Tiwari — Full-Stack Developer · MERN & Python · Applied AI"/>

<a href="https://www.linkedin.com/in/aditya-tiwari-5a1977249" target="_blank">
  <img src="https://readme-typing-svg.demolab.com/?lines=I+build+full-stack+apps+end-to-end;Clean+APIs+%E2%80%A2+Secure+auth+%E2%80%A2+Dockerized+deploys;MERN+%2B+FastAPI+%2B+NLP;Open+to+SDE+%2F+Full-Stack+roles&font=Fira+Code&center=true&width=620&height=45&color=8B5CF6&vCenter=true&size=22" alt="I build full-stack apps end-to-end · Clean APIs · Secure auth · Dockerized deploys" />
</a>

<p>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=Aditya-9753&style=flat-square&color=8B5CF6&label=Profile+Views" />
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/Aditya-9753?style=flat-square&color=8B5CF6&label=Followers" />
  <img alt="Open to work" src="https://img.shields.io/badge/Status-Open%20to%20Work-success?style=flat-square" />
</p>

<p>
  <a href="mailto:adityatiwari2044@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-adityatiwari2044%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/aditya-tiwari-5a1977249" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Aditya%20Tiwari-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
</p>

</div>

---

## 👋 About Me

I'm a full-stack developer who likes taking an idea all the way from **schema design → API → UI → deployment**. Most of my work sits at the intersection of **MERN / FastAPI backends** and **applied NLP**, and I care as much about *how* a project is built as *what* it does — readable code, predictable APIs, and a setup anyone can run in one command.

- 🔭 **Building:** AI-powered tools and production-style full-stack systems
- 🌱 **Leveling up in:** System Design · Advanced NLP · Cloud Deployment
- 🤝 **Open to:** SDE / Full-Stack internships & roles, and open-source collaboration
- 💬 **Ask me about:** REST API design, JWT auth flows, Dockerizing MERN/FastAPI apps

---

## 🧪 How I Build

> Shipping is the floor, not the ceiling. These are the habits I follow across my projects.

| Practice | What it looks like in my repos |
|---|---|
| 🏗️ **Clean architecture** | Separate routes / controllers / services / models — business logic never lives in route handlers |
| 🔐 **Security first** | JWT auth with protected routes, hashed passwords, input validation, secrets in `.env` (never committed) |
| 🐳 **Reproducible setup** | Docker + `docker-compose` so the whole stack runs with one command |
| 📄 **Documentation** | Every repo has a README with features, architecture, setup steps and env variables; FastAPI services expose auto-generated Swagger docs |
| 🌿 **Git discipline** | Small, focused commits with meaningful messages; feature branches merged via PRs |
| ✅ **Testing** | API testing with Postman collections; unit tests for core logic (pytest / Jest) |
| 🚀 **Deployment** | Live demos on Vercel; environment-based config for dev vs prod |

---

## 🌟 Featured Project — AI Resume Analyzer

<table>
<tr>
<td width="55%" valign="top">

### 🤖 [AI Resume Analyzer](https://github.com/Aditya-9753/BTech-AI-Resume-Analyzer-AdityaTiwari)

A production-style resume evaluator that tells candidates **how well their resume matches a job** — and how to fix it.

**What it does**
- Extracts skills from resumes using **spaCy NLP**
- Scores resume ↔ job-description fit via **semantic similarity**
- **Simulates ATS screening** to flag formatting & keyword gaps
- Generates actionable feedback with **Google Gemini**
- **Admin analytics dashboard** for usage insights

**Engineering highlights**
- FastAPI backend with typed request/response models
- JWT-based auth with role separation (user / admin)
- MongoDB for flexible resume + analysis storage
- Fully **Dockerized** — frontend, backend & DB in one compose file

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white"/> <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white"/> <img alt="spaCy" src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white"/> <img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/> <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

</td>
<td width="45%" valign="top">

**Architecture**

```mermaid
flowchart TD
    U[React Client] -->|JWT| A[FastAPI Gateway]
    A --> P[Resume Parser]
    P --> N[spaCy Skill Extraction]
    N --> S[Semantic Match + ATS Score]
    S --> G[Gemini Feedback]
    A <--> D[(MongoDB)]
    A --> R[Admin Analytics]
```

</td>
</tr>
</table>

---

## 🚀 More Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔗 [LinkZap](https://github.com/Aditya-9753/Linnkzap) · [▶ Live](https://linnkzap-yd76.vercel.app/)
Secure **MERN URL shortener** with auto QR-code generation and a real-time analytics dashboard for clicks & usage.

**Shows:** auth-protected CRUD, analytics data modeling, Dockerized MERN stack, live deployment

<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white"/> <img alt="Express" src="https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white"/> <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🏎️ [F1 Race Replay](https://github.com/Aditya-9753/F1-Race) · [▶ Live](https://f1-race-kappa.vercel.app)
Replays **real F1 telemetry** — live leaderboard, tyre data, per-driver speed / gear / DRS, with pause, rewind and speed controls.

**Shows:** working with large real-world datasets, time-series processing, interactive data visualization

<img alt="Python" src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54"/> <img alt="FastF1" src="https://img.shields.io/badge/FastF1-E10600?style=flat-square"/> <img alt="Data Viz" src="https://img.shields.io/badge/Data%20Viz-orange?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗣️ [Interview Platform](https://github.com/Aditya-9753/Interview-Platform-)
Backend that models **real technical-interview workflows** — scheduling, rounds and candidate state — through clean REST APIs.

**Shows:** RESTful resource design, workflow/state modeling, structured error handling

<img alt="Node.js" src="https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white"/> <img alt="Express" src="https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white"/> <img alt="REST API" src="https://img.shields.io/badge/REST%20API-blue?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 🔐 [CSMP — Secure Messaging Protocol](https://github.com/Aditya-9753/CSMP-)
A custom **secure messaging protocol** covering session management and real-time communication.

**Shows:** protocol design, session lifecycle handling, thinking about security and scale at the backend level

<img alt="Security" src="https://img.shields.io/badge/Security-critical?style=flat-square"/> <img alt="Real-time" src="https://img.shields.io/badge/Real--time-yellow?style=flat-square"/> <img alt="Backend" src="https://img.shields.io/badge/Backend-informational?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [AI Research Assistant](https://github.com/Aditya-9753/Research-Assistant)
Parses natural-language research queries and returns context-aware, structured responses.

**Shows:** NLP query handling, LLM integration, automation pipelines

<img alt="Python" src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54"/> <img alt="AI" src="https://img.shields.io/badge/AI-purple?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 📚 More on my profile
- **[LMS](https://github.com/Aditya-9753/LMS)** — MERN Learning Management System with courses & role-based access
- **[camonk-blog-app](https://github.com/Aditya-9753/camonk-blog-app)** — React + Vite blog platform

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<table align="center">
<tr>
<td align="center" width="130"><b>Frontend</b></td>
<td>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</td>
</tr>
<tr>
<td align="center"><b>Backend</b></td>
<td>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img alt="Express.js" src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
</td>
</tr>
<tr>
<td align="center"><b>Database</b></td>
<td>
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</td>
</tr>
<tr>
<td align="center"><b>AI / ML</b></td>
<td>
  <img alt="spaCy" src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" />
  <img alt="Google Gemini" src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img alt="NLP" src="https://img.shields.io/badge/NLP-8B5CF6?style=for-the-badge" />
</td>
</tr>
<tr>
<td align="center"><b>DevOps & Tools</b></td>
<td>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</td>
</tr>
</table>

---

## 📊 GitHub Activity

<div align="center">
  <a href="https://github.com/Aditya-9753">
    <img src="https://streak-stats.demolab.com/?user=Aditya-9753&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=8B5CF6&currStreakLabel=A78BFA" alt="GitHub streak stats for Aditya-9753" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/Aditya-9753">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Aditya-9753&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C4B5FD" width="95%" alt="Contribution activity graph for Aditya-9753" />
  </a>
</div>

---

## 📫 Let's Connect

<div align="center">

I'm actively looking for **SDE / Full-Stack opportunities**. If you're building something interesting, I'd love to talk.

<a href="https://www.linkedin.com/in/aditya-tiwari-5a1977249" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:adityatiwari2044@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br><br>

<i>⭐ Consistency beats speed — one commit at a time.</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:6366F1&height=100&section=footer" width="100%" alt=""/>
