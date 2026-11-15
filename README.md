# Awesome-Enterprise-Cloud-Application-Platform-Apaas

# Top Enterprise Cloud Application Platform (aPaaS) Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Low-Code App Development, Visual Modeling & Self-Hosted Application Platforms*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Cloud Application Platforms (aPaaS)**. These tools help organizations build and deploy business applications with minimal hand-coding—covering everything from visual drag-and-drop builders and spreadsheet-powered app generators to open-source frameworks that give you full code ownership without per-user licensing.

**Examples** include Microsoft Power Platform, Salesforce Platform, ServiceNow App Engine, Mendix, OutSystems, Quickbase, Appian, Oracle APEX, Google AppSheet, Zoho Creator, and open-source alternatives like Appsmith and Budibase (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted low-code platforms, open-source internal tool builders, and community-driven app development—ideal for organizations seeking data sovereignty and avoiding per-user pricing that compounds across business users. The open-source landscape is genuinely mature: **Appsmith** provides a powerful internal tool builder with 40+ widgets , **Budibase** offers a fast path to CRUD apps on top of SQL databases , and **ToolJet** delivers an AI-native low-code platform .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Microsoft Power Platform](https://powerplatform.microsoft.com/)** | Low-code platform with Power Apps, Power Automate, and Dataverse. **Power Apps Per App: $5/app/user** (1 app, 50 MB database); **Premium: $20/user/month** (unlimited apps, 2 GB files, 250 MB Dataverse) . **Note: Per App plan reached end of sale for new commercial clients in January 2026**—existing EA customers can renew . | Per App: **$5/app/user**; Premium: **$20/user/month** | **Free tier** available via Power Apps Developer Plan; capacity packs available |
| **[Salesforce Platform](https://www.salesforce.com/)** | Enterprise aPaaS with custom objects, Lightning Platform, and AppExchange ecosystem. **Platform Starter: $25/user/month** (10 custom objects); **Platform Plus: $100/user/month** (110 custom objects, full API) . | Starter: **$25/user/month**; Plus: **$100/user/month** | **Free Developer Edition** org for building and testing |
| **[ServiceNow App Engine](https://www.servicenow.com/)** | Low-code app development on the Now Platform. **App Engine Foundation** includes Now Assist for Creator, App Engine Studio, **15 custom tables**, and 3 scoped apps. **App Engine Prime** adds unlimited custom tables and scoped apps, Now Assist for App Engine, and enterprise governance . | Quote-only (Foundation/Prime packages) | No free tier; demo via sales |
| **[Mendix](https://www.mendix.com/)** | Enterprise low-code platform with visual modeling and multi-cloud deployment. Software Advice lists starting price at **€52.50/month** with free trial and free version available . | From **€52.50/month** (Software Advice) | **Free version** and **free trial** available |
| **[OutSystems](https://www.outsystems.com/)** | Enterprise aPaaS with AI-assisted development and full-lifecycle tooling. **Personal Edition free** for learning (up to 100 internal users). Paid plans priced by **Application Objects (AOs)**, end users, and runtimes . | Quote-only (priced by AOs, users, runtimes); Personal Edition: **free** | **Free (Personal Edition)**: up to 100 internal users, development and learning |
| **[Quickbase (Pave)](https://www.quickbase.com/)** | No-code app platform with AI-powered building. **Free: 1 app, 1 builder, up to 3 users, 100 credits**. Team: **$120 credits/month** (2 apps, 10 users); Department: **$300/month** (1,800 credits, ~10 apps, 50 users) . | Free: **$0** (3 users, 100 credits); Team/Department: credit-based tiers | **Free forever**: 1 app, 1 builder, 3 users, 100 credits |
| **[Appian](https://www.appian.com/)** | Enterprise low-code automation platform with process modeling and AI. Software Advice lists starting price at **$75/month** . | From **$75/month** (Software Advice) | Free trial available |
| **[Oracle APEX](https://apex.oracle.com/)** | **Free low-code platform** for building data-driven apps on Oracle Database. Included with Oracle Database licenses—**no additional cost** . | **Free** (with Oracle Database) | **Free forever** for Oracle Database customers |
| **[Google AppSheet](https://about.appsheet.com/)** | No-code app platform that builds apps from spreadsheets and cloud data. **Starter: $5/user/month**; Core: $10; Enterprise Plus: $20. **Test with up to 10 users free** . | Starter: **$5/user/month**; Core: $10; Enterprise Plus: $20 | **Free testing**: up to 10 users; Publisher Pro: $50/mo/app for public apps |
| **[Zoho Creator](https://www.zoho.com/creator/)** | Low-code app builder within the Zoho ecosystem. **Free Edition** for individuals/small teams with 1 custom app. **15-day fully featured trial** for paid plans . | Quote-only (paid tiers); Free Edition available | **Free Edition**: 1 app, basic building; **15-day full-feature trial** |

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
