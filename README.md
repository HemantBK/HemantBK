<h1 align="center">Hemant Kumar B K</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=22C55E&center=true&vCenter=true&width=600&lines=ML+Engineer+%7C+AI+Safety+Researcher;Multi-Agent+RL+%C2%B7+LLM+Safety+%C2%B7+RAG;PyTorch+%C2%B7+AWS+%C2%B7+Docker+%C2%B7+FastAPI" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/hemantbk"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:hemantkumar.bk@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://arxiv.org/abs/2601.22136"><img src="https://img.shields.io/badge/arXiv-StepShield-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv"/></a>
</p>

---

**ML Engineer building production-grade AI systems with safety at the core.** Currently researching Multi-Agent RL for cybersecurity at the University of Arizona and co-authoring [StepShield](https://arxiv.org/abs/2601.22136) — a safety benchmark for autonomous code agents (submitted to ICML 2026). Previously built recommendation engines at Escape LLC (30% engagement lift) and agentic RAG chatbots at Omdena (95% reduction in harmful responses).

**I don't treat AI safety as a checkbox — I treat it as an engineering discipline.**

---

## 🔬 Research

<table>
<tr>
<td>

### 🛡️ StepShield — *Co-Author* &nbsp; [![Paper](https://img.shields.io/badge/arXiv-2601.22136-B31B1B?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2601.22136) [![ICML 2026](https://img.shields.io/badge/ICML_2026-Submitted-blue?style=flat-square)](https://arxiv.org/abs/2601.22136)

First benchmark for evaluating when autonomous code agents go rogue — not just whether they do. Detects specification violations (data exfiltration, unauthorized access) in real-time across **9,213 agent trajectories**. Early detection cuts monitoring costs by **75%** (~$108M projected savings).

`Python` `PyTorch` `LLM Safety` `Red-Teaming` `Autonomous Agents`

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ LLM Eval Pipeline
**Production-grade LLM evaluation + red-teaming**

Hybrid n8n + FastAPI architecture with 4 LLM providers, LLM-as-Judge scoring, circuit breaker, DLQ, Redis caching, Prometheus/Grafana monitoring.

`Python` `FastAPI` `Redis` `Prometheus` `Red-Teaming`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/llm-eval-pipeline)

</td>
<td width="50%" valign="top">

### 🔐 MLShield
**ML-infra-aware defense for model weights**

Protects against model-weight exfiltration using a 3-layer cascaded architecture (Rules → ML → LLM). Kubernetes-native, GPU-aware anomaly detection.

`Python` `Kubernetes` `Model Security` `Anomaly Detection`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/MLShield)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ LLM Bias Sentinel
**7-benchmark bias evaluation + guardrails**

Open-source LLM bias evaluation framework with red-teaming, guardrails, and monitoring — all running locally via Ollama. Zero API costs.

`Python` `Ollama` `Red-Teaming` `Guardrails` `Responsible AI`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/llm-bias-sentinel)

</td>
<td width="50%" valign="top">

### 💰 Dynamic Pricing Engine
**Production-grade ML pricing system**

XGBoost demand forecasting + price elasticity estimation + scipy revenue optimization. FastAPI serving, Streamlit dashboard, MLflow tracking, Evidently drift monitoring.

`Python` `XGBoost` `FastAPI` `MLflow` `Streamlit`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/dynamic-pricing-engine)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗣️ AI Voice Assistant
**Full-stack speech pipeline: STT → LLM → TTS**

End-to-end voice assistant running entirely on your own machine — FastAPI backend, React frontend, Docker. Private by design: zero cloud calls.

`Python` `FastAPI` `React` `Docker` `LLM`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/AI-Voice-Assistant)

</td>
<td width="50%" valign="top">

### 🏍️ RideShala
**AI motorcycle advisor for Indian riders**

RAG over motorcycle specs with vLLM serving, Qdrant vector store, FastAPI. Personalized bike recommendations with source citations.

`Python` `vLLM` `RAG` `Qdrant` `FastAPI`

