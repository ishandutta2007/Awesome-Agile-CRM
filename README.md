# Awesome-Agile-CRM

# Awesome-Agile-CRM

**Top Agile CRM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Sales Pipelines, Contact Management, Workflow Automation & Self-Hosted CRM Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Agile CRM**. These tools enable sales teams to manage leads, track deals through visual pipelines, automate follow-ups, and close revenue faster—from fully managed platforms with AI copilots and predictive scoring to open-source CRMs that give organizations complete control over their customer data.



**Examples** include HubSpot CRM, Pipedrive, Copper, Salesforce Sales Cloud, Freshsales, Insightly, Capsule CRM, Close, Monday Sales CRM, and Zoho CRM (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted CRM, pipeline management, and open sales infrastructure. **Critical note**: The open-source CRM landscape has matured dramatically—**Twenty** leads on GitHub health (99/100) with 59k stars and a modern TypeScript stack , **EspoCRM** offers a proven PHP alternative with granular permissions, and **Relaticle** provides a production-grade MCP server for AI-agent access. No open-source project matches Salesforce's ecosystem or HubSpot's marketing integration, but for core sales CRM, the options are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Customer Relationship Management (CRM) market is estimated at approximately $100–$126 billion in 2025–2026 and is projected to exceed $150+ billion by the end of the decade. Structurally, the sector exhibits a dual dynamic: it is moderately concentrated at the top enterprise tier dominated by giants like Salesforce, Microsoft, and HubSpot, yet highly fragmented across mid-market and SMB segments where hundreds of agile, vertical, and open-source solutions compete actively for market share.



## SaaS/Hosted Platforms

| Product | Company Scale (Revenue / Valuation) | Pricing (Starting Paid Tier) | Free Tier / Trial Limits | Key Features & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **Salesforce Sales Cloud** | ~$41.5B Revenue (~$190B Market Cap) | Starter Suite from $25/user/month (annual); Pro Suite $100/user/month; Core $195/user/month | Permanent Free CRM tier up to 2 users (basic contact/lead tracking); or 30-day full-access free trial | Enterprise CRM standard with Agentforce AI, custom workflows, and deep AppExchange integrations. Best for large enterprises requiring custom governance. |
| **HubSpot CRM** | ~$3.13B+ Revenue (~$14B Market Cap) | Sales Hub Starter from $20/seat/month (annual, promotional from $7); Professional $90/seat/month (+$1,500 onboarding) | Permanent free plan with unlimited users (core deal/contact pipelines, ticketing, up to 1M contacts) | Inbound marketing and visual pipeline ecosystem. Best for fast-scaling teams wanting a comprehensive free starting platform. |
| **Zoho CRM** | ~$1.45B–$1.5B Revenue (Bootstrapped / Profitable) | Standard from $14/user/month (annual) or $20 monthly; Professional $23/user/month; Enterprise $40/user/month | Permanent free plan up to 3 users (5,000 records, standard reports, email templates); or 15-day free trial on paid plans | Comprehensive suite with Zia AI, custom modules, and workflow rules. Best for cost-conscious SMBs needing rich functionality. |
| **Monday Sales CRM** | ~$1.23B–$1.37B Revenue (~$3.8B Market Cap) | Basic CRM from $12/seat/month (annual, 3-seat minimum = $36/month); Standard $17/seat/month; Pro $28/seat/month | No permanent free plan; 14-day free trial (unlimited boards, no credit card required) | Work OS-driven CRM with visual boards, deal management, and cross-team workflows. Best for teams already using Monday.com. |
| **Pipedrive** | ~$1.5B Valuation (Acquired by Vista Equity Partners) | Lite plan from $14/user/month (annual) or $24 monthly; Growth $39/user/month | No permanent free plan; 14-day free trial with full feature access (no credit card required) | Pipeline-first visual CRM focused on activity-based selling and deal velocity. Best for SMB sales teams wanting clean deal tracking. |
| **Freshsales** | ~$750M–$1B ARR (~$3.5B Market Cap, Freshworks) | Growth plan from $9/user/month (annual) or $11 monthly; Pro $39/user/month | Permanent free plan up to 3 users (1 deal pipeline, contact lifecycle stages, built-in chat/email); or 21-day free trial of paid tiers | Freddy AI-powered contact scoring, predictive insights, and built-in telephony. Best for SMBs wanting modern AI capabilities. |
| **Copper** | ~$102M Total Funding Raised (Privately held) | Basic from $23/seat/month (annual) or $29 monthly (capped at 2,500 contacts); Professional $59/seat/month | No permanent free plan; 14-day free trial with full Google Workspace integration (no credit card required) | Google Workspace-native CRM embedding directly into Gmail and Google Calendar. Best for teams anchored in Google Workspace. |
| **Insightly** | ~$15M–$37M Est. Annual Revenue (Privately held) | Plus from $29/user/month (annual); Professional $49/user/month; Enterprise $99/user/month | No permanent free plan; 14-day free trial of Plus/Professional tiers (no credit card required) | Combined CRM and project post-sale delivery tracking with workflow automation. Best for professional services and project-driven sales teams. |
| **Close** | ~$13M–$27M Est. Annual Revenue (Bootstrapped/Private) | Solo from $9/user/month (annual, 1 user, 500 AI credits); Essentials $35/user/month (unlimited contacts); Growth $99/user/month | No permanent free plan; 14-day free trial including test calling and SMS credits (no credit card required) | Inside-sales CRM with built-in multi-channel calling, SMS sequences, and power dialers. Best for high-velocity outbound teams. |
| **Capsule CRM** | ~$7M Est. Annual Revenue (Bootstrapped/Private) | Starter from $18/user/month (annual, up to 30,000 contacts); Growth $36/user/month | Permanent free plan up to 2 users, 250 contacts, and 1 sales pipeline; or 14-day free trial of paid plans | Minimalist, relation-focused CRM with contact history and lightweight pipeline automation. Best for micro-businesses and solo entrepreneurs. |



## Open-Source GitHub Projects



- **Twenty**

  **Modern open-source CRM** (AGPL-3.0) — **the highest-health open-source CRM**, with **59k stars** and **2,568 commits in 90 days** . **Features**: **Modern TypeScript/React stack**; **custom objects and fields**; **kanban pipelines**; **workflows**; **API-first** with GraphQL; **Docker deployment available** . **Tech stack**: TypeScript, React, Node.js, PostgreSQL. **Deploy**: Self-hosted (Docker) or Twenty Cloud. **Trade-off**: **Lacks native marketing automation**; smaller ecosystem than EspoCRM or SuiteCRM. **Best for**: developers and tech-forward teams wanting a modern, actively maintained CRM foundation—the strongest open-source alternative to Salesforce for product-led sales orgs .



- **Relaticle**

  **Open-source CRM with production-grade MCP server** (AGPL-3.0) — **the most AI-agent-ready open-source CRM**, with **32 MCP tools** and human-in-the-loop approvals . **Features**: **MCP server for AI agents**; **REST API**; **custom fields**; **kanban boards**; **human-in-the-loop approvals** for destructive actions; **1.8k stars** with steady health (93/100) . **Tech stack**: PHP (Laravel), PostgreSQL. **Deploy**: Self-hosted (Docker). **Trade-off**: **Smaller community than Twenty** (1.8k vs. 59k stars) . **Best for**: teams wanting CRM access via AI agents (Claude, Cursor) with approval workflows—especially those already using MCP in their stack.



- **EspoCRM**

  **Complete CRM with clean UI and powerful administration** (AGPL-3.0) — **the most mature PHP-based open-source CRM**, with **3.5k stars** and active development (last commit yesterday) . **Features**: **Pipeline management**; **roles manager**; **audit log**; **analytics**; **fine-grained access control**; **OIDC/LDAP**; **email sync**; **rich extension library**; **REST API**; SPA architecture; powerful import/export . **Tech stack**: PHP, MySQL/PostgreSQL. **Deploy**: Self-hosted or cloud. **Trade-off**: **Homemade framework makes customization challenging**; limited developer documentation; one-man project. **Best for**: teams wanting a proven, self-hosted CRM with strong administration and no AI dependency—especially those with PHP expertise .



- **Krayin**

  **Laravel-based CRM** (MIT) — **the most permissively licensed full CRM**, with **24k stars** and active development . **Features**: **Lead and contact management**; **pipelines**; **activities**; **email**; **workflows**; **MIT license** allows forking and embedding without copyleft obligations . **Tech stack**: PHP (Laravel). **Deploy**: Self-hosted. **Trade-off**: **No Docker image**; smaller ecosystem than EspoCRM . **Best for**: teams wanting a permissively licensed CRM they can customize and embed without AGPL constraints—especially Laravel developers .



### Additional Strong Open-Source Options



- **SuiteCRM** — Enterprise-class open-source CRM (AGPL-3.0, 5.8k stars). Mature fork of SugarCRM with workflow, reporting, and security suite . **Note**: **Health score 66/100**—outdated UI, technical debt, no AI features . **Best for**: organizations with existing SuiteCRM investment, not greenfield adoption.

- **Dolibarr** — ERP/CRM suite (GPL-3.0, 7.8k stars). Contacts, invoices, orders, stocks, accounting . **Note**: **Broader ERP than pure CRM**—more than sales teams need. **Best for**: SMBs wanting integrated ERP/CRM in one platform.



**Frameworks for building custom systems**: Combine **Twenty** for modern sales CRM with **Relaticle** for AI-agent access and **EspoCRM** for proven administration—creating a layered open-source CRM stack. **None of these match Salesforce's AppExchange or HubSpot's marketing integration**, but for core sales pipeline management, the options are production-proven.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CRM platforms handling customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "free CRM" vs. "pipeline-first" vs. "enterprise standard" vs. "AI-native" distinction is critical.** **HubSpot, Capsule, and Zoho** offer **free tiers**—with limits on users, contacts, or features . **Pipedrive and Copper** are **pipeline-first**—they optimize for visual sales stages over marketing features . **Salesforce** is the **enterprise standard**—deep customization and ecosystem, but costs climb steeply . **Freshsales and Close** are **AI-native**—AI capabilities at SMB price points or built into telephony . **Choose based on whether you need free entry, pipeline focus, enterprise depth, or AI-first workflows.**

- **HubSpot's free CRM is the strongest free tier**—unlimited users with core contact/deal management . **The trade-off**: Professional requires **$1,500 onboarding** and **$90/seat/month**; Enterprise adds **$3,500 onboarding** .

- **Pipedrive's add-ons stack significantly**—chatbot and visitor tracking add **20–40%** to total contract value; renewal increases run **3–10% annually** . **Negotiate expansion pricing and multi-year fixed rates upfront** .

- **Copper has no free tier**—Basic starts at **$23/seat/month** (annual) with a 2,500 contact cap . **The trade-off**: Google Workspace-native UX justifies the premium for Gmail-centric teams.

- **Salesforce's Pro Suite at $100/user/month** is the practical entry for real customization—Starter at $25 is limited . **Costs climb steeply**: Core $195, Advanced $395, Max $550 .

- **Twenty is the highest-health open-source CRM**—59k stars, 2,568 commits in 90 days, modern TypeScript stack, and Docker deployment . **The trade-off**: no native marketing automation. **For product-led sales teams wanting a modern foundation, it is the strongest open-source option.**

- **Relaticle is the AI-agent-ready choice**—32 MCP tools with human-in-the-loop approvals . **The trade-off**: smaller community (1.8k stars). **For teams using Claude or Cursor, it is the most practical path to AI-accessible CRM data.**

- **Krayin is the permissive-license option**—MIT allows embedding without AGPL obligations . **The trade-off**: no Docker image; smaller ecosystem.

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL for Twenty and Relaticle, PHP for EspoCRM/Krayin), security hardening, and ongoing maintenance. **CRM data includes customer PII and deal information**—ensure your deployment meets your organization's privacy and compliance requirements before migrating production data.



---



**Made for sales teams, RevOps leaders, and organizations building transparent CRM solutions.**

Let's make Agile CRM more open, data-driven, and pipeline-friendly.
