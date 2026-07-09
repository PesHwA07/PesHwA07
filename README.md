<div align="center">

# ✨ DHANANJAY NAIKNAWARE — AI/ML Engineer, Data Scientist & LLM Systems Builder ✨

![](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=🤖+Building+Agentic+RAG+Systems;🧠+LLM+Fine-Tuning+%26+Multi-Agent+Orchestration;⚙️+From+Notebook+to+Production)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhananjay-naiknaware-a273982b8/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PesHwA07)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)

</div>

---

## 🎯 About Me

I'm a Computer Science undergrad (B.Tech, expected June 2026) building systems that go
beyond "train a model in a notebook" — self-critiquing RAG pipelines, multi-agent
orchestration, and LLM fine-tuning, with a growing focus on the production side:
evaluation, guardrails, and deployment.

- 🛰️ **Currently working on:** a self-critiquing RAG system (LangGraph) — retrieval +
  generation with a critic agent that catches hallucinations and reformulates queries
  instead of guessing, wrapped in guardrails and gated by an automated eval CI/CD pipeline
- 🧑‍🤝‍🧑 **Looking to collaborate on:** agentic AI / LLM systems projects — multi-agent
  orchestration (LangGraph, Deep Agents, CrewAI), RAG pipelines, or anything at the
  intersection of ML and production engineering
- 🥅 **Looking for help with:** MLOps and cloud deployment — Kubernetes, hands-on AWS/GCP
  experience, and scaling LLM systems past a single free-tier API
- 🌱 **Currently learning:** Deep Agents, MCP (Model Context Protocol), vector-less
  retrieval, and Apache Airflow for orchestrating data pipelines
- 💬 **Ask me about:** RAG architecture, LLM fine-tuning (QLoRA/LoRA), or agent framework
  trade-offs — I've built with more than one (LangGraph vs. CrewAI) and have opinions
- ⚡ **Fun fact:** I built a custom Elo-style rating system from scratch in JAX — because
  sometimes the fastest way to actually understand an algorithm is to stop calling the
  library and implement the math yourself

---

## 🔭 Current Focus Areas

<table>
<tr>
<td width="50%" valign="top">

### 🧠 LLM Applications
- Prompt design that fights generic output — explicit anti-genericism constraints,
  proven in a deployed marketing-report generator
- Multi-provider model routing (Groq ⇄ Ollama) behind one interface
- QLoRA fine-tuning under real memory/session constraints (CodeLlama-7B, 4-bit NF4)
- Cost-aware design: caching and tiered eval to stay within free-tier rate limits

</td>
<td width="50%" valign="top">

### 🔗 RAG & Knowledge Systems
- Groundedness critique — a second model checks if the answer is actually supported
  by retrieved chunks, before it reaches the user
- Dense retrieval (ChromaDB, Qdrant) *and* sparse/vector-less retrieval (BM25) —
  chosen deliberately per use case, not defaulted to embeddings
- Query reformulation on retrieval failure, instead of silent hallucination

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AI Agents & Orchestration
- Multi-agent systems across three different mental models: LangGraph (explicit state
  graphs), CrewAI (role-based crews), Deep Agents (planning + sub-agents)
- Tool-using agents with real fallback behavior — an agent that says "I don't know"
  instead of guessing
- Comparing frameworks firsthand, not just reading about them

</td>
<td width="50%" valign="top">

### ⚙️ Evaluation & Production Engineering
- Golden-dataset evaluation (100+ Q&A pairs) with hallucination-rate, latency, and
  cost tracked per commit
- CI/CD gating — GitHub Actions blocks a merge if quality regresses
- Experiment tracking (Weights & Biases), containerized deployment (Docker + FastAPI)

</td>
</tr>
</table>

### 📁 Repos
[`guarded-rag-system`](#) · [`marketing-system`](#) · [`ideal-ai-ide`](#) ·
[`codellama-qlora-finetune`](#) — links live once each repo is pushed public

---

## 🛠️ Tech Stack

<div align="center">

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

### 🤖 ML / Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-4285F4?style=flat-square&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### 🔗 LLM / Agent Frameworks
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

### 🗄️ Data & Vector Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)

### 🔧 Tools & Platforms
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

### 🌱 Currently Learning
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

</div>

---

## 🎓 Learning & Expertise

### 🧩 Skills, Backed by Receipts
*(no buzzword bingo — every skill below is tied to something you can actually click into)*

| Skill | Proven in |
|---|---|
| **RAG Architecture & Groundedness** | Guarded Self-Critiquing RAG System — critic agent + reformulate/fallback loop |
| **Multi-Agent Orchestration** | LangGraph (stateful graphs) · Deep Agents (planning) · CrewAI (role-based crews) |
| **LLM Fine-Tuning** | QLoRA on CodeLlama-7B — 4-bit NF4, LoRA rank 64, checkpointed across Colab sessions |
| **Eval & LLMOps** | 100+ question golden dataset, hallucination-rate CI gating, W&B experiment tracking |
| **Vector & Vector-less Retrieval** | ChromaDB/Qdrant (dense) alongside BM25 (sparse) — chosen deliberately, not by default |
| **Applied ML Beyond LLMs** | Random Forest/Logistic Regression evaluation, custom Elo rating system built from scratch in JAX |
| **Real-World Deployment** | Docker + FastAPI, and a live, deployed marketing-intelligence tool doing real web-grounded research |

### 🔭 Where I'm Headed Next
- Closing the gap between "works in a demo" and "survives production" — Kubernetes,
  cloud-hosted deployments, drift monitoring
- MCP (Model Context Protocol) as the emerging standard for how agents reach tools
- Reranking and hybrid retrieval — going past "retrieval exists" to "retrieval is actually good"
- Orchestrated, scheduled data pipelines (Apache Airflow) as the backbone under any ML system

### 🌍 Why I Build
Most "AI projects" stop at a notebook that works once. I'm more interested in the harder,
less glamorous half: does it fail gracefully, can you tell when it's wrong, and will it
still work after the tenth deploy? That's the thread running through everything above —
building things that are honest about their own limitations, not just impressive in a demo.

---

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=PesHwA07&theme=dark&show_icons=true)

---

## 💬 Let's Connect

I'm always happy to talk RAG architecture, agent framework trade-offs, or fine-tuning —
reach out if you're working on something similar or want to collaborate.

- 📧 Email: dnaiknaware.work@gmail.com
- 💼 LinkedIn: [Connect on LinkedIn](https://www.linkedin.com/in/dhananjay-naiknaware-a273982b8/)
- 🐙 GitHub: [Follow on GitHub](https://github.com/PesHwA07)

