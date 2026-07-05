# Abhinav Varma Vathadi

Applied AI Engineer and Data Scientist building GenAI, RAG, agentic AI, computer vision, MLOps/LLMOps, and ML systems across healthcare, sports, university, and startup settings.

**UMBC MPS Data Science '26 · GPA 3.86 · International Award, SAAL 2026**

---

## What I Build

- **Agentic AI Systems**: Tool-calling workflows, LangGraph pipelines, multi-agent reasoning, grounded Q&A, structured outputs, validation checks, and fallback logic.

- **RAG & Grounded LLM Apps**: Metadata-aware retrieval, query-to-context matching, vector search, prompt grounding, retrieval evaluation, and safe answer generation.

- **MLOps & LLMOps Platforms**: MLflow experiment tracking, LangSmith tracing, model/version metadata, API monitoring, privacy-aware logging, and reproducible evaluation workflows.

- **Computer Vision Analytics**: YOLOv8 detection, ByteTrack tracking, OpenCV video processing, field ROI filtering, visual analytics, and structured tracking exports.

- **Machine Learning Pipelines**: Classification, regression, feature engineering, leakage-safe validation, threshold tuning, SHAP explainability, and stakeholder-ready model outputs.

- **Data Products & Dashboards**: Streamlit, Gradio, Tableau, Power BI, Python, and SQL workflows that turn messy data into usable product experiences and decision-ready insights.

---

## Featured Projects

### [Clinical-Trace AI: Healthcare Readmission Risk Platform with MLOps & LLMOps Observability](https://github.com/AbhinavVarma02/Clinical-Trace-AI)

Built Clinical-Trace AI, a privacy-aware healthcare AI platform for 30-day readmission risk prediction using the UCI Diabetes 130-US Hospitals dataset, leakage-safe patient-level splits, engineered utilization features, and validation-tuned model selection across Logistic Regression, Random Forest, and XGBoost. The system serves predictions through FastAPI and a Streamlit dashboard, explains risk drivers with SHAP-style top features, tracks training with MLflow, supports optional LangChain/LangSmith LLM explanations, and includes offline rule-based fallback logic, safety disclaimers, secret checks, and pytest coverage for API, preprocessing, model, LLM safety, and security workflows.

**[Live Demo on Hugging Face](https://huggingface.co/spaces/abhinavvathadi/clinical-trace-ai)**

---

### [GameLens AI: Computer Vision and LLM-Powered Soccer Analytics](https://github.com/AbhinavVarma02/Gamelens-AI)

Built GameLens AI, an end-to-end soccer video analytics app that turns match clips into structured tracking data, visual analytics, and grounded AI-generated insights. The app uses YOLOv8 and ByteTrack for player detection and tracking, OpenCV for video processing, Pandas and NumPy for metric generation, Matplotlib for charts, and a LangGraph + GPT-4o-mini workflow for analyst-style reporting and Q&A. It exports annotated videos, CSV/JSON tracking data, movement metrics, zone activity charts, heatmaps, and grounded answers that reason only over computed pipeline outputs rather than inventing unsupported match events.

**[Live Demo on Hugging Face](https://huggingface.co/spaces/abhinavvathadi/gamelens-ai)**

---

### [ClearCast: Full-Stack Agentic AI App for Weather-Driven Marketing](https://github.com/AbhinavVarma02/ClearCast---Full-Stack-Agentic-AI-App-for-Weather-Driven-Marketing)

Built ClearCast, a weather-driven campaign planning app using Python, MCP, LangGraph, LangChain, GPT-4o-mini, OpenWeatherMap API, and Streamlit to combine campaign inputs with live weather data. The app generates 5-day campaign windows, ad copy, and risk mitigations through agentic tool calling, connecting real-time weather context with practical marketing recommendations.

---

### [DealSight Intelligence: Autonomous Multi-Agent Orchestration](https://github.com/AbhinavVarma02/DealSight-Intelligence-Autonomous-Multi-Agent-Orchestration)

Built DealSight Intelligence, a 3-agent ensemble combining GPT-4o-mini + RAG, a QLoRA fine-tuned Llama 3.2 specialist, and a PyTorch residual DNN to scan live e-commerce feeds and surface high-discount deals. Fine-tuned Meta Llama 3.2-3B on 20,000 e-commerce listings, reducing GPU memory from 6.4 GB to 2.2 GB with a 73.4 MB adapter. Deployed as a serverless endpoint on Modal with W&B experiment tracking, a Gradio dashboard, and Pushover alerts.

**[Live Demo on Hugging Face](https://huggingface.co/spaces/abhinavvathadi/DealSight-Intelligence)**

---

### [RIH Care Insight Assistant: Capstone](https://github.com/AbhinavVarma02/RIH-Care-Insight-Assistant)

Built a bounded agentic AI assistant for UMBC student services using LLM planning, RAG, IDF-weighted retrieval, prompt engineering, and Strands Agents. Designed deterministic safety routing across 5 crisis and policy intent categories with fail-closed fallbacks, regex-based intent classification, ambiguity detection, and reactive clarification. Validated through 56 automated tests covering retrieval ranking, routing accuracy, and decline handling.

---

### Hospital Performance Prediction: ML

Applied CRISP-DM to 578K+ California OSHPD hospital records, benchmarking Random Forest, XGBoost, and Linear Regression. Selected Random Forest for resource-usage regression with **R² 0.916** and high-demand classification with **83.5% accuracy / F1 0.84**. Used K-Means and PCA to segment hospitals into 3 operational efficiency tiers and translated results into stakeholder-ready summaries for staffing, budgeting, and capacity planning.

---

## Professional Impact

| Metric | Context |
|---|---|
| **400 processed frames / 4,718 tracking rows** | GameLens AI soccer video analytics using YOLOv8, ByteTrack, OpenCV, and structured tracking exports |
| **ROC-AUC ~0.683 / PR-AUC ~0.240** | Clinical-Trace AI readmission model with leakage-safe longitudinal features and validation-tuned thresholding |
| **MRR 0.73 → 0.91** | Metadata-aware RAG retrieval and query-to-context matching |
| **2,500+ survey responses analyzed** | GenAI/NLP pipeline for sentiment scoring, theme classification, and review routing |
| **35% fewer invalid KPI records** | XGBoost and Random Forest pipeline on Salesforce KPI data |
| **56 automated tests** | Safety, retrieval, routing, and decline-handling validation for RIH assistant |
| **578K+ records analyzed** | Hospital resource-usage prediction and operational segmentation |
| **International Award** | Student Affairs Assessment Leaders, Jan 2026 |

---

## Current Focus

Targeting **AI/ML Engineer, Applied AI Engineer, Data Scientist, and Computer Vision / MLOps-focused AI Engineer roles**, full-time, starting May/June 2026.

Currently deepening work in agentic AI systems, RAG evaluation, computer vision analytics, healthcare AI, MLOps/LLMOps observability, model deployment, safety validation, and stakeholder-facing AI/data products.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/sql-000000?style=for-the-badge&logo=postgresql&logoColor=white)

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
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

KPI design, dashboard refresh pipelines, data validation, stakeholder reporting, product analytics

**Platforms**

![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

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
