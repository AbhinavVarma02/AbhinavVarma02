
<img width="2172" height="724" alt="abhinav-github-banner-premium" src="https://github.com/user-attachments/assets/13ae0622-7b8a-45d1-83ab-3607f3f04b27" />

# Abhinav Varma Vathadi

Applied AI Engineer and Data Scientist building **evidence-grounded agents, full-stack AI products, evaluation platforms, computer vision, and reproducible ML/data pipelines**—with public demos, measured results, and documented limitations.

**UMBC MPS Data Science '26 · GPA 3.86 · International Award, SAAL 2026**

---

## What I Build

- **Agentic AI Systems**: LangGraph orchestration, MCP tools, multi-agent workflows, structured outputs, evidence checks, human-in-the-loop review, safety controls, and fallbacks.

- **RAG & Grounded LLM Apps**: Metadata-aware retrieval, query-to-context matching, vector search, prompt grounding, retrieval evaluation, and safe answer generation.

- **MLOps & LLMOps Platforms**: MLflow experiment tracking, LangSmith tracing, model/version metadata, API monitoring, privacy-aware logging, and reproducible evaluation workflows.

- **Computer Vision Analytics**: YOLOv8 detection, ByteTrack tracking, OpenCV video processing, field ROI filtering, visual analytics, and structured tracking exports.

- **Machine Learning Pipelines**: Classification, regression, feature engineering, leakage-safe validation, threshold tuning, SHAP explainability, and stakeholder-ready model outputs.

- **Data Products & Dashboards**: React/TypeScript, FastAPI, Streamlit, Gradio, Tableau, Power BI, Python, and SQL interfaces that make complex model outputs usable.

---

## Featured Projects

### [Clinical-Trace AI 2.0: Evidence-Grounded Clinical Agents & Readmission Risk](https://github.com/AbhinavVarma02/Clinical-Trace-AI)

An interactive healthcare AI research prototype that pairs a 30-day readmission model with a LangGraph case-review agent. The **React + TypeScript workspace** lets visitors explore **synthetic FHIR R4 records**, patient-scoped retrieval, source-linked claims, default-deny access controls, and content-bound human approval. In a recorded 42-case synthetic evaluation, the public Qwen3 model passed **39 cases**; the original readmission model achieved **0.683 ROC-AUC / 0.240 PR-AUC** on held-out data. **Not clinically validated or intended for patient care.**

