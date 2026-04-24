# Paras Sondhi
**Freelance AI Backend Engineer | Open Source Contributor | Production RAG**

I build resilient, backend-driven AI systems. While my formal academic background is in Engineering at NIT Hamirpur, my daily execution is strictly focused on AI architecture, multi-agent orchestration, and fixing broken data ingestion pipelines. 

I don't build thin LLM wrappers. I build the heavy plumbing underneath.

🏆 **Top 5.58% Nationally in GATE Data Science & AI (IIT Guwahati, 2026)**

### 🛠 Core Stack
* **AI & Orchestration:** LangGraph, LangChain, Groq, Local LLMs (Ollama), HuggingFace
* **Backend & Processing:** Python, FastAPI, Pandas, SQL
* **Infrastructure:** ChromaDB, Docker, Render
* **Frontend:** Streamlit

---

### 🌐 Open Source Contributions

**[infiniflow/ragflow](https://github.com/infiniflow/ragflow) Core Contributor** | [Merged PR #14218](https://github.com/infiniflow/ragflow/pull/14218)
* Engineered and shipped the native Docling chunking and document parsing engine into RAGFlow's main branch.
* Resolved critical context-limit failures for enterprise pipelines by building a graceful fallback mechanism. Code reviewed and approved by core maintainers.

---

### 🚀 Shipped Architecture

**[Autonomous Research Agent](https://github.com/ParasSondhi/AutonomousResearchAgent)** | [🌐 Live App](https://getwellresearchedreport.streamlit.app/) | [▶️ Watch Demo](https://www.loom.com/share/ad7905b8e029476882c42ae648d7fa59)
* **What it is:** A decoupled, asynchronous research microservice currently live-deployed on Render.
* **The Heavy Lifting:** Built a Human-in-the-Loop (HITL) approval gate using LangGraph. The agent autonomously validates scraped web data, self-corrects failing searches, and lets users intercept queries before execution. It delivers structured PDF reports with zero client wait time.

**[Zero-Leakage Enterprise RAG](https://github.com/ParasSondhi/Enterprise-RAG-Agent)** | [▶️ Watch Demo](https://drive.google.com/file/d/1Ib78egf57JLCYflITnxK3eL06--PIfZ4/view?usp=drive_link)
* **What it is:** A 100% local, privacy-first pipeline that simultaneously queries unstructured PDFs and structured SQL databases.
* **The Heavy Lifting:** Engineered the entire stack locally using Ollama and HuggingFace embeddings to guarantee zero data leakage. Built dynamic Pandas pipelines to clean raw CSVs before SQL insertion, and wrote the routing logic to seamlessly flip between ChromaDB vector search and SQL queries based on user intent.

---

### 📬 Let's Connect
**Currently taking on freelance contracts (15-20 hrs/wk).** If your FastAPI or LangGraph backend is hitting rate limits or dropping context, I'd be happy to connect and see if I can help.

* [LinkedIn](https://www.linkedin.com/in/paras-sondhi-6648a525a/)
* **Email:** parassondhi10@gmail.com
