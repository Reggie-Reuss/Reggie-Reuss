# Hi, I'm Reggie

**Business Intelligence Developer** at P.L. Marketing — cloud data infrastructure, ETL pipelines, and analytics products supporting Kroger retail brands.

BS in Informatics from Indiana University, with minors in Psychology and Neuroscience.

---

## What I'm building now

**three sixty Insights** — a multi-tenant client analytics portal. An SPFx/React web part on a FastAPI service reading a Microsoft Fabric Warehouse: retail brands sign in with their existing Microsoft identity and see their own performance inside Kroger alongside competitive category context.

I'm **one of two developers** on it, and I **lead the QA team of 3**.

**Building it** — backend API and query layer, commodity-scoped row-level security enforced at SQL-build time, an injection-safe drag-compose report builder, a validated calculated-field DSL, and an RLS-bound AI Q&A agent whose tools receive the caller's identity rather than a model-supplied scope. Launched to clients in October 2026, with 190 merged PRs across 45 tagged releases.

**Testing it** — five release-gated rounds through launch, including an external pilot with four client brands. The first three alone executed 372 checklist lines and filed and triaged 69 defects, across owned lanes for functionality and SQL verification, security and AI red-teaming, and platform/access. Each round's results also document what was left *unverified* — vacuous passes, blocked test accounts, regressions that fell through — and every one becomes a numbered line in the next round.

---

## What I Do

**Data Engineering** — Python ETL loading retail POS, velocity, and distribution data into Azure SQL and Microsoft Fabric. Automated scorecard generation serving 50+ clients supporting $500M in revenue, plus the desktop Pipeline Console the team runs the weekly load from.

**Analytics & Visualization** — SQL views, Power BI reports and semantic models, and executive reporting for senior leadership. Four custom Power BI visuals in TypeScript/D3 for cases stock visuals couldn't cover.

**AI & Automation** — Claude Vision brand matching, MCP-backed executive summary generation, product image and PDF automation. Plus a Power BI skill suite for Claude Code that builds reports from TMDL/PBIR source and self-verifies them against a live render before calling the work done.

**Platform & Administration** — GitHub and Claude organization admin and owner of three sixty's Azure environment: deployments, code reviews, access, and security. I also teach GitHub to the analyst team.

---

## Professional Contributions

| Workstream | Org | Contributions | Scope |
|---|---|---|---|
| Retail analytics warehouse & ETL | three sixty Merchandising Solutions | 157 commits · 91 PRs | Weekly Kroger ingestion into Azure SQL, the analytical view layer, scorecards, AI insight reports |
| Client analytics portal | three sixty Merchandising Solutions | 190 commits · 203 PRs | SPFx + FastAPI + Fabric Warehouse; row-level security, report builder, AI agent; QA lead and developer |
| Power BI reporting | three sixty Merchandising Solutions | 119 commits · 38 PRs | Reports, semantic models, executive reporting infrastructure |
| Power BI tooling & custom visuals | P.L. Marketing | 49 commits · 19 PRs | Claude Code skill suite for programmatic authoring; four TypeScript/D3 visuals |
| Pipeline Console | three sixty Merchandising Solutions | 60 commits · 49 PRs | Python desktop control room wrapping the weekly ETL |
| Business intelligence (ad hoc) | P.L. Marketing | 30 commits · 12 PRs | Python automation, product image generation, internal tooling |
| Platform administration & enablement | three sixty Merchandising Solutions | 35 commits · 10 PRs | GitHub and Claude org admin, three sixty Azure owner; moved the Fabric mirror to service-principal ownership with automated health checks; org engineering standards; GitHub for Beginners training |
| Cloud infrastructure & IaC | Kroger | ~91 contributions | Terraform IaC CI/CD with staged validation, nonprod SQL Server deployment, RBAC across nonprod and prod, Key Vault, networking, geo-redundant backups |

---

## Personal & Open Source

**[house-recon](https://github.com/Reggie-Reuss/house-recon)** — automated residential real-estate due diligence: one address in, a dated-history timeline, red-flag analysis, offer guidance, and a full photo/county-record dossier out. Ships three ways: a single-file Python CLI, a fully client-side [web analyzer](https://reggie-reuss.github.io/house-recon/) (nothing you paste leaves your browser), and a companion extension published on the Chrome and Edge stores that fetches listing pages automatically. A registry-driven Cloudflare Worker pulls county auditor records across 33 counties in Ohio and Indiana, and the offer heuristics are validated against 150 zips spanning all 50 states.

**RuneLite** — forked the Flipping Utilities plugin to add SQLite crash-proof storage and GE history import, with upstream PRs to [Flipping-Utilities/rl-plugin](https://github.com/Flipping-Utilities/rl-plugin). [Forensic recovery](https://github.com/Reggie-Reuss/runescape-fu-data-recovery) of ~1,400 lost trade entries from a corrupted NVMe SSD.

**[Ralph Wiggum Manager](https://github.com/Reggie-Reuss/ralph-wiggum-manager)** (archived) — full-stack dashboard for managing autonomous Claude Code loops. 127-endpoint Python API, 17-table SQLite backend, 25-command CLI bridge, 9-page vanilla JS frontend. In production: 908 tasks completed, 98.8% iteration success across 54+ hours unattended.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/reggie-reuss/)
