# Ricci Juaman | AI Engineer

**Production AI Systems | RAG Architectures | Full-Stack Development**

📍 Brisbane, Queensland, Australia  
📧 juamandudz1590@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/ricci-doddz-juaman)  
🔓 **Open to opportunities** | Available immediately

---

## 👋 About Me

I'm an AI Engineer specializing in production RAG (Retrieval-Augmented Generation) systems with full-stack capabilities. I build end-to-end AI applications from architecture design through deployment, with experience in both custom implementations and enterprise-scale solutions.

**What makes me different:**
- 🔧 Built RAG systems from scratch AND with enterprise tools (understand both approaches)
- 🏗️ Full-stack: Backend (Python, FastAPI, PostgreSQL) + Frontend (React) + DevOps (CI/CD, Azure)
- 💰 Cost-conscious: Evaluate build vs buy tradeoffs based on business requirements
- 🤝 Community: Active in Brisbane AI community, mentor software engineers transitioning to AI/ML
- 📊 Business-minded: 5+ years solving real-world problems in pricing strategy, analytics, and data

---

## 🚀 Featured Projects

### 1. Custom Full-Stack RAG System with Hybrid Search
**Production-grade retrieval system built from first principles**

[![GitHub](https://img.shields.io/badge/GitHub-View_Code-blue?logo=github)](https://github.com/RicciJuaman/faiss-vector-database)


**Tech Stack:** Python • React • FAISS • PostgreSQL • FastAPI • BGE-Large • BM25 • Azure • CI/CD

#### What I Built:
- **Custom Vector Database:** Built from scratch using FAISS with BGE-Large embeddings
- **Hybrid Search Engine:** Combined semantic similarity (vector search) with lexical matching (BM25) for superior retrieval accuracy
- **Full-Stack Application:** React frontend with real-time search + FastAPI backend + PostgreSQL metadata layer
- **Production Infrastructure:** CI/CD pipelines, automated testing, monitoring, deployment on Azure

#### Architecture:
<img width="2048" height="1246" alt="image" src="https://github.com/user-attachments/assets/7ada9365-41ee-4c08-9d80-99cd91e9716c" />


#### Key Technical Decisions:

**Why build custom instead of using Pinecone/Weaviate?**
- **Cost optimization:** ~$0/month vs $500+/month for managed services
- **Learning objective:** Deep understanding of vector search, embedding models, retrieval algorithms
- **Control:** Fine-grained tuning of hybrid search weights and retrieval strategies

**Why hybrid search (semantic + lexical)?**
- Pure semantic search fails on exact matches (names, codes, acronyms)
- Pure keyword search misses conceptual queries
- Hybrid approach handles both: "What is inclusive teaching?" (semantic) AND "Policy code 234B" (lexical)

**Performance:**
- 📄 50000 documents indexed
- ⚡ <4s average query latency - (Can be improved)
- 🎯 ~85% retrieval accuracy (measured on test queries)
- 💾 Efficient memory usage with FAISS IVF indexing

#### What This Demonstrates:
✅ Understanding of embedding models and vector search fundamentals  
✅ Algorithm implementation (BM25, score fusion, ranking)  
✅ Full-stack development (frontend, backend, database)  
✅ Production engineering (testing, CI/CD, deployment)  
✅ Cost-benefit analysis and architectural decision-making  

---

### 2. Enterprise Azure RAG System
**Production AI solution for Queensland Education Department**

[![GitHub](https://img.shields.io/badge/GitHub-Architecture_Docs-blue?logo=github)](YOUR_AZURE_DOCS_URL)
📸 <img width="1330" height="596" alt="Screenshot 2025-12-26 084820" src="https://github.com/user-attachments/assets/8b7aed1a-feeb-45b2-94c7-fb27781172b1" />


**Tech Stack:** Azure AI Search • Azure OpenAI • Document Intelligence • Blob Storage • Python • Skillsets

#### What I Built:
- **Enterprise RAG Architecture:** Production-ready system using Azure's managed AI services
- **Document Intelligence Pipeline:** Automated document cracking, parsing complex formats (PDF, HTML, DOCX)
- **Smart Chunking Strategy:** Skillset-based chunking with overlap for context preservation
- **Compliance-Aware:** Built for government sector with data sovereignty and audit requirements
- **Automated Workflows:** End-to-end pipeline from document upload to searchable knowledge base

#### System Flow:
```
Documents Upload (Blob Storage)
       ↓
Document Intelligence
(Crack, Parse, OCR)
       ↓
Azure AI Search Skillset
(Chunk, Embed, Enrich)
       ↓
Hybrid Index
(Vector + Keyword + Semantic)
       ↓
Azure OpenAI Integration
       ↓
Responses with Citations
```

#### Key Technical Decisions:

**Why Azure managed services instead of custom?**
- **Enterprise requirements:** Compliance, SLA guarantees, data sovereignty for government sector
- **Time to market:** Document Intelligence handles complex parsing (PDFs, forms) that would take weeks to build
- **Scalability:** Managed infrastructure handles load spikes automatically
- **Maintenance:** Azure manages updates, security patches, infrastructure

**Chunking Strategy:**
- Fixed-size chunking (current): 512 tokens with 128 token overlap
- Semantic chunking (planned): Chunk by document structure (sections, subsections) for legal documents
- Trade-offs evaluated: Speed vs accuracy, context preservation vs index size

**Performance:**
- 📄 7 HTML files → 1,320 chunks (demonstrates pipeline scalability)
- ⏱️ ~3 seconds query latency on free tier (sub-second on paid tier)
- 🔍 Hybrid ranking: Vector + keyword + semantic reranking
- 📚 Ready to scale to 100K+ documents

#### What This Demonstrates:
✅ Enterprise architecture and managed service expertise  
✅ Azure AI stack proficiency (AI Search, OpenAI, Document Intelligence)  
✅ Document processing and ETL pipeline design  
✅ Compliance and governance awareness  
✅ Evaluation of build vs buy tradeoffs  

---

### 3. Legal RAG System (In Development)
**Domain-specific RAG with document structure chunking**

**Tech Stack:** Python • Azure AI Search • Custom Chunking Logic • Queensland Legislation

#### Planned Features:
- **Hierarchical Chunking:** Preserve legal document structure (Act → Part → Division → Section)
- **Citation Accuracy:** Critical for legal applications - track exact sources
- **Cross-Reference Linking:** Connect related statutes and precedents
- **Jurisdiction Awareness:** Handle Queensland vs Federal legislation distinctions

#### Why Legal RAG is Complex:
Legal documents require specialized handling that generic RAG can't provide:
- 📋 **Structure matters:** A section means nothing without its parent Act context
- 🎯 **Citation precision:** Lawyers need exact sources, not "approximately from X"
- 🔗 **Relationships:** Statutes reference each other, amendments supersede originals
- ⚖️ **Jurisdiction:** Same topic, different rules by state/federal level

**Target Timeline:** Q1 2026  
**Goal:** Portfolio piece demonstrating domain specialization

---

## 🛠️ Technical Skills

### AI/ML
- **RAG Systems:** Architecture, implementation, evaluation, optimization
- **Vector Databases:** FAISS (custom implementation), Azure AI Search, Pinecone (familiar)
- **Embeddings:** BGE-Large, E5, OpenAI, Cohere (model selection and benchmarking)
- **Search Algorithms:** Hybrid search, BM25, semantic search, reranking strategies
- **LLMs:** Azure OpenAI, prompt engineering, response generation, citation handling

### Backend & Data
- **Languages:** Python (production-level), SQL, JavaScript
- **Frameworks:** FastAPI, Flask, LangChain, LlamaIndex
- **Databases:** PostgreSQL (schema design, optimization), SQL querying, indexing strategies
- **APIs:** RESTful API design, endpoint development, documentation

### Frontend
- **Frameworks:** React, JavaScript, HTML/CSS
- **UI/UX:** Real-time search interfaces, data visualization, responsive design

### Cloud & DevOps
- **Azure:** AI Search, OpenAI, Blob Storage, Document Intelligence, deployment
- **CI/CD:** GitHub Actions, automated testing, deployment pipelines
- **Tools:** Docker, Git/GitHub, pytest, monitoring/logging

### Data & Analytics
- **Experience:** 5+ years in data analytics, pricing strategy, business intelligence
- **Skills:** Statistical modeling, A/B testing, ETL pipelines, data visualization
- **Tools:** Python (pandas, numpy), SQL, Salesforce, Power BI

---

## 💼 Professional Experience Highlights

### Shiply | Pricing Strategy Manager
*March 2024 - Present | Remote (UK)*

Applied data-driven approaches to pricing optimization:
- Design and execute A/B tests for pricing experiments
- Build analytical pipelines and predictive models for price elasticity
- Collaborate with engineering on API integration and data infrastructure
- Translate complex analysis into executive-level insights

**Relevance to AI Engineering:** Statistical testing, model evaluation, API integration, stakeholder communication

### Acrewell | Data Analyst  
*July 2022 - November 2023 | Philippines*

Property valuation and analytics for land acquisition:
- Multi-criteria evaluation (accessibility, topography, utilities, soil type)
- Comparative analysis for pricing precision
- Built reports and dashboards in Salesforce
- Proactive research with county offices for due diligence

**Relevance to AI Engineering:** Multi-modal data evaluation, risk assessment, system integration

### Radarr (Genesys) | Data Analyst
*March 2022 - June 2022 | Singapore*

Social listening platform - ETL, analysis, and visualization:
- Full data lifecycle management
- Pattern recognition in noisy data (signal vs noise)
- Cross-functional collaboration with product teams

**Relevance to AI Engineering:** Data pipeline design, noise handling (critical for RAG retrieval quality)

---

## 🎓 Education & Continuous Learning

**Bachelor of Arts - Philosophy** | Notre Dame of Marbel University  
*2008 - 2012*

Philosophy training provides:
- First-principles thinking and problem decomposition
- Logical reasoning and argument construction  
- Abstract pattern recognition across domains
- Meta-learning skills (learning how to learn)

**Google Professional Data Analytics Certificate** | Coursera  
*2021 - 2022*

**Self-Directed AI/ML Learning:**
- RAG systems, vector databases, embeddings, LLMs
- Full-stack development (React, FastAPI, PostgreSQL)
- Azure AI services, DevOps, CI/CD pipelines
- Built production systems while learning (learning by doing)

---

## 🤝 Community & Collaboration

### Brisbane AI Community
- **Mentorship:** Guide software engineers transitioning into AI/ML roles
- **Collaboration:** Currently working with QUT software engineers on production AI projects
- **Knowledge Sharing:** Regular discussions on RAG architectures, vector databases, retrieval optimization
- **Engagement:** 4+ engineers have reached out for advice and guidance on AI career transitions

### Why This Matters:
- 💡 Teaching solidifies understanding (Feynman technique)
- 🌐 Active local network (Brisbane tech community)
- 🤝 Demonstrates collaboration and communication skills
- 📈 Others seek my expertise (validation of knowledge)

---

## 📝 Technical Writing & Content

### Planned Articles (Q1 2026):
1. **"Building a Production RAG System: Custom vs Enterprise"** - Architecture decisions, cost analysis, tradeoffs
2. **"Hybrid Search Explained: When Semantic Search Isn't Enough"** - Technical deep-dive with benchmarks
3. **"Legal RAG: Why Document Structure Matters"** - Domain-specific RAG challenges

### Why Writing Matters:
- Demonstrates communication skills (critical for senior roles)
- Solidifies technical understanding through teaching
- Builds personal brand and visibility
- Contributes to broader AI engineering community

---

## 🎯 What I'm Looking For

**Role:** AI Engineer or ML Engineer (mid to senior level)  
**Location:** Brisbane preferred, open to Sydney/Melbourne, remote considered  
**Type:** Full-time, contract, or contract-to-hire

**Ideal Environment:**
- 🚀 Building production AI products (not just research/POCs)
- 🏗️ Architecture decisions and technical ownership
- 🤝 Collaborative team that values knowledge sharing
- 📈 Growth opportunities and technical challenges
- 🎓 Learning culture and mentorship (both ways)

**What I Bring:**
- Production RAG experience (custom + enterprise)
- Full-stack capabilities (ship complete features)
- Cost-conscious engineering (build vs buy thinking)
- Business context (5+ years solving real problems)
- Mentorship and collaboration skills
- Self-directed learning and adaptability

---

## 📬 Let's Connect

**I'm actively seeking opportunities and happy to discuss:**
- RAG system architectures and implementation challenges
- Vector database tradeoffs (custom vs managed)
- AI engineering career transitions and mentorship
- Brisbane AI community events and collaboration

**Fastest response:**
- 📧 Email: juamandudz1590@gmail.com
- 💼 LinkedIn: [linkedin.com/in/ricci-doddz-juaman](https://www.linkedin.com/in/ricci-doddz-juaman)
- 📱 Phone: +61 494 376 293

**Portfolio & Projects:**
- 🔗 This Portfolio: `ricci-juaman.github.io/portfolio` (you're here!)
- 💻 GitHub: [[github.com/RicciJuaman](https://github.com/RicciJuaman)]

---

## 🏆 Quick Stats

```
📊 Production RAG Systems Built:        2 (custom + enterprise)
💻 Lines of Code (estimated):           15,000+
🏗️ Full-Stack Features Shipped:         Multiple (frontend + backend + AI)
👥 Engineers Mentored:                  4+
📈 Years in Data/Analytics:             5+
🎓 Self-Directed Learning Projects:     10+ (RAG, vector DBs, full-stack, cloud)
☁️ Cloud Platforms:                     Azure (production), AWS (learning)
```

---

## 📌 Pinned Repositories

### [custom-rag-system](YOUR_REPO_URL)
Full-stack RAG with FAISS, hybrid search, React UI, PostgreSQL. Production-grade retrieval system built from scratch.

### [azure-enterprise-rag](YOUR_REPO_URL)
Enterprise RAG using Azure AI Search, Document Intelligence, OpenAI. Built for Queensland Education Department.

### [legal-rag-prototype](YOUR_REPO_URL)
(In Development) Domain-specific RAG for legal documents with structure-aware chunking.

---

*Last Updated: December 28, 2024*

**⭐ If you find my work interesting, let's connect! I'm always happy to discuss RAG architectures, AI engineering, or grab coffee in Brisbane.**
