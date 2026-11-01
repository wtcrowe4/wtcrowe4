<!-- wtcrowe4/wtcrowe4 — GitHub profile README. Edit master-profile.md first, then sync. -->

<img src="golf_icons.jpg" alt="Thomas Crowe — Full-Stack Developer & Technical Operations Lead" width="100%" />

# Thomas Crowe

### Full-Stack Developer & Technical Operations Lead — [CalibrationWands.com](https://calibrationwands.com) (Fastec Services LLC)

📍 Greenville, SC &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/wthomascrowe) &nbsp;·&nbsp; [Portfolio](https://thomascrowe.netlify.app) &nbsp;·&nbsp; 📫 wtcrowe4@outlook.com

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

Full-stack developer and technical operations lead for a B2B e-commerce manufacturer. I build production web apps, internal platforms, business-system integrations, and self-hosted AI automation, and I run the infrastructure they deploy to.

## 🛠️ Recent work (shipped, for a real company)

- **Test Standards Hub**: internal platform (React/Vite · Express · Prisma/PostgreSQL) that turns orders into manufacturing outputs: **3,800+ auto-generated NIST-traceable certificates** (~450 hours of manual work eliminated), engraving SVGs, and STL files for the CNC machine. Certificates are signed with pyHanko for tamper-evident verification.
- **Self-hosted AI agents**: 6 production agents (order processing, PO parsing, email triage, document handling, CNC G-code) on LangGraph + custom Python, served on vLLM/Ollama at zero per-call API cost, with pgvector RAG and Langfuse tracing.
- **Order-to-manufacturing automation**: a WordPress webhook over a **Cloudflare Tunnel** triggers certificate generation and PrintNode shop-floor printing on every order, generates UPS labels with tracking written back, and serves certificates through an account-gated customer portal. No exposed origin, no manual hand-off.
- **Accounting & inventory integration**: QuickBooks Desktop (qbXML) and Zoho Inventory wired into the order platform, with per-write verification and an audit log with revert; an LLM intake pipeline turns emailed POs into validated orders, with human approval before anything posts.
- **Zero-downtime production migration**: moved a live B2B store to dedicated DigitalOcean NVMe hosting with no downtime or data loss; recurring outages went from 145+/month to near zero.
- **CI/CD & observability**: GitLab CI with secret scanning, zero-restart release-swap deploys with health checks, Sentry/Bugsink error tracking, and Slack alerting.
- **WooCommerce platform engineering**: 50+ custom plugins and a dynamic SKU configurator across 10 product lines; recovered 1,534 order records with targeted SQL and added validation guards.

➡️ Sanitized architecture write-ups: **[work-casebook](https://github.com/wtcrowe4/work-casebook)**

## 🧰 Stack

| | |
|---|---|
| **Languages** | JavaScript/TypeScript · Python · PHP · SQL · Bash · PowerShell · C# |
| **Web** | React · Next.js · Node.js/Express · REST APIs · React Three Fiber · Tailwind · Vite |
| **Data** | PostgreSQL · Prisma · pgvector · MySQL/MariaDB · SQL Server · MongoDB · FastAPI |
| **Testing** | Vitest · Node test runner · Supertest · Playwright · ESLint · CI test gates |
| **Infra / DevOps** | Docker · Linux/systemd · GitLab CI · Cloudflare (Tunnel/Access) · AWS · DigitalOcean · Oracle Cloud · Sentry · Tailscale |
| **Business systems** | WordPress/WooCommerce · Stripe · QuickBooks Desktop (qbXML) · Zoho Inventory · UPS API · PrintNode |
| **AI / Automation** | vLLM · Ollama · LangGraph · RAG (pgvector) · Unsloth/PyTorch · Langfuse · MCP · Claude Code |

## 📌 Featured

- **[work-casebook](https://github.com/wtcrowe4/work-casebook)** — architecture + outcomes from the production work above (no client IP)
- **[sawgrass_17](https://github.com/wtcrowe4/sawgrass_17)** / **[thomascrowe](https://github.com/wtcrowe4/thomascrowe)** — 3D golf-analytics visualization (Next.js 16 · React Three Fiber)
- **test-standards-hub** — internal order, certificate & CNC-engraving platform *(private — work)*
