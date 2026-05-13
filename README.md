<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Archit%20Pandey&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20Microservices%20%7C%20Shipped%20to%20Production&descAlignY=58&descSize=16" />
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

Full-stack developer who builds and ships production systems — not just side projects. Comfortable across the full stack, from Next.js frontends to Node.js microservices, with hands-on experience deploying containerized applications on AWS.

I care about writing software that holds up — clean architecture, reliable APIs, and systems that handle failure gracefully.

```js
const archit = {
  stack:     ["Node.js", "Express", "MongoDB", "Redis", "RabbitMQ", "Next.js", "React"],
  deployed:  ["Docker", "AWS ECS", "AWS ECR", "AWS ALB", "Vercel"],
  focus:     "Distributed systems, scalable architecture, full-stack depth",
  strengths: ["Building end-to-end", "Production deployments", "Event-driven systems"],
  currently: "Deepening system design knowledge. Shipping real things."
};
```

---

## Featured Projects

### Bazariya — Production Microservices E-Commerce Platform
> A full marketplace built as 8 independent microservices — buyers, sellers, payments, AI shopping assistant — containerized with Docker and deployed on AWS ECS + ALB.

**Live:** [bazariya.vercel.app](https://bazariya.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/Bazariya](https://github.com/archit7-gif/Bazariya)

**Key implementations**

- **8 independent services** — Auth, Product, Cart, Order, Payment, Notification, Seller Dashboard, AI Buddy — each with its own MongoDB database and deployed as separate ECS Fargate tasks behind an ALB
- **Event-driven architecture** via RabbitMQ — services communicate through message queues, keeping them fully decoupled
- **Stock consistency with rollback** — stock decrements before order creation; any partial failure triggers a full restore, keeping inventory accurate
- **Payment resilience** — after Razorpay payment is marked COMPLETED, all downstream failures (order status, notifications, dashboard sync) are handled independently and never return 500 to the user
- **Redis-backed rate limiting and token blacklisting** — persists across server restarts and multiple ECS instances; logout truly invalidates tokens across all 6 authenticated services
- **Same-origin proxy in Next.js** — all backend calls route through the Next.js server, keeping JWT cookies httpOnly and never exposed to client-side JavaScript
- **AI shopping assistant** via LangChain agent + Gemini — buyers can search products and add to cart through natural language over Socket.IO

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Redis` · `RabbitMQ` · `Razorpay` · `ImageKit` · `Socket.IO` · `Next.js` · `Tailwind CSS` · `Zustand` · `Docker` · `AWS ECS` · `AWS ECR` · `AWS ALB` · `Vercel`

---

### PR Lens — AI-Powered Pull Request Reviewer
> A GitHub App that analyzes pull request diffs using AI and delivers structured code review insights to a developer dashboard — built to assist the review process, not replace it.

**Live:** [github-buddy.vercel.app](https://github-buddy.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/GITHUB-BUDDY](https://github.com/archit7-gif/GITHUB-BUDDY)

**Key implementations**

- Async job processing that decouples GitHub event ingestion from AI analysis — keeping the system responsive under load
- **Human-in-the-loop publishing** — pending → approved → published, giving developers full control before feedback posts to GitHub
- **Commit-aware deduplication** using PR ID + commit SHA — each unique code change processed exactly once
- Secured with request signature verification, scoped permissions, and short-lived JWT sessions

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Redis` · `React` · `Google Gemini API` · `GitHub Apps API` · `JWT`

---

### JobScribe — AI Resume Optimizer & Job Tracker
> Analyzes resumes against job descriptions using AI and combines it with a full job application tracker — solving resume quality and application management in one place.

**Live:** [job-scribe-neon.vercel.app](https://job-scribe-neon.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/JOB-SCRIBE](https://github.com/archit7-gif/JOB-SCRIBE)

**Key implementations**

- AI resume analysis — match score, missing keywords, and section-wise feedback via Gemini API
- Response caching to eliminate redundant AI calls under concurrent usage
- Job application tracker with full status pipeline — Saved → Applied → Interview → Offer/Rejected
- JWT authentication, bcrypt, RBAC, and rate limiting

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `React.js` · `Redux Toolkit` · `Google Gemini API` · `JWT`

---

### Cognify — Real-Time AI Chat with Semantic Memory
> Real-time chat where AI remembers past conversations using vector search — keeping context alive across sessions.

**Live:** [cognify-taupe.vercel.app](https://cognify-taupe.vercel.app) &nbsp;|&nbsp; **Repo:** [archit7-gif/Cognify](https://github.com/archit7-gif/Cognify)

**Key implementations**

- Real-time bi-directional messaging via Socket.IO
- Message embeddings via Gemini, semantic memory stored and queried through Pinecone
- Synchronized deletion between MongoDB and Pinecone for consistent state
- JWT + httpOnly cookie authentication

**Tech Stack**

`Node.js` · `Express.js` · `MongoDB` · `Socket.IO` · `Pinecone` · `Google Gemini` · `React` · `Redux Toolkit`

---

## Technical Skills

### Backend & Infrastructure
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS ECS](https://img.shields.io/badge/AWS_ECS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![AWS ECR](https://img.shields.io/badge/AWS_ECR-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![AWS ALB](https://img.shields.io/badge/AWS_ALB-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

### Engineering Practices
`Microservices Architecture` &nbsp;·&nbsp; `Event-Driven Design` &nbsp;·&nbsp; `REST API Design` &nbsp;·&nbsp; `Authentication & Authorization` &nbsp;·&nbsp; `RBAC` &nbsp;·&nbsp; `Rate Limiting` &nbsp;·&nbsp; `Caching` &nbsp;·&nbsp; `Partial Failure Handling`

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
Distributed Systems     →  Failure modes, consistency models, and architecture at scale
System Design           →  Translating production experience into deliberate patterns
Backend Performance     →  Query optimisation, profiling, and understanding real bottlenecks
Cloud & Infrastructure  →  Going deeper on networking, IAM, and observability
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer"/>
  <br/>
  <em>Building real systems. Shipping to production.</em>
</div>
