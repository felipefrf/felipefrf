# Felipe Ribeiro

**AI & Automation Engineer** building production LLM agents and full-stack systems for a Brazilian fintech.
Aerospace Engineering + Data Science @ [ITA](https://www.ita.br/). I like systems where a wrong answer costs
real money — so I build them to fail loud, not silent.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felipe-farias-ribeiro)
&nbsp;·&nbsp; 📍 São Paulo, Brazil

---

### What I'm building right now

At **NG.CASH**, I design and ship AI systems end-to-end — LLM orchestration, the cloud infra under it, and the
guardrails that keep it safe in a regulated fintech:

- **WhatsApp debt-renegotiation agent** — a multi-turn negotiation agent with tiered multi-model LLM
  orchestration (planner / judge / transcription) where **the model decides the action but never the number** —
  every value is computed deterministically in code. Runs on AWS (DynamoDB, S3, CDK) with keyless CI/CD, and is
  hardened against prompt injection (0 policy leaks across a 34-attack test battery).
- **Full-stack payroll platform** — re-platformed a legacy spreadsheet workflow into a TypeScript app
  (Fastify + React) on GCP Cloud Run + Cloud SQL, with Terraform IaC, Workload-Identity-Federation CI/CD, and a
  Gemini pipeline that extracts and auto-validates contractor invoices.
- **Document & compliance automations** — multimodal OCR + entity extraction pipelines that triage judicial
  notifications and complaint inboxes against SLAs, integrating SOAP web services, Snowflake, and Slack.

> The company code lives in private repos (credentials, PII, internal data). Happy to walk through the
> architecture in a conversation.

---

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**yt-to-md**](https://github.com/felipefrf/yt-to-md) | Turn any YouTube video into clean, structured Markdown for AI agents — no API key, no cost | Python |
| [**dual-subtitles-extension**](https://github.com/felipefrf/dual-subtitles-extension) | Chrome extension showing two synced subtitle languages on YouTube for language learning | WXT, React |
| [**x-reset**](https://github.com/felipefrf/x-reset) | Bulk-delete old tweets from your official X archive — resumable, browser-driven | Playwright |
| **medical-residency-trainer** *(private)* | Production ML study platform (50k+ questions) — FSRS spaced repetition, IRT difficulty calibration, Bayesian knowledge tracing | FastAPI, PostgreSQL, PyTorch |
| **application-agent** *(private)* | End-to-end AI application pipeline — scrapes program pages, RAG over past writing, browser automation to submit forms | Python, Gemini, Playwright |

---

### Stack

**AI/ML** — LLM orchestration, prompt engineering, RAG, guardrails/evals, PyTorch, XGBoost, NLP, computer vision
**Backend & Full-Stack** — TypeScript, Node.js, Fastify, NestJS, React, Python (FastAPI)
**Data** — SQL, Snowflake, PostgreSQL/pgvector, DynamoDB, ETL/ELT
**Cloud & DevOps** — AWS (DynamoDB, S3, CDK), GCP (Cloud Run, Cloud SQL), Terraform, Docker, CI/CD

---

### Before this

**Credix** — ML Engineer, built the credit-decisioning models (XGBoost / logistic regression) that became the
primary automated engine. **LinkedIn** — shipped an LLM revenue-forecasting chatbot for the US & Canada sales team.
Earlier: physics & robotics olympiad medalist (🥇 Iberoamerican Physics gold, 3× Brazilian Physics gold).
