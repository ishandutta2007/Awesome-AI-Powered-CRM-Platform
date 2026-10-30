# Awesome-AI-Powered-CRM-Platform

# Awesome-AI-Powered-CRM-Platform

**Top AI Powered CRM Platform (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Assistants, Predictive Scoring, MCP Integration & Self-Hosted Agentic CRM*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI-Powered CRM Platforms**. These tools enable sales and revenue teams to automate data entry, score leads, summarize conversations, and interact with CRM records through natural language—from fully managed enterprise suites with embedded AI agents and governance guardrails to self-hosted CRMs with built-in AI chat and MCP servers that give teams complete control over their customer data and model choices.



**Examples** include HubSpot Smart CRM (Breeze), Salesforce Einstein 1 (Agentforce), Zoho Zia, Freshworks Freddy, Microsoft Dynamics 365 Copilot, Pipedrive AI, Creatio, and the open-source Twenty and Relaticle (the category leaders in commercial and open-source space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, AI-native CRM, and open agent infrastructure. **Critical note**: The open-source CRM landscape has matured significantly—**Twenty** and **Relaticle** now offer production-grade AI features with MCP support—but no open-source project matches Salesforce Agentforce's agent orchestration breadth or HubSpot Breeze's out-of-the-box included AI. The projects below range from AI-native CRMs with 37+ MCP tools to file-based minimalist CRMs with AI querying.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Einstein 1 / Agentforce](https://www.salesforce.com/)**

  **Enterprise CRM with agentic AI layer** for autonomous sales workflows. Gartner 2026 highlights predictive scoring, conversation intelligence, agentic cadences, and **governance controls including agent analytics, trust-layer guardrails, and audit tracing** for autonomous actions . **Pricing**: Agentforce Sales Pro Suite ~$100/user/month; Agentforce priced separately at ~$550/user/month for advanced agent orchestration . **Free tier**: None. **Best for**: enterprises orchestrating AI agents across sales, service, and custom clouds—with the governance controls that agent autonomy demands.



- **[HubSpot Smart CRM (Breeze)](https://www.hubspot.com/)**

  **AI included out of the box across paid tiers**, with Breeze Prospecting Agent (research and outreach) and Breeze Customer Agent (support). Data enrichment runs on HubSpot's Clearbit acquisition; predictive lead scoring uses your own conversion history . **Pricing**: Free CRM for unlimited users; Starter $15/seat/month; Sales Hub Professional $100/seat/month (includes Breeze agents and $1,500 onboarding) . **Free tier**: Yes, with Breeze basics. **Best for**: SMBs and mid-market teams wanting useful AI without a separate AI project—Breeze works out of the box at a fraction of Agentforce's cost.



- **[Zoho Zia](https://www.zoho.com/crm/)**

  **AI layer across Zoho CRM** with predictive scoring and assistant-led workflows. **Zia Agent Studio** gives administrators a granular environment to configure knowledge sources and manage multi-agent orchestration . **Pricing**: Quote-only; tiered by users and features. **Free tier**: Limited. **Best for**: Zoho-centric organizations wanting a unified AI experience—**note**: Gartner flagged incomplete mobile AI (Zia primarily optimized for desktop) .



- **[Freshworks Freddy AI](https://www.freshworks.com/)**

  **AI sales CRM** with lead scoring, deal insights, and content generation built in. Accessible SMB pricing from **$9/user/month** . **Pricing**: Growth $9, Pro $39, Enterprise $59/user/month (annual) . **Free tier**: Trial available. **Best for**: SMBs wanting integrated AI at a materially lower price point than Salesforce or HubSpot Professional—**trade-off**: less workflow depth and smaller ecosystem .



- **[Microsoft Dynamics 365 Copilot](https://www.microsoft.com/dynamics-365)**

  **Sales workflows across Dynamics 365, Outlook, Teams, and Microsoft 365 Copilot**. **Sales Research Agent** combines CRM information with web insights and SQL context to investigate opportunities and surface account intelligence . **Pricing**: Quote-only; bundled with Dynamics 365 licenses. **Free tier**: None. **Best for**: Microsoft-centric enterprises where sellers already live in Outlook and Teams—Copilot meets them there.



- **[Pipedrive AI](https://www.pipedrive.com/)**

  **Pipeline-first CRM with Nova meeting intelligence and native MCP server on every plan**. AI email creation and deal notifications start on Premium . **Pricing**: Lite from $14/seat/month (includes AI report creation, Nova, MCP); Premium $59/seat/month for AI automations . **Free tier**: 14-day trial, no credit card. **Best for**: SMB and mid-market teams wanting a visual pipeline with AI that doesn't require enterprise configuration.



- **[Creatio](https://www.creatio.com/)**

  **No-code CRM with AI governance capabilities**. Gartner highlights **session monitoring, latency tracking, token consumption, audit trails, evaluation tools, and rollback mechanisms** for AI agents . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations prioritizing AI governance and auditability—**trade-off**: configuration burden for sophisticated AI workflows .



- **[SugarCRM](https://www.sugarcrm.com/)**

  **Enterprise CRM** with AI capabilities through SugarPredict. **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting a mature CRM with optional AI add-ons—**note**: the open-source SuiteCRM fork lacks AI features .



## Open-Source GitHub Projects



- **[Relaticle](https://github.com/relaticle/relaticle)**

  **Open-source CRM with built-in AI assistant and 37 MCP tools** (AGPL-3.0) — **the most AI-native open-source CRM** found in this research, with ~1,790 GitHub stars and active development (last commit 10 hours ago) . **Features**: **Built-in AI chat** for natural-language queries, record creation/update by typing, pipeline summaries, and task rollups; **voice input**; **destructive actions require approval cards with 5-second undo**; **MCP server with 37 tools** connecting Claude, ChatGPT, Gemini, or custom agents through the same permission layer and schema as the UI; custom data model with **22 field types** including entity relationships, conditional visibility, and per-field encryption; 5-layer authorization with multi-workspace support; REST API; CSV import/export . **Production hardening**: 2,000+ automated tests, PHPStan static analysis, 56+ MCP-specific tests . **Tech stack**: PHP (Laravel), PostgreSQL. **Deploy**: Self-hosted (KVM VPS with one-click installer) or managed hosting. **Trade-off**: **PHP/Laravel stack** may not suit teams preferring TypeScript; smaller ecosystem than Twenty; AI requires your own provider keys (Anthropic, Google, or OpenAI-compatible) . **Best for**: teams wanting a production-ready open-source CRM where AI is woven into three distinct interfaces—traditional UI, chat, and external agent MCP—with approval workflows for destructive actions.



- **[Twenty 2.0](https://github.com/twentyhq/twenty)**

  **Developer-friendly open-source CRM** (AGPL-3.0, ~59,855 stars growing quickly) — **the most popular open-source Salesforce alternative**, with a 2.0 release focused on AI integration and enterprise hardening . **Features**: **MCP integration with OAuth** for external AI clients (Claude can directly access CRM data secured via established authentication); internal AI renamed to `Ai` with new error codes; **SDK split into subpaths reducing bundle size by 700x** for serverless Logic Functions; Docker targets for AWS EKS; OAuth PKCE mandatory for public clients; GraphQL admin panel; SVG export; improved i18n . **Tech stack**: TypeScript, React, Node.js, PostgreSQL. **Deploy**: Self-hosted (Docker) or Twenty Cloud. **Trade-off**: **AI features are still maturing** compared to Relaticle's built-in chat and 37 MCP tools; no native AI chat interface for end users; commercial licensing and billing added in 2.0 for self-hosting . **Best for**: developers and technical teams wanting the most popular, actively developed open-source CRM with strong MCP foundations and a modern TypeScript stack.



- **[EspoCRM](https://github.com/espocrm/espocrm)**

  **Complete CRM with clean UI and powerful administration** (AGPL-3.0) — **a mature, feature-rich CRM with no AI features** . **Features**: Pipeline management, roles manager, audit log, analytics, fine-grained access control, OIDC/LDAP, email sync, rich library of paid extensions; complete API, active support, regular updates, SPA architecture, powerful import/export . **Tech stack**: PHP, home-made backend framework (Espo), Handlebars, Bootstrap, MySQL/PostgreSQL. **Deploy**: Self-hosted or cloud. **Trade-off**: **No AI-powered features**; homemade frameworks make code customization challenging; limited developer documentation; one-man project . **Best for**: teams wanting a proven, self-hosted CRM with strong administration and no AI dependency—pair with external AI tools via API if needed.



- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**

  **Feature-rich open-source CRM** (AGPL-3.0) — **the open-source successor to SugarCRM**, with a large user base but dated codebase . **Features**: Workflow automation, reporting tools, security suite (groups), customization framework, rich plugin ecosystem, logic hooks, extension framework . **Tech stack**: PHP 8, Smarty, custom framework/ORM, MySQL/MariaDB/SQLServer, jQuery. **Deploy**: Self-hosted. **Trade-off**: **No AI features**; outdated UI and coding practices; technical debt; clunky reports; subpar mobile UI . **Best for**: organizations with existing SuiteCRM investment needing workflow automation—**not a choice for AI-powered CRM**.



- **[hermitcrm](https://pypi.org/project/hermitcrm/)**

  **File-based minimalist CRM with AI querying and MCP server** (license per PyPI) — **the most radical approach: a CRM where every record is a Markdown file in a Git repo** . **Features**: **Every company is a folder, every contact and interaction is a file**; Git log for full history; **"Ask Hermit" question box** that answers from the current page or reads the whole data folder (read-only) with the AI; **MCP server with 10 read and 7 write tools** (records, bulk changes, undo); pipeline board with custom stages; follow-up radar; pre-meeting briefs; bookmarklet for LinkedIn enrichment; **enrichment via any AI CLI (claude, codex, gemini, grok)**; message drafts without AI in four languages . **Tech stack**: Python (CLI), Markdown files, Git. **Deploy**: Local CLI (`hermitcrm`); `serve --host 0.0.0.0` for network access. **Trade-off**: **Single-user, file-based**—no multi-tenant permissions, no team collaboration, no web UI for multiple users. Not a Glean or Salesforce replacement. **Best for**: individuals and very small teams wanting a Git-native, AI-queryable CRM they fully own—no database, no vendor, no lock-in.



- **[Krayin CRM](https://github.com/krayin/laravel-crm)**

  **Free and open-source Laravel CRM** (MIT) — **a Laravel-native alternative for SMEs** . **Features**: Complete customer lifecycle management; automates sales and marketing operations; built on Laravel ecosystem . **Tech stack**: PHP (Laravel). **Deploy**: Self-hosted. **Trade-off**: **No AI features mentioned in available sources**; smaller ecosystem than Twenty or EspoCRM; MIT license is permissive but verification of AI capabilities required. **Best for**: Laravel developers wanting a permissively licensed CRM foundation to extend with AI.



- **[Odoo CRM](https://github.com/odoo/odoo)**

  **ERP-integrated CRM** (LGPL-3 for Community) — **the choice when CRM must connect to inventory, accounting, and HR** . **Features**: Customizable workflows, integrations (auth & data), app marketplace, multi-channel (email, social media, VoIP), ERP modules covering finance, supply chain, POS, HR, marketing . **Tech stack**: Python, OWL JS framework, PostgreSQL. **Deploy**: Self-hosted or Odoo.sh. **Trade-off**: **Behemoth codebase**—most Odoo projects require specialized developers; not suitable for small businesses wanting simple CRM . **Best for**: organizations wanting CRM as one module of an integrated ERP—not a standalone AI CRM.



### Additional Strong Open-Source Options



- **enrichment-kit** — Open-source Clay.com alternative (TypeScript, ~33 stars). Multi-vendor enrichment waterfalls with bring-your-own API keys; pays ~85% less per lead than Clay by chaining cheap providers first . **Note**: **Enrichment tool, not a CRM**—it enriches leads, not manages pipelines or AI interactions. **Best for**: teams wanting to add cost-efficient enrichment to any CRM.

- **Customermates** — Open-source CRM for small teams (source available). Contacts, organizations, deals via REST API, webhooks, and MCP for external AI clients . **Note**: Source-available, not OSI open source; minimal validation. **Best for**: small teams wanting a lightweight CRM with MCP access.



**Frameworks for building custom systems**: Combine **Relaticle** for AI-native CRM with built-in chat and 37 MCP tools, **Twenty** for a developer-friendly TypeScript stack with MCP foundations, **EspoCRM** for a proven administration-heavy CRM (pair with external AI), and **enrichment-kit** for cost-efficient lead enrichment—creating an AI-powered CRM stack. **None of these match Salesforce Agentforce's agent orchestration or HubSpot Breeze's out-of-the-box included AI**, but Relaticle and Twenty cover the core AI-native needs for most teams.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI-powered CRM platforms handling customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls. AI features that take actions (create, update, delete) require human-in-the-loop safeguards.

- **The "AI included out of the box" vs. "AI-native with MCP" vs. "no AI" distinction is critical.** **HubSpot Breeze** includes useful AI across paid tiers without a separate project . **Salesforce Agentforce** offers the most powerful agent orchestration with governance guardrails—at ~$550/user/month . **Relaticle** is AI-native with built-in chat and 37 MCP tools, requiring your own LLM keys . **Twenty** has strong MCP foundations but AI features are still maturing . **EspoCRM, SuiteCRM, and Krayin** have **no AI features**—they are proven CRMs to pair with external AI tools . **Odoo** is an ERP first, CRM second. **Choose based on whether you want AI included, AI-native, or no AI.**

- **Relaticle is the most AI-native open-source CRM** with approval workflows for destructive actions and 5-second undo—a critical safeguard that most open-source CRMs lack . **The trade-off**: PHP/Laravel stack and smaller ecosystem than Twenty.

- **Twenty is the most popular open-source CRM** (~60k stars, growing quickly) with a 2.0 release focused on MCP and developer experience . **The trade-off**: no built-in AI chat for end users; MCP integration requires external clients. **It is the better choice for teams wanting to build their own AI layer on top of a modern CRM.**

- **HubSpot Breeze is included, not an add-on.** Gartner noted HubSpot shifted from Niche Player to Challenger largely on seller experience and Breeze . **For SMBs, it is the pragmatic choice**—useful AI at $15–$100/seat/month without an AI project. **Salesforce Agentforce is more powerful but requires enterprise commitment** (~$550/user/month plus implementation) .

- **Pricing opacity varies.** HubSpot, Freshsales, and Pipedrive publish tiered pricing. Salesforce publishes Agentforce tiers. Zoho, Microsoft, Creatio, and SugarCRM require sales contact. **Validate with direct vendor conversations against your team size and AI requirements.**

- Self-hosted open-source solutions require proper server setup, LLM API key management, security hardening, and ongoing maintenance. **Customer data and AI conversations are sensitive**—ensure your deployment meets your organization's privacy and security requirements, and **verify that AI actions have appropriate approval workflows before enabling write access**.



---



**Made for developers, sales teams, and organizations building transparent AI-powered CRM solutions.**

Let's make AI-Powered CRM Platforms more open, data-driven, and agent-governed.
