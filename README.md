# Hi, I'm Wong Anne 👋

**Backend & Applied AI Engineer | Java · Python · Distributed Systems**

I'm a software engineer building reliable backend systems and AI-powered applications.

My professional experience is in **B2B commerce, cross-border logistics, and backend engineering**, where I work on order processing, data synchronization, asynchronous workflows, and operational reliability.

Outside of work, I build and open-source projects focused on **payment infrastructure, distributed systems, and production-oriented AI agents**.

I'm particularly interested in engineering problems where correctness, reliability, and real-world constraints matter more than just making the happy path work.

## What I've Built

### 💳 [Payments Ledger Platform](https://github.com/WongAnneLister/Payments-ledger-platform)

**Java 21 · Spring Boot · PostgreSQL · Redis · Kafka · Stripe**

A payment processing and double-entry accounting platform built to explore the engineering challenges behind reliable financial systems.

- Designed an immutable double-entry ledger with database-enforced financial invariants and controlled balance updates.
- Implemented payment and refund workflows, idempotency, webhook processing, reconciliation, payouts, and failure recovery.
- Built a modular monolith with separate API and worker roles, transaction boundaries, and asynchronous merchant notifications.
- Developed property-based and concurrency tests, including 42 fault-injection scenarios covering duplicate and out-of-order webhooks, provider timeouts, process crashes, and messaging failures.
- Documented recovery procedures, architectural decisions, and verification evidence.

**Verification:** 748 regression tests passed in the documented PR20 run. Full performance acceptance remains incomplete.

[Repository →](https://github.com/WongAnneLister/Payments-ledger-platform)

### 🎙️ [Interview Agent](https://github.com/WongAnneLister/Interview-Agent)

**Python · FastAPI · LiveKit · Next.js · PostgreSQL · Langfuse**

An AI-powered voice mock-interview application designed around role-specific interviewing and evidence-based feedback.

- Designed a two-layer architecture separating low-latency interviewing from background evaluation.
- Built backend infrastructure for resume processing, structured data extraction, and user-scoped data access.
- Implemented LLM usage tracking, cost estimation, budget checks, and observability integrations.
- Added automated testing, database migrations, and reproducible development workflows.

**Status:** Active development (v0). Currently designed for local, single-user operation.

[Repository →](https://github.com/WongAnneLister/Interview-Agent)

### 📝 [Paperlane — Personal Blog](https://github.com/WongAnneLister/MyBlog)

**Next.js · TypeScript · Hono · Docker**

A self-hosted technical blog and portfolio.

Built with a Next.js frontend, Hono API, S3-compatible object storage, and containerized deployment.

[Repository →](https://github.com/WongAnneLister/MyBlog) · [Visit Blog →](https://blog.michikatsu.top/)

## Open Source Contributions

I contribute bug fixes to open-source infrastructure and developer tools, particularly in AI systems and backend engineering.

**Merged contributions**

- **[LiteLLM — Provider routing fix](https://github.com/BerriAI/litellm/pull/36346)**  
  Fixed explicit provider handling across asynchronous image, audio, and realtime routes.

- **[Alibaba Canal — Windows startup script fix](https://github.com/alibaba/canal/pull/5573)**  
  Removed a duplicated string in the Windows startup script.

I also explore and contribute fixes around LLM tool calling, MCP integration, and cross-platform compatibility.

## Engineering Experience

### Software Engineer @ GigaCloud

**B2B Commerce · Cross-border Logistics · Backend Systems**

I work on backend services supporting an international B2B commerce platform and its logistics and operational workflows.

Some of the engineering problems I've worked on include:

- **Large-scale data synchronization:** Built a recoverable synchronization workflow for European order history, processing approximately 1 million orders and over 3 million shipment records during a production migration.
- **Asynchronous processing:** Used message queues, scheduled jobs, state transitions, and retry mechanisms to coordinate multi-step business workflows.
- **Data consistency and recovery:** Worked with idempotency, failure handling, and reconciliation of business data across internal and external systems.
- **Operational reliability:** Improved observability, error handling, and recovery processes for backend integrations.

My primary production stack includes Java, Spring Boot, MyBatis-Plus, MySQL/OceanBase, Redis, RabbitMQ, and scheduled job infrastructure.

## Technical Focus

| Area | Technologies & Concepts |
|---|---|
| **Backend** | Java, Spring Boot, Python, FastAPI, REST APIs |
| **Data & Messaging** | PostgreSQL, MySQL, OceanBase, Redis, RabbitMQ, Kafka |
| **Distributed Systems** | Transactions, Idempotency, Outbox Pattern, State Machines, Failure Recovery |
| **Applied AI** | RAG, AI Agents, Tool Calling, LLM APIs, Evaluation, Observability |
| **Full-stack** | TypeScript, React, Next.js, Hono |
| **Infrastructure** | Docker, Linux, GitHub Actions, CI/CD, Prometheus, Grafana |

## How I Approach Engineering

I care about building systems that remain understandable and recoverable when things go wrong.

My approach emphasizes:

- **Correctness before performance:** Define invariants and failure behavior before optimizing throughput.
- **Explicit failure handling:** Design for retries, duplicates, partial failures, and uncertain outcomes.
- **Evidence over assumptions:** Use automated tests, reproducible experiments, and observable metrics to validate behavior.
- **Pragmatic architecture:** Choose complexity based on actual requirements, not trends.
- **AI-assisted development with engineering ownership:** Use AI tools to accelerate implementation while treating design decisions, verification, and maintainability as engineering responsibilities.

## Currently Exploring

- Reliable AI agent infrastructure and LLM evaluation
- Payment systems, financial ledgers, and distributed transactions
- Open-source contributions to AI and developer infrastructure
- Technical writing and sharing engineering lessons

## Connect

- 📝 **Blog:** [blog.michikatsu.top](https://blog.michikatsu.top/)
- 𝕏 **X / Twitter:** [@WongAnneLister](https://x.com/WongAnneLister)
- ✉️ **Email:** [wongannelister@gmail.com](mailto:wongannelister@gmail.com)

**Open to remote backend engineering and applied AI engineering opportunities.**
