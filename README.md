# Rafael Caetité

**Computer Science Undergraduate @ UFV | Software Engineering • Machine Learning • Data Systems**

Undergraduate researcher and software developer with hands-on experience designing end-to-end Machine Learning pipelines, modular backend systems, and data-intensive applications. Focused on software architecture (Hexagonal / Clean Architecture, DDD), low-latency inference, algorithmic optimization, and software quality (automated CI/CD, unit/integration testing, and zero-leakage data pipelines).

[Portfolio](https://www.rafaelcaetite.dev/) • [LinkedIn](https://linkedin.com/in/rafaelcaetite) • [Email](mailto:rafael.cancado@ufv.br)

---

## Overview

- **Education:** B.S. in Computer Science, Federal University of Viçosa (UFV) — 6th period.
- **Core Competencies:** Machine Learning Engineering (MLE), Software Architecture (Hexagonal / Ports & Adapters), High-Performance / Low-Latency Systems, SQL Data Profiling & Modeling, Feature Engineering, Model Calibration & Evaluation, Automated CI/CD & Testing (`pytest`, `vitest`).
- **Research Background:** First author of 1 scientific article and co-author of 2; hands-on experience in predictive modeling, statistical learning, and spatial reanalysis data (ERA5/Copernicus).

---

## Technical Skills

- **Languages:** Python, SQL, TypeScript, JavaScript
- **Software Engineering & Architecture:** Hexagonal Architecture (Ports & Adapters), Clean Architecture, Domain-Driven Design (DDD) principles, Object-Oriented Design, Modular Systems
- **Machine Learning & MLOps:** Scikit-learn, XGBoost, TreeSHAP, Pandas, NumPy, SciPy, Probability Calibration (Isotonic), Model Governance, Reproducibility, Leakage Prevention
- **Data Engineering & Databases:** PostgreSQL, Docker Compose, Data Modeling, Schema Validation, CTEs, Window Functions, Query Optimization
- **DevOps, CI/CD & Tooling:** GitHub Actions (Matrix CI), Pytest, Vitest, Docker, Git, Linux/Bash, Latency Benchmarking (P95 < 10ms)

---

## Selected Projects

### [Credit Risk & Default Prediction Pipeline](https://github.com/rafaelcaetite/credit-risk-ml)
Production-grade credit scoring and probability-of-default (PD) engine built with **Hexagonal Architecture (Ports & Adapters)** and strict domain-driven decoupling.
- **Software Architecture & Design Patterns:** Decoupled core domain logic from infrastructure via ports (`DataLoaderPort`, `RiskModelPort`, `FeaturePipelinePort`, `MetricsEvaluatorPort`); swappable adapters for PostgreSQL and CSV data sources with strict schema contract validation.
- **Regulatory Explainability & Low Latency:** Real-time inference ($p_{95} < 10\text{ms}$) calculating Adverse Action Reasons via native C++ TreeSHAP (`pred_contribs`) in XGBoost, adhering to regulatory compliance standards (BACEN, LGPD art. 20, ECOA).
- **Modeling, Calibration & Data Systems:** XGBoost classifier paired with post-hoc Isotonic Calibration (`FrozenEstimator`) ensuring calibrated probabilities without class distortion; reproducible training with zero-leakage transforms and automated metadata provenance tracking.
- **DevOps, CI/CD & Testing:** 80 automated unit, integration, and latency tests (`pytest`) enforced via **GitHub Actions** multi-version CI matrix (Python 3.10–3.12); containerized development PostgreSQL database with Docker Compose.
- **Stack:** Python, Scikit-learn, XGBoost, PostgreSQL, Docker Compose, GitHub Actions, Pandas, NumPy, Pytest.

### [Reference Manager — Algorithmic Deduplication & LLM Tooling](https://github.com/rafaelcaetite/Reference-Manager)
High-performance bibliographic processing tool engineered to automate duplicate detection and batch partitioning for systematic reviews (PRISMA 2020 protocol).
- **Algorithms & Optimization:** Implemented fuzzy string matching (Gestalt pattern matching / Ratcliff-Obershelp) with inverted indices ($O(L)$ average search) and length-bound pruning to eliminate redundant distance computations.
- **Parser & Concurrency:** Zero-dependency recursive-descent BibTeX/LaTeX tokenizer; non-blocking client-side processing offloaded to headless **Web Workers** for high-volume record comparison.
- **Security & Quality:** Sanitized against CSV Formula Injection (CWE-1236) and covered with automated unit tests via **Vitest**.
- **Stack:** TypeScript, React, Vite, Web Workers, TailwindCSS, Vitest.

### [PluvioMT — Agroclimatic Decision Support System](https://github.com/rafaelcaetite)
Predictive instrument developed for agricultural planning and climate risk assessment in Mato Grosso, Brazil.
- **Modeling:** Partial Least Squares (PLS) Regression paired with Bayesian Optimization to predict rainfall onset and demise using atmospheric dynamics and oceanic teleconnections.
- **Interface & Full-Stack:** Interactive telemetry dashboard for spatio-temporal data visualization built with React, Vite, and TailwindCSS.
- **Stack:** Python, Scikit-learn, SciPy, React, Vite, TailwindCSS.

### [METABRIC — Genomic & Clinical Mortality Prediction](https://github.com/rafaelcaetite)
Supervised classification pipeline applied to high-dimensional biomedical data (clinical and genomic profiles).
- **Feature Engineering:** Reduced the search space from 693 original features to 25 using a hybrid selection approach to mitigate the curse of dimensionality.
- **Modeling:** Weighted ensemble classifier tuned to optimize screening recall while controlling precision degradation.
- **Stack:** Python, Scikit-learn, Pandas, NumPy.

---

## Contact

- **Personal Site:** [rafaelcaetite.dev](https://www.rafaelcaetite.dev/)
- **LinkedIn:** [linkedin.com/in/rafaelcaetite](https://linkedin.com/in/rafaelcaetite)
- **Institutional Email:** [rafael.cancado@ufv.br](mailto:rafael.cancado@ufv.br)
