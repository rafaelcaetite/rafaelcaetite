# Rafael Caetité

**Computer Science Undergraduate @ UFV | Machine Learning • Data Science • SQL**

Undergraduate researcher with hands-on experience building end-to-end Machine Learning pipelines, statistical models, and data analytics solutions. Focused on feature engineering, robust model evaluation, and software quality (automated testing, zero-leakage pipelines, and reproducible code).

[Portfolio](https://www.rafaelcaetite.dev/) • [LinkedIn](https://linkedin.com/in/rafaelcaetite) • [Email](mailto:rafael.cancado@ufv.br)

---

## Overview

- **Education:** B.S. in Computer Science, Federal University of Viçosa (UFV) — 6th period.
- **Core Competencies:** Machine Learning Pipelines, Feature Engineering, Exploratory Data Analysis (EDA), SQL Data Profiling, Model Calibration & Evaluation (ROC-AUC, Precision/Recall), Unit & Integration Testing (`pytest`).
- **Research Background:** First author of *[Modeling Rainfall Seasonality: A Systematic Review of Machine Learning Approaches for Onset and Demise](https://rafaelcaetite.github.io/Modeling-Rainfall-Seasonality/)* (PRISMA 2020 protocol; manuscript under review); predictive modeling using spatial reanalysis data (ERA5/Copernicus).

---

## Technical Skills

- **Languages:** Python, SQL, JavaScript
- **Machine Learning & Data Science:** Scikit-learn, XGBoost, Pandas, NumPy, SciPy, Matplotlib, Seaborn
- **Data Engineering & Databases:** PostgreSQL, Data Profiling, CTEs, Window Functions, Data Cleaning & Preprocessing
- **Modeling & Analytics:** Supervised Classification & Regression, Feature Engineering, Probability Calibration (Isotonic), Cross-Validation, Out-of-Time (OOT) Testing, Leakage Prevention
- **Testing & Tools:** Pytest, Git, GitHub, Docker, Linux/Bash, Jupyter, Google Colab

---

## Selected Projects

### [Credit Risk & Default Prediction Pipeline](https://github.com/rafaelcaetite/credit-risk-ml)
Production-ready machine learning pipeline for credit scoring and probability-of-default estimation (*Give Me Some Credit* dataset).
- **Data & SQL Analytics:** Advanced data profiling in SQL (CTEs, `NTILE`, aggregations) to detect sentinel codes and validate feature signals; strictly separated train-only imputation and outlier capping (p99).
- **Modeling & Calibration:** Trained an XGBoost classifier paired with post-hoc Isotonic Probability Calibration (`CalibratedClassifierCV`) to ensure well-calibrated decision bands without class distortion.
- **Software Quality & Testing:** 77 automated `pytest` tests enforcing performance gates (`ROC-AUC >= 0.80`, P95 scoring latency < 10ms), full reproducible runs (`metadata.json`, SHA256 hashes), and modular PostgreSQL/CSV data adapters.
- **Stack:** Python, Scikit-learn, XGBoost, SQL (PostgreSQL), Pandas, NumPy, Pytest.

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
