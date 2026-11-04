# Rafael Caetité

Computer Science student at UFV, graduating in January 2028. I build systems with LLMs and agents, and the software, data pipelines and tests around them.

[Portfolio](https://www.rafaelcaetite.dev/) · [LinkedIn](https://linkedin.com/in/rafaelcaetite) · [Email](mailto:rafael.cancado@ufv.br)

## What I'm working on

**Talon Tech** is my web studio for local businesses, run by me and a set of AI agents. Between late October and early November 2026 I rebuilt how it operates:

- **[Caça-Cliente](https://github.com/rafaelcaetite/caca-cliente)** finds businesses with no website through the Google Places API and scores them. It has mapped 991 businesses in 3 cities so far. Open source.
- **Outreach pipeline** (private): 12 n8n workflows on a VPS with PostgreSQL, Redis and a WhatsApp gateway. An LLM classifies each reply into one of seven intents with validated JSON output. A rule in code checks for stop requests before the model is called, with the model as a second layer, and a person takes over when the lead shows interest. The workflows are generated from versioned code and covered by 65 tests.
- **Site factory** (private): Caça-Cliente launches a Claude Code agent through [Orca](https://github.com/stablyai/orca) in a folder holding only verified client data. A QA script must pass, three read-only reviewers check facts, design and code, and I approve before anything is sent.

I also offer this kind of automation to clients: outreach pipelines, WhatsApp bots and internal tools.

## Other projects

**[CreditRisk ML](https://github.com/rafaelcaetite/credit-risk-ml).** Probability-of-default scoring with XGBoost and isotonic calibration. ROC-AUC 0.868, p95 latency under 10 ms, 80 tests in CI. Hexagonal architecture, with acceptance gates written as tests.

**[Reference Manager](https://github.com/rafaelcaetite/Reference-Manager).** Deduplicates bibliographic references in the browser for systematic reviews. Fuzzy matching in a Web Worker, BibTeX and LaTeX parsing, and CSV export protected against formula injection.

**[LabHO](https://github.com/rafaelcaetite/labho-historia-oral).** Custom WordPress theme and site for UFV's Oral History Lab, with a Three.js scene and WCAG 2.2 AA as a requirement.

**[Breast Cancer Mortality](https://github.com/rafaelcaetite/Breast-Cancer-Mortality-Prediction).** Course project on METABRIC using only what is known at diagnosis. AUC 0.68, a modest result that comes from refusing to use post-diagnosis variables.

**Arbolia** (private). Offline-first PWA for urban tree inventory, with server-side Gemini generating technical reports from risk matrices.

## Research

Undergraduate research (PIBIC/CNPq) at UFV on machine learning for rainy-season forecasting in Mato Grosso, plus a literature review on RAG. First author of one article and co-author of two.

## Tools

Python, TypeScript, SQL · Claude Code, Orca, n8n, Claude, Gemini and Groq APIs · scikit-learn, XGBoost, LightGBM · PostgreSQL, Redis, Docker, GitHub Actions · React, Next.js
