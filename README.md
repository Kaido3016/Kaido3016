# Ali El-Sayed Ali 👋

### AI Engineer · Applied AI · LLMs · RAG · Agentic AI · AI Platforms

I build **production-oriented AI systems** where models are only one part of the engineering problem.

My focus is applied AI engineering: turning LLMs, retrieval, agents, structured data, and multimodal models into software that is **secure, grounded, evaluated, observable, cost-aware, and maintainable**.

**Architecture → model integration → retrieval → orchestration → security → evaluation → observability → deployment**

---

## What I Build

- **LLM applications** — OpenAI, Amazon Bedrock, Gemini / Vertex AI, Azure OpenAI, Ollama, structured outputs
- **RAG systems** — hybrid/vector/semantic retrieval, grounding, citations, evidence handling
- **Agentic AI** — LangGraph, tool calling, bounded agent loops, MCP, workflow orchestration
- **AI security** — prompt-injection defense, authorization-aware retrieval, tenant isolation, SQL safety, secure file handling
- **AI evaluation** — regression datasets, retrieval metrics, groundedness, safety tests, latency/cost measurement
- **Document intelligence** — ingestion, extraction, evidence preservation, semantic search
- **Structured-data AI** — NL→SQL, deterministic routing, validation, read-only execution
- **Multimodal AI** — vision, speech, image generation, desktop/tool interaction
- **AI platforms** — FastAPI, PostgreSQL, Docker, Kubernetes, Terraform, CDK, CI/CD, cloud infrastructure

---

## Featured Projects

### 📊 QStock — Enterprise Inventory Intelligence Platform

**250+ users · Real operational application · AI-powered structured-data workflows**

QStock combines inventory management with a controlled natural-language interface to PostgreSQL. It uses deterministic routing and reusable SQL templates first, with controlled LLM assistance for harder queries.

**Highlights:** NL→SQL · English/French queries · SQL validation · read-only execution · prompt-injection defenses · grounded answers · AI regression testing · latency/token/cost instrumentation.

**Stack:** Python · FastAPI · PostgreSQL · OpenAI · Ollama · React · TypeScript · Docker

