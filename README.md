<div align="center">

# Rahul Kumar
### Full-Stack & AI Engineer · NIT Raipur CSE '26

[![Portfolio](https://img.shields.io/badge/Portfolio-rk.dev-6c6ef7?style=for-the-badge&logoColor=white)](https://rahulxgit.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rahulxnit-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulxnit)
[![GitHub](https://img.shields.io/badge/GitHub-rahulxgit-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulxgit)
[![LeetCode](https://img.shields.io/badge/LeetCode-1549_Rating-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/S4gKOmKmsm/)
[![Email](https://img.shields.io/badge/Email-rahulkumarshc00@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulkumarshc00@gmail.com)

<br/>

> *Building production-grade systems with startup-level ownership.*

</div>

---

## 🟢 Status — Open to SDE Roles · June 2026

Looking for **Full-Stack / Frontend / AI-adjacent SDE roles** at product companies and startups.  
Preferred locations: Bangalore · Pune · Hyderabad · Gurgaon · Remote  
Response time: within 24 hours.

---

## At a Glance

| | |
|---|---|
| 🎓 **Education** | B.Tech CSE · NIT Raipur · CGPA 8.67/10 |
| 💼 **Experience** | SDE Intern · Bluestock Fintech |
| 🏆 **Assessment** | 99.41 Percentile · Naukri Campus Young Turks 2025 |
| 🧠 **DSA** | 500+ problems · LeetCode 1549 Rating |
| 🌍 **CP Contest** | Rank ~8552 · TCS CodeVita Season 13 (100K+ participants) |
| 🤖 **AI Stack** | MCP Servers · RAG · LLM APIs · Agent Architecture |
| 📦 **Deployment** | Production systems on Vercel with CI/CD (not just demos) |

---

## Tech Stack

**Frontend**
`React.js` `Next.js 15` `TypeScript` `JavaScript` `Tailwind CSS` `Framer Motion` `Redux Toolkit` `Zustand`

**Backend**
`Node.js` `Express.js` `REST APIs` `JWT Auth` `Prisma ORM` `Firebase` `Supabase`

**Databases**
`PostgreSQL` `MongoDB` `MySQL` `IndexedDB` `Neon (Serverless)`

**AI Engineering**
`Prompt Engineering` `MCP Servers` `Context Engineering` `RAG Systems` `AI Agents` `Claude API` `OpenAI API` `LangChain` `Token Streaming` `Function Calling`

**LLMs Used**
`GPT-4o / GPT-4.1` `Claude Sonnet / Opus` `Gemini` `DeepSeek` `Grok` `OpenRouter`

**DevOps & Tools**
`Git` `GitHub Actions` `CI/CD` `Vercel` `Docker` `Postman`

**CS Fundamentals**
`DSA` `System Design` `OOP` `DBMS` `Operating Systems`

---

## Work Experience

### Software Development Engineer Intern · Bluestock Fintech
`Feb 2026 – Mar 2026 · Remote · Certified`

Built **Logic Looper** from scratch — a production-deployed daily puzzle platform. The mandate was clear: ship a real product, not a prototype.

- Designed a deterministic puzzle engine using SHA256(date + secret key) — same puzzle for all users daily, works 100% offline, zero server storage cost
- Client-side validation with <50ms latency — no server round-trips, no score tampering
- Reduced server API calls by ~70% via IndexedDB-first architecture; GitHub-style streak/heatmap loads with zero DB reads
- Backend (Node.js + PostgreSQL/Neon + Prisma) improved response time by ~40%, load-tested to 500+ concurrent users
- GitHub Actions CI/CD → Vercel with ISR caching; reduced server load globally by ~60%
- Also worked on an open-source **AI Profile Picture Maker** integrating Stable Diffusion + GFPGAN + rembg via Dockerized microservices

### Executive Member · Innovation Cell (I-Cell), NIT Raipur
`2022 – 2026 · Sponsorship & Outreach Lead`

- Led end-to-end planning of a **200+ participant national-level hackathon** — sponsorships, partnerships, technical coordination, and logistics

### Technical Events Coordinator · Robotics & Coding Club, NIT Raipur
`2022 – 2026`

- Organized contests, mentored juniors on DSA, facilitated workshops

---

## Projects

### 🎯 Logic Looper — Daily Puzzle Platform
`React · TypeScript · Redux Toolkit · IndexedDB · Node.js · PostgreSQL · Prisma · Vercel`

**[Live](https://logic-looper-mu.vercel.app/) · [GitHub](https://github.com/rahulxgit/logic-looper)**

The flagship internship capstone. The engineering challenge wasn't building a puzzle game — it was making it offline-first, cost-efficient, and production-ready.

- Deterministic generation: SHA256(date + key) delivers 365+ unique puzzles/year with zero server storage
- Client-side validation engine: <50ms, tamper-proof, no server dependency
- Offline-first via IndexedDB; backend sync batches to 1 write/day/user (1M DAU at ~$0 storage cost)
- Full CI/CD pipeline: GitHub Actions → Vercel with ISR caching

---

### 🗂️ DriveClone + MCP Server — AI-Accessible File System
`React · Node.js · MongoDB · Express · MCP Server · AI Agents`

**[GitHub](https://github.com/rahulxgit/driveclone)**

Google Drive clone with an integrated Model Context Protocol server — AI agents (Claude, GPT) can interact with the file system through natural language. Not just a MERN clone; a demonstration of agent-first architecture.

- MCP server exposes file operations as structured, AI-callable tools
- Agents can list, read, create, and move files through tool calls
- Full MERN stack with auth, folder hierarchy, and file upload

---

### ⚗️ AI Inference Playground
`React · TypeScript · SSE Streaming · LLM APIs · Tailwind`

**[GitHub](https://github.com/rahulxgit/ai-inference-playground)**

Real-time LLM inference tool built for multi-model experimentation — not a wrapper, a technical instrument.

- Token streaming via Server-Sent Events — real-time model output visualization
- Token-level diff using LCS algorithm — highlights changes between model responses
- Live latency and throughput metrics for model comparison
- Accessibility-first (ARIA) throughout

---

### 🎨 Open-Source AI Profile Picture Maker
`React · Node.js · Stable Diffusion · GFPGAN · rembg · Docker · Redis · BullMQ`

Built during internship. Self-hosted AI pipeline for profile picture generation.

- Stable Diffusion + ControlNet + GFPGAN + rembg via Dockerized microservices
- BullMQ + Redis queue for concurrent AI job handling without blocking the event loop
- Stateless by design — no accounts, temp file storage, hourly cleanup

---

### 🔖 Smart Bookmark App
`Next.js · TypeScript · Supabase · Tailwind`

**[Demo](https://www.loom.com/share/71832d00480b434eb2835f2d4fd92eee) · [GitHub](https://github.com/rahulxgit/smart-bookmark-app)**

Production-style full-stack bookmark manager built as an internship assignment.

- SSR-compatible auth with Supabase — secure session handling across server and client
- Clean layered architecture: UI → Hooks → Services → Database
- RBAC with protected routes and proper error handling

---

### 🖼️ Realtime Gallery
`React · TypeScript · Zustand · InstantDB · Tailwind`

**[Live](https://realtime-gallery-tau.vercel.app/) · [GitHub](https://github.com/rahulxgit/realtime-gallery)**

Multi-user collaborative gallery with instant emoji reactions and comments. Real-time systems exercise — event-driven, no polling.

---

### 📊 Swiggy SQL Case Study
`SQL · PostgreSQL · Data Analysis`

**[GitHub](https://github.com/rahulxgit/Swiggy-Case-Study-SQL)**

Comprehensive analytical SQL study on Swiggy operational data — cohort analysis, funnel metrics, revenue reporting. Demonstrates backend data-layer thinking beyond CRUD.

---

## Competitive Programming

| Platform | Profile | Metric |
|---|---|---|
| 🟠 LeetCode | [@S4gKOmKmsm](https://leetcode.com/u/S4gKOmKmsm/) | 1549 Rating · 500+ solved |
| 🍴 CodeChef | [@rahulxcodechef](https://www.codechef.com/users/rahulxcodechef) | Active |
| ⚡ Codeforces | [@rahulxcodeforces](https://codeforces.com/profile/rahulxcodeforces) | Active |
| 🥷 Code360 | [@rahulxninjas](https://www.naukri.com/code360/profile/rahulxninjas) | Active |
| 🟢 GeeksforGeeks | [@rahulkumo88b](https://www.geeksforgeeks.org/profile/rahulkumo88b) | Active |

DSA isn't just interview prep — it's how I think about performance-critical code. Dynamic programming, graph algorithms, and sliding-window techniques show up directly in how I design systems.

---

## Achievements

- 🥇 **99.41 Percentile** — Naukri Campus Young Turks 2025 (India's largest national tech assessment)
- 🌍 **Rank ~8552** — TCS CodeVita Season 13 (100,000+ global participants)
- ⚡ **LeetCode 1549 Rating** — 500+ problems solved across platforms
- 🏆 **Hackathon Organizer** — led 200+ participant national-level event at NIT Raipur
- 🤖 **MCP Server Integration** — DriveClone is among early student-built projects implementing Model Context Protocol for AI agent file access
- 📦 **Production-deployed internship project** — Logic Looper shipped with CI/CD, load testing, and offline architecture within a 2-month timeline

---

## Why I Build the Way I Do

Most student projects are tutorials with different variable names. I approach engineering the way a product team does — thinking about system design, scalability, and user impact from the start.

Three things I consistently prioritize:

**Client-First Architecture** — I design systems to minimize server dependency. IndexedDB, ISR caching, and deterministic client-side generation keep infrastructure costs near zero at scale.

**AI as Architecture** — I integrate LLMs and MCP servers as first-class architectural decisions, not feature additions bolted on at the end.

**Production Readiness** — Schema design, CI/CD pipelines, load testing — I treat these as requirements, not afterthoughts.

---

## Education

**National Institute of Technology, Raipur**  
B.Tech in Computer Science Engineering · 2022 – 2026  
CGPA: **8.67 / 10.0**

---

## Contact

| | |
|---|---|
| 📧 Email | [rahulkumarshc00@gmail.com](mailto:rahulkumarshc00@gmail.com) |
| 📱 Phone | [+91 7762068086](tel:+917762068086) |
| 💼 LinkedIn | [linkedin.com/in/rahulxnit](https://linkedin.com/in/rahulxnit) |
| 🐙 GitHub | [github.com/rahulxgit](https://github.com/rahulxgit) |
| 🌐 Portfolio | [rk.dev](#) |

---

<div align="center">

*Available June 2026 · Responds within 24 hours*

</div>