![MasterHead](https://d2r55xnwy6nx47.cloudfront.net/uploads/2020/07/Qubits_2880x1220_Lede_HPA.gif)
<h1 align="center">Hi, I'm Abid 👋</h1>
<h3 align="center">Agentic AI · AI Solutions · Data Systems</h3>
<h4 align="center"> Business Associate, Strategy & Data @ Copado · Building production AI agents for GTM, CS & Legal teams</h4>
<p align="center">
  Physics & CS, Washington & Lee University '26 · GPA 3.9 · AWS Certified · IEEE Published
</p>
<p align="center">
  <a href="https://linkedin.com/in/profjeem"><img src="https://img.shields.io/badge/LinkedIn-profjeem-0A66C2?style=flat&logo=linkedin" /></a>
  <a href="mailto:abid.farhan.jeem@gmail.com"><img src="https://img.shields.io/badge/Email-abid.farhan.jeem@gmail.com-EA4335?style=flat&logo=gmail" /></a>
  <img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat&logo=amazonaws" />
</p>

## 🧠 What I Do

I build **production AI agents and data systems** at Copado (New Orleans) — the business↔technical bridge work: take a team's manual, high-stakes workflow, and ship an agent or dashboard that survives contact with real users. My background is physics and ML systems: inference optimization, large-scale simulation pipelines, and retrieval systems, now pointed at enterprise agentic operations.

- **Agentic AI in production** — multi-agent workflows, tool use, output validation, evals, and the documentation standards that let a team maintain them
- **Data systems** — Salesforce-connected dashboards and analytics over live CRM data, nightly sync pipelines, data-quality surfacing
- **ML Inference & Optimization** — JIT compilation (Numba), vectorization, flamegraph profiling, pipeline benchmarking on AWS EC2/S3
- **AI Systems & RAG** — LLaMA-3 inference, vector search (FAISS/ChromaDB), retrieval-augmented generation, multi-agent LLM platforms

---

## 💼 Currently @ Copado

- **TAM Function Update Agent** — took an AI agent from pilot to **production** for Technical Account Managers; now expanding into Customer Success workflows
- **Account 360** — live, secured seller dashboard over **~1,050 paying accounts** with nightly Salesforce sync; surfaced 37 accounts over-consuming testing minutes (one at ~4× its annual pool)
- **AE Legal Answers Bot** — shipped to production for the sales org's legal questions
- **Retention Analytics Dashboard** — renewals forecasting and retention analytics for the Q4 renewals workload
- Authored the **agent documentation standard** my team now builds to
- Preparing for the **Claude Certified Architect — Foundations** exam (Nov 2026)

---

## 🔭 Where I'm Headed

- 🚀 **Long term:** found a **quantum computing + AI** startup — currently building the operator skills, network, and technical depth to get there
- 🎯 Growing toward **AI Solutions Architect / Forward Deployed Engineer** roles — shipping end-to-end outcomes where business meets technical
- 📖 Writing a book — a fictionalized autobiography — along the way

---

## 🚀 Projects

### ⚡ [Northstar — Low-Latency Gravitational-Wave Localization](https://github.com/tjamcclain2/Northstar-Python-)
`Python` `Numba` `NumPy` `AWS EC2/S3` `Random Forest` `scikit-learn` `cProfile` `flamegraphs`

> **46.7× inference speedup** on a physics localization pipeline — the kind of optimization that matters at scale.

- Inherited an O(n³) algorithm; profiled with cProfile + flamegraphs, then restructured via **vectorization, JIT compilation (Numba), and antenna-pattern caching** — reducing runtime from **43s → 0.92s per 100 events**
- Benchmarked the pipeline on **AWS EC2 (t3.medium) vs. local hardware** across 10k+ simulated events; streamed outputs to **S3** to support large-scale ML training runs
- Built a **120k-injection labeled dataset** and trained a Random Forest model to learn the optimal sky-localization exponent, minimizing RMS residuals between predicted and true sky positions
- Engineered a **real-time lookup table** for model inference and designed a reproducible profiling toolkit (flamegraphs, SnakeViz) for non-technical handoff
- *Honors thesis, advised by Dr. Tom McClain · Presented at APS Global Physics Summit 2026, Denver*

---

### 🤖 [AI Conversation Debugger — Copado Multi-Agent Platform](https://github.com/schwabjonas/TeamA-Intern26-Copado)
`Python (FastAPI)` `Angular` `TypeScript` `LLM Agents` `Real-time Streaming`

> **1st place** out of the Copado intern cohort — built in a single hackathon.

- Designed and deployed a full-stack multi-agent LLM platform that routes queries across six specialized AI agents and streams outputs in real time; implemented output validation and model evaluation logic to surface failure modes across agent transitions
- Built an interactive graph visualization that converts any AI conversation into a node-and-edge map — flagging model errors, knowledge-retrieval failures, and low-confidence replies with color-coded badges
- Added on-demand LLM-generated summary nodes (key insights + action items) so teams can audit AI agent outputs at scale without opening every message

---

### 🧮 [Deep Learning Suite: Perceptron → Backprop MLP → CNN](https://github.com/ajeem2026/ML-foundations)
`Python` `NumPy` `PyTorch` `Scikit-Learn`

- Implemented backpropagation from scratch in NumPy: sigmoid activations, batch delta rule, 196→250→10 digit recognizer; visualized the 3D error landscape across weight-space dimensions to analyze convergence behavior
- Built a ConvNet in PyTorch (Conv2d×2, MaxPool2d, Dropout) trained on MNIST over 500 epochs with SGD + CrossEntropyLoss; evaluated with a full 10×10 confusion matrix and per-class precision/recall breakdown

---

### 🏥 [Clinical RAG Pipeline — Letters of Medical Necessity](https://github.com/ajeem2026/AI_Research/tree/main/lomn-rag)
`Python` `LLaMA-3` `LangChain` `FAISS` `ChromaDB` `RAG` `Mechanistic Interpretability`

> End-to-end **LLM inference pipeline** with auditable, citation-traced outputs — built for high-stakes clinical documentation.

- Engineered a **RAG system** (local LLaMA-3 + vector search) that queries clinical guidelines and prior letters before generating insurance documentation — exposing retrieved sources and how they shaped each section
- Implemented **mechanistic interpretability modules**: citation tracing, contrastive "what-if" prompts, and failure-mode probes to audit model reasoning
- Modeled stakeholder personas to evaluate how transparency tooling enables social recourse in denied insurance cases
- *Research advised by Dr. Upol Ehsan (Northeastern University) — extending his Social Transparency framework to clinical AI*

---

### 🧪 [Quantum Annealing for TSP](https://github.com/ajeem2026/TSP-DWave)
`Python` `D-Wave Ocean SDK` `QUBO` `Quantum Optimization`

- Formulated the Traveling Salesman Problem as a **QUBO instance** and mapped it onto the D-Wave quantum annealer
- Investigated quantum vs. classical optimization tradeoffs for NP-hard combinatorial problems
---

---

## ⚙️ Technical Skills

### 🤖 Agentic AI & LLM Systems
`AI Agents` `Multi-Agent Workflows` `Tool Use` `LLM Evals` `Output Validation` `Prompt Engineering` `RAG Pipelines` `LLaMA-3` `FAISS` `ChromaDB` `LangChain`

### 🔥 Inference & Performance Engineering
`Numba (JIT)` `Vectorization` `cProfile` `Flamegraphs` `SnakeViz` `Pipeline Benchmarking` `AWS EC2/S3`

### 🧠 ML & Data
`CNNs` `PyTorch` `scikit-learn` `Random Forests` `Backpropagation` `Google BigQuery` `Apache Superset` `Salesforce CRM` `SQL` `SOQL` `Large-scale Simulation Pipelines` `Labeled Dataset Construction` `S3 Data Streaming` `NumPy` `SciPy`

### ☁️ Cloud & Infrastructure
`AWS EC2` `S3` `Bedrock` `OpenSearch` `CloudFront` `WAF` `GCP` · **AWS Certified Cloud Practitioner (CLF-C02)**

### 💻 Languages
`Python` `SQL` `SOQL` `TypeScript` `JavaScript` `C/C++` `Bash` `LaTeX`

### 🔬 Scientific & Systems
`Linux Systems` `D-Wave Ocean SDK` `Qiskit` `Cirq` `COMSOL Multiphysics`

---

## 📄 Publications & Presentations

- 📝 **A. F. Jeem & T. McClain** — *Low-Latency Gravitational-Wave Sky Localization: Optimization and ML Extensions of the NorthStar Pipeline* — Manuscript in preparation, W&L 2026
- 📝 **K. Gamage et al. (incl. A. Jeem)** — *A Cost-Effective 3D Finite Element Model for Predicting Transient Heat Transfer in U-tube Ground Heat Exchangers* — **IEEE GEC 2024**, Batman, Türkiye
- 🎤 **APS Global Physics Summit 2026** — Poster, Denver, CO
- 🎤 **AGU Annual Meeting 2023** — Poster, San Francisco, CA
- 🎤 **Shenandoah Undergraduate Math & Stats Conference 2023** — Invited Talk
---

## 🏅 Honors & Awards

| Award | Year |
|---|---|
| H. Thomas Williams Jr. Undergraduate Research Award ($4,000) | 2026 |
| Omicron Delta Kappa — National Leadership Honor Society | 2025 |
| Sigma Pi Sigma — National Physics Honor Society | 2024 |
| W&L International Scholar (Full-Ride, $95,225/yr) | 2022 |
| Queen's Commonwealth Essay Competition — Gold Award (Top 0.1% of 13,000+) | 2020 |
| Valedictorian, Sunway International College, Malaysia | 2020 |
| George Mason Travel Grants — Italy/Switzerland (CERN & VIRGO), Barbados, Zimbabwe | 2024–2026 |

---

## 📈 GitHub Stats

<p>
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=ajeem2026&show_icons=true&locale=en&layout=compact&theme=dark" alt="ajeem2026" />
</p>
<p>
  &nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=ajeem2026&show_icons=true&locale=en&theme=dark" alt="ajeem2026" />
</p>
<p>
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=ajeem2026&theme=dark" alt="ajeem2026" />
</p>
---

<p align="center">
  <i>Building production AI agents at Copado in New Orleans · Building toward quantum + AI.</i><br><br>
  <a href="https://linkedin.com/in/profjeem">LinkedIn</a> · <a href="mailto:abid.farhan.jeem@gmail.com">Email</a>
</p>
