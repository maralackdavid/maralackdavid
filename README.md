# David Maralack, PMP, PMI-CPMAI
### **Artificial Intelligence (AI) Systems | Cloud Solutions Architecture | Software & Hardware Delivery**


📍 **Seattle, WA** | ✉️️ [maralackdavid@gmail.com](mailto:maralackdavid@gmail.com) | 🔗 [LinkedIn Profile](https://www.linkedin.com/in/david-maralack-3898135/)

---

## 🏛️ Executive Summary

**Strategic Technical Program Management Leader** with 20+ years of high-impact delivery at Amazon and Microsoft, specializing in the end-to-end orchestration of complex global software and hardware ecosystems, including Alexa, Kindle, and Windows. **PMP** (PMI - Project Management Professional) and **PMI-CPMAI** (Certified Professional in Managing AI) certified with domain expertise spanning Cloud Solutions Architecture, Machine Learning, Generative AI and Agentic AI frameworks, and edge-to-cloud device lifecycles. Proven track record bridging technical innovation with business strategy—driving multi-million-dollar initiatives, cross-functional business and engineering alignment, and data-driven operational readiness across distributed systems.

---

## 🚀 Featured Enterprise AI Architecture Portfolio

Below are four production-benchmarked architectural reference implementations engineered using Google and AWS and evaluated under the **PMI-CPMAI Phase I (Matching AI to Business Needs)** methodology:

### 1. 🗣️️ [GenAI ChatBot - Afrikaans AI Companion (Multimodal Heritage & Real-Time Voice System)](https://github.com/maralackdavid/Afrikaans-AI-companion/blob/main/README.md)
**Full-Duplex Multimodal Language Learning & Cultural Preservation Platform**
* **CPMAI & Cultural Impact Alignment**: Maps to the **Conversational & Human Interaction** pattern and **Augmented Intelligence** framework to interact with Kaapse Afrikaans (Cape Flats), Afrikaans (Formal Afrikaans), and isiXhosa heritage through ultra-low latency voice engagement.
* **Key Features**: Full-Duplex Live Voice Partner (`LiveMode`), Learn Studio with Pronunciation Coach (`LearnMode`), Cape Flats Persona Trivia Game Show (`TriviaMode`), and Multimodal Heritage Media Generation (`ImageGenMode` / Veo Video).
* **Architecture**: Full-duplex WebSocket audio streaming pipeline integrating **Gemini Live API** (`gemini-3.1-flash-live-preview` & `gemini-3.5-live-translate-preview`) with 16kHz PCM capture, **Gemini 3.1 Flash Lite**, **Gemini TTS**, **Gemini 2.5 Flash Image**, and **Google Veo 3.1** video synthesis. Built using **React 19 + TypeScript**, **Express 5**, and `@google/genai` SDK.
* **Key Artifacts**: [System Architecture & Sequence Flow Diagrams](https://github.com/maralackdavid/Afrikaans-AI-companion#2-target-system-architecture--modes) | Full-Stack Node.js/Express & WebSocket Server.
* **Application**: [Maralack Cape Flats AI Companion](https://maralack-afrikaans-ai-companion-1072691364189.us-east1.run.app)

---

### 2. 🛡️ [Permission-Aware AWS RAG Engine](https://github.com/maralackdavid/aws-permission-aware-rag-engine)
**Enterprise Knowledge Intelligence System with Granular Document Security**
* **CPMAI & ROI Alignment**: Solved cross-departmental data leakage risks while modeling a **35% support handle-time reduction** (~**\$1.8M annual ROI** for a 500-agent tier-1 baseline).
* **Measured Benchmarks**: **92.4% retrieval precision** | **1.38s P95 response latency** | **100% RBAC security compliance**.
* **Architecture**: Hybrid search combining **Amazon OpenSearch Serverless** (Vector + BM25) and **Amazon Bedrock (Claude 3.5 Sonnet)**, backed by cross-encoder re-ranking and **AWS IAM Role-Based Access Control (RBAC)** metadata filtering.
* **Key Artifacts**: [`ADR-001: Managed vs Custom RAG`](https://github.com/maralackdavid/aws-permission-aware-rag-engine/blob/main/docs/adrs/ADR-001-managed-vs-custom-rag.md) | System Architecture Blueprint | Python Retriever Handler.

---

### 3. 🤖 [Agentic Workflow Automation & Tool Governance](https://github.com/maralackdavid/aws-agentcore-mcp-governance)
**Multi-Agent Tool Orchestration with Deterministic Human-in-the-Loop (HITL) Safeguards**
* **CPMAI & Governance Alignment**: Separates probabilistic model reasoning from state-changing database writes. Enforces mandatory HITL approval for high-risk write operations (refunds, privilege changes), projecting **\$1.2M in annual cost avoidance**.
* **Measured Benchmarks**: **95.2% tool execution accuracy** | **100% prompt-injection attack blocking** | **100% HITL policy compliance**.
* **Architecture**: Dynamic agentic planning via **Amazon Bedrock AgentCore** and **Model Context Protocol (MCP)** on **AWS Fargate/Lambda**, guarded by deterministic **AWS Step Functions** state machines.
* **Key Artifacts**: [`ADR-002: Agentic Orchestration vs Deterministic Governance`](https://github.com/maralackdavid/aws-agentcore-mcp-governance/blob/main/docs/adrs/ADR-002-agentic-orchestration-vs-deterministic-state-machines.md) | Defensive Security Test Suite.

---

### 4. 📊 [Automated LLMOps Telemetry & Quality Guardrails](https://github.com/maralackdavid/aws-llmops-quality-guardrails)
**Full-Stack Observability & Continuous In-Pipeline Regression Gating**
* **CPMAI & Risk Alignment**: Protects enterprise SLAs and prevents silent production model degradation by automatically aborting deployments if citation accuracy or hallucination rates exceed threshold guardrails (**\$950K/yr risk avoidance**).
* **Measured Benchmarks**: **96.1% citation accuracy** | **2.3% hallucination rate** | **1.42s P95 latency SLA** | **100% trace coverage**.
* **Architecture**: Real-time distributed tracing with **AWS X-Ray** and **Amazon CloudWatch**, paired with automated pre-deployment evaluation harnesses using **AWS SageMaker Model Evaluation** integrated into **AWS CodePipeline**.
* **Key Artifacts**: [`ADR-003: In-Pipeline Quality Gating vs Passive Logging`](https://github.com/maralackdavid/aws-llmops-quality-guardrails/blob/main/docs/adrs/ADR-003-automated-llmops-quality-gating.md) | Automated CI/CD Gate Script.

---

## 🛠️ Core Architectural Competencies

| Domain | Specialization & Tooling |
| :--- | :--- |
| **AI & Agentic Systems** | Permission-Aware RAG, Bedrock AgentCore, Model Context Protocol (MCP), LangChain, Cross-Encoder Re-Ranking, Prompt Engineering & Guardrails |
| **AWS Cloud Infrastructure** | AWS Well-Architected Framework, OpenSearch Serverless, Lambda, Fargate, Step Functions, S3, Glue, Athena, API Gateway, IAM RBAC |
| **LLMOps & Observability** | SageMaker Model Evaluation, Ragas, AWS X-Ray Distributed Tracing, CloudWatch Metrics, Continuous Quality Regression Gating |
| **AI Governance & Strategy** | PMI-CPMAI Phase I Business Feasibility, TCO/ROI Modeling, ADR Authoring, DIKUW Data Alignment, Defensive Ethics & Prompt Injection Safeguards |
| **Technical Leadership** | 20+ Years Enterprise Experience (Amazon, Microsoft), Cross-Functional Stakeholder Alignment, PMP Governance, U.S. Patent Holder |

---

## 📜 Certifications, Patents & Education

* **Project Management Professional (PMP)** | Project Management Institute
* **PMI Certified Professional in Managing AI (PMI-CPMAI)** | Project Management Institute
* **AWS & Cloud Specializations**: AWS Solutions Architect, AWS Data Lake Specialization, Google Cloud Advanced Data Analytics
* **B.S. in Computer Science & Mathematics** | University of the Western Cape
* **U.S. Patents**:
  * Patent #8,683,579: *Software Activation Using Digital Licenses*
  * Patent #8,984,124: *System and Method for Adaptive Data Monitoring*

---

## 📬 Connect With Me

* 💼 **LinkedIn**: [linkedin.com/in/david-maralack-3898135/](https://www.linkedin.com/in/david-maralack-3898135/)
* 📧 **Email**: [maralackdavid@gmail.com](mailto:maralackdavid@gmail.com)
