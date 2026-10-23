## David Maralack, PMP, PMI-CPMAI

##### **Senior Technical Program Manager | Software & Hardware Delivery | Enterprise AI Strategy | Cloud Solutions Architecture**

###### 📍 Seattle, WA | <maralackdavid@gmail.com> | LinkedIn: https://www.linkedin.com/in/david-maralack-3898135/

---

### 🏛️ Executive Summary

**Senior Technical Program Management Leader** with 20+ years driving global software and hardware ecosystems at **Amazon** (Alexa, Kindle) and **Microsoft** (Windows) — spanning device NPI, large-scale telemetry, and enterprise software solutions — complemented by an ongoing, intensive focus on enterprise AI strategy, cloud architecture, and CPMAI governance. **Certified PMP and PMI-CPMAI, applying AWS AI Business Strategist frameworks (AIB-C01 in progress)**, specializing in bridging AWS cloud engineering with executive business and financial governance to deliver high-impact GenAI, Agentic workflows, and predictive AI initiatives. Translates complex AI capabilities into executive business cases using **3-Year TCO models**, **4-Component ROI frameworks**, and **CPMAI Phase Gate project controls** — delivering AI initiatives that scale safely, enforce zero-trust security, and yield provable, sustainable business value.

---

### 🎯 How I Evaluate AI Investments: CPMAI & AWS Strategy Frameworks

Every AI initiative I lead goes through rigorous business justification before code is written, anchored on the **Cognitive Project Management for AI (CPMAI)** and the **AWS AI Business Strategist** frameworks and methodologies:


**Some of the core frameworks and methodologies I apply:**

- **Probabilistic vs. Deterministic (The 95% Rule):** if business rules cover 95% of cases, automate with rules — reserve AI for high-variability pattern recognition (visual defect detection, unstructured language).
- **CPMAI 3x3 Feasibility:** Go/No-Go across Business, Data, and Execution feasibility (9 traffic-light indicators).
- **DIKUW & 7 Patterns of AI:** mapping problems to the AI "sweet spot" (Knowledge/Understanding layers) and classifying against the seven AI patterns.
- **4-Filter Use-Case Selection:** Business Impact, Data Availability, Organizational Readiness, Strategic Alignment.
- **3-Year Build vs. Buy vs. Partner TCO:** full cost modeling including hidden opex (e.g., false-positive throughput losses), enforcing enterprise IP ownership.
- **Active Portfolio Governance:** Scale, Pause (30/60-day conditions), or Terminate — via Parallel Running, Phased Rollout, and pre-defined Rollback Triggers.
- **Value Measurement:** pre-launch baseline capture ("a KPI without a baseline is an opinion"), 4-component ROI model, multi-stakeholder KPI framing (CFO/COO/CIO/CHRO), and FinOps cost controls.
- **Trustworthy AI by Design:** fairness, explainability, privacy, safety, and human-in-the-loop embedded in planning — not bolted on after deployment.

---
### 🚀 Featured AI Architecture Portfolio

Five production-grade prototype architectures built on AWS and Google Cloud, evaluated under the **PMI-CPMAI** and **AWS AI Business Strategy** frameworks.

> **Prototype disclaimer:** Independent lab-based production-grade AI proof-of-concepts — **no client engagements**. All business-value figures are *modeled* at enterprise scale, not measured at a client. Benchmarks below are simulated prototype evaluation results.

