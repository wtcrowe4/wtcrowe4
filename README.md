<!-- wtcrowe4/wtcrowe4 — GitHub profile README. Edit master-profile.md first, then sync. -->

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

Sole technical operator of a B2B WooCommerce e-commerce manufacturer — I own the whole surface: the WordPress/PHP storefront and custom SKU systems, self-hosted Linux infrastructure, an ERP deployment with Python ETL, business-system integrations, and AI automation. I ship revenue-critical features, run the platform they deploy to, and translate between technical and business stakeholders daily.

## 🛠️ Recent work (shipped, for a real company)

- **Zero-downtime production migration** — moved a live WooCommerce store off a failing shared host to a Cloudways-managed DigitalOcean droplet. DNS + CDN cutover (Cloudflare), SSL, email deliverability, WP-cron via system crontab, Stripe webhook verification — **zero data loss**, plus post-migration credential rotation and 2FA rollout.
- **Test Standards Hub** — built an internal order, certificate & production platform (React/Vite · Express · Prisma/PostgreSQL · Adobe PDF Services). Unifies WooCommerce + QuickBooks order tracking in one dashboard, auto-generates calibration certificates, tracks serialized test numbers in a relational DB, and emits **SVG engraving files straight to a CNC machine**.
- **ERPNext v16 deployment + ETL** — built and deployed ERPNext (Docker) ahead of company rollout; designed a company-wide SKU schema and wrote Python ETL converting QuickBooks exports — **4,720 products and 2,852 customers** imported via API.
- **Forensic data recovery** — recovered **1,534 corrupted WooCommerce order numbers** (third-party plugin fault) via SQL, then wrote PHP guards to prevent recurrence.
- **Custom storefront engineering** — dynamic SKU-configurator JavaScript across **10 product lines**, conditional product-options logic, custom Dompdf invoice templates, Stripe payments, Cloudflare CDN.
- **AI automation** — LLM-powered purchase-order agent (Ollama, local models) that parses customer POs and auto-maps line items to catalog SKUs.

➡️ Sanitized architecture write-ups: **[work-casebook](https://github.com/wtcrowe4/work-casebook)**

## 🧰 Stack

| | |
|---|---|
| **Languages** | JavaScript/TypeScript · Python · PHP · SQL · C# · Bash |
| **Frontend** | React · Next.js · Node/Express · React Three Fiber · Tailwind · HTML/CSS |
| **Backend / CMS** | WordPress · WooCommerce · Express · custom PHP · REST APIs |
| **Data** | PostgreSQL · Prisma · MySQL/MariaDB · MongoDB · MSSQL |
| **Infra / DevOps** | Docker · Linux/WSL · Cloudflare · DigitalOcean/Cloudways · Tailscale · AWS · Azure · Netlify |
| **ERP / Business** | ERPNext · QuickBooks (QBWC/SOAP) · Stripe |
| **AI / Automation** | Ollama (local LLMs) · agent pipelines · MCP · PDF pipelines · Claude Code |

## 📌 Featured

- **[work-casebook](https://github.com/wtcrowe4/work-casebook)** — architecture + outcomes from the production work above (no client IP)
- **[sawgrass_17](https://github.com/wtcrowe4/sawgrass_17)** / **[thomascrowe](https://github.com/wtcrowe4/thomascrowe)** — 3D golf-analytics visualization (Next.js 16 · React Three Fiber)
- **test-standards-hub** — internal order, certificate & CNC-engraving platform *(private — work)*
