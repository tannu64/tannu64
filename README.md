# Tanveer Hussain

**AI Automation Engineer · n8n Specialist · Distributed Systems Thinker**

Electrical engineer turned automation builder. I design AI systems that survive production, not just demos.

![Top Rated](https://img.shields.io/badge/Top%20Rated-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white) ![Projects Shipped](https://img.shields.io/badge/Projects%20Shipped-100%2B-blue?style=for-the-badge) ![Based In Pakistan](https://img.shields.io/badge/Based%20In-Pakistan-006A4E?style=for-the-badge)

---

## Who I actually am

I'm an electrical engineer who got pulled into AI automation, not the other way around. My degree is in electrical and communications from the Institute of Space Technology in Islamabad. I spent years on radar DSP and metamaterials research before n8n and language models showed up and quietly rewrote my career path. I don't say that with regret. I say it because it shaped how I think about every system I build.

Most automation people online treat n8n like a religion. I treat it like a tool. A useful one, often the right one, but a tool. When a client brings me a workflow problem, the first question I ask myself is whether the workflow should exist at all, not how to drag-and-drop it together. Half the automations people pay for are solving problems they manufactured by adopting the wrong stack three months earlier.

## What I actually believe

I think most AI agent demos on LinkedIn are theater. I've shipped enough RAG pipelines to know retrieval quality starts dying the moment your corpus crosses a few thousand documents and nobody set up reranking. I've watched voice synthesis costs blow up overnight because someone wired ElevenLabs into a loop with no async handling. I've seen n8n workflows with 80 nodes that should have been 12 nodes and a queue.

When I review an automation system, I look for where it will fail first. Tight coupling between orchestration and compute. Webhooks with no idempotency. Retry storms from chained nodes that nobody traced. Embedding drift that goes unmonitored because there's no observability layer. Single points of failure dressed up as "automation." That critical eye is the thing my clients actually pay for, even when they think they're paying for an n8n workflow.

## My working life

I work nights. 3 PM to 4 AM, mostly. I have ADHD, so I built my own productivity system on top of n8n and Telegram to keep my brain on track. It's the most useful thing I've ever automated, and no client will ever pay me for it.

I keep a research streak alongside the freelance grind. Physics-informed machine learning, weather prediction with graph neural networks, synthetic image detection. I co-authored work on gradient field and spectral slope analysis for detecting AI-generated images. I applied to the iPSRS Erasmus Mundus photonics program because I haven't fully let go of the engineer who started all this. The freelancing pays the bills. The research is who I am when nobody's watching.

## My frustrations

I'm tired of clients who want "AI agents" without understanding what autonomy actually costs in safety, observability, and execution control. I'm tired of proposals that sell magic. I'm tired of pretending that gluing an LLM to a Google Sheet counts as engineering. The honest version of this work is unglamorous. It's writing fallback logic. Monitoring token costs. Debugging a webhook that fires twice because someone skipped retry semantics.

I'm a freelancer who refuses to be quiet about technical disagreements. I'll push back on a requirement that doesn't make sense. That has cost me work before. I'd rather lose a contract than ship something I know will break under load.

---

## What I've built

### Production systems shipped to clients

**High-volume lead generation pipelines.** Scrapers processing 30,000+ records with self-healing retry logic, dynamic prompt engineering for structured data extraction, and multi-source enrichment across web and public data. n8n orchestration with Apify, Firecrawl, and LLM-driven validation layers.

**Content generation platforms.** End-to-end systems with LLM-powered draft improvement loops, A/B comparison interfaces, voice synthesis pipelines, and multi-format publishing. Flask backends with custom-branded frontends.

**RAG-based file intelligence systems.** PostgreSQL with pgvector pulling from cloud storage and shared drives. Whisper transcription for audio, OCR for scanned documents, semantic search across mixed file formats with hybrid retrieval.

**Multi-regional localization pipelines.** Translation and adaptation workflows for product copy across regions with QA layers, fallback logic, and human review gates.

**Customer support automation.** Gmail-integrated agents using LangChain with conversation memory, escalation routing, and human-in-the-loop safeguards.

**Voice agent integrations.** Telephony flows combining GoHighLevel with Retell AI, plus custom voice agents handling intake, qualification, and routing.

**Multi-platform social automation suites.** Six-plus interconnected workflows for ideation, generation, scheduling, and analytics on a single platform.

**Vertical news and digest engines.** RSS-driven content pipelines with LLM summarization and personalized email delivery.

**Scientific computing apps.** Streamlit deployments for domain-specific optimization problems including terahertz metamaterials and photonics.

### Research and academic work

- Co-authored research on synthetic image detection using gradient field and spectral slope analysis
- Working on physics-informed machine learning for atmospheric prediction with graph neural networks
- Erasmus Mundus iPSRS photonics program applicant

---

## Stack

### Automation and orchestration

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) ![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white) ![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white)

### Languages and frameworks

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

### AI and LLMs

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![Whisper](https://img.shields.io/badge/Whisper-74AA9C?style=for-the-badge&logo=openai&logoColor=white) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white)

### Data and RAG

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=chromadb&logoColor=white)

### Web, scraping, and automation

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![Apify](https://img.shields.io/badge/Apify-1B273C?style=for-the-badge&logo=apify&logoColor=white) ![Firecrawl](https://img.shields.io/badge/Firecrawl-F97316?style=for-the-badge&logo=firefox&logoColor=white)

### Integrations

![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white) ![Google Workspace](https://img.shields.io/badge/Google%20Workspace-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white) ![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=for-the-badge&logo=nextcloud&logoColor=white)

### Deployment and DevOps

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## What I'm building toward

I want to move from contractor to system designer. The kind of work where the question isn't "build me a workflow" but "tell me why my stack will collapse at 10x scale and fix it." I'm spending 2026 expanding past n8n into Claude Code, OpenClaw, and proper agent runtimes, because the next layer of this industry isn't drag-and-drop anymore. It's distributed systems thinking applied to language models, and most of the field hasn't caught up yet.

---

## How I work with clients

Roman Urdu, English, Urdu, whichever lets us move faster. Concise. Direct. I'll tell you "this won't scale" before I start, not after the invoice. I offer a 72-hour free trial because I'd rather you fire me on day three than pay for a month of misaligned expectations.

If you want a yes-man with a Zapier certificate, I'm not the guy. If you want someone who will tell you your RAG is garbage and then fix it, we'll get along.

---



## Connect

- **Upwork:** [Top Rated profile](https://www.upwork.com/freelancers/~01a14d825a9bd8689d)
- **LinkedIn:** [tanveer-hussain-277119196](https://linkedin.com/in/tanveer-hussain-277119196)
- **Working hours:** 8 AM to 10 PM PKT (UTC+5)
- **Languages:** English, Urdu,  Urdu
