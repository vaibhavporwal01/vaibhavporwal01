<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Building+multi-agent+GenAI+systems;Scaling+backend+infra+that+doesn't+fall+over;Java+%7C+LangChain+%7C+AWS+%7C+Distributed+Systems" alt="Typing SVG" />

</div>

```bash
$ whoami
> Vaibhav Porwal — Final-year CSE @ Gautam Buddha University
> Obsessed with: agentic pipelines, real-time voice AI, backend that scales without babysitting
```

## About

I build two kinds of things — systems that reason (agents, RAG pipelines, LLM orchestration) and systems that hold up under load (queues, caching, real-time infra). Most of what's below sits at the intersection: AI features that actually ship on production-grade backends, not notebooks.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="3px">

## GenAI & Agentic Systems

### [AdvRAG](https://github.com/vaibhavporwal01/AdvRAG)
![Repo](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/vaibhavporwal01/AdvRAG&label=%E2%AD%90%20stars&query=$.stargazers_count&color=00D9FF&style=flat-square) ![Lang](https://img.shields.io/badge/LangGraph-Multi--Agent-1C3C3C?style=flat-square)

Multi-agent RAG pipeline.
- Multi-agent orchestration via LangChain + LangGraph — separate agents for retrieval, reranking, and synthesis instead of one monolithic chain.
- FAISS-backed vector store with custom chunking and embedding strategy for retrieval accuracy.
- Deployed on AWS (S3 for storage, ECS for compute) — not just a local demo.

### Enterprise AI Voice Interviewer
![Stack](https://img.shields.io/badge/LiveKit-Deepgram-blueviolet?style=flat-square) ![State](https://img.shields.io/badge/XState-v5-2C3E50?style=flat-square)

Full-duplex voice interview platform, built and iterated on extensively.
- **Multi-brain architecture**: Claude Sonnet runs the live conversation ("voice brain"), Claude Haiku runs supervision/scoring in parallel — split by cost and latency needs, not just capability.
- Real-time audio via **LiveKit** (transport) + **Deepgram** (STT), with **XState v5** finite-state machines managing interview flow so the conversation can't drift into an undefined state.
- **Redis + BullMQ** for async job processing (scoring, report generation), **pgvector** for long-term interview memory.
- Shipped alongside full HLD/LLD documentation, a cost model, and a client-facing architecture proposal — treated as a real system, not a hackathon prototype.

**Other GenAI work**
- **VedaAI** — Gemini API integration with Socket.IO for real-time responses, backed by BullMQ/Redis job queues.
- **Signalrank** — hybrid BM25 + embedding candidate-ranking engine, CPU-only, built to rank 100K candidates without GPU cost (Redrob AI Hackathon).
- Prompt engineering, agent tooling strategies (Gemini Pro + Antigravity), and browser-automation agents.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="3px">

## ⚙️ Backend & Scalable Systems

### Fullstack Postman Clone
![Stack](https://img.shields.io/badge/Next.js-FastAPI-000000?style=flat-square)

Next.js frontend + FastAPI backend + SQLite, deployed split across Vercel + Render.
- Multi-agent tooling strategy for request generation and validation, not just a CRUD wrapper.

### VedaAI Platform
![Stack](https://img.shields.io/badge/BullMQ-Redis-DC382D?style=flat-square) ![DB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

Next.js 15 + Node.js, MongoDB for persistence, BullMQ/Redis for background jobs, deployed on Vercel + Render.

**Core backend toolkit**: Spring Boot, REST APIs, Microservices, Node.js, PostgreSQL, MySQL, MongoDB — plus AWS (EC2, S3, IAM, CloudWatch) for infra that isn't just "works on my machine."

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="3px">

<div align="center">

### 🛠️ Stack

<img src="https://skillicons.dev/icons?i=java,python,spring,nodejs,nextjs,redis,aws,postgres,docker,kotlin,git&theme=dark" alt="Skills" />

</div>

<div align="center">


<img src="https://github-readme-streak-stats.herokuapp.com/?user=vaibhavporwal01&theme=tokyonight&hide_border=true" width="49%" alt="GitHub Streak" />

</div>

<div align="center">

<img src="https://raw.githubusercontent.com/vaibhavporwal01/vaibhavporwal01/output/github-contribution-grid-snake.svg" alt="Snake animation" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="3px">

## 🚀 Leadership

Founder & Captain, **AWS Student Builder Group @ GBU** — grew a 600+ member community, ran hands-on EC2/S3/CloudWatch workshops from the ground up.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="3px">

<div align="center">

[![Portfolio](https://img.shields.io/badge/-Portfolio-FF5722?style=flat-square&logo=vercel&logoColor=white)](https://vaibhavporwal01.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaibhav-porwal-4b219028a/)
[![Gmail](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vaibhavporwal135@gmail.com)

</div>
