<!-- Header -->
<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=2000&color=9B59B6&center=true&vCenter=true&width=600&duration=3000&lines=Cameron+Williams;Shipping+products+from+a+homelab." alt="Typing SVG" />

<br/>

<a href="https://github.com/camwillm">GitHub</a> &nbsp;•&nbsp;
<a href="https://camwillm.hashnode.dev">Blog</a> &nbsp;•&nbsp;
<a href="https://linkedin.com/in/camwillm">LinkedIn</a> &nbsp;•&nbsp;
<span>Baltimore, MD</span>
</div>

<br/>

---

## About Me

I'm a computer science graduate (B.S., Morgan State University, May 2026) and an M.S. in Artificial Intelligence student at Texas A&M. I build full-stack AI systems, self-host my own infrastructure, and ship real products, not just side projects.

My homelab runs 24/7 on a Ryzen 7 5800X with 32GB RAM, hosting LLM inference, vector search, RAG pipelines, and everything I'm currently building. I use it as my personal dev platform and deploy things people actually use.

- Currently building: **Gluecozs**, a Go dashboard for my personal homelab that I plan to release as a Docker container, starting with a **read-only stock position monitor** (v1 is live on my homelab)
- Also building: **AI Resume Tailoring System** (self-hosted RAG + Claude Haiku)
- Researching: LLM failure modes, prompt evaluation, and automated grading systems
- Open to: Software Engineer / AI Engineer roles (internships and full-time) in Healthcare Tech and Fintech
- Writing about building on the homelab at: camwillm.hashnode.dev

---

## Tech Stack

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat&logo=zig&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**AI & LLM**
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=flat)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat)
![Flowise](https://img.shields.io/badge/Flowise-00C4CC?style=flat)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)

**Infra & Cloud**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

---

## Projects

| Project | Demo | Stack |
|--------|------|-------|
| [Stock Position Monitor](https://github.com/camwillm/stock-position-monitor) | [Architecture](https://github.com/camwillm/stock-position-monitor#readme) | Go, SQLite, Docker, Tailscale |
| [AI Resume Tailoring System](https://github.com/camwillm) | Private (self-hosted) | Python, Node.js, React, Qdrant, Docker |
| [BearAdvisorAI](https://github.com/camwillm/BearAdvisorAI) | Demo coming soon | React, Vertex AI, Gemini 1.5 Pro, PostgreSQL |
| [Cenarium](https://github.com/camwillm/Cenarium) | Demo coming soon | React, Fastify, PostgreSQL, Terraform, Docker |
| [The Bear Rooms](https://github.com/camwillm/ThebearRooms) | Demo coming soon | React Native, Node.js, TypeScript |
| [PantryLogger](https://github.com/camwillm/PantryLogger) | Demo coming soon | Swift, SwiftUI, MVVM |
| [Slime Mold Simulation](https://github.com/camwillm/slime-mold-zig) | Demo coming soon | Zig, WASM, Canvas |

<details>
<summary>Project descriptions</summary>

- **Stock Position Monitor** — Self-hosted, read-only stock tracker in Go. Each purchase is its own lot, with volatility-tiered alert rules, alert state saved in SQLite, a shared-fetch quote cache, and tests run under Go's race detector. No broker connection, so a bug can't trade. Alerts are log-only today; phone push is next, then it becomes a module of Gluecozs
- **AI Resume Tailoring System** — Self-hosted RAG pipeline that tailors resumes per job description. Flowise + Qdrant + Claude Haiku, 7 templates, PDF export, token tracking
- **BearAdvisorAI** — Multimodal AI advising system for Morgan State. Catches Gemini hallucinations with a 7-step validation pipeline
- **Cenarium** — Full-stack nutrition and meal planning SaaS. ETL pipeline over 1,100+ USDA food records, deployed on AWS
- **The Bear Rooms** — Roommate matching platform shipped in 24hrs at Morgan Hacks 2025
- **PantryLogger** — iOS pantry tracker with barcode scanning, expiration tracking, and waste gamification. Submitted to Apple Swift Student Challenge
- **Slime Mold Simulation** — Physarum polycephalum simulation compiled to WASM. Tero 2007 model with Gauss-Seidel solver

</details>

---

## Homelab

Running a production-grade self-hosted stack on personal hardware, 40+ containers on one server. Not a cloud VM, actual bare metal.

```
Hardware:  Ryzen 7 5800X · 32GB DDR4 · 1TB NVMe · Ubuntu 24.04
Network:   Tailscale VPN · Nginx Proxy Manager
Services:  Ollama (qwen2.5:14b) · Qdrant · Flowise · Vaultwarden · Plane · Langfuse
Apps:      AI Resume Tailoring System (RAG + Claude Haiku + React frontend)
           Stock Position Monitor (Go + SQLite, read-only alerts)
```

First blog post: [I Turned My Old Gaming PCs Into the Infrastructure I Run My Life On](https://camwillm.hashnode.dev)

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=camwillm&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=camwillm&layout=compact&theme=github_dark&hide_border=true" height="150"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=camwillm&theme=github-dark-blue&hide_border=true" height="150"/>
</div>

<!-- Snake contribution graph -->
<div align="center">
  <img src="https://raw.githubusercontent.com/camwillm/camwillm/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

---

<div align="center">
  <sub>AWS Cloud Practitioner · Morgan State University '26 · M.S. AI @ Texas A&M</sub>
</div>
