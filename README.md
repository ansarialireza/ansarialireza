# Alireza Ansari

<div align="center">
  <img src="assets/hero-banner.svg" alt="Alireza Ansari -- Full-Stack Software Engineer" width="100%" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/ansarialireza">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://ansarialireza.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-212830?style=flat&logo=google-chrome&logoColor=CCFF00" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="mailto:anssrza@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

Full-Stack Software Engineer focused on building resilient web applications, distributed backend services, and production RAG (Retrieval-Augmented Generation) systems.

---

### Focus & Core Strengths

- **Full-Stack Engineering**: Developing responsive web clients, robust REST APIs, and database-backed services using Python, Django, FastAPI, React, and Next.js.
- **AI & Retrieval Systems**: Designing multi-tenant vector retrieval pipelines with PostgreSQL and `pgvector`, modular chunking engines, and structured tool orchestration.
- **System Discipline**: Prioritizing explicit data boundaries, automated testing, containerized reproducibility, and maintainable domain architecture.

---

### Selected Projects

#### [Weirwise RAG Core](https://github.com/ansarialireza/weirwise-rag-core)
> **Open-Source Modular RAG & Knowledge Retrieval Infrastructure**
> *Python · FastAPI · PostgreSQL · pgvector · Alembic · Docker · pytest*

A self-hostable headless backend for AI knowledge retrieval. Ingests documents, extracts text, generates vector embeddings, and performs native PostgreSQL + pgvector similarity search with strict multi-tenant isolation.

- **Multi-Tenant Isolation**: Strict boundaries across tenants, knowledge bases, documents, and query runs.
- **PostgreSQL / pgvector Retrieval**: Direct vector similarity search using Jina AI `jina-embeddings-v4` (1536 dimensions) without external vector database lock-in.
- **Robust Ingestion Pipeline**: Asynchronous and inline extraction for PDF, DOCX, TXT, and Markdown documents with SHA-256 API authentication.

#### [Weirwise RAG Platform](https://github.com/ansarialireza/weirwise-rag-platform)
> **Full-Stack Enterprise AI Assistant & Knowledge Platform**
> *FastAPI · Next.js 14 · TypeScript · Tailwind CSS · SQLite/PostgreSQL · Docker*

The complete customer-facing product layer built on Weirwise Core, enabling teams to organize knowledge sources, configure domain-specific AI assistants, and converse with grounded citation verification.

- **Assistant Studio**: Configure system instructions, temperature, and score thresholds with interactive real-time chat playgrounds.
- **Knowledge Grounding**: Multi-file document upload with status tracking, verifiable citation attribution, and tenant-scoped retrieval.
- **Client Application**: Responsive Next.js 14 web application featuring full workspace onboarding, project routing, and authenticated sessions.

---

### Tech Stack

| Area | Tools & Technologies |
| :--- | :--- |
| **Backend & APIs** | Python, Django, Django REST Framework, FastAPI, Alembic, Pydantic |
| **AI & Retrieval** | RAG Architectures, PostgreSQL `pgvector`, Document Chunking, Vector Similarity Search |
| **Frontend & UI** | TypeScript, JavaScript, React, Next.js, Tailwind CSS, Web Components (Shadow DOM) |
| **Storage & Data** | PostgreSQL, Redis, Relational Data Modeling, Schema Migrations |
| **DevOps & Tooling** | Docker, Docker Compose, Git & GitHub Actions, pytest, Ruff, Linux / WSL |

---

### Connect

- **LinkedIn**: [linkedin.com/in/ansarialireza](https://linkedin.com/in/ansarialireza/)
- **Portfolio**: [ansarialireza.github.io](https://ansarialireza.github.io/)
- **Email**: [anssrza@gmail.com](mailto:anssrza@gmail.com)
