<h1 align="center">Hemant Kumar B K</h1>

<h3 align="center">Research Engineer · AI Control &amp; Security</h3>

<p align="center">
  <a href="https://linkedin.com/in/hemantbk"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:hemantkumar.bk@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
</p>

I work on evaluating and monitoring autonomous AI agents, for AI control and cyber defense: benchmarks whose answer keys hold up, and detectors that flag an agent going rogue early enough to matter.

MATS Summer 2026 fellow (Asymmetric Security stream).

## Research

<table>
<tr>
<td valign="top">
<h3><a href="https://arxiv.org/abs/2601.22136">StepShield: When, Not Whether to Intervene on Rogue Agents</a> &nbsp; <img height="18" src="https://img.shields.io/badge/NeurIPS_2026-JUDGe_%26_IAB_Workshops-1F6FEB?style=flat-square" alt="NeurIPS 2026 workshops"></h3>
<p><b>Benchmark for when autonomous code agents go rogue</b></p>
<p>Co-authored. 9,429 labeled agent trajectories with temporal metrics that score how early a monitor flags unsafe behavior. Early flagging cut monitoring cost by roughly 75% against end-of-run review, and a high-recall detector can still intervene too late to be useful.</p>
<p><img src="https://img.shields.io/badge/Agent_monitoring-F1F3F5?style=flat-square" alt="Agent monitoring"> <img src="https://img.shields.io/badge/Benchmark_design-F1F3F5?style=flat-square" alt="Benchmark design"> <img src="https://img.shields.io/badge/AI_control-F1F3F5?style=flat-square" alt="AI control"></p>
</td>
</tr>
<tr>
<td valign="top">
<h3><a href="https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np">Can AI agents investigate a real email breach?</a> &nbsp; <a href="https://www.lesswrong.com/posts/5qPxQsM4vtTirN3np"><img height="18" src="https://img.shields.io/badge/LessWrong-Write--up-6E6E6E?style=flat-square" alt="LessWrong write-up"></a> <img height="18" src="https://img.shields.io/badge/MATS-Summer_2026_%C2%B7_Asymmetric_Security-1F6FEB?style=flat-square" alt="MATS Summer 2026, Asymmetric Security stream"></h3>
<p><b>Frontier agents on real business-email-compromise incidents, scored against human responders</b></p>
<p>Sandboxed harness that runs five frontier models on two real BEC cases. Only 1 of 30 runs named every compromised account without accusing an innocent one, and three models scored at least 50% lower on the second case than on the first. Most lost points were judgment errors, not retrieval failures. The harness also generates new tasks with their own grading criteria, so coverage isn't capped by hand-written answer keys.</p>
<p><img src="https://img.shields.io/badge/Agent_evals-F1F3F5?style=flat-square" alt="Agent evals"> <img src="https://img.shields.io/badge/Cyber_defense-F1F3F5?style=flat-square" alt="Cyber defense"> <img src="https://img.shields.io/badge/Benchmark_generation-F1F3F5?style=flat-square" alt="Benchmark generation"> <img src="https://img.shields.io/badge/KQL-F1F3F5?style=flat-square" alt="KQL"></p>
</td>
</tr>
<tr>
<td valign="top">
<h3>A Survey of Multi-Agent Reinforcement Learning in Cybersecurity &nbsp; <img height="18" src="https://img.shields.io/badge/Under_review-2026-6E6E6E?style=flat-square" alt="Under review, 2026"> <img height="18" src="https://img.shields.io/badge/Preprint-Forthcoming-6E6E6E?style=flat-square" alt="Preprint forthcoming"></h3>
<p><b>Taxonomy of threat models, environments and evaluation suites for MARL in cyber defense</b></p>
<p>With the University of Arizona. Organizes 200+ papers by threat model, simulation environment and evaluation suite.</p>
<p><img src="https://img.shields.io/badge/Multi--agent_RL-F1F3F5?style=flat-square" alt="Multi-agent RL"> <img src="https://img.shields.io/badge/Cyber_defense-F1F3F5?style=flat-square" alt="Cyber defense"> <img src="https://img.shields.io/badge/Survey-F1F3F5?style=flat-square" alt="Survey"></p>
</td>
</tr>
</table>

## Agent and model security

