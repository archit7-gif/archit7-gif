<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Archit%20Pandey&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20MERN%20%7C%20Building%20Systems%20That%20Ship&descAlignY=58&descSize=16" />
</div>

<br/>

<div align="center">
  <a href="mailto:archit.pandey0007@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/archit-pandey-580069349/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://portfolio-ochre-eta-10.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</div>

<br/>

---

## About

Full-stack developer building production-ready applications with the MERN stack, focused on clean architecture, scalable systems, and reliable API design. Experienced in integrating modern APIs and AI services while designing systems that remain maintainable, secure, and resilient under real-world usage.

Every project I ship teaches me something about what it actually takes to build software that holds up.

```js
const archit = {
  stack:     ["Node.js", "Express", "MongoDB", "React"],
  focus:     "API design, auth systems, scalable data flow, AI integrations",
  strengths: ["Building things end-to-end", "Security & reliability", "Solving real problems with code"],
  currently: "Building systems. Shipping code. Learning by doing."
};
```

---

## Featured Projects

### PR Lens — AI-Powered Pull Request Reviewer
> A GitHub App that analyzes pull request diffs using AI and delivers structured code review insights to a developer dashboard — built to assist the review process, not replace it.

**Live:** [github-buddy.vercel.app](https://github-buddy.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/GITHUB-BUDDY](https://github.com/archit7-gif/GITHUB-BUDDY)

**Key implementations**

- Designed an async job processing system that decouples GitHub event ingestion from AI analysis — keeping the system fast and resilient under load
- **Human-in-the-loop publishing pipeline**: pending → approved → published, giving developers full control before any feedback is posted back to GitHub
- **Commit-aware job deduplication** using PR ID + commit SHA — guaranteeing each unique code change is processed exactly once
- **Short-term review context** retained per PR so feedback stays consistent and non-repetitive across multiple commits
- Secured end-to-end with request signature verification, scoped permissions, and short-lived JWT sessions

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Redis` · `React 19` · `Google Gemini API` · `GitHub Apps API` · `JWT`

---

### JobScribe — AI Resume Optimizer & Job Tracker
> Analyzes resumes against job descriptions using AI and combines it with a full job application tracker — solving resume quality and application management in one place.

**Live:** [job-scribe-neon.vercel.app](https://job-scribe-neon.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/JOB-SCRIBE](https://github.com/archit7-gif/JOB-SCRIBE)

**Key implementations**

- **AI resume analysis** — match score (0–100%), missing keywords, and section-wise feedback via Google Gemini API
- **Response caching** to eliminate redundant AI calls and stay within rate limits under concurrent usage
- **Job application tracker** with Saved → Applied → Interview → Offer/Rejected status pipeline
- Backend secured with **JWT authentication**, bcrypt password hashing, **RBAC**, and request rate limiting

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `React.js` · `Redux Toolkit` · `Google Gemini API` · `JWT`

---

### Cognify — Real-Time AI Chat with Semantic Memory
> Real-time chat application where AI remembers past conversations using vector search — keeping context alive across sessions.

**Live:** [cognify-taupe.vercel.app](https://cognify-taupe.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/Cognify](https://github.com/archit7-gif/Cognify)

**Key implementations**

- Real-time bi-directional messaging via **Socket.IO**
- Message embeddings via **Google Gemini**, semantic memory stored and queried through **Pinecone**
- Synchronized deletion between MongoDB and Pinecone to maintain consistent data state
- Secure authentication with **JWT + httpOnly cookies**

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Socket.IO` · `Pinecone` · `Google Gemini` · `React` · `Redux Toolkit`

---

## Technical Skills

### Backend & Data
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square)

### Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

### Engineering Practices
`API Design` &nbsp;·&nbsp; `Authentication & Authorization` &nbsp;·&nbsp; `RBAC` &nbsp;·&nbsp; `Rate Limiting` &nbsp;·&nbsp; `Caching` &nbsp;·&nbsp; `Security Hardening` &nbsp;·&nbsp; `Async Processing` &nbsp;·&nbsp; `Performance Optimization`

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
Docker & CI/CD          →  Containerizing apps, automating deployment pipelines
Redis & Caching         →  API performance optimization at scale
MongoDB Aggregation     →  Complex data pipelines and query optimization
Distributed Systems     →  Reliability, consistency, and scalable architecture patterns
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer"/>
  <br/>
  <em>Building real systems. Learning by shipping.</em>
</div>
