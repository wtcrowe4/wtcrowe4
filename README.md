<!-- wtcrowe4/wtcrowe4 — GitHub profile README. Edit master-profile.md first, then sync. -->

<img src="golf_icons.jpg" alt="Thomas Crowe — Full-Stack & AI Engineer" width="100%" />

# Thomas Crowe

### Full-Stack & AI Engineer — [CalibrationWands.com](https://calibrationwands.com) (Fastec Services LLC)

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

I build and run the entire technical stack of a B2B e-commerce manufacturer — production web apps, self-hosted AI automation, cloud infrastructure, and business-system integrations. Solo operator, every layer from React UI to Linux box. I turn manual operations into software that ships, and I run the platform it deploys to.

## 🤖 AI automation (self-hosted, zero per-call cost)

- **6 production AI agents** — order processing, PO-to-SKU parsing, email triage, document handling, CNC G-code generation — orchestrated on **LangGraph** + custom Python (Slack Socket Mode), served on a self-hosted **vLLM / Ollama** stack at **zero per-call API cost**. Quantized (AWQ/GPTQ) for throughput; traces and evals in **Langfuse**.
- **RAG knowledge system** — semantic retrieval (chunk to embeddings to **pgvector**) grounding agent responses in source documents; local models fine-tuned with **Unsloth/PyTorch**, training tracked in Weights & Biases.

## 🛠️ Shipped for a real company

- **Test Standards Hub** — internal full-stack platform (React/Vite · Express · Prisma/PostgreSQL · Adobe PDF Services) turning WooCommerce orders into manufacturing outputs: **3,800+ NIST-traceable certificates** (~450 hrs of manual work eliminated), engraving SVGs, and CNC-ready STL files. Certs cryptographically signed (pyHanko) for tamper-evidence.
- **Order-to-manufacturing automation** — WordPress webhook over a **Cloudflare Tunnel** triggers cert generation + PrintNode shop-floor printing on every order, generates UPS labels with tracking write-back, serves certs through an account-gated customer portal. No exposed origin, no manual hand-off.
- **Zero-downtime production migration** — moved a live store to dedicated DigitalOcean NVMe hosting with no data loss; killed a **CVSS 9.8** plugin vuln; three-tier backup/DR; two-tailnet **Tailscale** topology for least-privilege remote access.
- **ERPNext v16 deployment + ETL** — deployed ERPNext (Docker) ahead of rollout; Python ETL converting QuickBooks exports — **4,720 products, 2,852 customers** under a custom SKU schema.
- **SQL data recovery** — recovered **1,534 corrupted order records** via targeted SQL, then added PHP guards to prevent recurrence.

➡️ Sanitized architecture write-ups: **[work-casebook](https://github.com/wtcrowe4/work-casebook)**

## 🧰 Stack

| | |
|---|---|
| **Languages** | JavaScript/TypeScript · Python · PHP · SQL · C# · Bash |
| **AI / ML** | vLLM · Ollama · LangGraph/LangChain · RAG (pgvector) · Hugging Face/PyTorch · Unsloth · AWQ/GPTQ · Langfuse · MCP |
| **Frontend** | React · Next.js · Node/Express · React Three Fiber · Tailwind · Playwright |
| **Backend / CMS** | WordPress · WooCommerce · Express · custom PHP · REST APIs |
| **Data** | PostgreSQL · Prisma · pgvector · MySQL/MariaDB |
| **Infra / DevOps** | Docker · Linux/WSL · Cloudflare · DigitalOcean/Cloudways · Tailscale · SOPS/age · Netlify |
| **ERP / Business** | ERPNext · QuickBooks (QBWC/SOAP) · Stripe · PrintNode |

## 📌 Featured

- **[work-casebook](https://github.com/wtcrowe4/work-casebook)** — architecture + outcomes from the production work above (no client IP)
- **[sawgrass_17](https://github.com/wtcrowe4/sawgrass_17)** / **[thomascrowe](https://github.com/wtcrowe4/thomascrowe)** — 3D golf-analytics visualization (Next.js 16 · React Three Fiber)
- **test-standards-hub** — internal order, certificate & CNC-engraving platform *(private — work)*
