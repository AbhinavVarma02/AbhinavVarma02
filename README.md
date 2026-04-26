# Abhinav Varma Vathadi

Applied AI Engineer and Data Scientist building agentic systems, RAG pipelines, and ML workflows that ship to production, not just notebooks.

**UMBC MPS Data Science '26 · GPA 3.92 · International Award, SAAL 2026**

---

## What I Build

- **Agentic AI Systems**: Multi-agent workflows that route tasks, call tools, recover from failures, and produce structured outputs.

- **RAG Pipelines**: Retrieval systems with chunking, grounding, evaluation, and latency-aware model routing.

- **Machine Learning Pipelines**: End-to-end classification and regression workflows with thorough evaluation and production monitoring.

- **LLM Fine-Tuning**: QLoRA and PEFT-based fine-tuning workflows for task-specific models with experiment tracking.

- **Data Products & Dashboards**: Tableau, Power BI, and Python-based reporting tools that turn messy data into clear decisions.

---

## Featured Projects

### [DealSight Intelligence: Autonomous Multi-Agent Orchestration](https://github.com/AbhinavVarma02/DealSight-Intelligence-Autonomous-Multi-Agent-Orchestration)
3-agent ensemble combining GPT-4o-mini + RAG, a QLoRA fine-tuned Llama 3.2 specialist, and a PyTorch residual DNN to scan live e-commerce feeds and surface high-discount deals in real time. Fine-tuned on 20K product listings; reduced GPU memory from 6.4 GB to 2.2 GB via QLoRA. Deployed serverless on Modal with W&B experiment tracking and a live Gradio dashboard.

**[Live Demo on Hugging Face](https://huggingface.co/spaces/abhinavvathadi/DealSight-Intelligence)**

---

### [RIH Care Insight Assistant: Capstone](https://github.com/AbhinavVarma02/RIH-Care-Insight-Assistant)
Bounded agentic AI assistant for UMBC student health services. Multi-phase NLP pipeline with LLM planning, RAG, IDF-weighted retrieval, and fail-closed safety routing across 5 crisis intent categories. Non-bypassable crisis routing with reactive replanning on retrieval failure. Validated by 56 automated tests covering retrieval ranking, routing accuracy, and decline handling.

---

### Hospital Performance Prediction: ML
Applied CRISP-DM across 578K+ California hospital records. Random Forest final model: **R² 0.916** for resource-usage regression, **83.5% accuracy / F1 0.84** for high-demand classification. K-Means + PCA segmentation into 3 operational efficiency tiers, translated into staffing and capacity planning summaries.

---

## Professional Impact

| Metric | Context |
|---|---|
| **90% reduction** in LLM inference spend | Step-level routing between Ollama and gpt-4o-mini (Anthem Nation) |
| **MRR 0.73 → 0.91** | RAG chunking, retrieval, and evaluation refinements |
| **95% reduction** in survey synthesis effort | 40 hours → 2 hours via GenAI + NLP pipeline (UMBC) |
| **~80% reduction** in reporting time | CrewAI coder agent running Python in Docker sandbox |
| **57% fewer** reporting handoffs | RAG + CI/CD automation at Micron Technology |
| **35% reduction** in invalid KPI records | XGBoost pipeline feeding Salesforce Einstein AI |
| **International Award** | Student Affairs Assessment Leaders (SAAL), Jan 2026 |

---

## Current Focus

Targeting **AI/ML Engineer and Data Scientist roles**, full-time, starting May/June 2026.

Currently deepening work in: MLOps (model observability, drift detection), production deployment patterns, and multi-agent system evaluation.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/sql-000000?style=for-the-badge&logo=postgresql&logoColor=white)

**Agentic AI / LLM Engineering**

![OpenAI](https://img.shields.io/badge/OpenAI_Agents_SDK-000000?style=for-the-badge&logo=openai&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-111111?style=for-the-badge&logo=robotframework&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6C3FC0?style=for-the-badge&logo=databricks&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper_ASR-412991?style=for-the-badge&logo=openai&logoColor=white)
![Strands Agents](https://img.shields.io/badge/Strands_Agents-111111?style=for-the-badge&logo=amazonwebservices&logoColor=white)

RAG, QLoRA, PEFT, prompt engineering, tool-calling, quantization, structured JSON outputs, fine-tuning

**Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)

Classification, regression, K-Means, PCA, feature engineering, model evaluation, leakage-safe time splits, PR-AUC, recall@K

**Deployment / Infra**

![Modal](https://img.shields.io/badge/Modal-000000?style=for-the-badge&logo=lightning&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

**BI / Analytics**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Tableau Prep](https://img.shields.io/badge/Tableau_Prep-1F1F1F?style=for-the-badge&logo=Tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**Platforms**

![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

---

## Certifications

**AI / LLM Engineering**
- AI Engineer Core Track: LLM Engineering, RAG, QLoRA, Agents
- Mastering GenAI: Fine-Tune and Adapt LLMs Effectively
- Generative AI for Everyone
- Machine Learning: Build Neural Networks in 77 Lines of Code

**Data & Analytics**
- Google Data Analytics Professional Certificate *(Google)*
- Google AI Essentials *(Google)*
- Recommendation Systems With Terraform on Google Cloud
- Statistics and Data Analysis with SPSS: Descriptive Statistics
- Power BI Beginner to Pro Workshop

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
