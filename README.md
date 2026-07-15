<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=00D9FF&center=true&vCenter=true&width=550&lines=AI+Automation+Engineer;Workflow+Automation+%26+Integration;n8n+%7C+Python+%7C+LLMs" alt="Typing SVG" />
</p>

<h1 align="center">Hi, I'm Amirreza 👋</h1>

<p align="center"><b>AI Automation Engineer building intelligent workflows, integrations, and automation systems.</b></p>

<p align="center">
  <a href="https://github.com/Amirezamky9">
    <img src="https://img.shields.io/github/followers/Amirezamky9?label=Follow&style=social&logo=github" alt="GitHub followers" />
  </a>
  <a href="mailto:amirrezamokhtari2000@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Amirezamky9">
    <img src="https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## About Me

I'm an AI Automation Engineer. I build automation workflows, Telegram and Bale bots, API integrations, data pipelines, and AI-powered tools — mostly with Python and n8n.

What I focus on day-to-day:

- **n8n automation** — workflow design, webhook orchestration, business process automation
- **Python automation** — backend scripts, bot development, data extraction
- **LLM integrations** — connecting applications to LLMs, building AI-powered tools and assistants
- **API integrations** — connecting services, building REST interfaces, webhook handling
- **PostgreSQL** — data persistence, SQL, vector database concepts

Experience working with **Hermes Agent** and AI agent workflows.

---

## What I Build

Workflow automation systems that connect services, process data, and handle business logic.

Telegram and Bale bots for automation, AI assistance, and data collection.

API integrations between services, with error handling and observability.

Data extraction and scraping pipelines for e-commerce and market research.

---

## Current Focus

- Building AI automation workflows and n8n systems with MCP tools and RAG capabilities
- Designing automation infrastructure — resilient, logged, and observable
- API integrations and workflow automation

---

## Featured Projects

### n8n Teacher Bot + WorkflowYab

**Problem:** n8n users needed an interactive learning tool and a way to search workflow-related documentation semantically.

**What I built:** A multi-mode Telegram bot built entirely in n8n that provides three services through a single bot interface — an AI tutor for learning n8n (in Persian), a semantic WorkflowYab search engine using RAG, and a debugging assistant.

**Technical details:**
- n8n workflow architecture with AI agents using OpenAI, Gemini, and Groq
- MCP integration for searching n8n nodes, documentation, and workflow templates
- PostgreSQL memory with conversation history management
- Email OTP authentication system
- Rate limiting across multiple LLM providers
- Telegram Bot API interface

**Tech:** n8n · AI Agents · MCP · PostgreSQL · Telegram API · LLMs (OpenAI, Gemini, Groq)

[View repository](https://github.com/Amirezamky9/n8n-teacher-bot)

---

### Crypto Ingestion Pipeline

**Problem:** Needed a reliable, on-demand service to fetch KuCoin OHLCV candlestick data and upsert it into an existing PostgreSQL table without schema changes or local log storage.

**What I built:** A FastAPI webhook-triggered ingestion service that runs a smart delta + backfill cycle across requested symbol/timeframe pairs.

**Technical details:**
- FastAPI backend with Bearer token authentication
- Smart delta strategy — only fetches new data since the latest candle in the database, with optional full backfill
- Zero DDL — operates on existing `candles` table using `INSERT ... ON CONFLICT DO UPDATE`
- Zero disk logs — all logging streams to an external webhook
- Exponential backoff retry on transient failures (timeouts, 429, 5xx)
- Candle overlap guard to handle in-progress bars
- Docker-ready with healthcheck endpoint

**Tech:** FastAPI · Python · PostgreSQL · Docker · KuCoin API · Webhooks

[View repository](https://github.com/Amirezamky9/crypto_ingestion_pipeline)

---

### n8n Torob Scraper

**Problem:** Needed automated price monitoring for Persian e-commerce products without relying on external APIs.

**What I built:** An n8n workflow that scrapes product listings and pricing data from torob.com using a two-pass strategy — first collecting product links from category pages, then visiting each product page for seller-level pricing.

**Technical details:**
- Two-pass scraping architecture in n8n
- Pure HTTP + HTML/CSS selector parsing — no API keys required
- Smart link filtering to exclude non-product URLs
- Batch looping with configurable delays to rate-limit requests
- Price comparison across multiple sellers per product

**Tech:** n8n · Web Scraping · HTML Parsing · CSS Selectors

[View repository](https://github.com/Amirezamky9/n8n-torob-scraper)

---

## Tech Stack

**AI & Automation**
n8n · LLM APIs (OpenAI, Gemini, Groq) · AI Agent Workflows · MCP · RAG

**Backend**
Python · FastAPI · REST APIs

**Database**
PostgreSQL · SQL · Vector Database Concepts

**Automation & Integration**
Webhooks · Telegram Bots · Bale Bots · Workflow Automation

**Infrastructure**
Docker · Linux · Git · Self-hosted Services

**Data & Scraping**
Data Extraction · HTML Parsing · CSS Selectors

---

## GitHub Stats

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=Amirezamky9&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amirezamky9&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=c9d1d9" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Amirezamky9&theme=dark&hide_border=true&background=0D1117&stroke=00D9FF&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" />
</p>

---

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Amirezamky9/Amirezamky9/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Amirezamky9/Amirezamky9/output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Amirezamky9/Amirezamky9/output/github-contribution-grid-snake.svg">
</picture>

---

## Contact

- **GitHub:** [github.com/Amirezamky9](https://github.com/Amirezamky9)
- **Email:** [amirrezamokhtari2000@gmail.com](mailto:amirrezamokhtari2000@gmail.com)

---

<p align="center">
  <sub>Profile last updated 2026</sub>
</p>
