# Awesome-Enterprise-Cloud-Application-Platform-Apaas

## Top Enterprise Cloud Application Platform (aPaaS) Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Low-Code App Development, Visual Modeling & Self-Hosted Application Platforms*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Cloud Application Platforms (aPaaS)**. These tools help organizations build and deploy business applications with minimal hand-coding—covering everything from visual drag-and-drop builders and spreadsheet-powered app generators to open-source frameworks that give you full code ownership without per-user licensing.

**Examples** include Microsoft Power Platform, Salesforce Platform, ServiceNow App Engine, Mendix, OutSystems, Quickbase, Appian, Oracle APEX, Google AppSheet, Zoho Creator, and open-source alternatives like Appsmith and Budibase (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted low-code platforms, open-source internal tool builders, and community-driven app development—ideal for organizations seeking data sovereignty and avoiding per-user pricing that compounds across business users. The open-source landscape is genuinely mature: **Appsmith** provides a powerful internal tool builder with 40+ widgets , **Budibase** offers a fast path to CRUD apps on top of SQL databases , and **ToolJet** delivers an AI-native low-code platform .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global enterprise cloud application platform (aPaaS) and low-code development market was valued at ~$25 billion in 2023 and is projected to reach $58B–$100B+ by 2029–2030 (growing at ~14–22% CAGR). The sector exhibits **moderate-to-high concentration** at the top tier—dominated by mega-cap ecosystem giants (Microsoft, Alphabet, Salesforce, ServiceNow, Oracle) leveraging deep cloud suites and distribution lock-in—alongside a **fragmented specialized long-tail** of pure-play vendors (Mendix, OutSystems, Appian) and fast-growing open-source self-hosted solutions offering data sovereignty and freedom from compounding per-seat licenses.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-----------------------------|--------------------|--------------------------|
| **[Microsoft Power Platform](https://powerplatform.microsoft.com/)** | **~$3.9 Trillion** Market Cap (Microsoft) | **$20/user/month** (Power Apps Premium; unlimited apps); Legacy **$5/app/user** (Per App, 1 app) | **Free Forever (Developer Plan)**: 1 non-production developer environment, full Premium connector access, Dataverse database for personal learning/testing (no production use). |
| **[Google AppSheet](https://about.appsheet.com/)** | **~$3.5 Trillion** Market Cap (Alphabet) | **$5/user/month** (Starter tier); Core: $10/user/month | **Free Forever (Prototype Plan)**: Up to 10 test users with full feature access during prototype/development; zero time limit before production deployment. |
| **[Oracle APEX](https://apex.oracle.com/)** | **~$375 Billion** Market Cap (Oracle) | **$118/month** (~$0.0807/ECPU-hr, 2 ECPUs base OCI APEX service); **$0** (included with Oracle DB license) | **Free Forever (OCI Always Free APEX)**: 2 Autonomous DB instances, 20 GB Exadata storage, max 30 concurrent sessions (~3–6 active concurrent users); strictly reclaims if inactive >7 days. |
| **[Siemens Mendix](https://www.mendix.com/)** | **~$219 Billion** Market Cap (Siemens AG; acquired for $730M) | **$1,090/month** (Standard 1-App tier; unlimited apps from $2,725/month) | **Free Forever (Free Edition)**: Unlimited test users, full visual modeling, deployed on free Mendix Cloud; apps sleep after inactivity and limited to ~1–2 hour runtimes (non-production). |
| **[Salesforce Platform](https://www.salesforce.com/)** | **~$200 Billion** Market Cap (Salesforce) | **$25/user/month** (Platform Starter, 10 custom objects); Plus: $100/user/month | **Free Forever (Developer Edition)**: 1 full-feature developer org, 2 Salesforce Platform licenses, 5 MB data storage, 20 MB file storage for development/testing. |
| **[ServiceNow App Engine](https://www.servicenow.com/)** | **~$105 Billion** Market Cap (ServiceNow) | **~$75/user/month** (Standard/Foundation tier add-on, billed annually; 15 custom tables limit) | **Free Forever (Personal Developer Instance - PDI)**: 1 dedicated sandbox with App Engine Studio; hibernates after 10 days of inactivity, reclaimed if inactive >10 days when >90 days old; no commercial/outbound traffic. |
| **[Zoho Creator](https://www.zoho.com/creator/)** | **~$12.5 Billion** Valuation (Zoho Corp; ~$1.5B Revenue) | **$8/user/month** ($12/user/mo billed monthly; Standard tier, 1 app) | **Free Forever (Free Edition)**: 1 app, 1 user, 250 developer API calls/day, basic building (or 15-day full-feature trial for paid plans). |
| **[OutSystems](https://www.outsystems.com/)** | **$4.3 Billion** Valuation (KKR-backed Series G) | **~$36,300/year** (Entry-level OutSystems Developer Cloud base package, ~150 AOs, 100 internal users) | **Free Forever (Personal Edition)**: Up to 100 internal users, 1 GB database storage, max 8 concurrent active apps/workflows/agents; hosted on shared cloud without live production environment. |
| **[Appian](https://www.appian.com/)** | **$2.6 Billion** Market Cap (NASDAQ: APPN; ~$727M Revenue) | **~$70/user/month** (Standard tier, single data source, 5 RPA bots, typically 100-user contract minimum) | **Free Forever (Community Edition)**: 1 personal cloud environment, up to 15 users, 25k synced record rows, 1 RPA bot (~50 runs/day); live production disabled (or 14-day evaluation trial). |
| **[Quickbase (Pave)](https://www.quickbase.com/)** | **~$1.5 Billion+** Valuation (Vista Equity Partners; ~$215M+ ARR) | **$120/month** (Team tier, 120 credits/mo, 2 apps, 10 users); Department: $300/month | **Free Forever (Pave Free Plan)**: 1 app, 1 builder seat, up to 3 users, 100 credits/month (or 30-day trial of Enterprise platform). |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Appsmith](https://github.com/appsmithorg/appsmith)** | [![Stars](https://img.shields.io/github/stars/appsmithorg/appsmith?style=social&color=white)](https://github.com/appsmithorg/appsmith/stargazers) | **The most complete open-source low-code platform for internal tools.** Apache-2.0. **40+ widgets** including tables, forms, charts, and maps. Connects to **25+ databases and any REST API**. JavaScript everywhere for custom logic. **Role-based access control, audit logs, and SSO** on self-hosted deployments. **Drag-and-drop UI builder** with real-time preview. Docker/Kubernetes deployment. **Best for teams wanting a powerful, mature open-source alternative to Retool** with enterprise governance features without per-user pricing. |
| **[Budibase](https://github.com/Budibase/budibase)** | [![Stars](https://img.shields.io/github/stars/Budibase/budibase?style=social&color=white)](https://github.com/Budibase/budibase/stargazers) | **The fastest path from SQL database to CRUD application.** GPL-3.0. **Auto-generates CRUD screens** from existing PostgreSQL, MySQL, MSSQL, or MongoDB schemas—no manual wiring. Built-in **BudibaseDB** for new apps. **Automation engine** with cron triggers and webhooks. **Public apps** for external users. Self-hosted via Docker. **Best for operations teams needing to expose database tables as internal tools quickly** without writing code. |
| **[ToolJet](https://github.com/ToolJet/ToolJet)** | [![Stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers) | **AI-native open-source low-code platform.** AGPL-3.0. **ToolJet AI** generates apps from prompts, SQL queries, or screenshots. **80+ data sources** and **45+ widgets**. Visual app builder with JavaScript logic. Self-hosted with Docker/Kubernetes. **Best for teams wanting AI-assisted app generation** with a mature open-source platform. |
| **[NocoBase](https://github.com/nocobase/nocobase)** | [![Stars](https://img.shields.io/github/stars/nocobase/nocobase?style=social&color=white)](https://github.com/nocobase/nocobase/stargazers) | **Data-model-driven open-source no-code platform.** AGPL-3.0. **Plugin-based architecture**—every feature is a plugin, including the core. **Data model first**: define collections and relationships, then build UI. Supports PostgreSQL, MySQL, SQLite, MariaDB. **Best for teams wanting a highly extensible platform** where they control the data model and plugin ecosystem. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Refine](https://github.com/refinedev/refine)** | [![Stars](https://img.shields.io/github/stars/refinedev/refine?style=social&color=white)](https://github.com/refinedev/refine/stargazers) | **React-based framework for building internal tools and admin panels.** MIT-licensed. **Not a drag-and-drop builder**—a code-first framework with pre-built hooks, components, and integrations for 15+ backends (REST, GraphQL, Supabase, Strapi). **Best for React developers** who want full control over their internal tools with a proven framework rather than a visual builder. |
| **[Lowdefy](https://github.com/lowdefy/lowdefy)** | [![Stars](https://img.shields.io/github/stars/lowdefy/lowdefy?style=social&color=white)](https://github.com/lowdefy/lowdefy/stargazers) | **Config-driven web stack for building internal tools and dashboards.** Apache-2.0. **YAML/JSON configuration** generates Next.js applications. Connects to databases and APIs. **Best for teams wanting Infrastructure-as-Code for internal tools**—version-controlled app definitions without a visual builder. |

**Frameworks for building custom systems**: Choose **Appsmith** for the most complete internal tool builder with enterprise governance , **Budibase** for the fastest CRUD app generation from existing databases , or **ToolJet** for AI-assisted app creation —all without per-user or per-app pricing that compounds across business teams.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise aPaaS platforms handle business-critical application data and workflows; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Pricing models vary dramatically and per-user costs compound.** **Microsoft Power Apps Per App ($5/app/user)** reached end of sale for new commercial customers in January 2026—existing EA customers can renew, but new buyers must model Premium ($20/user/month) or pay-as-you-go . **Salesforce Platform Plus ($100/user/month)** is 4x Starter for object headroom most users never reach . **Oracle APEX is genuinely free** with Oracle Database licensing—no additional platform cost . **Quickbase's Pave offers a real free tier** (3 users, 100 credits) with credit-based scaling . **Open-source alternatives eliminate per-user fees but require infrastructure**: Appsmith provides enterprise RBAC and SSO on self-hosted deployments , Budibase auto-generates CRUD from SQL schemas , and ToolJet adds AI app generation . **Validate whether you need a visual builder (Appsmith, Budibase) or a code-first framework (Refine)** based on your team's skills and governance requirements.

---

**Made for business technologists, platform teams, and organizations building low-code application infrastructure.**  
Let's make enterprise aPaaS more open, accessible, and cost-predictable.
