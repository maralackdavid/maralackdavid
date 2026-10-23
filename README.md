## David Maralack, PMP, PMI-CPMAI

##### **Senior Technical Program Manager | Software & Hardware Delivery | Enterprise AI Strategy | Cloud Solutions Architecture**

###### 📍 Seattle, WA | <maralackdavid@gmail.com> | LinkedIn: https://www.linkedin.com/in/david-maralack-3898135/

---

### 🏛️ Executive Summary

**Senior Technical Program Management Leader** with 20+ years driving global software and hardware ecosystems at **Amazon** (Alexa, Kindle) and **Microsoft** (Windows) — spanning device NPI, large-scale telemetry, and enterprise software solutions — complemented by an ongoing, intensive focus on enterprise AI strategy, cloud architecture, and CPMAI governance. **Certified PMP and PMI-CPMAI, applying AWS AI Business Strategist frameworks (AIB-C01 in progress)**, specializing in bridging AWS cloud engineering with executive business and financial governance to deliver high-impact GenAI, Agentic workflows, and predictive AI initiatives. Translates complex AI capabilities into executive business cases using **3-Year TCO models**, **4-Component ROI frameworks**, and **CPMAI Phase Gate project controls** — delivering AI initiatives that scale safely, enforce zero-trust security, and yield provable, sustainable business value.

---

### Core Competencies: CPMAI & AWS AI Business Strategy Frameworks

Every AI initiative I lead undergoes rigorous business justification and data-centric feasibility screening before code is written, anchored on the **Cognitive Project Management for AI (CPMAI)** framework and **AWS AI Business Strategist** methodologies:

#### 1. CPMAI 6-Phase Lifecycle & Gate Governance (PMI-CPMAI)
* **Phase I (Business Understanding)**: Evaluates business objectives, maps requirements to the **Seven Patterns of AI** (*Conversational*, *Recognition*, *Predictive Analytics*, *Hyper-Personalization*, *Patterns & Anomalies*, *Autonomous Systems*, *Goal-Driven Systems*), and verifies data feasibility at the **DIKUW Knowledge level** (Data -> Information -> Knowledge -> Understanding -> Wisdom).
* **Phase II & III (Data Understanding & Preparation)**: Audits data sources for quality, bias, and privacy compliance; enforces FinOps data sampling policies (e.g., 15% sample limits) to control experimental compute costs.
* **Phase IV & V (Model Development & Evaluation)**: Integrates automated CI/CD quality regression gates, golden test datasets, and model evaluation harnesses (citation accuracy, hallucination rates, P95 latency).
* **Phase VI (Operationalization & Gate Controls)**: Implements formal **Go/No-Go Decision Gates (Gates 1–4)** with strict SLA exit criteria before advancing initiatives from laboratory PoCs to production deployment.

#### 2. Strategic Solution Selection & Architecture (AWS AI Business Strategy)
* **Probabilistic vs. Deterministic Filtering (The 95% Rule)**: If a decision tree or rules engine covers 95%+ of operational cases, build the rules engine; reserve cognitive ML for high-variability unstructured data and complex visual patterns.
* **4-Filter Use Case Selection Framework**: Systematically screens candidates across **Business Impact** (quantifiable metric movement), **Data Availability** (baseline cleanliness), **Organizational Readiness** (sponsor alignment), and **Strategic Alignment** (3-year enterprise roadmap).
* **3-Year Build vs. Buy vs. Partner TCO Framework**: Models full Total Cost of Ownership across 3-year horizons—evaluating upfront development fees, ongoing maintenance, hidden false-positive throughput losses, and securing **100% full enterprise IP ownership**.
* **Active Portfolio Governance & Phased Transition**: Classifies active initiatives into **Scale** (proven return), **Pause** (30/60-day condition triggers), or **Terminate** (budget redeployment), employing line-by-line phased rollouts with predefined rollback triggers to minimize operational blast radius.

#### 3. Value Measurement & Financial Governance (AWS AI Business Strategy)
* **Pre-Launch Baseline Capture**: Enforces strict baseline measurements prior to deployment (*"A KPI without a baseline is an opinion; a KPI with a baseline is evidence"*).
* **4-Component Financial ROI Equation**: Formulates defensible C-suite business cases modeling net operating benefits across Direct Savings, Indirect Gains, Hidden Operating Costs, and Productivity Gains.
* **Multi-Stakeholder KPI Matrix**: Tailors financial and operational scorecards for executive stakeholders:
  * **CFO**: Net Annual Savings, Payback Period (~7–12 months), 2-Year ROI (200%+).
  * **COO / Plant Ops**: Scrap Rate Reduction, OEE Lift, False Positive Rate (<2.8%), MTBF.
  * **CIO / CTO**: User Adoption Rate, Data Pipeline Uptime (>99.2%), Integration Health, SLA Compliance.
  * **CHRO / Legal**: Recovered Workforce Hours, Responsible AI Compliance, Audit Trail Integrity.
* **FinOps & Leading Indicator Controls**: Monitors leading indicators (user adoption, pipeline uptime, accuracy trajectory) and enforces FinOps cost controls (compute right-sizing, 90-day model artifact retention).

#### 4. Trustworthy & Responsible AI Governance
* **8 Dimensions of Responsible AI**: Integrates *Fairness*, *Explainability*, *Controllability*, *Transparency*, *Governance*, *Privacy & Security*, *Safety*, and *Veracity & Robustness* directly into project planning.
* **Zero-Trust & Human-in-the-Loop (HITL)**: Enforces deterministic state-machine approval gates on high-risk write operations (refunds > $500, IAM privilege updates, database schema changes), policy-as-code (OPA + Bedrock Guardrails), and document-level IAM RBAC data isolation.
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

** | AWS Lake Formation, AWS Glue, Amazon Athena, Amazon QuickSight, DIKUW Knowledge-Level Data Roadmaps, Pipeline Latency SLAs |
| **Executive Leadership** | 20+ Years Enterprise Delivery (Amazon, Microsoft), Cross-Functional Alignment, PMP Agile/Waterfall Governance, U.S. Patent Holder |

---

### Certifications, Patents & Education

* **Project Management Professional (PMP)** | Project Management Institute
* **PMI Certified Professional in Managing AI (PMI-CPMAI)** | Project Management Institute
* **AWS Certified AI Business Strategist (AIB-C01 Specialization Track)** | Amazon Web Services *(In Progress)*
* **AWS & Cloud Specializations**: AWS Solutions Architect, AWS Data Lake Specialization, Google Cloud Advanced Data Analytics
* **B.S. in Computer Science & Mathematics** | University of the Western Cape
* **U.S. Patents**:
  * *Patent #8,683,579*: Software Activation Using Digital Licenses
  * *Patent #8,984,124*: System and Method for Adaptive Data Monitoring

---

### 📬 Connect & Collaborate

- 💼 **LinkedIn**: https://www.linkedin.com/in/david-maralack-3898135/
- 📧 **Email**: <maralackdavid@gmail.com>
