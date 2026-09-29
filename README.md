# Awesome-Buyer-Intent-Data-Platform

## Top Buyer Intent Data Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Intent Signal Aggregation, Account-Based Marketing & Lead Prioritization*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Buyer Intent Data**. These tools aggregate behavioral signals from across the web — content consumption, search activity, hiring patterns, and community engagement — to identify companies actively researching or in-market for specific products and services.



**Examples** include 6sense, Demandbase, Bombora, G2 Buyer Intent, ZoomInfo Intent, Leadfeeder, RB2B, Factors.ai, Clearbit, RollWorks, Slintel, and TechTarget Priority Engine (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom intent scoring, and transparent data pipelines — ideal for GTM teams, developers, and researchers building vendor-independent intent intelligence. Note that the open-source ecosystem for true third-party intent data aggregation remains limited, as most intent data is proprietary and syndicated across publisher networks. Open-source projects primarily focus on first-party signals, lead scoring, and CDP infrastructure.



Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[6sense](https://6sense.com/)**  

  Revenue AI platform combining intent data, predictive analytics, and ABM orchestration with a proprietary Buyer Intent Network covering 90% of B2B buying activity.



- **[Demandbase](https://www.demandbase.com/)**  

  Account-based GTM platform with intent data aggregation from 3,000+ sources, advertising, and sales intelligence capabilities.



- **[Bombora](https://bombora.com/)**  

  The original B2B intent data co-op, aggregating content consumption signals from 5,000+ publisher sites to identify companies researching specific topics. Serves as the data backbone for many other intent platforms.



- **[G2 Buyer Intent](https://www.g2.com/)**  

  Intent data derived from G2's own review platform activity — category browsing, competitor comparisons, and review reading by verified business users.



- **[ZoomInfo Intent](https://www.zoominfo.com/)**  

  Intent signals from ZoomInfo's data network and acquisitions (Clickagy), integrated with the broader sales intelligence platform.



- **[Leadfeeder](https://www.leadfeeder.com/)**  

  Website visitor identification and intent data platform revealing which companies visit your site and what they engage with.



- **[RB2B](https://www.rb2b.com/)**  

  Person-level website visitor identification with intent signals for real-time outbound targeting.



- **[Factors.ai](https://factors.ai/)**  

  Intent data and account identification platform with website visitor tracking and engagement analytics.



- **[Clearbit](https://clearbit.com/)**  

  Data enrichment and intent platform (now part of HubSpot) providing company and person data with buying signals.



- **[RollWorks](https://rollworks.com/)**  

  ABM platform (part of NextRoll) with intent data, advertising, and sales intelligence.



- **[Slintel](https://www.slintel.com/)**  

  Buyer intent and technographic data platform (now part of 6sense) providing purchase likelihood signals.



- **[TechTarget Priority Engine](https://www.techtarget.com/)**  

  Intent data from TechTarget's enterprise IT publisher network, with verified purchase intent from content consumption.



## Open-Source GitHub Projects



- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**  

  Open-source AI-first Customer Data Platform for building self-hosted, privacy-friendly CDP infrastructure. Features omni-channel data collection and unification, real-time Customer 360, AI-based segmentation and scoring including **lead scoring**, RFM analysis, CLV prediction, churn prediction, and purchase propensity. Behavioral tracking and journey mapping capture customer interactions in real time. Agentic AI and LLM integration enable personalized experiences and next-best-action recommendations. Java/ArangoDB stack with Docker deployment, Prometheus/Grafana monitoring, and on-premise hosting for data sovereignty .



- **[ai-lead-scoring-engine](https://github.com/Nikkk2312/ai-lead-scoring-engine)**  

  AI-powered B2B lead scoring engine with 136 features, self-hosted and privacy-first. Features **tri-dimensional scoring** (Fit/Engagement/Intent), buying stage pipeline inspired by 6sense, Fit-Engagement matrix (A1-C3 grid), sales feedback loop, scoring model templates, and negative scoring rules. Includes local LLM reasoning with zero API costs, full web dashboard, REST API, Docker deployment, and account-based scoring (ABM) support. Imports templates for HubSpot, Salesforce, and Apollo .



- **[gtm-enrichment-pipeline](https://github.com/beautifulgownss/gtm-enrichment-pipeline)**  

  Automated account research, ICP scoring, and personalized outreach using Python, real-time APIs, and LLMs. Features static scoring plus **signal-weighted composite scoring** that captures live buying signals (funding announcements, hiring activity, product launches) to adjust prioritization dynamically. HubSpot CRM sync with idempotent record creation, email alerting on score shifts, React dashboard, and scheduled CI runs. Demonstrates that "static data tells you who a company is, live signals tell you why now is the right time" .



- **[Bright Data SERP APIs Lead Enrichment](https://github.com/sanbhaumik/bright-data-serp-apis-lead-enrichment)**  

  Lead enrichment engine using Bright Data's SERP APIs to detect buying signals including **hiring signals** (job postings), **tech stack signals**, **pain point signals**, and **strategic signals** (funding, acquisitions, partnerships). CLI supports single lead enrichment, batch CSV processing, and scheduled monitoring. Industry presets for devtools, fintech, and security verticals. Configurable signal weights and intent thresholds .



- **[SaaSquatch Intelligence Hub](https://github.com/HmbleCreator/SaaSquatch-Intelligence-Hub)**  

  AI-powered lead scoring and prioritization tool analyzing leads across 5 dimensions with automatic A/B/C/D tier assignment. Provides actionable **buying signals** including high budget capacity, growth indicators, tech compatibility, and decision-maker level. Client-side React processing with CSV upload, demo dataset, and export to CRM-ready format. Gemini AI integration for scoring and insights .



- **[lead-scoring-ai-mcp](https://www.npmjs.com/package/lead-scoring-ai-mcp)**  

  MCP server for B2B lead scoring with engagement tracking and prioritization. Features score_lead based on firmographic data, add_lead/update_lead_activity for tracking email opens, website visits, demo requests, and pricing page views. Includes predict_conversion, get_priority_leads, and track_engagement_trend tools. Free tier: 15 calls/day. MIT licensed .



- **[crowd.dev](https://sourceforge.net/software/buyer-intent/integrates-with-discourse/)**  

  Open-source developer data platform unifying community, product, and customer data for go-to-market teams. Integrates with GitHub, Discord, Slack, and LinkedIn to consolidate developer interactions across touchpoints. AI-powered data enrichment with 25+ contact attributes and 50+ organization attributes. Advanced analytics for identifying trends and sentiment analysis. Starting price: free tier available .



- **[Scarf](https://scarf.sh/)**  

  Open-source sales and marketing intelligence platform that operationalizes open-source usage data. Tracks companies interacting with open-source projects, syncing key metrics (funnel stage, first/last seen dates, version details) directly into Salesforce CRM. Over 7 billion events processed. SOC 2 Type 2 and PCI-DSS compliant .



- **[Intelligent Customer Analysis Platform](https://github.com/mario2046/Intelligent-Customer-Analysis-Platform)**  

  HTTP API server providing customer data including CRM, engagement, market intelligence, and knowledge base information. Serves as data backend for Customer 360 platforms with FastAPI, Python. Includes engagement history tracking, market intelligence APIs for industry news, and knowledge base for products. Designed for integration with Dify agentic orchestration .



### Additional Strong Open-Source Options



- **rudder-server** — Open-source, warehouse-first Customer Data Pipeline and Segment alternative. Collects and routes clickstream data to build customer data lake on your data warehouse. TypeScript-based with active development .

- **laravel-visitor** — Privacy-friendly, self-hosted visitor tracking for Laravel applications. Server-side tracking with GeoIP resolution, device detection, and real-time active-visitor count. Data stays in your database .

- **BT Visitor Insights** — WordPress plugin for privacy-friendly, self-hosted analytics. Real-time visitor tracking, IP geolocation, page view tracking, and per-visitor history. No third-party tracking scripts .

- **reddit-intel-agent-mcp** — MCP server for Reddit intelligence gathering. Read-only operations with no tracking or telemetry. Can surface pain points and buying signals from Reddit discussions for intent research .



**Frameworks for building custom intent solutions**: Combine **LEO CDP** for unified customer data infrastructure with AI-based lead scoring and segmentation . Use **ai-lead-scoring-engine** for tri-dimensional scoring (Fit/Engagement/Intent) with buying stage pipeline modeling . Implement **gtm-enrichment-pipeline** for signal-weighted composite scoring that captures live buying signals from public sources . For SERP-based signal detection, **Bright Data Lead Enrichment** provides hiring, tech stack, and strategic signal extraction . Note that true third-party intent data — aggregated across publisher networks with verified research behavior — remains fundamentally proprietary and commercial. Open-source stacks excel at first-party signal capture, lead scoring, and CDP infrastructure, but cannot replicate the co-op data network models of Bombora or G2.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Intent data platforms must comply with data privacy regulations (GDPR, CCPA, ePrivacy Directive) and applicable laws regarding behavioral tracking and data aggregation.

- Self-hosted open-source solutions require proper infrastructure, data pipeline maintenance, and ongoing model tuning. Signal quality depends on data source coverage and freshness.

- The open-source ecosystem provides strong first-party signal capture, lead scoring, and CDP foundations, but third-party intent data aggregated across publisher networks remains primarily a commercial offering.



---



**Made for GTM engineers, revenue operations, marketing technologists, and sales intelligence professionals.**  

Let's make buyer intent data more open, transparent, and actionable.