→ [View QStock](https://github.com/Kaido3016/QStock-Enterprise-Inventory-Intelligence-Platform)

### ☁️ AWS GenAI LLM Chatbot — Enterprise RAG & AI Security

Enterprise-oriented **AWS generative-AI chatbot and RAG platform**, built on the AWS sample architecture and extended with AI-specific security, evaluation, observability, file validation, and automated security tooling.

**Highlights:** Amazon Bedrock · SageMaker · OpenSearch · S3 · Cognito · Lambda · AppSync/GraphQL · React · multi-provider LLMs · RAG evaluation · prompt-injection/RAG-poisoning defense · citation controls · token/cost/latency observability · secure upload validation · CodeQL · Dependabot.

**Engineering work:** Added an A1–A6 hardening/evaluation layer around the original AWS sample, including a standard-library evaluation framework, retrieval-path prompt-injection defenses, redacted citations, AI cost/latency metrics, server-side file-signature and zip-bomb validation, and security automation.

**Verification:** 211/211 tests passing locally across A1–A6. The repository explicitly distinguishes locally verified implementation from AWS-account-dependent deployment/runtime verification.

**Stack:** AWS · Amazon Bedrock · SageMaker · OpenSearch · S3 · Cognito · Lambda · AppSync · CDK · Python · TypeScript · React · Jest · CodeQL · Dependabot

→ [View AWS GenAI LLM Chatbot](https://github.com/Kaido3016/aws-genai-llm-chatbot)

### ☁️ AzureBot — Enterprise RAG Engineering Platform

Azure-based RAG focused on **authorized evidence rather than unconstrained model knowledge**. The repository began from Microsoft's `azure-search-openai-demo`; the portfolio work adds enterprise RAG controls, evaluation, security hardening, and architecture while retaining attribution/licensing.

**Highlights:** Azure OpenAI · Azure AI Search · hybrid/vector/semantic retrieval · fail-closed ACLs · citation-first generation · abstention · indirect prompt-injection defense · retrieval/groundedness/citation/authorization evaluation · telemetry · IaC.

→ [View AzureBot](https://github.com/Kaido3016/AzureBot)

### 🧠 GCP GenAI Platform — Vertex AI RAG + Agentic AI

Original FastAPI platform built around **Vertex AI / Gemini**, document-grounded RAG, bounded agentic tools, structured outputs, and MCP.

**Highlights:** Gemini service abstraction · PDF/DOCX/TXT ingestion · embeddings/vector retrieval · citations · RAG search + calculator tools · structured-output validation · JSON-RPC/stdio MCP subset · deterministic local mock backend · evaluation/security/observability documentation.

The repository explicitly separates locally verified behavior from cloud functionality requiring GCP credentials and documents its test/verification boundaries.

→ [View GCP GenAI Platform](https://github.com/Kaido3016/gcp-genai-platform)

### 📄 GoAnalyze — Enterprise Document Intelligence & Secure RAG

Enterprise-oriented document platform combining RAG/LLM analysis with **multi-tenancy, authorization, auditability, observability, and cloud-native infrastructure**.

**Highlights:** document ingestion · semantic/vector retrieval · RBAC/ABAC · tenant isolation · audit/evidence workflows · Docker · Kubernetes/Helm · Terraform · Nginx · testing · CI/CD.

→ [View GoAnalyze](https://github.com/Kaido3016/GoAnalyze---Enterprise-Document-Intelligence-Secure-RAG-Platform)

### 🏥 MediQuery — Privacy-Conscious Medical Report Intelligence

Security-focused platform for organizing text-based medical PDF reports, extracting structured laboratory findings, preserving page-level evidence, and enforcing authenticated owner isolation.

The verified workflow is intentionally **deterministic and evidence-first**, not a claimed clinical AI system.

**Highlights:** authentication · IDOR protection · layered PDF validation · private storage keys · deterministic extraction · page-level evidence · deletion controls · rate limiting · security headers · E2E/security testing · Docker CI.

**Boundary:** no claims of diagnosis, clinical decision support, regulatory clearance, HIPAA/PIPEDA/PHIPA compliance, or clinical validation.

→ [View MediQuery](https://github.com/Kaido3016/MediQuery)

### 🛡️ DataGuard — Privacy & PII Intelligence Platform

Privacy-engineering foundation for **PII discovery, explainable risk assessment, PIA workflows, control mapping, and auditable evidence**.

**Highlights:** deterministic PII detection · optional multilingual spaCy NER · explainable risk scoring · tenant-aware authorization · PostgreSQL RLS support · PIA state model · Québec/Canadian/GDPR/CCPA control definitions · synthetic data · security/API/domain testing.

→ [View DataGuard](https://github.com/Kaido3016/DataGuard)

### 🧙 Gandalf — Multimodal AI Agent

Python agent connecting **LLM reasoning, voice, computer vision, image generation, and local desktop tools** through modular orchestration.

**Highlights:** command routing · provider-isolated reasoning · vision · TTS · image generation · browser/application automation · shell-free process launching · runtime isolation · bounded timeouts · pytest/Ruff/GitHub Actions.

→ [View Gandalf](https://github.com/Kaido3016/Gandalf)

---

## Other Projects

### 🔬 CodingResearchAgentAI
Agentic technical-research prototype using **LangGraph + GPT-4** for research planning, web/tool execution, structured extraction, comparison, and analysis.

→ [View project](https://github.com/Kaido3016/CodingResearchAgentAI)

### 🎬 DeepScene-AI
Generative-AI exploration combining **Stable Diffusion, prompt engineering, scene analysis, and dialogue generation** into a text-to-cinematic-scene workflow.

→ [View project](https://github.com/Kaido3016/DeepScene-AI)

---

## Engineering Philosophy

I treat AI as a **software engineering discipline**, not simply a model-selection exercise.

```text
Models ──┐
Data ────┼──► AI Application ──► Security / Evaluation / Observability ──► Reliable System
Tools ───┘
```

My strongest engineering themes:

**Secure · Grounded · Evaluated · Observable · Cost-aware · Maintainable**

### Patterns I care about

- Keep models behind explicit provider/service boundaries.
- Treat model output and retrieved content as untrusted input.
- Keep authorization outside the LLM.
- Prefer deterministic paths when they are safer, cheaper, or easier to test.
- Ground generated answers in retrievable evidence.
- Evaluate retrieval and generation separately.
- Measure latency, token usage, and cost instead of guessing.
- Clearly distinguish implemented, tested, and unverified functionality.

---

## Technical Stack

**AI / ML:** LLMs · RAG · Agentic AI · Multimodal AI · NLP · Embeddings · Vector Search · Structured Outputs · Prompt Engineering

**Application:** Python · FastAPI · PostgreSQL · SQLAlchemy · Pydantic · React · TypeScript · Next.js

**Cloud / Platform:** AWS · Amazon Bedrock · SageMaker · OpenSearch · S3 · Cognito · Lambda · AppSync · AWS CDK · Azure · Azure OpenAI · Azure AI Search · GCP · Vertex AI · Gemini · Docker · Kubernetes · Helm · Terraform · Nginx

**AI Tooling:** LangGraph · LangChain · MCP · OpenAI · Ollama · GitHub Actions

**Quality / Security:** Pytest · Jest · Ruff · CodeQL · Dependabot · CI/CD · AI Evaluation · RAG Evaluation · Threat Modeling · RBAC · ABAC · Guardrails · Observability

---

## Portfolio at a Glance

| Project | Core signal |
|---|---|
| **QStock** | AI + NL→SQL + real users |
| **AWS GenAI LLM Chatbot** | Bedrock + enterprise RAG + AI security + evaluation |
| **AzureBot** | Enterprise RAG + security + evaluation |
| **GCP GenAI Platform** | Vertex AI + RAG + agents + MCP |
| **GoAnalyze** | Secure RAG + multi-tenancy + infrastructure |
| **MediQuery** | Evidence-first document processing + security |
| **DataGuard** | Privacy engineering + PII + compliance workflows |
| **Gandalf** | Multimodal agents + tool/desktop automation |
| **CodingResearchAgentAI** | Agentic research + LangGraph |
| **DeepScene-AI** | Generative AI + multimodal workflow |

---

## 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/ali-el-sayed-ali/)
- [GitHub](https://github.com/Kaido3016)

> **Open to AI Engineer, Applied AI Engineer, AI Platform, LLM, RAG, Generative AI, Agentic AI, and Cloud AI opportunities.**
