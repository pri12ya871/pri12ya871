<h1 align="center">Hi, I'm Priya 👋</h1>

<p align="center">
  Backend &amp; AI engineer — I build the primitives instead of importing them.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/priya-sharma-a65902253">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:priyanautiyal978@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/pri12ya871?tab=repositories">
    <img src="https://img.shields.io/badge/All_projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="All projects" />
  </a>
</p>

---

## 🚀 About me

- 🛠️ Backend in **Node.js / Express**, AI work in **Python**
- 🧩 Most of my projects run on **zero or one runtime dependency** — I'd rather understand the layer underneath than import it
- 🤖 Currently building **LLM infrastructure**: semantic caching, agent loops, RAG with page-level citations
- 🧠 Things I've written from scratch: **Raft consensus**, the **WebSocket protocol**, a **chess engine**, a **ReAct agent loop**
- 📫 Reach me at **priyanautiyal978@gmail.com**

## 📌 Featured projects

| Project | What it is |
| --- | --- |
| **[raft-kv](https://github.com/pri12ya871/raft-kv)** | Distributed key-value store on a from-scratch Raft implementation — leader election, log replication, crash recovery, linearizable reads. Zero dependencies. |
| **[llm-gateway](https://github.com/pri12ya871/llm-gateway)** | LLM proxy with semantic caching, circuit breaking, load shedding and per-tenant cost control. Runs with no API keys. |
| **[url-shortener](https://github.com/pri12ya871/url-shortener)** | Base62 codes with collision handling, Redis cache-aside redirects, and a Lua-backed sliding-window rate limiter. |
| **[chess](https://github.com/pri12ya871/chess)** | C++20 0x88 engine verified with perft, an alpha-beta opponent, and network play. No dependencies. |
| **[doc-intelligence](https://github.com/pri12ya871/doc-intelligence)** | Ask your PDFs a question, get answers cited to the exact page. Express + pgvector + BullMQ. |
| **[chat-api](https://github.com/pri12ya871/chat-api)** | Real-time chat with rooms, presence and history over a WebSocket implementation written from scratch. |
| **[auth-service](https://github.com/pri12ya871/auth-service)** | JWT auth with refresh-token rotation, reuse detection, scrypt passwords and RBAC. |
| **[inbox-agent](https://github.com/pri12ya871/inbox-agent)** | Mail → action items → tracker. Hand-written tool-use loop with idempotent writes and a resumable journal. |

## 💻 Tech stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-404d59?style=for-the-badge&logo=express&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSockets-black?style=for-the-badge&logo=socket.io&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Frontend & tooling**

![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

## 🌱 Open source

I send patches to the tools I build on:

- **[typeorm/typeorm](https://github.com/typeorm/typeorm/pulls?q=is%3Apr+author%3Apri12ya871)** — `perf: use performance.now() for query execution timing`. `QueryRunner.query()` measured elapsed time with `Date.now()`, a wall-clock source that an NTP correction can move mid-query.
- **[brianc/node-postgres](https://github.com/brianc/node-postgres/pulls?q=is%3Apr+author%3Apri12ya871)** — the PostgreSQL client for Node.js.
- **[FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise/pulls?q=is%3Apr+author%3Apri12ya871)** — visual builder for LLM applications.
