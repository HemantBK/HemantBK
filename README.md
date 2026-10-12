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

<table>
<tr>
<td valign="top">
<h4><a href="https://arxiv.org/abs/2601.22136"><b>StepShield: When, Not Whether to Intervene on Rogue Agents</b></a></h4>
<p><i>Benchmark for when autonomous code agents go rogue, not just whether</i></p>
<p><a href="https://arxiv.org/abs/2601.22136"><img src="https://img.shields.io/badge/arXiv--2601.22136-B31B1B?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a> <img src="https://img.shields.io/badge/NeurIPS_2026-JUDGe_%26_IAB_Workshops_·_Poster-1f6feb?style=flat-square" alt="NeurIPS 2026"> <img src="https://img.shields.io/badge/Co--author-6E6E6E?style=flat-square" alt="Co-author"></p><p>9,429 labeled agent trajectories with temporal metrics that score <i>when</i> a monitor flags unsafe behavior. Early flagging cut monitoring cost by roughly 75% against end-of-run review, and a high-recall detector can still intervene too late to be useful.</p>
<p><img src="https://img.shields.io/badge/Agent_monitoring-8B1A1A?style=flat-square" alt="Agent monitoring"> <img src="https://img.shields.io/badge/Benchmark_design-8B1A1A?style=flat-square" alt="Benchmark design"> <img src="https://img.shields.io/badge/Autonomous_agents-8B1A1A?style=flat-square" alt="Autonomous agents"> <img src="https://img.shields.io/badge/AI_control-8B1A1A?style=flat-square" alt="AI control"></p>
</td>
</tr>
<tr>
<td valign="top">
<h4><a href="https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np"><b>Can AI agents investigate a real email breach?</b></a></h4>
<p><i>Frontier agents on real business-email-compromise incidents, scored against human responders</i></p>
<p><img src="https://img.shields.io/badge/MATS-Summer_2026_·_Asymmetric_Security-3b9ddd?style=flat-square" alt="MATS"> <a href="https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np"><img src="https://img.shields.io/badge/LessWrong-Write--up-5a5a5a?style=flat-square" alt="Write-up"></a></p><p>Sandboxed harness that runs five frontier models on two real BEC cases. Only 1 of 30 runs named every compromised account without accusing an innocent one; three models lost half or more of their score between the two cases. Most lost points were judgment errors (who was compromised, how access was gained), not retrieval failures. The harness also generates new tasks along with their grading criteria, so coverage isn't capped by hand-written answer keys.</p>
<p><img src="https://img.shields.io/badge/Agent_evals-8B1A1A?style=flat-square" alt="Agent evals"> <img src="https://img.shields.io/badge/Cyber_defense-8B1A1A?style=flat-square" alt="Cyber defense"> <img src="https://img.shields.io/badge/Benchmark_generation-8B1A1A?style=flat-square" alt="Benchmark generation"> <img src="https://img.shields.io/badge/KQL-0078D4?style=flat-square" alt="KQL"> <img src="https://img.shields.io/badge/Sandboxing-8B1A1A?style=flat-square" alt="Sandboxing"></p>
</td>
</tr>
<tr>
<td valign="top">
<h4><b>A Survey of Multi-Agent Reinforcement Learning in Cybersecurity</b></h4>
<p><i>Taxonomy of threat models, environments and evaluation suites for MARL in cyber defense</i></p>
<p><img src="https://img.shields.io/badge/University_of_Arizona-Under_review_2026-5a5a5a?style=flat-square" alt="Status"></p><p>Survey of 200+ papers organized by threat model, simulation environment and evaluation suite.</p>
<p><img src="https://img.shields.io/badge/Multi--agent_RL-8B1A1A?style=flat-square" alt="Multi-agent RL"> <img src="https://img.shields.io/badge/Cyber_defense-8B1A1A?style=flat-square" alt="Cyber defense"> <img src="https://img.shields.io/badge/Survey-8B1A1A?style=flat-square" alt="Survey"></p>
</td>
</tr>
</table>

## Projects

### Agent and model security

<table>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/mlshield"><b>MLShield</b></a></h4>
<p><i>Weight-exfiltration detection for Kubernetes ML clusters</i></p>
<p>Three-layer cascade (rules → LSTM + isolation forest → LLM judge) over k8s audit logs, GPU telemetry and app events; adapts StepShield's early-intervention metric to infrastructure events. On 2,200 synthetic trajectories the rules layer clears ~94% of events at microsecond latency. 117 tests, CI, Helm chart, documented threat model.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"> <img src="https://img.shields.io/badge/Model_security-8B1A1A?style=flat-square" alt="Model security"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/llm-eval-pipeline"><b>LLM Eval Pipeline</b></a></h4>
<p><i>Evaluation and red-teaming harness for production LLM deployments</i></p>
<p>Runs prompt suites against four providers and scores outputs with an LLM judge. Built to keep running when a provider fails (circuit breaker, dead-letter queue) and to be watched in production.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"> <img src="https://img.shields.io/badge/Red--teaming-8B1A1A?style=flat-square" alt="Red-teaming"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/chatbot-auditor"><b>Chatbot Auditor</b></a></h4>
<p><i>Quality and safety auditor for deployed chatbots</i></p>
<p>Analyzes conversation logs to find where chatbots underperform or behave unsafely.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/LLM--as--judge-8B1A1A?style=flat-square" alt="LLM-as-judge"></p>
</td>
<td width="50%"></td>
</tr>
</table>

### Responsible AI

