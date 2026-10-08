# Ali El-Sayed Ali

### Applied AI Engineer · Machine Learning Evaluation · LLM Reliability

Montreal, QC · [LinkedIn](https://www.linkedin.com/in/ali-el-sayed-ali/) · [GitHub](https://github.com/Kaido3016)

I build and evaluate AI systems with an emphasis on **experimental validation, measurable quality, reliability, and secure deployment**. My work spans machine learning, Generative AI, RAG, agentic workflows, and structured-data applications.

My technical focus includes Python, statistical testing, model validation, experimental comparison, error analysis, LLM evaluation, retrieval metrics, and reproducible regression tests. I have used **scikit-learn, PySpark, MLflow, Azure Databricks, Azure AI Services, and Azure OpenAI**, alongside Python and cloud AI platforms.

> **Scientific mindset:** define the evaluation question, select appropriate data and metrics, compare systems carefully, investigate errors, document limitations, and distinguish measured results from assumptions.

---

## Featured projects for AI evaluation & applied research

### 1. AzureBot — RAG Evaluation, Statistical Comparison & Reliability

[Repository](https://github.com/Kaido3016/AzureBot)

Azure-based retrieval-augmented generation focused on authorized evidence, grounded answers, citation quality, and measurable behavior.

**Evaluation evidence in the repository**
- Comparison of evaluation runs across groundedness, relevance, citation matching, and latency.
- Bootstrap confidence intervals and paired permutation tests in the evaluation comparison utility.
- Reproducible random seeds and question-level alignment for run comparisons.
- Dedicated tests for the evaluation comparison logic.
- Retrieval, citation, authorization, and prompt-injection regression coverage.

**Interpretation boundary:** stored evaluation summaries are evidence for specific runs and datasets, not a universal performance guarantee. Citation presence and citation correctness are distinct measures.

### 2. DataGuard — PII Detection & NER Benchmarks

[Repository](https://github.com/Kaido3016/DataGuard)

Privacy-engineering platform for PII discovery, explainable risk assessment, privacy-impact workflows, and auditable controls.

**Evaluation evidence in the repository**
- Synthetic benchmarks for PII detection and named-entity recognition.
- Per-class precision, recall, and F1, plus macro-F1.
- False-positive and false-negative counts to support error analysis.
- Domain, API, security, and architecture tests.

**Interpretation boundary:** the inspected benchmarks use small synthetic datasets. They demonstrate evaluation mechanics, not production-level generalization or validated real-world accuracy.

### 3. QStock — Evaluating Natural-Language Data Operations

[Repository](https://github.com/Kaido3016/QStock-Enterprise-Inventory-Intelligence-Platform)

Inventory intelligence platform used by 250+ users and containing 10,000+ registered items. The AI workflow translates natural-language requests into validated, permission-aware data operations.

**Evaluation evidence in the repository**
- Dataset-driven intent-classification checks, including English and French examples.
- Regression coverage for invalid requests, SQL validation, authorization, and unsafe execution paths.
- Separation of deterministic checks from behavior that requires a live model or operational data.
- Instrumentation and reliability controls for AI-assisted workflows.

### 4. GCP GenAI Platform — RAG & Agent Evaluation

[Repository](https://github.com/Kaido3016/gcp-genai-platform)

FastAPI platform built around Vertex AI/Gemini, document-grounded RAG, bounded agent tools, structured outputs, and MCP.

**Focus:** retrieval metrics, groundedness, tool behavior, structured validation, security tests, and explicit verification boundaries.

**Interpretation boundary:** consult the repository's verification documentation before treating a result as a live-cloud evaluation; mock and local checks are not equivalent to running against a configured cloud deployment.

### 5. AWS GenAI LLM Chatbot — Evaluation & AI Security

[Repository](https://github.com/Kaido3016/aws-genai-llm-chatbot)

AWS-oriented RAG and generative-AI platform with an evaluation framework, retrieval-path prompt-injection defenses, citation controls, observability, and automated security checks.

**Focus:** repeatable offline evaluation, regression tests, secure document handling, and explicit separation between locally verified code and AWS-account-dependent behavior.

---

## Additional projects

- **[GoAnalyze](https://github.com/Kaido3016/GoAnalyze---Enterprise-Document-Intelligence-Secure-RAG-Platform)** — document intelligence, RAG, multi-tenancy, authorization, auditability, and cloud-native infrastructure.
- **[MediQuery](https://github.com/Kaido3016/MediQuery)** — privacy-conscious document processing, structured extraction, evidence preservation, and security testing using synthetic data.
- **[CareerCoach](https://github.com/Kaido3016/CareerCoach)** — AI-assisted resume and job matching with structured outputs and multi-provider support.
- **[GoMeet](https://github.com/Kaido3016/GoMeet)** — desktop meeting workflow with transcription and LLM-assisted summarization.
- **[Gandalf](https://github.com/Kaido3016/Gandalf)** — multimodal agent and tool/desktop automation exploration.
- **[CodingResearchAgentAI](https://github.com/Kaido3016/CodingResearchAgentAI)** — LangGraph-based technical research and structured analysis prototype.
- **[DeepScene-AI](https://github.com/Kaido3016/DeepScene-AI)** — generative-AI exploration for scene analysis and cinematic content.

---

## Skills

**Machine learning & experimentation:** Python · scikit-learn · model validation · statistical testing · experimental comparison · evaluation metrics · error analysis

**Data & experiment tooling:** SQL · PySpark · MLflow · Azure Databricks

**Generative AI:** Azure AI Services · Azure OpenAI · LLM evaluation · prompt engineering · RAG · embeddings · vector search · structured outputs · agent workflows · MCP

**Evaluation & reliability:** benchmark design · retrieval evaluation · groundedness · citation correctness · regression testing · adversarial testing · robustness investigation · latency and token-cost analysis

**Engineering & cloud:** FastAPI · PostgreSQL · TypeScript · Docker · Kubernetes · Terraform · CI/CD · OpenTelemetry · AWS · Azure · Google Cloud

---

## How I approach AI evaluation

1. **Define the question:** identify the model, workflow, failure mode, or quality dimension being evaluated.
2. **Choose representative data:** use explicit test cases and reference expectations, documenting synthetic-data limitations.
3. **Select metrics:** separate retrieval quality, answer quality, safety, latency, and cost instead of collapsing them into one score.
4. **Compare carefully:** align comparable examples, use appropriate statistical methods, and report uncertainty where justified.
5. **Analyze failures:** inspect false positives, false negatives, unsupported claims, citation errors, authorization failures, and regressions.
6. **Document the boundary:** distinguish code implemented, tests executed, results observed, and production behavior not yet verified.

---

## Contact

- [LinkedIn](https://www.linkedin.com/in/ali-el-sayed-ali/)
- [GitHub repositories](https://github.com/Kaido3016?tab=repositories)

**Target roles:** Senior AI Engineer · Applied AI / Machine Learning · AI Evaluation · LLM Evaluation · Generative AI.
