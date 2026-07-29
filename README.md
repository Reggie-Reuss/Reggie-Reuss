# Hi, I'm Reggie

**Business Intelligence Developer** at P.L. Marketing — cloud data infrastructure, ETL pipelines, and analytics products supporting Kroger retail brands.

BS in Informatics from Indiana University, with minors in Psychology and Neuroscience.

---

## What I'm building now

**three sixty Insights** — a multi-tenant client analytics portal. An SPFx/React web part on a FastAPI service reading a Microsoft Fabric Warehouse: retail brands sign in with their existing Microsoft identity and see their own performance inside Kroger alongside competitive category context.

I'm **one of two developers** on it, and I **lead the QA team of 3**.

**Building it** — backend API and query layer, commodity-scoped row-level security enforced at SQL-build time, an injection-safe drag-compose report builder, a validated calculated-field DSL, scorecard generation with `.pptx` export, and an RLS-bound AI Q&A agent whose tools receive the caller's identity rather than a model-supplied scope. 69 merged PRs across 19 tagged releases.

**Testing it** — three release-gated rounds so far: 283 checklist lines executed, 49 defects filed and triaged, across owned lanes for functionality and SQL verification, security and AI red-teaming, and platform/access. Each round's results also document what was left *unverified* — vacuous passes, blocked test accounts, regressions that fell through — and every one becomes a numbered line in the next round.

---

## What I Do

**Data Engineering** — Python ETL loading retail POS, velocity, and distribution data into Azure SQL and Microsoft Fabric. Automated scorecard generation serving 50+ clients supporting $500M in revenue, plus the desktop Pipeline Console the team runs the weekly load from.

**Analytics & Visualization** — SQL views, Power BI reports and semantic models, and executive reporting for senior leadership. Four custom Power BI visuals in TypeScript/D3 for cases stock visuals couldn't cover.

**AI & Automation** — Claude Vision brand matching, MCP-backed executive summary generation, product image and PDF automation. Plus a Power BI skill suite for Claude Code that builds reports from TMDL/PBIR source and self-verifies them against a live render before calling the work done.

---

## Professional Contributions

| Workstream | Contributions | Scope |
|---|---|---|
| Retail analytics warehouse & ETL | 128 commits · 62 PRs | Weekly Kroger ingestion into Azure SQL, the analytical view layer, scorecards, AI insight reports |
| Client analytics portal | 65 commits · 70 PRs | SPFx + FastAPI + Fabric Warehouse; row-level security, report builder, AI agent; QA lead |
| Power BI reporting | 90 commits · 25 PRs | Reports, semantic models, executive reporting infrastructure |
| Power BI tooling & custom visuals | 46 commits · 18 PRs | Claude Code skill suite for programmatic authoring; four TypeScript/D3 visuals |
| Pipeline Console | 21 commits · 13 PRs | Python desktop control room wrapping the weekly ETL |
| P.L. Marketing BI (ad hoc) | 28 commits · 8 PRs | Python automation, product image generation, internal tooling |
| Kroger Technology | ~91 contributions | Terraform IaC CI/CD with staged validation, nonprod SQL Server deployment, RBAC across nonprod and prod, Key Vault, networking, geo-redundant backups |

---

## Personal & Open Source

**[Ralph Wiggum Manager](https://github.com/Reggie-Reuss/ralph-wiggum-manager)** (archived) — full-stack dashboard for managing autonomous Claude Code loops. 127-endpoint Python API, 17-table SQLite backend, 25-command CLI bridge, 9-page vanilla JS frontend. In production: 908 tasks completed, 98.8% iteration success across 54+ hours unattended.

**RuneLite** — forked the Flipping Utilities plugin to add SQLite crash-proof storage and GE history import, with upstream PRs to [Flipping-Utilities/rl-plugin](https://github.com/Flipping-Utilities/rl-plugin). [Forensic recovery](https://github.com/Reggie-Reuss/runescape-fu-data-recovery) of ~1,400 lost trade entries from a corrupted NVMe SSD.

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
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/reggie-reuss/)
