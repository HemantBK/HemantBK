<h1 align="center">Hemant Kumar B K</h1>

<h3 align="center">Research Engineer · AI Control & Security</h3>

<p align="center">
  <a href="https://linkedin.com/in/hemantbk"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hemantkumar.bk@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
</p>

I work on evaluating and monitoring autonomous AI agents, for AI control and cyber defense: benchmarks whose answer keys hold up, and detectors that flag an agent going rogue early enough to matter.

MATS Summer 2026 fellow (Asymmetric Security stream).

## Research

### [StepShield: When, Not Whether to Intervene on Rogue Agents](https://arxiv.org/abs/2601.22136)

**Benchmark for when autonomous code agents go rogue, not just whether**

[![arXiv](https://img.shields.io/badge/arXiv-2601.22136-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.22136)
![NeurIPS 2026](https://img.shields.io/badge/NeurIPS_2026-JUDGe_%26_IAB_Workshops_·_Poster-1f6feb?style=flat-square)
![Role](https://img.shields.io/badge/Co--author-6E6E6E?style=flat-square)

9,429 labeled agent trajectories with temporal metrics that score *when* a monitor flags unsafe behavior. Early flagging cut monitoring cost by roughly 75% against end-of-run review, and a high-recall detector can still intervene too late to be useful.

![](https://img.shields.io/badge/Agent_monitoring-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Benchmark_design-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Autonomous_agents-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/AI_control-8B1A1A?style=flat-square)

---

### [Can AI agents investigate a real email breach?](https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np)

**Frontier agents on real business-email-compromise incidents, scored against human responders**

![MATS](https://img.shields.io/badge/MATS-Summer_2026_·_Asymmetric_Security-3b9ddd?style=flat-square)
[![Write-up](https://img.shields.io/badge/LessWrong-Write--up-5a5a5a?style=flat-square)](https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np)

Sandboxed harness that runs five frontier models on two real BEC cases. Only 1 of 30 runs named every compromised account without accusing an innocent one; three models lost half or more of their score between the two cases. Most lost points were judgment errors (who was compromised, how access was gained), not retrieval failures. The harness also generates new tasks along with their grading criteria, so coverage isn't capped by hand-written answer keys.

![](https://img.shields.io/badge/Agent_evals-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Cyber_defense-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Benchmark_generation-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/KQL-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Sandboxing-8B1A1A?style=flat-square)

---

### A Survey of Multi-Agent Reinforcement Learning in Cybersecurity

**Taxonomy of threat models, environments and evaluation suites for MARL in cyber defense**

![Status](https://img.shields.io/badge/University_of_Arizona-Under_review_2026-5a5a5a?style=flat-square)

Survey of 200+ papers organized by threat model, simulation environment and evaluation suite.

![](https://img.shields.io/badge/Multi--agent_RL-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Cyber_defense-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Survey-8B1A1A?style=flat-square)

---

## Projects

### Agent and model security

#### [MLShield](https://github.com/HemantBK/mlshield)

**Weight-exfiltration detection for Kubernetes ML clusters**

Three-layer cascade (rules → LSTM + isolation forest → LLM judge) over k8s audit logs, GPU telemetry and app events; adapts StepShield's early-intervention metric to infrastructure events. On 2,200 synthetic trajectories the rules layer clears ~94% of events at microsecond latency. 117 tests, CI, Helm chart, documented threat model.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![](https://img.shields.io/badge/Model_security-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Anomaly_detection-8B1A1A?style=flat-square)

---
#### [LLM Eval Pipeline](https://github.com/HemantBK/llm-eval-pipeline)

**Evaluation and red-teaming harness for production LLM deployments**

Runs prompt suites against four providers and scores outputs with an LLM judge. Built to keep running when a provider fails (circuit breaker, dead-letter queue) and to be watched in production.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![](https://img.shields.io/badge/Red--teaming-8B1A1A?style=flat-square)

---
#### [Chatbot Auditor](https://github.com/HemantBK/chatbot-auditor)

**Quality and safety auditor for deployed chatbots**

Analyzes conversation logs to find where chatbots underperform or behave unsafely.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/LLM--as--judge-8B1A1A?style=flat-square)

---

### Responsible AI

#### [LLM Bias Sentinel](https://github.com/HemantBK/llm-bias-sentinel)

**Seven-benchmark bias evaluation with guardrails**

Open-source bias evaluation framework with red-teaming, guardrails and monitoring, running fully local via Ollama.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![](https://img.shields.io/badge/Red--teaming-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Guardrails-2E7D32?style=flat-square)

---
#### [Credit Scoring Fairness MLOps](https://github.com/HemantBK/credit-scoring-fairness-mlops)

**MLOps pipeline with automated fairness gates**

End-to-end pipeline with fairness checks in CI, drift monitoring and EU AI Act compliance reporting.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/XGBoost-1E88E5?style=flat-square) ![](https://img.shields.io/badge/Fairlearn-1565C0?style=flat-square) ![](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

---
#### [Healthcare Bias Audit](https://github.com/HemantBK/healthcare-bias-audit)

**Bias audit of healthcare ML on the MEPS dataset**

Measures and mitigates demographic bias with AIF360, with SHAP/LIME explainability for the audited models.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/AIF360-1565C0?style=flat-square) ![](https://img.shields.io/badge/SHAP-6A1B9A?style=flat-square) ![](https://img.shields.io/badge/LIME-6A1B9A?style=flat-square)

---

### LLM systems

#### [AI Chief](https://github.com/HemantBK/AI-Chief)

**Food-science assistant with real-time safety monitoring**

Multi-agent RAG with dangerous-advice detection on every response.

![](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![](https://img.shields.io/badge/HNSW-455A64?style=flat-square) ![](https://img.shields.io/badge/Multi--agent-455A64?style=flat-square) ![](https://img.shields.io/badge/RAG-6E6E6E?style=flat-square)

---
#### [AI Wildlife Tracker](https://github.com/HemantBK/AI-Wildlife-Tracker)

**RAG over 500+ Indian wildlife species**

Identifies species from text or photos with hybrid retrieval, ONNX inference and Langfuse observability.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) ![](https://img.shields.io/badge/Langfuse-3B3B3B?style=flat-square) ![](https://img.shields.io/badge/RAG-6E6E6E?style=flat-square)

---
#### [RideShala](https://github.com/HemantBK/rideshala)

**AI motorcycle advisor for Indian riders**

RAG over motorcycle specs with cited recommendations; vLLM serving, Qdrant vector store, FastAPI.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/vLLM-6B46C1?style=flat-square) ![](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/RAG-6E6E6E?style=flat-square)

---
#### [AI Voice Assistant](https://github.com/HemantBK/AI-Voice-Assistant)

**Fully local STT → LLM → TTS pipeline**

End-to-end voice assistant running entirely on your own machine; FastAPI backend, React frontend, Docker. No cloud calls.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---
#### [Multilingual Audiobook Assistant](https://github.com/HemantBK/Interactive-Multilingual-AI-Audiobook-Assistant)

**OCR → TTS → translation → real-time Q&A**

Turns scanned books into multilingual audiobooks with question answering over the text.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/OCR-455A64?style=flat-square) ![](https://img.shields.io/badge/TTS-455A64?style=flat-square)

---

### Applied ML

#### [Multilingual Sentiment Engine](https://github.com/HemantBK/Multilingual-Sentiment-Emotion-Intelligence-Engine)

**Sentiment and emotion analysis across five languages**

Multi-task XLM-RoBERTa with LoRA adapters, Hindi-English code-switching support, ONNX INT8 inference.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/XLM--RoBERTa-8E24AA?style=flat-square) ![](https://img.shields.io/badge/LoRA-8E24AA?style=flat-square) ![](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

---
#### [LLaMA Summarization Fine-tune](https://github.com/HemantBK/LLaMA-Sum-Fine-Tuning)

**LLaMA 3.2 1B fine-tuned with QLoRA**

+40% ROUGE-2 over the base model on CNN/DailyMail.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/LLaMA-0467DF?style=flat-square) ![](https://img.shields.io/badge/QLoRA-8E24AA?style=flat-square) ![](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

---
#### [Dynamic Pricing Engine](https://github.com/HemantBK/dynamic-pricing-engine)

**ML pricing system with demand forecasting and revenue optimization**

XGBoost demand forecasting, price-elasticity estimation, scipy revenue optimization; MLflow tracking, Evidently drift monitoring, Streamlit dashboard.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/XGBoost-1E88E5?style=flat-square) ![](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![](https://img.shields.io/badge/Evidently-D32F2F?style=flat-square) ![](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square)

---
#### [Algorithmic Trading AI](https://github.com/HemantBK/Algorithmic-Trading-AI)

**Trading signals from real-time financial news**

FinBERT sentiment, spaCy NER and TimeGPT forecasting combined into BUY/SELL/HOLD signals.

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/FinBERT-1E88E5?style=flat-square) ![](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white) ![](https://img.shields.io/badge/TimeGPT-00897B?style=flat-square)

---

## Skills

| | |
|---|---|
| **Evaluation & safety** | ![](https://img.shields.io/badge/Agent_monitoring-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/LLM_%26_agent_benchmarking-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Benchmark_%26_grader_design-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Automated_scoring-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Capability_elicitation-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Red_teaming-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/Alignment_evaluation-8B1A1A?style=flat-square) ![](https://img.shields.io/badge/A%2FB_testing_%26_statistics-8B1A1A?style=flat-square) |
| **Languages** | ![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![](https://img.shields.io/badge/KQL-0078D4?style=flat-square) |
| **ML / DL** | ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![](https://img.shields.io/badge/QLoRA_%2F_LoRA-6E6E6E?style=flat-square) ![](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) |
| **LLMs & agents** | ![](https://img.shields.io/badge/vLLM-6B46C1?style=flat-square) ![](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![](https://img.shields.io/badge/CrewAI-000000?style=flat-square) ![](https://img.shields.io/badge/RAG-6E6E6E?style=flat-square) |
| **Infrastructure** | ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Cloud** | ![](https://img.shields.io/badge/AWS_(EC2,_S3,_Lambda,_SageMaker)-FF9900?style=flat-square&logo=amazonwebservices&logoColor=black) ![](https://img.shields.io/badge/GCP_(Vertex_AI)-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |
| **Observability** | ![](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![](https://img.shields.io/badge/Evidently-D32F2F?style=flat-square) ![](https://img.shields.io/badge/Langfuse-3B3B3B?style=flat-square) |
| **Security** | ![](https://img.shields.io/badge/Sandboxed_tool_execution-2E7D32?style=flat-square) ![](https://img.shields.io/badge/CTF_challenges-2E7D32?style=flat-square) ![](https://img.shields.io/badge/OverTheWire-2E7D32?style=flat-square) ![](https://img.shields.io/badge/Applied_cryptography-2E7D32?style=flat-square) |

---

Looking for research engineer roles in AI safety and security. Based in Bengaluru, open to relocation or remote, available now.
