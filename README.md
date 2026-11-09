# Hi, I'm Ibrahim Goumrane 👋

**Freelance AI engineer in Casablanca, Morocco.** I build **RAG search over large document collections** (including Arabic), **AI agents** that act on what they find, and the **Google Cloud infrastructure** that runs both in production.

Engineering degree in AI & software engineering from **ENSAM Casablanca, ranked 1st in my class**. 14+ clients so far, from startups to OCP Group.

🌐 **[ibrahimgoumrane.dev](https://www.ibrahimgoumrane.dev)** · 💼 **[LinkedIn](https://www.linkedin.com/in/ibrahim-goumrane)** · ✉️ **ibrahimgoumrane01@gmail.com** · 📍 Available for freelance and full-time work

---

## 🧭 What I do

| | |
|---|---|
| 🔎 **Search & RAG** | Turning messy document collections into reliable answers: parsing, deduplication, chunking, embeddings, hybrid semantic + keyword search, reranking, and citations back to the source. |
| 🤖 **AI agents** | LangGraph agent graphs with human checkpoints, error recovery and tool calling; MCP servers that let Claude and other assistants use your data directly. |
| ☁️ **Cloud infrastructure** | Google Cloud as code with Terraform: Cloud Run, Cloud SQL + pgvector, Vertex AI, Workload Identity Federation, CI/CD. |
| 🧩 **Product engineering** | Full-stack platforms and integrations around the AI: Next.js, Spring Boot, FastAPI, Shopify / Odoo / HubSpot APIs. |

---

## 🏗️ Selected client work

Most of this lives in private client repositories, so each project links to a full case study.

- **[Arabic legal RAG for a Moroccan law firm](https://www.ibrahimgoumrane.dev/work/legal-rag/)** (2026): semantic search over **1.8 million passages** of Moroccan law (legislation, 191,000 court decisions, doctrine), mostly in Arabic. Answers in **~50 ms**, in French or Arabic, and is served to Claude as a **remote MCP connector** with six tools. *Postgres + pgvector (HNSW), Vertex AI embeddings, Cloud Run, Cloud SQL.*
- **[Multi-agent report platform at OCP Group](https://www.ibrahimgoumrane.dev/work/ocp/)** (2026): LangGraph agents that draft documentary-analysis reports, with every claim traced back to its source. **In production internally.** *LangGraph, FastAPI, Milvus, Qwen Embedding 4B, bge-reranker, React over WebSocket.*
- **Hybrid RAG platform on GCP for Seement** (2026, ongoing): Vertex AI RAG Engine paired with pgvector for filtered queries; the whole stack provisioned in **Terraform**, with GitLab CI authenticating through Workload Identity Federation (no service-account keys).
- **[Two-hour delivery engine for DITOCO](https://www.ibrahimgoumrane.dev/work/ditoco/)** (2026): eligibility decided at checkout in **under 300 ms (p95)** across Shopify, Odoo and Onfleet, on an event-sourced journal.
- **[Salvage-vehicle auction engine for Maroc Réforme](https://www.ibrahimgoumrane.dev/work/maroc-reforme/)** (2026): a four-role workflow and a custom auction engine, all enforced server-side with row-level locking.
- **[Prospecting automation for a craft brewery](https://www.ibrahimgoumrane.dev/work/pierron/)** (2026): a Python research orchestrator that scores prospects A+ to D, feeding HubSpot and Lemlist.
- **[Financial-health platform for FINANCIANA](https://www.ibrahimgoumrane.dev/work/financiana/)** (2025): a per-instrument formula interpreter, currency unification, balance-sheet extraction and generated Word reports.

---

## 📌 Open-source projects

| Project | What it does |
|---|---|
| [**RAG engine for websites**](https://github.com/ibrahimGoumrane/DataProject) | Scrapes a whole site (JS rendering), ranks with hybrid semantic + TF-IDF on FAISS, answers with an LLM, and exposes an MCP server. |
| [**Docling PDF extraction for RAG**](https://github.com/ibrahimGoumrane/llamaparse-vs-docling) | Complex PDFs to Markdown/JSON with tables, figures and vision-model descriptions, chunked for retrieval. |
| [**LangGraph agent**](https://github.com/ibrahimGoumrane/langraph) | Retrieval tools, conditional routing, memory, retries, human-in-the-loop approval and loop guards. |
| [**AI technical recruiter**](https://github.com/ibrahimGoumrane/langraphLearning) | Structured LLM extraction from CVs and job descriptions, with explainable, evidence-based scoring. |
| [**Web sales analytics pipeline**](https://github.com/ibrahimGoumrane/web_sales_analytic_pipeline) | Daily Airflow ETL of 1,000+ products into PostgreSQL, a Streamlit dashboard, and CI. |
| [**Business-card reader**](https://github.com/ibrahimGoumrane/CodeBarDetector) | OCR + LLM field extraction + YOLO QR-code fallback, exported to CSV. |

---

## 🛠️ Tools I use on real projects

**Agents & LLMs:** LangGraph · LangChain · Model Context Protocol · Claude · OpenAI · Gemini
**Retrieval:** pgvector · Milvus · FAISS · Vertex AI RAG Engine · Qwen Embedding · bge-reranker · Docling
**Cloud & DevOps:** Google Cloud (Cloud Run, Cloud SQL, Vertex AI, GCS) · Terraform · Docker · Kubernetes · GitLab CI · GitHub Actions · Linux · Nginx
**Backend:** Python · FastAPI · Java / Spring Boot · Node.js · Django · Laravel · PostgreSQL · MySQL · WebSockets · Event sourcing
**Data:** Apache Airflow · Apache Spark · n8n · Playwright · Selenium · spaCy
**Frontend:** React · Next.js · TypeScript · Tailwind CSS

---

## 🎓 Background

- **ENSAM Casablanca**: engineering degree, Artificial Intelligence & Software Engineering (2021–2026). **Ranked 1st in my class.**
- Graduation project deployed at **OCP Group**, where it is used internally.
- Presented **AutoGradeAI** (automated exam grading with OCR + LLMs) at ENSAM's AGIOS day.
- Languages: 🇲🇦 Arabic (native) · 🇫🇷 French (fluent) · 🇬🇧 English (fluent)

---

### 📬 Working on something with documents, search or agents?
Tell me about the documents, the question people need answered, and what makes today's answer unreliable: **ibrahimgoumrane01@gmail.com** · [ibrahimgoumrane.dev](https://www.ibrahimgoumrane.dev)
