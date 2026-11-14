<div align="center">

# Cássio Henrique

**Computer Science @ CIn/UFPE**

**AI Engineering · Generative AI · Machine Learning · Backend Development**

I build AI systems that connect **models, data, and APIs** to real workflows, with a focus on **evaluation, reliability, and reproducibility**. My work spans evidence-grounded LLM applications, predictive ML pipelines, and tested backend services.

[LinkedIn](https://www.linkedin.com/in/c%C3%A1ssio-henrique-336a993aa) · [Hugging Face](https://huggingface.co/cassiohfs/fooddemand-ai) · [Email](mailto:cassiofreitas011@gmail.com) · [Lattes](http://lattes.cnpq.br/6554361672671225)

</div>

---

## Featured AI Projects

### 01 — GovCheck AI | Evidence-grounded Multi-Agent RAG

**Problem:** Public procurement notices contain requirements, deadlines, and conditions spread across lengthy documents. Summaries without sources can be misleading.

**Solution:** A document-analysis MVP using **LLMs, hybrid RAG (BM25 + semantic retrieval), LangGraph, FastAPI, PostgreSQL/pgvector, and Next.js**. A structured workflow retrieves evidence, extracts findings, performs optional external checks, critiques source support, and produces reviewable reports with page-level citations.

**Engineering focus:** Typed LLM outputs, evidence states (`supported`, `unsupported`, `conflicting`), tool constraints, automated tests, and human review.

**Status:** Open-source portfolio MVP, now publicly accessible at [GovCheck AI](https://github.com/Cassio327/govcheck-ai). The [reviewed demo documentation](https://github.com/Cassio327/govcheck-ai/blob/main/docs/demo.md) and [Portuguese captions](https://github.com/Cassio327/govcheck-ai/blob/main/docs/demo-captions.srt) are available; **the actual MP4 upload is still pending**. Real-LLM evaluation remains a separate workstream; deterministic fixture scores are **not** model-accuracy claims.

### 02 — [FoodDemand AI](https://github.com/Cassio327/fooddemand-ai) | End-to-end Demand Forecasting

**Problem:** Estimate retail product demand from historical signals to support data-informed planning.

**Solution:** A reproducible **scikit-learn** pipeline with calendar and lag features, chronological backtesting, baselines, a **FastAPI inference service**, **Streamlit dashboard**, automated tests, Docker, and CI.

| Verified experiment | Result |
| --- | ---: |
| Real Kaggle Store Sales training rows used | **598,752** |
| Model-ready rows | **547,074** |
| Temporal evaluation | **3 folds × 16 days** |
| Seasonal-naive baseline RMSLE | **0.5316** |
| Model RMSLE | **0.3802** |
| Relative RMSLE reduction | **28.48%** |

These are **rolling one-step backtesting** results on a subset of the public Ecuadorian Store Sales dataset, **not** the Kaggle leaderboard, a 16-day fixed-horizon evaluation, or iFood data.

**Evidence:** [Source code and reproducible benchmark](https://github.com/Cassio327/fooddemand-ai) · [Published model and Model Card on Hugging Face](https://huggingface.co/cassiohfs/fooddemand-ai)

---

## Software Engineering

| Project | Engineering evidence |
| --- | --- |
| **[CourseSphere Security Hardening](https://github.com/Cassio327/coursesphere-security-hardening)** | Five confirmed security findings; four vulnerable API behaviors corrected; regression tests, Flask, Nginx, Docker, Prometheus/Grafana, and CI security checks. |
| **[TaskFlow API](https://github.com/Cassio327/taskflow-api)** | Multi-user REST API with FastAPI, JWT authentication, user-level data isolation, PostgreSQL, Alembic migrations, Docker, and automated tests. |

## Academic Research

**Undergraduate research — HC-UFPE:** Research in progress on **predicting missed outpatient appointments (absenteeism)** with data science and Machine Learning. Current work focuses on data specification, quality validation, and a reproducible analytical pipeline. **No unverified research results or patient data are published.**

## Core Stack

- **Generative AI & LLMs:** RAG, hybrid retrieval, LangGraph, structured outputs, evidence grounding, tool calling, Groq/Ollama integration.
- **Machine Learning & Data:** Python, pandas, NumPy, scikit-learn, temporal validation, feature engineering, RMSLE/MAE/WAPE, Hugging Face.
- **Backend & MLOps:** FastAPI, Flask, PostgreSQL/pgvector, Docker, GitHub Actions, pytest, REST APIs, Streamlit, CI/CD, Git, Linux.

---

**Interested in AI Engineering, GenAI, ML Engineering, and software internships.**

[LinkedIn](https://www.linkedin.com/in/c%C3%A1ssio-henrique-336a993aa) · [Email](mailto:cassiofreitas011@gmail.com) · [GitHub](https://github.com/Cassio327)