<table>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/llm-bias-sentinel"><b>LLM Bias Sentinel</b></a></h4>
<p><i>Seven-benchmark bias evaluation with guardrails</i></p>
<p>Open-source bias evaluation framework with red-teaming, guardrails and monitoring, running fully local via Ollama.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"> <img src="https://img.shields.io/badge/Red--teaming-8B1A1A?style=flat-square" alt="Red-teaming"> <img src="https://img.shields.io/badge/Guardrails-2E7D32?style=flat-square" alt="Guardrails"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/credit-scoring-fairness-mlops"><b>Credit Scoring Fairness MLOps</b></a></h4>
<p><i>MLOps pipeline with automated fairness gates</i></p>
<p>End-to-end pipeline with fairness checks in CI, drift monitoring and EU AI Act compliance reporting.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XGBoost-1E88E5?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/Fairlearn-1565C0?style=flat-square" alt="Fairlearn"> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/healthcare-bias-audit"><b>Healthcare Bias Audit</b></a></h4>
<p><i>Bias audit of healthcare ML on the MEPS dataset</i></p>
<p>Measures and mitigates demographic bias with AIF360, with SHAP/LIME explainability for the audited models.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/AIF360-1565C0?style=flat-square" alt="AIF360"> <img src="https://img.shields.io/badge/SHAP-6A1B9A?style=flat-square" alt="SHAP"> <img src="https://img.shields.io/badge/LIME-6A1B9A?style=flat-square" alt="LIME"></p>
</td>
<td width="50%"></td>
</tr>
</table>

### LLM systems

<table>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/AI-Chief"><b>AI Chief</b></a></h4>
<p><i>Food-science assistant with real-time safety monitoring</i></p>
<p>Multi-agent RAG with dangerous-advice detection on every response.</p>
<p><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify"> <img src="https://img.shields.io/badge/HNSW-455A64?style=flat-square" alt="HNSW"> <img src="https://img.shields.io/badge/Multi--agent-455A64?style=flat-square" alt="Multi-agent"> <img src="https://img.shields.io/badge/RAG-6E6E6E?style=flat-square" alt="RAG"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/AI-Wildlife-Tracker"><b>AI Wildlife Tracker</b></a></h4>
<p><i>RAG over 500+ Indian wildlife species</i></p>
<p>Identifies species from text or photos with hybrid retrieval, ONNX inference and Langfuse observability.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"> <img src="https://img.shields.io/badge/Langfuse-3B3B3B?style=flat-square" alt="Langfuse"> <img src="https://img.shields.io/badge/RAG-6E6E6E?style=flat-square" alt="RAG"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/rideshala"><b>RideShala</b></a></h4>
<p><i>AI motorcycle advisor for Indian riders</i></p>
<p>RAG over motorcycle specs with cited recommendations; vLLM serving, Qdrant vector store, FastAPI.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/vLLM-6B46C1?style=flat-square" alt="vLLM"> <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/RAG-6E6E6E?style=flat-square" alt="RAG"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/AI-Voice-Assistant"><b>AI Voice Assistant</b></a></h4>
<p><i>Fully local STT → LLM → TTS pipeline</i></p>
<p>End-to-end voice assistant running entirely on your own machine; FastAPI backend, React frontend, Docker. No cloud calls.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/Interactive-Multilingual-AI-Audiobook-Assistant"><b>Multilingual Audiobook Assistant</b></a></h4>
<p><i>OCR → TTS → translation → real-time Q&A</i></p>
<p>Turns scanned books into multilingual audiobooks with question answering over the text.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/OCR-455A64?style=flat-square" alt="OCR"> <img src="https://img.shields.io/badge/TTS-455A64?style=flat-square" alt="TTS"></p>
</td>
<td width="50%"></td>
</tr>
</table>

### Applied ML

<table>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/Multilingual-Sentiment-Emotion-Intelligence-Engine"><b>Multilingual Sentiment Engine</b></a></h4>
<p><i>Sentiment and emotion analysis across five languages</i></p>
<p>Multi-task XLM-RoBERTa with LoRA adapters, Hindi-English code-switching support, ONNX INT8 inference.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XLM--RoBERTa-8E24AA?style=flat-square" alt="XLM-RoBERTa"> <img src="https://img.shields.io/badge/LoRA-8E24AA?style=flat-square" alt="LoRA"> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/LLaMA-Sum-Fine-Tuning"><b>LLaMA Summarization Fine-tune</b></a></h4>
<p><i>LLaMA 3.2 1B fine-tuned with QLoRA</i></p>
<p>+40% ROUGE-2 over the base model on CNN/DailyMail.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/LLaMA-0467DF?style=flat-square" alt="LLaMA"> <img src="https://img.shields.io/badge/QLoRA-8E24AA?style=flat-square" alt="QLoRA"> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/dynamic-pricing-engine"><b>Dynamic Pricing Engine</b></a></h4>
<p><i>ML pricing system with demand forecasting and revenue optimization</i></p>
<p>XGBoost demand forecasting, price-elasticity estimation, scipy revenue optimization; MLflow tracking, Evidently drift monitoring, Streamlit dashboard.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XGBoost-1E88E5?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"> <img src="https://img.shields.io/badge/Evidently-D32F2F?style=flat-square" alt="Evidently"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square" alt="Streamlit"></p>
</td>
<td valign="top" width="50%">
<h4><a href="https://github.com/HemantBK/Algorithmic-Trading-AI"><b>Algorithmic Trading AI</b></a></h4>
<p><i>Trading signals from real-time financial news</i></p>
<p>FinBERT sentiment, spaCy NER and TimeGPT forecasting combined into BUY/SELL/HOLD signals.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FinBERT-1E88E5?style=flat-square" alt="FinBERT"> <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy"> <img src="https://img.shields.io/badge/TimeGPT-00897B?style=flat-square" alt="TimeGPT"></p>
</td>
</tr>
</table>

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
