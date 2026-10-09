# Ali El-Sayed Ali

### AI Engineer · Generative AI · RAG Systems · AI Evaluation & Reliability

Montreal, Québec, Canada · [LinkedIn](https://www.linkedin.com/in/ali-el-sayed-ali/) · [GitHub](https://github.com/Kaido3016)

I design and build **AI-enabled applications and engineering platforms**—from retrieval-augmented generation (RAG) and tool-using agents to natural-language data access, document intelligence, and privacy-aware systems. I focus on the complete lifecycle: architecture, evaluation, security boundaries, testing, observability, and deployment readiness.

My portfolio emphasizes systems that can be inspected and tested—not just prompts or notebooks. I document what is implemented, what has been tested locally, and what still requires validation in a live cloud environment.

---

## Selected impact

- **250+ users** — QStock inventory intelligence platform used by Scouts Musulmans de Montréal.
- **10,000+ registered items** — inventory domain handled by QStock, as documented in its repository.
- **211/211 tests passed** — local test evidence reported for the AWS GenAI chatbot engineering work; this is not evidence of a live AWS deployment.
- **108 tests** — reported across the GCP GenAI Platform application and MCP-related test suites; live Vertex AI behavior remains a separate verification step.

> Metrics are scoped to the project and verification context described. Test counts indicate test-suite results, not model accuracy or production service-level guarantees.

---

## Featured AI engineering projects

### 1. [QStock — Enterprise Inventory Intelligence Platform](https://github.com/Kaido3016/QStock-Enterprise-Inventory-Intelligence-Platform)

**Real-world application · Natural-language data access · Secure NL→SQL**

An inventory platform used by 250+ users, with 10,000+ registered items. Its AI assistant translates natural-language requests into controlled data operations using intent routing, reusable query templates, an LLM fallback for harder requests, SQL validation, read-only execution, and grounded answers.

**Engineering focus:** Python, FastAPI, PostgreSQL, React/TypeScript, model-provider abstraction, authorization, SQL safety, regression tests, and CI.

### 2. [AzureBot — Enterprise RAG Engineering Platform](https://github.com/Kaido3016/AzureBot)

**Azure AI · Evidence-grounded answers · Evaluation · Security**

An enterprise-oriented RAG platform built around Azure AI Search and Azure OpenAI, with identity-aware retrieval, authorization filters, citation-first generation, insufficient-evidence behavior, prompt-injection defenses, and observability.

**Engineering focus:** retrieval evaluation (Precision@K, Recall@K, MRR), groundedness, citation correctness, authorization-leakage tests, and statistically informed comparison utilities.

*Attribution note: this repository builds on Microsoft's azure-search-openai-demo; upstream attribution and licensing are retained. See the repository for the distinction between upstream components and portfolio engineering work.*

### 3. [GCP GenAI Platform — Vertex AI RAG & Agentic AI](https://github.com/Kaido3016/gcp-genai-platform)

**Gemini · RAG · Agent tools · MCP**

A modular FastAPI platform with a provider abstraction, document ingestion and chunking, embedding-based retrieval, grounded answers with citations, structured outputs, and a bounded tool-calling agent. Includes a real, explicitly scoped JSON-RPC-over-stdio MCP client/server implementation.

**Engineering focus:** retrieval and answer evaluation, schema validation, tool authorization, execution limits, prompt-injection defenses, reproducible tests, and Cloud Run-oriented architecture.

**Verification boundary:** local/mock tests do not substitute for live Vertex AI, managed vector-search, or cloud-deployment validation.

### 4. [GoAnalyze — Enterprise Document Intelligence & Secure RAG](https://github.com/Kaido3016/GoAnalyze---Enterprise-Document-Intelligence-Secure-RAG-Platform)

**Document intelligence · Multi-tenancy · Cloud-native engineering**

A security-first document intelligence platform combining ingestion, semantic retrieval, LLM-assisted analysis, tenant-aware authorization, audit trails, and operational foundations.

**Engineering focus:** RAG pipeline design, RBAC/ABAC boundaries, tenant isolation, Docker, Kubernetes/Helm, Terraform, migrations, observability, and CI quality gates.

### 5. [MediQuery — Privacy-Conscious Medical Report Intelligence](https://github.com/Kaido3016/MediQuery)

**Document AI · Structured extraction · Evidence-first workflows**

A platform for organizing text-based medical PDF reports, extracting structured laboratory findings, preserving page-level evidence, and enforcing authenticated owner isolation.

**Engineering focus:** secure document handling, owner-scoped access, validation, privacy-conscious telemetry, test automation, and synthetic-data-only development. It is not a diagnostic system or a clinically validated medical device.

### 6. [DataGuard Québec — Privacy & PII Engineering](https://github.com/Kaido3016/DataGuard)

**PII discovery · Explainable risk · Privacy workflows**

A privacy automation foundation for sensitive-information discovery, explainable risk assessment, Privacy Impact Assessment workflows, control mapping, tenant-aware boundaries, and auditable evidence.

**Engineering focus:** deterministic detection, optional multilingual NER, precision/recall/F1 evaluation on synthetic fixtures, FastAPI, PostgreSQL, and automated tests.

### 7. [Gandalf — Multimodal AI Agent](https://github.com/Kaido3016/Gandalf)

**LLM agents · Voice · Vision · Desktop automation**

A modular Python assistant exploring the connection between language-model reasoning and real-world tools, including speech, vision endpoints, image generation, and desktop workflows.

**Engineering focus:** provider boundaries, tool orchestration, bounded requests, safer process launching, concurrency, and automated quality checks.

### 8. [CodingResearchAgentAI — Research Agents with LangGraph, LangChain & MCP](https://github.com/Kaido3016/CodingResearchAgentAI)

**Agentic research · Web evidence · Structured outputs**

A developer-research project with two entry points: a LangGraph workflow for source-backed research and a separate MCP-powered Firecrawl assistant.

**Engineering focus:** evidence-aware extraction, source-excerpt checks, structured attributes, bounded input/history, failure handling, and automated tests. Retrieved web content remains untrusted and recommendations require source verification.

### 9. [DeepScene-AI — Generative AI for Scene Analysis](https://github.com/Kaido3016/DeepScene-AI)

**Generative AI · Scene workflows · Model evaluation**

An experimental application for scene analysis and cinematic-content workflows, with ongoing work around real model inference, image-generation validation, evaluation fixtures, and secure deployment.

**Engineering focus:** distinguish heuristic behavior from trained-model inference, test image generation on accessible models/hardware, and expand evaluation beyond small labeled fixtures.

### Additional project

- [AWS GenAI LLM Chatbot](https://github.com/Kaido3016/aws-genai-llm-chatbot) — AWS-oriented RAG platform with evaluation tooling, prompt-injection/RAG-poisoning defenses, citation handling, AI observability, upload validation, and security automation. The repository is based on the AWS sample; see its audit and attribution documents. Local tests are not a claim of live AWS deployment.

---

## Technical toolkit

**Languages & APIs:** Python · SQL · TypeScript · FastAPI · REST APIs

**LLMs & GenAI:** RAG · embeddings · vector retrieval · prompt design · structured outputs · tool calling · agent workflows · MCP · NL→SQL

**Evaluation & reliability:** Precision@K · Recall@K · MRR · groundedness · citation correctness · precision/recall/F1 · regression testing · adversarial testing · statistical comparison · error analysis

**Data & application engineering:** PostgreSQL · document processing · authentication · authorization · multi-tenancy · audit trails

**Cloud & delivery:** Azure AI · Azure OpenAI · Google Cloud / Vertex AI · AWS / Bedrock-oriented systems · Docker · Kubernetes · Terraform · GitHub Actions · CI/CD · observability

---

## How I engineer AI systems

1. **Define the task and failure modes** before choosing a model or architecture.
2. **Build measurable workflows** with explicit datasets, reference expectations, and separate retrieval, answer-quality, safety, latency, and cost signals.
3. **Treat model output and retrieved content as untrusted**; validate structured data and constrain tools and data access.
4. **Test the application around the model**—authorization, malformed inputs, failure paths, citations, and regression behavior.
5. **Report evidence honestly**, distinguishing local tests, synthetic evaluations, live-model results, and production deployment verification.

## Contact

- [LinkedIn](https://www.linkedin.com/in/ali-el-sayed-ali/)
- [GitHub repositories](https://github.com/Kaido3016?tab=repositories)

**Focus:** AI Engineer · Applied AI · Generative AI / RAG · AI Platform Engineering · LLM Evaluation & Reliability
