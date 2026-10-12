# Awesome-Enterprise-AI-Guardrails-Privacy

## Top Enterprise AI Guardrails & Privacy Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Safety, Prompt Defense & AI Governance*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise AI Guardrails & Privacy**. These tools enable organizations to deploy generative AI safely by intercepting prompts and responses for toxicity, prompt injection, PII leakage, and hallucination — while maintaining compliance and audit trails.



**Examples** include Salesforce Einstein Trust Layer, Lakera Guard, Guardrails AI, Protect AI, HiddenLayer, Arthur Shield, NVIDIA NeMo Guardrails, CalypsoAI, Patronus AI, and Credo AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom guardrail validators, and open AI security infrastructure — ideal for security engineers, ML platform teams, and developers seeking transparent, vendor-independent AI safety.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Salesforce Einstein Trust Layer](https://www.salesforce.com/products/secure-ai/)** | Secure AI architecture built into Salesforce Platform with dynamic CRM grounding, PII masking, Zero Data Retention, toxicity detection, and audit trails. | Included in Enterprise & Unlimited Editions; advanced Agentforce / Einstein 1 tiers start at list price of **$550/user/month** (billed annually) or custom quotes. | **30-day free trial** available for Salesforce Enterprise Edition (includes standard platform features and trial credits). |
| **[Lakera Guard](https://platform.lakera.ai/)** | API-first runtime security layer for LLM and agent applications providing prompt injection defense, jailbreak prevention, and PII leakage guardrails. | **$0/month** for Community Tier; Enterprise tier starts at custom negotiated annual contracts (acquired by Check Point). | **Free forever Community tier** includes up to **10,000 API requests/month** with up to 8,000 tokens per prompt and SaaS dashboard access. |
| **[Patronus AI](https://www.patronus.ai/)** | Automated evaluation, red-teaming, and guardrail API for hallucinations (Lynx model), toxicity, PII, and custom enterprise criteria. | **€0/month** (Monitor tier); **€6.99/device/month** (Light tier); **€69/month** (Pro tier up to 5 devices); custom for Business/Enterprise. | **Free forever Monitor tier** includes basic desktop app visibility and limited API scan units; Developer API offers free trial evaluation credits. |
| **[Guardrails AI](https://guardrailsai.com/)** | Framework and Hub for input/output guards, PII filtering, and structured Pydantic data generation for LLM applications. | Core framework is **$0 (Apache 2.0 open source)**; Guardrails Pro / Managed Cloud starts via custom enterprise annual contracts or AWS Marketplace private offers. | **Free forever open-source** self-hosted engine with unrestricted local runs; Guardrails Hub public validators are free to pull and run. |
| **[Arthur Shield](https://www.arthur.ai/product/shield)** | Real-time LLM firewall and guardrail intercepting sensitive data leakage, hallucinations, prompt injection, and toxic responses. | Arthur Monitoring entry tiers start at **$60/month**; Arthur Shield enterprise runtime guardrail starts via custom annual enterprise agreements (~$30,000–$50,000+/year). | **14-day free trial** available for Arthur core evaluation/monitoring platform upon request (no self-serve free forever tier for Shield). |
| **[Credo AI](https://www.credo.ai/)** | Enterprise AI governance, risk management, and compliance platform with GAIA assistant automating policy enforcement and audit trails. | Annual platform subscription starting between **$30,000 to $150,000/year** based on active AI use cases and compliance modules. | **Free access to AI Governance Insights Hub and templates**; enterprise platform evaluation via customized guided proof-of-concept (PoC) demo upon request. |
| **[Protect AI](https://protectai.com/)** | AI security posture management, Guardian model scanner, and LLM supply-chain security against serialization attacks. | Annual commercial enterprise contracts starting at mid-five figures (~$35,000–$50,000+/year) via direct sales or AWS Marketplace (acquired by Palo Alto Networks). | **Free forever open-source ModelScan** tool for scanning local models; enterprise platform PoC/trial available upon sales request. |
| **[HiddenLayer](https://hiddenlayer.ai/)** | AI security platform providing ML model scanning, attack simulation, and Agentic Runtime Security for multi-turn sessions and tool calls. | Annual commercial enterprise contracts starting at mid-five figures (~$50,000+/year) scaled by model count and runtime deployment mode. | **Guided Proof-of-Concept (PoC) trial** available upon scheduled enterprise demo (no self-serve free forever tier). |
| **[CalypsoAI](https://calypsoai.com/)** | Real-time inference-layer security (Inference Defend) blocking prompt injections, jailbreaks, and data exfiltration. | Annual enterprise subscription starting at custom rates (acquired by F5 Networks for $180M). | **Guided enterprise Proof-of-Concept (PoC)** available upon sales request and demo (no public self-serve free tier). |



## Open-Source GitHub Projects



- **[NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Leading open-source toolkit (Apache-2.0) for programmable LLM guardrails. Colang modeling language for dialogue flows. Five rail types: Input, Dialog, Retrieval, Execution, Output. Built-in rails for self-checking (moderation, fact-checking, hallucination), jailbreak detection, and NVIDIA safety models. LangChain integration. Docker and CLI support .



- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  

  Python framework (Apache-2.0) for input/output validation and structured data generation. Guardrails Hub with 24+ pre-built validators (PII, toxicity, competitor check, regex match). Guardrails API server (FastAPI) provides OpenAI-compatible endpoints for applying guards in your own environment. Supports PostgreSQL persistence and full CRUD .



- **[ModelScan (Protect AI)](https://github.com/protectai/modelscan)**  

  Open-source model scanner (Apache-2.0) protecting against Model Serialization Attacks. Reads files byte-by-byte without loading malicious code. Supports PyTorch, TensorFlow, Keras, Sklearn, XGBoost, and Pickle-derived formats. Ranks threats as Critical/High/Medium/Low. Scans in seconds .



- **[Arthur Engine (GenAI Engine)](https://github.com/arthur-ai/arthur-engine)**  

  Open-source engine (Apache-2.0) for LLM evaluation and guardrails. Provides task-based validation, rule configuration, hallucination detection for RAG applications, and API endpoints. Can disable guardrail model loading via environment variable for faster startup .



- **[Patronus Lynx](https://huggingface.co/PatronusAI/lynx)**  

  Open-source hallucination detection model (Apache-2.0) from Patronus AI. State-of-the-art for RAG workflows. Also available via hosted API. Research paper: Ravi et al., "Lynx: An Open Source Hallucination Evaluation Model" (arXiv:2407.08488) .



- **[Sponsio](https://github.com/SponsioLabs/Sponsio)**  

  Open-source runtime safety tool for AI agents (Apache-2.0). Checks every agent action against deterministic rules called "agent contracts" before execution. Contracts can allow, block, escalate, or redirect actions. Ready-made contract bundles or plain-English rules. Works with major Python and TypeScript agent frameworks .



- **[Doberman](https://github.com/Doberman-AI/doberman)**  

  Open-source security layer for AI coding agents (Apache-2.0). Checks every action before execution: routine actions pass, sensitive actions need human approval, dangerous actions blocked. Uncertainty results in denial. Protections can tighten automatically but weakening requires human approval and is logged .



- **[Inner Warden](https://github.com/InnerWarden/inner-warden)**  

  Open-source security agent for Linux/macOS (MIT). Detects brute-force and privilege escalation attacks. Can monitor autonomous AI agents and block risky commands. All actions reversible and recorded in audit trail. AI is advisory unless operators allow automatic action .



- **[Meilynx](https://github.com/Meilynx/meilynx)**  

  Open-source LLM governance proxy for regulated sectors (financial services, insurance, healthcare, HR). Redacts sensitive data, restricts model use, controls agent tool calls. Tamper-evident audit log mappable to EU AI Act controls .



### Additional Strong Open-Source Options



- **[FLARE-AI](https://github.com/FLARE-AI/flare-ai)** — Open-source AI flaw and incident reporting platform. Standardized JSON-LD reports routed to multiple developers and coordinators .

- **[AI Facts](https://github.com/AI-Facts/ai-facts)** — Free, open-source Decision Terrain tool mapped to NIST AI RMF 1.0. Documents safeguards, evidence, gaps, and actions .

- **[RecourseBench](https://github.com/RecourseBench/recoursebench)** — Modular evaluation framework for algorithmic recourse methods .

- **[The Model Card Builder](https://github.com/HCXAIResearch/model-card-builder)** — Free browser-based tool for documenting AI systems against NIST AI RMF and EU AI Act .

- Community **n8n** workflows for guardrail alerting and audit log routing.



**Frameworks for building custom systems**: Combine **NeMo Guardrails** or **Guardrails AI** as the guardrail engine with **ModelScan** for model supply chain security, **Sponsio** or **Doberman** for agent runtime safety, **Meilynx** for governance proxy, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade AI guardrails platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI guardrails systems handling prompts and outputs must comply with data protection regulations (GDPR, CCPA, EU AI Act, etc.).

- Self-hosted open-source solutions require proper security hardening, model artifact management, and ongoing maintenance. AI safety is an evolving field — guardrails should be tested against adversarial inputs before production deployment.



---



**Made for security engineers, AI platform teams, compliance officers, and developers building transparent AI safety solutions.**  

Let's make Enterprise AI Guardrails & Privacy more open, secure, and trustworthy.