[![Code](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/HemantBK/RideShala)

</td>
</tr>
</table>

---

## 📂 All Projects

### 🛡️ AI Safety & Responsible AI

- **[chatbot-auditor](https://github.com/HemantBK/chatbot-auditor)** — Quality auditor for AI chatbots; analyzes conversation logs to surface where bots underperform.
- **[credit-scoring-fairness-mlops](https://github.com/HemantBK/credit-scoring-fairness-mlops)** — End-to-end MLOps with automated fairness gates, drift monitoring, EU AI Act compliance (XGBoost, Fairlearn, MLflow).
- **[healthcare-bias-audit](https://github.com/HemantBK/healthcare-bias-audit)** — Bias audit of healthcare ML on the MEPS dataset; AIF360 mitigation, SHAP/LIME explainability.

### 🤖 LLM Systems & RAG

- **[AI-Chief](https://github.com/HemantBK/AI-Chief)** — Food science assistant with multi-agent RAG, real-time safety monitoring, dangerous-advice detection (TypeScript, Fastify, HNSW).
- **[Interactive-Multilingual-AI-Audiobook-Assistant](https://github.com/HemantBK/Interactive-Multilingual-AI-Audiobook-Assistant)** — OCR extraction → neural TTS → multilingual translation → real-time Q&A audiobook pipeline.
- **[AI-Wildlife-Tracker](https://github.com/HemantBK/AI-Wildlife-Tracker)** — RAG identifying 500+ Indian wildlife species from text or photos; hybrid retrieval, ONNX inference, Langfuse observability.

### ⚙️ Applied ML & MLOps

- **[Multilingual-Sentiment-Emotion-Intelligence-Engine](https://github.com/HemantBK/Multilingual-Sentiment-Emotion-Intelligence-Engine)** — 5 languages + Hindi-English code-switching; multi-task XLM-RoBERTa with LoRA adapters, ONNX INT8.
- **[Algorithmic-Trading-AI](https://github.com/HemantBK/Algorithmic-Trading-AI)** — FinBERT sentiment + spaCy NER + TimeGPT forecasting → BUY/SELL/HOLD signals from real-time financial news.
- **[LLaMA-Sum-Fine-Tuning](https://github.com/HemantBK/LLaMA-Sum-Fine-Tuning)** — LLaMA 3.2 1B fine-tuned via QLoRA; 40%+ ROUGE-2 improvement over base on CNN/DailyMail.

---

## 🛠️ Tech Stack

<table>
<tr>
<td><b>💻 Languages</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

</td>
</tr>
<tr>
<td><b>🤖 ML / DL</b></td>
<td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

</td>
</tr>
<tr>
<td><b>🧠 LLM & Agents</b></td>
<td>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-7C3AED?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square&logoColor=white)

</td>
</tr>
<tr>
<td><b>🛠️ MLOps / Cloud</b></td>
<td>

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

</td>
</tr>
<tr>
<td><b>📊 Observability</b></td>
<td>

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Evidently](https://img.shields.io/badge/Evidently-ED0606?style=flat-square&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-4B5563?style=flat-square&logoColor=white)

</td>
</tr>
<tr>
<td><b>🛡️ AI Safety & Responsible AI</b></td>
<td>

![Red Teaming](https://img.shields.io/badge/Red_Teaming-B91C1C?style=flat-square&logoColor=white)
![AIF360](https://img.shields.io/badge/AIF360-2563EB?style=flat-square&logoColor=white)
![Fairlearn](https://img.shields.io/badge/Fairlearn-0EA5E9?style=flat-square&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8B5CF6?style=flat-square&logoColor=white)
![Guardrails](https://img.shields.io/badge/Guardrails-059669?style=flat-square&logoColor=white)

</td>
</tr>
<tr>
<td><b>🗄️ Data</b></td>
<td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

</td>
</tr>
</table>

---

<p align="center">
  <b>Open to ML Engineer, AI Safety, and AI Researcher roles — remote & relocation</b><br/>
  <i>Let's build AI systems that are powerful AND trustworthy.</i>
</p>
