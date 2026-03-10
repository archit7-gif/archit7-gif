<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Archit%20Pandey&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20MERN%20%7C%20Building%20Systems%20That%20Ship&descAlignY=58&descSize=16" />
</div>

<br/>

<div align="center">
  <a href="mailto:archit.pandey0007@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/archit-pandey-580069349/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/ArchitP8296053"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>
</div>

<br/>

---

## About

Full-stack developer building production-ready MERN applications — from REST API architecture and authentication systems to async job processing and AI integrations. I focus on the backend layer: event-driven design, secure APIs, scalable data flow, and systems that hold up under real-world conditions.

Currently exploring Docker, CI/CD pipelines, and distributed system patterns to push what I build closer to production-grade infrastructure.

```js
const archit = {
  stack:     ["Node.js", "Express", "MongoDB", "React"],
  focus:     "Backend systems, API design, event-driven architecture",
  strengths: ["Async processing", "Auth & security", "AI integrations", "Webhook systems"],
  currently: "Building systems. Shipping code. Learning by doing."
};
```

---

## Featured Projects

### PR Lens — AI-Powered Pull Request Reviewer
> Automates PR feedback for engineering teams using AI-assisted code analysis integrated directly into GitHub.

**Live:** [github-buddy.vercel.app](https://github-buddy.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/GITHUB-BUDDY](https://github.com/archit7-gif/GITHUB-BUDDY)

**What it does**

PR Lens is a GitHub App that listens for pull request events, analyzes code diffs using AI, and delivers structured review insights to a developer dashboard. AI reviews are never posted automatically — every review goes through a developer-controlled pipeline before reaching GitHub.

**Key implementations**

- Webhook ingestion with **immediate HTTP 200 response** and async job queuing via **Redis** — keeping handlers fast and the system resilient
- **Human-in-the-loop publishing pipeline**: pending → approved → published, giving developers full control before feedback reaches GitHub via the Apps API
- **Commit-aware job deduplication** using PR ID + commit SHA — each unique code change is processed exactly once regardless of repeated webhook deliveries
- **Short-term review context** retained per PR to reduce repeated suggestions and keep feedback consistent across multiple commits
- Security hardened with **GitHub webhook signature verification**, scoped App permissions, and short-lived JWT sessions

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Redis` · `React 19` · `Google Gemini API` · `GitHub Apps API` · `JWT`

---

### JobScribe — AI Resume Optimizer & Job Tracker
> Helps job seekers analyze resume-job fit and manage their entire application pipeline from one place.

**Live:** [job-scribe-neon.vercel.app](https://job-scribe-neon.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/JOB-SCRIBE](https://github.com/archit7-gif/JOB-SCRIBE)

**What it does**

JobScribe sends resumes and job descriptions to the Google Gemini API and returns a structured match score, missing keywords, and section-wise improvement suggestions. Built alongside a job application tracker so users can manage their entire search in one place.

**Key implementations**

- **AI resume analysis** — match score (0–100%), missing keywords, section-wise feedback via Google Gemini API
- **AI response caching** to reduce redundant API calls and prevent rate-limit exhaustion under concurrent load
- **Job application tracker** with Saved → Applied → Interview → Offer/Rejected status pipeline
- Backend secured with **JWT authentication**, bcrypt, **RBAC**, and request rate limiting

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `React.js` · `Redux Toolkit` · `Google Gemini API` · `JWT`

---

### Cognify — Real-Time AI Chat with Semantic Memory
> Real-time chat application with persistent AI memory across sessions using vector search.

**Live:** [cognify-taupe.vercel.app](https://cognify-taupe.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/Cognify](https://github.com/archit7-gif/Cognify)

**Key implementations**

- Real-time bi-directional messaging via **Socket.IO**
- Message embeddings via **Google Gemini**, semantic memory stored and queried through **Pinecone**
- Synchronized deletion between MongoDB and Pinecone for consistent data state
- Secure auth with **JWT + httpOnly cookies**

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Socket.IO` · `Pinecone` · `Google Gemini` · `React` · `Redux Toolkit`

---

## Technical Skills

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### Engineering Practices
`RBAC` · `Rate Limiting` · `Caching` · `Webhook Systems` · `Async Processing` · `API Design` · `Security Hardening` · `Performance Optimization`

---

## GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=archit7-gif&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=archit7-gif&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=archit7-gif&theme=tokyonight&hide_border=true"/>
</div>

---

## Current Focus

```
Docker & CI/CD          →  Containerizing apps and automating deployment pipelines
Redis & Caching         →  Optimizing API performance at scale
MongoDB Aggregation     →  Complex data pipelines and query optimization
Distributed Systems     →  Reliability, consistency, and event-driven design patterns
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer"/>
  <br/>
  <em>Building real systems. Learning by shipping.</em>
</div>