<table>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/mlshield">MLShield</a></h3>
<p><b>Weight-exfiltration detection for Kubernetes ML clusters</b></p>
<p>Three-layer cascade (rules → LSTM + isolation forest → LLM judge) over k8s audit logs and GPU telemetry. On 2,200 synthetic trajectories the rules layer clears ~94% of events at microsecond latency. 117 tests, CI, Helm chart, threat model.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/llm-eval-pipeline">LLM Eval Pipeline</a></h3>
<p><b>Evaluation and red-teaming harness for production LLM deployments</b></p>
<p>Runs prompt suites against four providers and scores outputs with an LLM judge. Keeps running when a provider fails (circuit breaker, dead-letter queue); monitored with Prometheus and Grafana.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/chatbot-auditor">Chatbot Auditor</a></h3>
<p><b>Quality and safety auditor for deployed chatbots</b></p>
<p>Scores conversation logs with an LLM judge to surface the turns where a bot gave wrong, unsafe or evasive answers.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/LLM--as--judge-37474F?style=flat-square" alt="LLM-as-judge"></p>
</td>
</tr>
</table>

## Responsible AI

<table>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/llm-bias-sentinel">LLM Bias Sentinel</a></h3>
<p><b>Seven-benchmark bias evaluation with guardrails</b></p>
<p>Bias evaluation framework with red-teaming, guardrails and monitoring, running fully local via Ollama.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Ollama-37474F?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"> <img src="https://img.shields.io/badge/Guardrails-37474F?style=flat-square" alt="Guardrails"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/credit-scoring-fairness-mlops">Credit Scoring Fairness MLOps</a></h3>
<p><b>MLOps pipeline with automated fairness gates</b></p>
<p>Fairness checks in CI, drift monitoring and EU AI Act compliance reporting on an XGBoost credit model.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XGBoost-37474F?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/Fairlearn-37474F?style=flat-square" alt="Fairlearn"> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/healthcare-bias-audit">Healthcare Bias Audit</a></h3>
<p><b>Bias audit of healthcare ML on the MEPS dataset</b></p>
<p>Measures and mitigates demographic bias with AIF360; SHAP and LIME explainability for the audited models.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/AIF360-37474F?style=flat-square" alt="AIF360"> <img src="https://img.shields.io/badge/SHAP-37474F?style=flat-square" alt="SHAP"> <img src="https://img.shields.io/badge/LIME-37474F?style=flat-square" alt="LIME"></p>
</td>
</tr>
</table>

## LLM systems

<table>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/AI-Chief">AI Chief</a></h3>
<p><b>Food-science assistant with real-time safety monitoring</b></p>
<p>Multi-agent RAG with dangerous-advice detection on every response.</p>
<p><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Fastify-37474F?style=flat-square" alt="Fastify"> <img src="https://img.shields.io/badge/HNSW-37474F?style=flat-square" alt="HNSW"> <img src="https://img.shields.io/badge/RAG-37474F?style=flat-square" alt="RAG"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/AI-Wildlife-Tracker">AI Wildlife Tracker</a></h3>
<p><b>RAG over 500+ Indian wildlife species</b></p>
<p>Identifies species from text or photos; hybrid retrieval, ONNX inference, Langfuse observability.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"> <img src="https://img.shields.io/badge/Langfuse-37474F?style=flat-square" alt="Langfuse"> <img src="https://img.shields.io/badge/RAG-37474F?style=flat-square" alt="RAG"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/rideshala">RideShala</a></h3>
<p><b>AI motorcycle advisor for Indian riders</b></p>
<p>RAG over motorcycle specs with cited recommendations; vLLM serving, Qdrant vector store.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/vLLM-37474F?style=flat-square" alt="vLLM"> <img src="https://img.shields.io/badge/Qdrant-37474F?style=flat-square" alt="Qdrant"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/AI-Voice-Assistant">AI Voice Assistant</a></h3>
<p><b>Fully local STT → LLM → TTS pipeline</b></p>
<p>Whisper transcription, local LLM and neural TTS behind a FastAPI backend and React frontend; nothing leaves the machine.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/React-37474F?style=flat-square&logo=react&logoColor=white" alt="React"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/Interactive-Multilingual-AI-Audiobook-Assistant">Multilingual Audiobook Assistant</a></h3>
<p><b>OCR → TTS → translation → real-time Q&amp;A</b></p>
<p>Turns scanned books into multilingual audiobooks with question answering over the text.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/OCR-37474F?style=flat-square" alt="OCR"> <img src="https://img.shields.io/badge/TTS-37474F?style=flat-square" alt="TTS"></p>
</td>
</tr>
</table>

## Applied ML