| # | Project | Focus | Key Tech | Prototype mectrics/benchmarks |
|---|---------|-------|----------|---------------------------------|
| 1 | 🗣️ [GenAI ChatBot - Afrikaans AI Companion (Multimodal Heritage & Real-Time Voice System)](https://github.com/maralackdavid/Afrikaans-AI-companion/blob/main/README.md) | Full-duplex voice language learning | Gemini Live API, Google Cloud Run, Veo | <500ms P95 Voice Response Latency, > 90.0% Dialect Recognition Fidelity |
| 2 | 🛡️ [Permission-Aware AWS RAG Engine](https://github.com/maralackdavid/aws-permission-aware-rag-engine/blob/main/README.md) | Zero-trust RAG with IAM RBAC filtering | AWS Bedrock, OpenSearch Serverless, Cohere | 92.4% Retrieval Precision, 1.38s P95 Latency, 100% RBAC Isolation, 96.1% Citation Coverage |
| 3 | 🤖 [Agentic Workflow Automation & Tool Governance](https://github.com/maralackdavid/aws-agentcore-mcp-governance/blob/main/README.md) | Multi-agent orchestration, HITL safeguards | Bedrock AgentCore, MCP, Step Functions | 95.2% Tool Execution Accuracy, 100% Prompt-Injection Blocking, 100% HITL Policy Compliance |
| 4 | 📊 [Automated LLMOps Telemetry & Quality Guardrails](https://github.com/maralackdavid/aws-llmops-quality-guardrails/blob/main/README.md) | Observability, in-pipeline quality gates | X-Ray, CloudWatch, SageMaker | 96.1% Citation Accuracy, 2.3% Hallucination Rate, 1.42s P95 Latency, 100% Trace Coverage |
| 5 | 🏦 [Enterprise GenAI Governance Control Plane](https://github.com/maralackdavid/Enterprise-GenAI-Governance/blob/main/README.md) | AI risk registry, policy guardrails, audit | OPA, Bedrock Guardrails, PrivateLink | <60ms P99 Policy-Gate Latency, 98.2% Guardrail Block Precision, 100% Audit Integrity,<90s Kill-Switch Propagation |

---

#### 1. 🗣️ [GenAI ChatBot - Afrikaans AI Companion (Multimodal Heritage & Real-Time Voice System)](https://github.com/maralackdavid/Afrikaans-AI-companion/blob/main/README.md)

**Full-Duplex Multimodal Language Learning & Cultural Preservation Platform**

- Full-duplex WebSocket audio streaming with Gemini Live API (16kHz PCM capture), Gemini 3.1 Flash Lite, Gemini TTS, and Google Veo video synthesis on Cloud Run. Supports Kaapse Afrikaans (Cape Flats), formal Afrikaans and isiXhosa.
- **Try the working prototype**: [Maralack Cape Flats AI Companion](https://maralack-afrikaans-ai-companion-1072691364189.us-east1.run.app/)

#### 2. 🛡️ [Permission-Aware AWS RAG Engine](https://github.com/maralackdavid/aws-permission-aware-rag-engine/blob/main/README.md)

**Zero-Trust Retrieval-Augmented Generation with IAM RBAC Metadata Filtering**

- Document-level AWS IAM RBAC metadata filtering inside OpenSearch Serverless hybrid vector search; Cohere Cross-Encoder re-ranking, Amazon Bedrock (Claude 3.5 Sonnet), CI/CD quality regression gates in CodePipeline.
- Modeled impact at Tier-1 support scale: 35% reduction in Average Handle Time (AHT), ~$1.8M/yr savings, <12-month payback.
- Prototype benchmarks: **92.4% Retrieval Precision** | **1.38s P95 Latency** | **100% RBAC Isolation** | **96.1% Citation Coverage**.

#### 3. 🤖 [Agentic Workflow Automation & Tool Governance](https://github.com/maralackdavid/aws-agentcore-mcp-governance/blob/main/README.md)

**Multi-Agent Tool Orchestration with Deterministic Human-in-the-Loop (HITL) Safeguards**

- Dynamic agentic planning via Amazon Bedrock AgentCore and Model Context Protocol (MCP) on Fargate/Lambda, guarded by deterministic AWS Step Functions state machines; mandatory HITL approval for high-risk writes (refunds, privilege changes).
- Modeled impact: ~$1.2M/yr risk avoidance.
- Prototype benchmarks: **95.2% Tool Execution Accuracy** | **100% Prompt-Injection Blocking** | **100% HITL Policy Compliance**.

#### 4. 📊 [Automated LLMOps Telemetry & Quality Guardrails](https://github.com/maralackdavid/aws-llmops-quality-guardrails/blob/main/README.md)

**Full-Stack Observability & Continuous In-Pipeline Quality Regression Gating**

- Real-time distributed tracing with AWS X-Ray and CloudWatch; pre-deployment evaluation harnesses via SageMaker Model Evaluation in CodePipeline; deployments auto-abort when citation accuracy or hallucination rates breach guardrails.
- Modeled impact: ~$950K/yr risk avoidance.
- Prototype benchmarks: **96.1% Citation Accuracy** | **2.3% Hallucination Rate** | **1.42s P95 Latency** | **100% Trace Coverage**.

#### 5. 🏦[Enterprise GenAI Governance Control Plane](https://github.com/maralackdavid/Enterprise-GenAI-Governance/blob/main/README.md)

**Applied AI Business Strategy on AWS's Governed Inference Platform**

- Applies the AI Business Strategy framework (AIB-C01 methodology) to AWS's Governed Inference Platform sample: AI use-case registry with EU AI Act risk-tier classification, policy-as-code deployment gates (OPA + Bedrock Guardrails), PrivateLink-only Bedrock access, immutable audit trail (S3 Object Lock + Athena), and an org-wide kill switch.
- Modeled impact: ~$2.25M/yr net annual benefit, ~5-month payback, ~436% 3-year ROI; 3-yr TCO $1.4M vs. $4.1M Big-4-led program.
- Prototype benchmarks: **<60ms P99 Policy-Gate Latency** | **98.2% Guardrail Block Precision** | **100% Audit Integrity** | **<90s Kill-Switch Propagation**.

---

### 🛠️ Strategic & Technical Program Management Competencies

| Competency Pillar | Specialization & Tooling |
| --- | --- |
| **Enterprise AI Strategy** | CPMAI Phase I Business Feasibility, AWS Methodologies, Build vs. Buy vs. Partner TCO Analysis, Active Portfolio Governance (Scale/Pause/Terminate), Shadow AI Governance |
| **Financial & Value Governance** | 4-Component Financial ROI Modeling, Pre-Launch Baseline Capture, Multi-Stakeholder KPI Framing (CFO/COO/CIO/CHRO), FinOps Cost Factor Controls, Payback Period Calculation |
| **AI Architecture & RAG** | Permission-Aware RAG, Amazon Bedrock, OpenSearch Serverless Hybrid Search, Cohere Cross-Encoder Re-Ranking, Prompt Engineering & Guardrails, Vector Indexing |
| **Agentic Systems & Governance** | Amazon Bedrock AgentCore, Model Context Protocol (MCP), AWS Step Functions HITL State Machines, Deterministic Guardrails, Tool Execution Oversight |
| **LLMOps & Observability** | SageMaker Model Evaluation, Ragas Evaluation Framework, AWS X-Ray Distributed Tracing, CloudWatch Telemetry, Continuous CI/CD Quality Regression Gating |
| **Executive Leadership** | 20+ Years Enterprise Delivery (Amazon, Microsoft), Cross-Functional Stakeholder Alignment, PMP Agile/Waterfall Governance, U.S. Patent Holder |

---

### 📜 Certifications, Patents & Education

- **Project Management Professional (PMP)** | Project Management Institute
- **PMI Certified Professional in Managing AI (PMI-CPMAI)** | Project Management Institute
- **AWS Certified AI Business Strategist (AIB-C01 Specialization Track)** | Amazon Web Services (in progress)
- **AWS & Cloud Specializations**: AWS Solutions Architect, AWS Data Lake Specialization, Google Cloud Advanced Data Analytics
- **B.S. in Computer Science & Mathematics** | University of the Western Cape
- **U.S. Patents**:
  - *Patent #8,683,579*: Software Activation Using Digital Licenses
  - *Patent #8,984,124*: System and Method for Adaptive Data Monitoring

---

### 📬 Connect & Collaborate

- 💼 **LinkedIn**: https://www.linkedin.com/in/david-maralack-3898135/
- 📧 **Email**: <maralackdavid@gmail.com>
