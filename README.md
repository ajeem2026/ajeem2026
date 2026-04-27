![MasterHead](https://d2r55xnwy6nx47.cloudfront.net/uploads/2020/07/Qubits_2880x1220_Lede_HPA.gif)

<h1 align="center">Hi, I'm Abid 👋</h1>
<h3 align="center">ML Inference · Data Engineering · AI Systems</h3>
<p align="center">
  Physics & CS @ Washington & Lee University · GPA 3.9 · AWS Certified · IEEE Published
</p>

<p align="center">
  <a href="https://linkedin.com/in/profjeem"><img src="https://img.shields.io/badge/LinkedIn-profjeem-0A66C2?style=flat&logo=linkedin" /></a>
  <a href="https://abidjeem.com"><img src="https://img.shields.io/badge/Portfolio-abidjeem.com-000000?style=flat&logo=vercel" /></a>
  <a href="mailto:ajeem@mail.wlu.edu"><img src="https://img.shields.io/badge/Email-ajeem@mail.wlu.edu-EA4335?style=flat&logo=gmail" /></a>
  <img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat&logo=amazonaws" />
</p>

---

## 🧠 What I Build

I specialize in making ML systems **fast, scalable, and production-ready** — from profiling and optimizing inference pipelines to building data-intensive workflows on cloud infrastructure. My work lives at the intersection of systems-level performance engineering and applied AI.

- **ML Inference & Optimization** — JIT compilation (Numba), vectorization, flamegraph profiling, pipeline benchmarking on AWS EC2/S3
- **Data Engineering** — large-scale simulation pipelines, labeled dataset construction (120k+ events), S3-backed streaming workflows
- **AI Systems & RAG** — LLaMA-3 inference, vector search (FAISS/ChromaDB), retrieval-augmented generation, mechanistic interpretability
- **Scientific HPC** — high-throughput physics simulations, reproducible research pipelines, AWS-benchmarked compute workflows

---

## 🚀 Projects

### ⚡ [Northstar — Low-Latency Gravitational-Wave Localization](https://github.com/tjamcclain2/Northstar-Python-)
`Python` `Numba` `NumPy` `AWS EC2/S3` `Random Forest` `scikit-learn` `cProfile` `flamegraphs`

> **46.7× inference speedup** on a physics localization pipeline — the kind of optimization that matters at scale.

- Inherited an O(n³) algorithm; profiled with cProfile + flamegraphs, then restructured via **vectorization, JIT compilation (Numba), and antenna-pattern caching** — reducing runtime from **43s → 0.92s per 100 events**
- Benchmarked the pipeline on **AWS EC2 (t3.medium) vs. local hardware** across 10k+ simulated events; streamed outputs to **S3** to support large-scale ML training runs
- Built a **120k-injection labeled dataset** and trained a Random Forest model to learn the optimal sky-localization exponent, minimizing RMS residuals between predicted and true sky positions
- Engineered a **real-time lookup table** for model inference and designed a reproducible profiling toolkit (flamegraphs, SnakeViz) for non-technical handoff
- *Manuscript in preparation · Presented at APS Global Physics Summit 2026, Denver*

---

### 🏥 [Clinical RAG Pipeline — Letters of Medical Necessity](https://github.com/ajeem2026/AI_Research/tree/main/lomn-rag)
`Python` `LLaMA-3` `LangChain` `FAISS` `ChromaDB` `RAG` `Mechanistic Interpretability`

> End-to-end **LLM inference pipeline** with auditable, citation-traced outputs — built for high-stakes clinical documentation.

- Engineered a **RAG system** (local LLaMA-3 + vector search) that queries clinical guidelines and prior letters before generating insurance documentation — exposing retrieved sources and how they shaped each section
- Implemented **mechanistic interpretability modules**: citation tracing, contrastive "what-if" prompts, and failure-mode probes to audit model reasoning
- Modeled stakeholder personas to evaluate how transparency tooling enables social recourse in denied insurance cases
- *Research advised by Dr. Upol Ehsan (Northeastern University) — extending his Social Transparency framework to clinical AI*

---

### 🌡️ [Ground Heat Exchanger — Finite Element Modeling](https://github.com/ajeem2026)
`Python` `COMSOL Multiphysics` `FEA` `NumPy` `SciPy` `Data Pipelines`

- Collected field data from a 10-meter hand-augered borehole; built a **transient FEM heat transfer model** in COMSOL calibrated against experimental measurements
- Developed a data pipeline to analyze subsurface temperature evolution and evaluate GHX sizing efficiency under varying soil/climate conditions
- *Co-authored IEEE GEC 2024 · Presented at AGU Annual Meeting 2023 (San Francisco) and invited talk at Shenandoah Undergraduate Math & Stats Conference*

---

### 🧮 [Quantum Annealing for TSP](https://github.com/ajeem2026/TSP-DWave)
`Python` `D-Wave Ocean SDK` `QUBO` `Quantum Optimization`

- Formulated the Traveling Salesman Problem as a **QUBO instance** and mapped it onto the D-Wave quantum annealer
- Investigated quantum vs. classical optimization tradeoffs for NP-hard combinatorial problems

---

### 🐧 [Linux From Scratch](https://github.com/ajeem2026)
`Bash` `GCC` `Make` `Systemd` `Linux Systems`

- Built a fully functional Linux distribution from source — compiled core system components, configured Systemd for service management, and constructed a minimal package-less OS architecture

---

## ⚙️ Technical Skills

### 🔥 Inference & Performance Engineering
`Numba (JIT)` `Vectorization` `cProfile` `Flamegraphs` `SnakeViz` `Pipeline Benchmarking` `AWS EC2/S3`

### 📦 ML & AI Systems
`PyTorch` `scikit-learn` `Random Forests` `LLaMA-3` `RAG Pipelines` `FAISS` `ChromaDB` `LangChain` `Mechanistic Interpretability`

### 🗄️ Data Engineering
`Large-scale Simulation Pipelines` `Labeled Dataset Construction` `S3 Data Streaming` `NumPy` `SciPy` `Reproducibility Workflows`

### ☁️ Cloud & Infrastructure
`AWS EC2` `S3` `Bedrock` `OpenSearch` `CloudFront` `WAF` · **AWS Certified Cloud Practitioner (CLF-C02)**

### 💻 Languages
`Python` `C/C++` `Bash` `Assembly` `Java` `LaTeX`

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
  <i>Open to new grad SWE and ML Engineer roles for Summer/Fall 2026. Let's build something fast.</i><br><br>
  <a href="https://linkedin.com/in/profjeem">LinkedIn</a> · <a href="https://abidjeem.com">Portfolio</a> · <a href="mailto:ajeem@mail.wlu.edu">Email</a>
</p>