<table>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/Multilingual-Sentiment-Emotion-Intelligence-Engine">Multilingual Sentiment Engine</a></h3>
<p><b>Sentiment and emotion analysis across five languages</b></p>
<p>Multi-task XLM-RoBERTa with LoRA adapters, Hindi-English code-switching, ONNX INT8 inference.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XLM--RoBERTa-37474F?style=flat-square" alt="XLM-RoBERTa"> <img src="https://img.shields.io/badge/LoRA-37474F?style=flat-square" alt="LoRA"> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/LLaMA-Sum-Fine-Tuning">LLaMA Summarization Fine-tune</a></h3>
<p><b>LLaMA 3.2 1B fine-tuned with QLoRA</b></p>
<p>4-bit quantization plus LoRA adapters on CNN/DailyMail; +40% ROUGE-2 over the base model.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/QLoRA-37474F?style=flat-square" alt="QLoRA"> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"></p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/dynamic-pricing-engine">Dynamic Pricing Engine</a></h3>
<p><b>Demand forecasting and revenue optimization</b></p>
<p>XGBoost demand forecasting, price-elasticity estimation and scipy revenue optimization; MLflow tracking, Evidently drift monitoring.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/XGBoost-37474F?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"> <img src="https://img.shields.io/badge/Evidently-37474F?style=flat-square" alt="Evidently"></p>
</td>
<td valign="top" width="50%">
<h3><a href="https://github.com/HemantBK/Algorithmic-Trading-AI">Algorithmic Trading AI</a></h3>
<p><b>Trading signals from real-time financial news</b></p>
<p>FinBERT sentiment, spaCy NER and TimeGPT forecasting combined into BUY/SELL/HOLD signals.</p>
<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FinBERT-37474F?style=flat-square" alt="FinBERT"> <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy"> <img src="https://img.shields.io/badge/TimeGPT-37474F?style=flat-square" alt="TimeGPT"></p>
</td>
</tr>
</table>

## Skills

<table>
<tr>
<td valign="top"><b>Agent evaluation</b></td>
<td><img src="https://img.shields.io/badge/Agent_monitoring-37474F?style=flat-square" alt="Agent monitoring"> <img src="https://img.shields.io/badge/LLM_%26_agent_benchmarking-37474F?style=flat-square" alt="LLM %26 agent benchmarking"> <img src="https://img.shields.io/badge/Benchmark_%26_grader_design-37474F?style=flat-square" alt="Benchmark %26 grader design"> <img src="https://img.shields.io/badge/Automated_scoring-37474F?style=flat-square" alt="Automated scoring"></td>
</tr>
<tr>
<td valign="top"><b>Safety & red teaming</b></td>
<td><img src="https://img.shields.io/badge/Red_teaming-37474F?style=flat-square" alt="Red teaming"> <img src="https://img.shields.io/badge/Capability_elicitation-37474F?style=flat-square" alt="Capability elicitation"> <img src="https://img.shields.io/badge/Alignment_evaluation-37474F?style=flat-square" alt="Alignment evaluation"> <img src="https://img.shields.io/badge/A%2FB_testing_%26_statistics-37474F?style=flat-square" alt="A%2FB testing %26 statistics"></td>
</tr>
<tr>
<td valign="top"><b>Languages</b></td>
<td><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/SQL-37474F?style=flat-square" alt="SQL"> <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"> <img src="https://img.shields.io/badge/KQL-37474F?style=flat-square" alt="KQL"></td>
</tr>
<tr>
<td valign="top"><b>ML / DL</b></td>
<td><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"></td>
</tr>
<tr>
<td valign="top"><b>LLMs & agents</b></td>
<td><img src="https://img.shields.io/badge/vLLM-37474F?style=flat-square" alt="vLLM"> <img src="https://img.shields.io/badge/Ollama-37474F?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"> <img src="https://img.shields.io/badge/CrewAI-37474F?style=flat-square" alt="CrewAI"> <img src="https://img.shields.io/badge/QLoRA_%2F_LoRA-37474F?style=flat-square" alt="QLoRA %2F LoRA"> <img src="https://img.shields.io/badge/RAG-37474F?style=flat-square" alt="RAG"></td>
</tr>
<tr>
<td valign="top"><b>Infrastructure</b></td>
<td><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"></td>
</tr>
<tr>
<td valign="top"><b>Cloud</b></td>
<td><img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"> <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP"></td>
</tr>
<tr>
<td valign="top"><b>Observability</b></td>
<td><img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"> <img src="https://img.shields.io/badge/Evidently-37474F?style=flat-square" alt="Evidently"> <img src="https://img.shields.io/badge/Langfuse-37474F?style=flat-square" alt="Langfuse"></td>
</tr>
<tr>
<td valign="top"><b>Security</b></td>
<td><img src="https://img.shields.io/badge/Sandboxed_tool_execution-37474F?style=flat-square" alt="Sandboxed tool execution"> <img src="https://img.shields.io/badge/CTF_challenges-37474F?style=flat-square" alt="CTF challenges"> <img src="https://img.shields.io/badge/OverTheWire-37474F?style=flat-square" alt="OverTheWire"> <img src="https://img.shields.io/badge/Applied_cryptography-37474F?style=flat-square" alt="Applied cryptography"></td>
</tr>
</table>

---

Looking for research engineer roles in AI safety and security. Based in Bengaluru, open to relocation or remote, available now.