**[Try Clinical-Trace AI 2.0](https://clinical-trace-ai.vathadiabhinav.workers.dev/)** · [Original Streamlit demo](https://huggingface.co/spaces/abhinavvathadi/clinical-trace-ai) · [Evaluation details](https://github.com/AbhinavVarma02/Clinical-Trace-AI/blob/main/docs/EVALUATION.md)

---

### [AgentOps EvalBench MCP: RAG Evaluation & Observability](https://github.com/AbhinavVarma02/Agentops-Evalbench-MCP)

An evaluation workbench for testing RAG and agentic AI systems before release. **FastAPI, Streamlit, a CLI, PostgreSQL, and six MCP tools** share an engine for groundedness, hallucination risk, retrieval quality, latency, estimated generation cost, run comparison, and CI quality gates. On **40 human-labeled RAG examples**, it measured **87.5% pass/fail agreement** and **0.94 hallucination F1**. The public demo uses a deterministic offline mode.

**[Live Dashboard](https://agentops-evalbench-mcp.streamlit.app/)** · [API documentation](https://agentops-evalbench-api.onrender.com/docs)

---

### [ClearCast: Full-Stack Agentic AI for Weather-Driven Marketing](https://github.com/AbhinavVarma02/ClearCast---Full-Stack-Agentic-AI-App-for-Weather-Driven-Marketing)

A campaign-planning app that turns OpenWeatherMap forecasts into five-day promotion windows, supporting evidence, suggested copy, and risk notes. Built with **LangGraph, GPT-4o-mini, four MCP weather tools, FastAPI, and a TypeScript/Fastify gateway**; deterministic checks verify the model's cited forecasts and client rules before human review. Includes **45 scripted offline evaluation scenarios**. Demo clients are fictional, and plans are not automatically published.

**[Live Demo](https://huggingface.co/spaces/abhinavvathadi/ClearCast-AI)**

---

### [Room for Both: Cultural Discovery & Negotiation Decision Support](https://github.com/AbhinavVarma02/Room-for-Both)

A collaboration-planning app that helps independent brands and venues find common ground. It uses **Qloo cultural signals** to explain venue matches, collects each party's actual terms, checks nine partnership arrangements against explicit constraints, and proposes the smallest negotiable change that could make a blocked deal feasible. Produces a shareable brief while keeping unknown terms and hypothetical changes clearly labeled. The live app can fall back to fictional demonstration data when its time-limited discovery access is unavailable.

**[Explore the App](https://room-for-both.room-for-both.workers.dev/)**

---

### [FabPilot AI: Explainable Semiconductor Yield Decision Support](https://github.com/AbhinavVarma02/Fabpilot-ai)

A Streamlit + LangGraph workflow combining **SECOM process-sensor risk**, a **PyTorch CNN for wafer-map defect patterns**, local feature explanations, and confidence-based human-review routing. On a 180-map public demo sample, **85 predictions were auto-accepted at 88.2% accuracy within that accepted subset**; the other **95 were flagged for review**. Built to support investigations, not to assert physical root causes or autonomous production decisions.

**[Live Demo](https://huggingface.co/spaces/AbhinavVarma/fabpilot-ai)** · [Evaluation audit](https://github.com/AbhinavVarma02/Fabpilot-ai/blob/main/reports/wm811k_review_audit.md)

---

### [GameLens AI: Computer Vision & Grounded Soccer Analytics](https://github.com/AbhinavVarma02/Gamelens-AI)

Converts soccer clips into player detections, tracks, movement charts, heatmaps, and evidence-grounded analyst Q&A. **YOLOv8, ByteTrack, OpenCV, Pandas, and LangGraph** turn visual observations into structured outputs rather than asking an LLM to invent match events. A bundled 20-second clip produced **400 processed frames and 4,718 tracking rows**.

**[Live Demo](https://huggingface.co/spaces/abhinavvathadi/gamelens-ai)**

---

### [DealSight Intelligence: RAG, QLoRA & Multi-Agent Price Estimation](https://github.com/AbhinavVarma02/DealSight-Intelligence-Autonomous-Multi-Agent-Orchestration)

An e-commerce deal-discovery system combining **RAG + GPT-4o-mini**, a **QLoRA fine-tuned Llama 3.2 specialist**, and a **PyTorch pricing network**. Fine-tuned on **20,000 listings** and reduced specialist-training GPU memory from **6.4 GB to 2.2 GB**. Includes Gradio review, Weights & Biases tracking, and optional alerts; the public Space runs in **dry-run mode** without paid integrations.

**[Demo](https://huggingface.co/spaces/abhinavvathadi/DealSight-Intelligence)**

---

### [Flight Trajectory Anomaly Detection: Reproducible Multi-Model Benchmark](https://github.com/AbhinavVarma02/A-Multi-Model-Benchmark-for-Flight-Trajectory-Anomaly-Detection)

A reproducible ADS-B trajectory research benchmark comparing **Isolation Forest, LSTM autoencoder, VAE, and TS2Vec-style representations**. Includes seeded synthetic anomaly injection, multi-seed evaluation, error diagnostics, and a Gradio demo. Reported model runs are **smoke-mode pipeline validation**, not final claims about real-world anomaly-detection quality.

**[Demo](https://abhinavvathadi-flight-trajectory-anomaly-detection.hf.space/)**

---

### GA4 Checkout Funnel Analytics: Data Engineering & Power BI

Modeled **4.3 million GA4 events** using **BigQuery, dbt, Python, and Power BI** to study checkout behavior and identify **279,586 of 360,000 sessions** without a product view. Produced a four-page analysis with **hypothetical** recovery scenarios, not measured revenue improvements.

---

### [NYC Mobility Big Data Analytics: Reproducible Spark & Hadoop Pipeline](https://github.com/AbhinavVarma02/NYC-Mobility-Big-Data-Analytics)

A locally reproducible data platform that ingests public **NYC TLC taxi trips and traffic counts** into **HDFS**, transforms data with **PySpark and Spark SQL**, publishes curated **Parquet/Hive** tables, and generates zone-demand summaries using **Scala**. Dockerized infrastructure lets others reproduce the historical analysis without a cloud account; traffic counts are treated as a proxy, not direct travel-time measurements.

---

### RIH Care Insight Assistant: Bounded Student-Support AI Capstone

A collaborative agentic assistant for university student-services Q&A using **RAG, IDF-weighted retrieval, Strands Agents, and deterministic safety routing**. Designed fail-closed handling for crisis and policy-sensitive requests, ambiguity detection, and human-facing clarification, with **56 automated tests** in the documented capstone version.

---

### [Hospital Performance Prediction: Regression, Classification & Clustering](https://github.com/AbhinavVarma02/Hospital_Performance_Prediction_ML)

A **collaborative UMBC machine-learning course project** with Devika Rani Sanaboyina, exploring hospital readmission and performance data through preprocessing, regression, classification, and clustering notebooks. The repository includes an executive summary and presentation documenting the modeling workflow and comparisons.

---

### [Agentic Profile & Lead Assistant: Tool-Calling Q&A](https://github.com/AbhinavVarma02/Agentic-profile-lead-assistant)

A Python + Gradio professional-profile assistant using **OpenAI tool calling, curated SQLite Q&A memory, and an evaluator–optimizer loop**. Includes runtime logging and optional Pushover notifications for new leads or unanswered questions, while keeping personal local-only data out of the public demo.

**[Demo](https://huggingface.co/spaces/abhinavvathadi/agentic-profile-lead-assistant)**

---


## Professional Impact

| Metric | Context |
|---|---|
| **39/42 cases passed** | Clinical-Trace AI 2.0's recorded public-model evaluation on a synthetic case suite; deterministic mode passed 41/42 |
| **ROC-AUC 0.683 / PR-AUC 0.240** | Clinical-Trace's held-out readmission-risk model; research prototype, not clinical validation |
| **87.5% agreement / 0.94 F1** | AgentOps EvalBench's pass/fail agreement and hallucination F1 on 40 labeled RAG cases |
| **85 of 180 maps auto-accepted** | FabPilot AI achieved 88.2% accuracy *among accepted cases*; 95 were routed for review |
| **400 frames / 4,718 tracking rows** | GameLens AI video analysis using YOLOv8 and ByteTrack |
| **4.3M events analyzed** | GA4 funnel analysis; identified 279,586 of 360K sessions without a product view |
| **45 scripted evaluation scenarios** | ClearCast's offline, evidence-and-constraint validation checks |
| **MRR@10: 0.73 → 0.91** | Metadata-aware retrieval work |
| **2,500+ survey responses analyzed** | GenAI/NLP review with human checks |
| **~35% fewer invalid KPI records** | Observed after combined reviewer-prioritization and validation/process changes |
| **International Award** | Student Affairs Assessment Leaders, 2026 |

---


## Current Focus

Open to **full-time Applied AI Engineer, AI/ML Engineer, AI-focused Software Engineer, Forward Deployed Engineer, and Data Scientist roles**.

I focus on building AI applications people can inspect and test: grounded agents, human-in-the-loop workflows, LLM evaluation, computer vision, reproducible machine-learning pipelines, and production-minded APIs and user interfaces. Explore the **live demos and linked repositories above** to see how the systems work, what was measured, and where their limitations are documented.

---


## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/sql-000000?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**LLM / Agentic AI**

![OpenAI](https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-111111?style=for-the-badge&logo=robotframework&logoColor=white)
![Strands Agents](https://img.shields.io/badge/Strands_Agents-111111?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6C3FC0?style=for-the-badge&logo=databricks&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

RAG, QLoRA, PEFT, prompt engineering, tool-calling workflows, structured outputs, model routing, retrieval evaluation, grounded Q&A, safety routing, fallback logic

**Computer Vision / Video Analytics**

![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111111?style=for-the-badge&logo=python&logoColor=white)
![ByteTrack](https://img.shields.io/badge/ByteTrack-000000?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

Object detection, player tracking, frame processing, ROI filtering, tracking exports, annotated video generation, movement analytics, heatmaps

**Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=python&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-111111?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Classification, regression, Random Forest, XGBoost, K-Means, PCA, feature engineering, leakage-safe validation, threshold tuning, model evaluation, explainability

**MLOps / LLMOps / Deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-000000?style=for-the-badge&logo=lightning&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)

Experiment tracking, model artifacts, API deployment, LLM tracing, privacy-aware metadata logging, test automation, Dockerized services, Streamlit and Gradio apps

**BI / Analytics**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Tableau Prep](https://img.shields.io/badge/Tableau_Prep-1F1F1F?style=for-the-badge&logo=Tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

KPI design, dashboard refresh pipelines, data validation, stakeholder reporting, product analytics

**Platforms**

![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

## Certifications

**AI / LLM Engineering**

- **AI Engineer Agentic Track: Complete Agent & MCP Course**  
  Udemy, Ed Donner · 2026

- **AI Engineer Core Track: LLM Engineering, RAG, QLoRA, Agents**  
  Udemy, Ed Donner · 2026

- **Mastering GenAI: Fine-Tune & Adapt LLMs Effectively**  
  Udemy · 2026

- **Generative AI for Everyone**  
  DeepLearning.AI · 2025

- **Google AI Essentials**  
  Google · 2025

**Data & Analytics**

- **Google Data Analytics Professional Certificate**  
  Google · 2025

- **Statistics and Data Analysis with SPSS: Descriptive Statistics**  
  Udemy · 2026

- **Power BI Beginner to Pro Workshop**  
  Pragmatic Works · 2025

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/abhinav-varma-vathadi)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:abhinavvathadi@gmail.com)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AbhinavVarma02/AbhinavVarma02/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AbhinavVarma02/AbhinavVarma02/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/AbhinavVarma02/AbhinavVarma02/output/github-snake.svg" />
</picture>
