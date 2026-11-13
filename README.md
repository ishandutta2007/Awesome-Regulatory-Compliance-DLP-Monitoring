# Awesome-Regulatory-Compliance-DLP-Monitoring

# Awesome Regulatory Compliance & DLP Monitoring

> A curated list of top Regulatory Compliance and Data Loss Prevention (DLP) Monitoring platforms — both SaaS/Hosted commercial compliance automation suites and open-source alternatives for maintaining audit readiness and monitoring sensitive data exposure.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Vanta](#vanta)
  - [Drata](#drata)
  - [Secureframe](#secureframe)
  - [Hyperproof](#hyperproof)
  - [Scrut Automation](#scrut-automation)
  - [Sprinto](#sprinto)
  - [Thoropass](#thoropass)
  - [TrustArc](#trustarc)
  - [Druva Compliance Monitoring](#druva-compliance-monitoring)
- [Open-Source Software](#-open-source-software)
  - [Openlane Core](#openlane-core)
  - [Microsoft Presidio](#microsoft-presidio)
  - [Hawk-Eye](#hawk-eye)
  - [Data Boar](#data-boar)
  - [Lacuna](#lacuna)
  - [Gitleaks / Betterleaks](#gitleaks--betterleaks)
  - [Wazuh (Compliance Monitoring Context)](#wazuh-compliance-monitoring-context)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Regulatory Compliance and DLP Monitoring platforms. These are not open-source but are included as reference points for feature comparison.

### Vanta
**Type:** Agentic trust management with AI-powered evidence lifecycle
Vanta's Compliance Agent automates the full evidence lifecycle—generating tailored documents, collecting, reviewing, and validating evidence—with full program awareness across frameworks, controls, and policies . It detects policy-to-program inconsistencies before they become audit issues and provides AI-driven remediation guidance . Vanta is among the first companies certified under ISO 42001 for responsible AI management, with strict data governance ensuring no customer data is used for model training . Users report saving up to four hours weekly, with 91% saying it improved audit readiness .
**Best for:** Organizations wanting a mature compliance automation platform with strong AI agent capabilities and ISO 42001-certified responsible AI practices.

### Drata
**Type:** GRC platform with continuous compliance and SafeBase Trust Center
Drata's Q4 2025 releases added no-code custom workflows for automating follow-ups based on control status or evidence gaps, MTTR insights for failed monitoring tests, and support for TISAX, NYDFS, and ISO/IEC 27018:2025 frameworks . It supports multiple HRIS and IdP connections for unified workforce evidence, and AI Feature Items enable publishing structured AI disclosures in the Trust Center . SafeBase Documents APIs allow programmatic document lifecycle management, and a Chrome extension supports questionnaire import .
**Best for:** Enterprises needing scalable GRC with multi-framework support, continuous monitoring, and a deeply integrated Trust Center powered by SafeBase.

### Secureframe
**Type:** Compliance automation with tiered packages
Secureframe's Fundamentals plan starts at $7,500/year with infrastructure monitoring, evidence collection, risk management, policy management, and Trust Center . The Complete tier adds advanced third-party risk management, advanced risk management, advanced user access reviews, and advanced questionnaire automation (15,000 questions/year) . It offers 300+ native integrations, continuous control monitoring, and Comply AI for policies and remediation . Defense tier supports CMMC requirements with SSP, POA&M, and SPRS score tracking .
**Best for:** Mid-market organizations wanting a comprehensive compliance platform with clear tiered pricing and strong CMMC support.

### Hyperproof
**Type:** GRC platform with AI Guided Experiences
Hyperproof's AI Guided Experiences handle complexity behind the scenes while keeping users in control. **Suggested Links** eliminates manual mapping by analyzing controls, policies, risks, and evidence to surface missing connections . **Evidence Collection and Validation** identifies required evidence, drafts credential requests, and validates evidence items for potential audit failures before the auditor finds them . The platform offers modular purchases for Policies, Access Reviews, Risk Register, and Vendors .
**Best for:** Compliance teams wanting AI-assisted mapping and evidence validation that reduces manual work without sacrificing control.

### Scrut Automation
**Type:** AI-powered risk and compliance with Scrut Teammates
Scrut Teammates is an AI-powered risk and compliance agent leveraging a proprietary knowledge graph and specialized AI agents . Scrut is ISO 42001 certified for AI risk management, with no data sharing or cross-training, privacy-by-design encryption, and opt-in configurability . All AI workflows are regularly audited for compliance and security . The platform emphasizes moving 10x faster by automating execution and eliminating context switching.
**Best for:** Organizations prioritizing AI governance (ISO 42001) and wanting AI agents that keep humans in control.

### Sprinto
**Type:** Autonomous trust platform with multi-approval workflows
Sprinto offers 25+ frameworks automated out of the box with 200+ digitized, continuous monitoring across 300+ integrations, and automated evidence collection . Enterprise features include multi-approval policy workflows, role-based access control with custom roles, configurable multi-step approval workflows, and AI-powered vendor assessments . It supports multi-entity workspaces, custom risk registers with ISO 27005 alignment, and AI systems inventory with AI risk assessments .
**Best for:** Enterprises needing granular approval workflows and multi-entity support alongside broad framework coverage.

### Thoropass
**Type:** Compliance and audit platform with expanded frameworks
Thoropass added eight frameworks in 2025 including CSA STAR, DORA, FERPA, WCAG 2, C5 (Germany), ISO 27017, NIST 800-53, and NIST 800-171 . It emphasizes deep alignment to a multi-framework control architecture, allowing ISO 27001 and CSA STAR to be aligned in a single workflow. Suited for cloud service providers, financial services firms (DORA), and organizations targeting European or public sector markets.
**Best for:** Organizations needing specific framework coverage (DORA, C5, CSA STAR) with a unified multi-framework control architecture.

### TrustArc
**Type:** Privacy management platform with Arc Intelligence
TrustArc's next-generation platform is built around Arc Intelligence, a contextual, explainable AI engine purpose-built for privacy . It understands 1,000+ regulations and 50,000+ references with full source citations, integrates with live program data, and ensures customer data is never used to train models . The platform unifies PrivacyCentral, Assessment Manager, and Cookie Consent Manager into one intelligent workspace with an action-oriented homepage and universal command bar .
**Best for:** Privacy teams wanting an explainable, citation-backed AI layer specifically designed for privacy regulations.

### Druva Compliance Monitoring
**Type:** Data protection with Sensitive Data Governance and end-user violation resolution
Druva provides compliance monitoring through its Sensitive Data Governance Dashboard, scanning backed-up data across endpoints, Microsoft 365, and Google Workspace for policy violations . Administrators can enable **end-user violation visibility**, allowing users to review and resolve violations (Resolve, Acceptable Risk, False Positive, or Delete) without admin intervention, while admins retain control over the workflow . Druva's DLP capabilities include remote data wipe (user or admin-initiated), geo-tracking, and enforced device encryption .
**Best for:** Druva customers wanting data-centric compliance monitoring with delegated violation resolution and built-in DLP controls.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Regulatory Compliance and DLP Monitoring tools. The open-source ecosystem spans **compliance automation platforms**, **PII detection and anonymization libraries**, **sensitive data discovery scanners**, and **data governance engines**.

### Openlane Core
**Stack:** Go / GraphQL / PostgreSQL | **License:** Apache-2.0
Openlane Core is an open-source compliance automation platform for SOC 2, GDPR, ISO 27001, NIST 800-53, and more . It provides a comprehensive GRC foundation with modules for controls, policies, risks, evidence, vendors, and trust center functionality . The project includes a workflow engine for orchestrating compliance processes, a catalog system for managing products and features, entitlements with Stripe integration, and multi-tenant file storage . It is actively developed with 280+ GitHub stars .
**Best for:** Organizations wanting a genuinely open-source compliance automation platform under a permissive Apache-2.0 license, accepting the operational overhead of a Go/PostgreSQL stack.

### Microsoft Presidio
**Stack:** Python | **License:** MIT
Microsoft Presidio is the most established open-source PII detection and anonymization library, pairing spaCy NER with regex, rule-based recognizers, and checksums . It provides **50+ predefined recognizers** (credit cards, SSNs, phone numbers, names, locations, financial data, bitcoin wallets) plus custom recognizers, covering text and DICOM/standard images across multiple languages with context-aware confidence scoring . The separate Anonymizer module can mask, redact, hash, or encrypt findings in the same pipeline . **Trade-off:** There is no native database scanner—you sample rows yourself and tag results yourself. It is a library, not a complete DLP platform.
**Best for:** Developers building custom PII detection pipelines who want a proven, flexible library with both detection and anonymization capabilities.

### Hawk-Eye
**Stack:** Python | **License:** Open Source
Hawk-Eye is a broad-spectrum sensitive data discovery scanner covering databases, cloud storage, and files including images and videos via OCR . It does pattern matching with configurable fingerprints in YAML and runs OCR across 350+ file types (DOCX, PDF, images, videos). Data sources include MySQL, PostgreSQL, MongoDB, CouchDB, Redis, S3, Google Cloud Storage, Firebase, Slack, Google Drive, and local filesystem . **Differentiator:** It follows PII wherever it leaks—Slack threads, CSVs in S3, screenshots in Drive—rather than stopping at the database boundary.
**Best for:** Security teams needing to audit sensitive data across diverse sources beyond just databases, particularly where PII has spread into SaaS and cloud storage.

### Data Boar
**Stack:** Python / SQLite / REST API | **License:** Open Core
Data Boar is a technical inventory and triage tool that finds where personal and sensitive data may live across databases, filesystems, APIs, shares, Power BI, and Dataverse . It assigns technical severity and norm-oriented hints while leaving lawful basis and purpose decisions to DPOs and counsel. It runs as a one-shot CLI or REST API with a web dashboard, outputs findings to SQLite, and produces Excel reports and heatmaps . It is explicitly positioned as an evidence layer for audits and DLP rollout preparation, not as a full DLP enforcement engine.
**Best for:** DPOs and compliance consultants wanting technical evidence of data locations and sensitive data posture before a DLP rollout or audit.

### Lacuna
**Stack:** Python / PostgreSQL | **License:** Open Source
Lacuna is a governance and data classification engine that combines automatic classification (heuristics, embeddings, LLM) with **lineage tracking** and **policy-as-code via Open Policy Agent (OPA)** . It tracks source → transformation → destination, propagates classification through joins and derivations (PUBLIC + PROPRIETARY = PROPRIETARY), and enforces allow/deny decisions considering data tier, user role, destination, and purpose . It includes ISO 27001-compliant audit logging with tamper-evident hash chains and complete provenance (who, what, when, why, how).
**Best for:** Data engineering and governance teams wanting classification that propagates through lineage with policy enforcement and audit-grade provenance.

### Gitleaks / Betterleaks
**Stack:** Go | **License:** MIT
Gitleaks is a secrets scanner that is now feature-complete, with future releases intended primarily for security patches while feature development shifts to **Betterleaks** . Both tools detect credentials and API tokens in repositories, files, and CI workflows, with Betterleaks adding contextual filtering, extensible validation, and broader source coverage (GitHub/GitLab APIs, Hugging Face, S3, local files) . They can gate commits and CI/CD workflows. **Limitation:** These are specialized secrets scanners for development environments, not enterprise DLP platforms—organizations seeking policy across SaaS, email, browsers, endpoints, and AI activity typically need a dedicated DLP layer alongside them.
**Best for:** DevOps teams wanting preventive secrets scanning in repositories and CI/CD pipelines, accepting that broader data protection requires additional tooling.

### Wazuh (Compliance Monitoring Context)
**Stack:** C++ / OpenSearch | **License:** GPL-2.0
Wazuh is primarily a SIEM, XDR, and File Integrity Monitoring platform, **not a dedicated DLP solution** . However, its FIM capabilities can report content changes, and it documents custom PAN scanning rules for detecting unmasked payment card numbers . These capabilities can contribute telemetry and compliance monitoring while a dedicated DLP layer handles broader content classification and data movement policy. Wazuh is often used alongside DLP tools rather than as a replacement.
**Best for:** Security teams already using Wazuh for SIEM/FIM who want to add basic sensitive-data detection rules while pairing with a dedicated DLP solution for comprehensive coverage.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Compliance Automation | DLP/PII Detection | Policy-as-Code | Self-Hosted | Best For |
|----------|---------|-------|----------------------|-------------------|----------------|-------------|----------|
| **Vanta** | Proprietary | Cloud | ✅ Agentic | ❌ | (AI policies) | ❌ | AI-powered audit readiness |
| **Drata** | Proprietary | Cloud | ✅ Multi-framework | ❌ | (No-code) | ❌ | Enterprise GRC + SafeBase |
| **Secureframe** | Proprietary | Cloud | ✅ Tiered | ❌ | (Comply AI) | ❌ | Mid-market + CMMC |
| **Hyperproof** | Proprietary | Cloud | ✅ AI Guided | ❌ | ❌ | ❌ | AI-assisted mapping |
| **Scrut** | Proprietary | Cloud | ✅ AI Teammates | ❌ | ❌ | ❌ | ISO 42001 AI governance |
| **Sprinto** | Proprietary | Cloud | ✅ Multi-approval | ❌ | (Rule engine) | ❌ | Granular approvals |
| **Thoropass** | Proprietary | Cloud | ✅ Multi-framework | ❌ | ❌ | ❌ | DORA/C5/CSA STAR |
| **TrustArc** | Proprietary | Cloud | (Privacy-focused) | ❌ | ❌ | ❌ | Privacy AI + citations |
| **Druva** | Proprietary | Cloud | (Sensitive data) | ✅ End-user resolution | ❌ | ❌ | DLP + remote wipe |
| **Openlane Core** | Apache-2.0 | Go/GraphQL | ✅ Full GRC | ❌ | (Workflow) | ✅ | OSS compliance automation |
| **Presidio** | MIT | Python | ❌ | ✅ 50+ recognizers | ❌ | ✅ (Library) | PII detection + anonymization |
| **Hawk-Eye** | Open Source | Python | ❌ | ✅ OCR + 350 types | ❌ | ✅ | Broad sensitive data discovery |
| **Data Boar** | Open Core | Python | ❌ | ✅ Inventory + triage | ❌ | ✅ | Audit evidence layer |
| **Lacuna** | Open Source | Python/Postgres | ❌ | ✅ Classification + lineage | ✅ OPA | ✅ | Lineage-aware governance |
| **Gitleaks** | MIT | Go | ❌ | ✅ Secrets only | ❌ | ✅ | CI/CD secrets scanning |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Regulatory Compliance or DLP Monitoring tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits sharply** between **compliance automation platforms** (Openlane Core) and **data discovery/PII detection tools** (Presidio, Hawk-Eye, Data Boar, Lacuna, Gitleaks). There is **no single open-source project** that replicates the combined compliance automation and DLP monitoring breadth of Vanta or Druva. **Presidio** is the most mature open-source PII detection library with both detection and anonymization , while **Hawk-Eye** offers the broadest data source coverage . **Openlane Core** is the strongest open-source compliance automation foundation under Apache-2.0 . For organizations needing enterprise-grade DLP with content-aware enforcement across SaaS, email, and endpoints, commercial platforms remain the only viable option.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
