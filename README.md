# Francesco Ojoko

**Information Security Analyst | Banking & Finance Background | Bridging Security Operations and Audit-Ready Governance**

Information Security Analyst with 3+ years of experience across security operations, fraud and risk analytics, and financial systems monitoring. Currently completing an MSc Cybersecurity (Machine Learning specialisation) at Robert Gordon University. Focused on the bridge between technical security signals and the financial-governance language public sector and financial services need to make defensible, audit-ready risk decisions.

---

## 🎓 Education

**MSc Cybersecurity (Machine Learning Specialisation)** — Robert Gordon University, Aberdeen *(Sept 2025 – Sept 2026, expected)*
- Modules: ML for Cybersecurity, Network Security, Penetration Testing, Risk Management
- Grade A achievements in Penetration Testing (91.8%) and ISO 27005 Risk Assessment
- Research: two-stage ensemble ML pipeline (Random Forest + XGBoost + BiLSTM), 96.5% F1-score on intrusion detection

**BSc Banking & Finance (2:1)** — Nnamdi Azikiwe University, Nigeria *(2019 – 2023)*
- Foundation in financial operations, risk management, regulatory frameworks

---

## 💼 Professional Experience

**Security Analyst** — S2E Data Solutions, United Kingdom *(June 2025 – Present)*
- SIEM (Splunk/ELK) and XDR alert triage; runbook-led incident response
- Detection tuning, false-positive reduction, severity calibration
- Azure AD RBAC and identity hygiene activities
- Vulnerability remediation tracking and CAF-aligned playbook development

**Security Operations Analyst** — Sabfranco Ltd, Nigeria *(March 2023 – May 2025)*
- Hybrid infrastructure monitoring and incident response leadership
- Log aggregation and correlation engineering for detection speed
- Python and Wireshark anomaly investigation; stakeholder reporting
- Operational dashboard development; tabletop exercise design

**Security Analyst** — Bocheng Consulting Ltd, Nigeria *(June 2021 – July 2023)*
- Risk assessments on financial transaction systems
- Security hardening and baseline control improvements
- Incident reporting at technical and executive levels
- Translation of technical risk to business impact for stakeholders

---

## 🔒 Security Domains

### Risk Methodology & Governance
- ISO 27005 risk assessments with comprehensive risk registers
- ISO 27001 Annex A control mapping
- NIST CSF and NCSC CAF v4 framework alignment
- Audit-ready evidence and reproducibility-by-design
- Statutory financial accountability awareness (Section 95 / Section 151)

### Security Operations & Detection Engineering
- SIEM (Splunk, ELK), XDR, alert triage and tuning
- Detection rule engineering and false-positive reduction
- Incident response, runbook development, post-incident review
- MITRE ATT&CK framework application

### Machine Learning for Security
- Two-stage intrusion detection pipeline (96.5% F1-score)
- Random Forest / XGBoost for binary threat detection
- BiLSTM neural networks for multi-class attack classification (14 attack types)
- Explainability via feature importance; concept drift management

### Penetration Testing & Offensive Research
- Black-box security assessments with full kill-chain to root
- CVE exploitation: ProFTPD, UnrealIRCd, Drupal, vsftpd
- Privilege escalation via Docker misconfiguration
- Active LLM-orchestrated bug bounty research (Monzo / Intigriti)

---

## 🏦 Featured Build — [AML Transaction Monitoring Engine](https://github.com/Cesco556/aml-transaction-monitoring-engine)

**Production-grade Anti-Money Laundering platform** — not a toy demo, a real system with 368 passing tests.

| Capability | Implementation |
|---|---|
| **Detection** | 8 configurable rules + Isolation Forest ML (hybrid approach) |
| **Sanctions** | Fuzzy matching (Jaro-Winkler, Levenshtein, phonetic) + OFAC SDN + PEP screening |
| **Scoring** | Weighted severity, temporal decay, customer risk profiles |
| **Network** | Graph analysis, community detection (Louvain), money flow tracing |
| **Streaming** | Real-time consumer + WebSocket alerts + deduplication |
| **Compliance** | FinCEN SAR (XML), PDF reports, regulatory timelines, audit exports |
| **Governance** | Audit Playbook, Model Risk Management, tuning evidence, data quality controls |
| **Infrastructure** | FastAPI + Docker Compose + PostgreSQL + Redis |

> Competes with commercial tools like Actimize, Featurespace, and Feedzai — except open-source.

---

## 🚧 Currently Building — Financial Crime Detection Suite

A suite of interconnected tools that extend the AML engine into a full financial crime detection platform:

| Project | Status | Description |
|---|---|---|
| `aml-explainability-dashboard` | 🔨 Building | SHAP/LIME explanations for AML model decisions — EU AI Act compliant XAI |
| `kyc-identity-verification-pipeline` | 📋 Planned | Document OCR + face verification + risk-based KYC scoring |
| `financial-crime-knowledge-graph` | 📋 Planned | Neo4j graph DB — shell company detection, circular transaction rings |
| `aml-ctf-threat-intelligence` | 📋 Planned | OSINT + STIX/TAXII threat feeds + incident response playbooks |
| `synthetic-financial-crime-dataset` | 📋 Planned | GAN-generated transaction networks for AML research — Hugging Face |

---

## 📊 Other Featured Projects

### Argus Investigator — Claude-Powered Security Investigation Agent
**Stack:** Python, Anthropic Claude API, Model Context Protocol (MCP), FastAPI, DigitalOcean

Claude-powered investigation agent with MCP tool integration for evidence-grounded security analysis. Engineered cite-or-refuse behaviour so every assertion is bound to a retrieved artifact, designed to prevent hallucinated security claims.

→ [github.com/Cesco556/argus-investigator](https://github.com/Cesco556/argus-investigator)

### Two-Stage ML Network Threat Detection Pipeline — MSc Research
**Stack:** Python, scikit-learn, TensorFlow, PyTorch, XGBoost

Two-stage ensemble model (Random Forest + XGBoost binary, BiLSTM multi-class) with SOC-oriented feature engineering and MITRE ATT&CK-aligned interpretation. Achieved 96.5% F1-score with 97.9% recall. Designed for empirical reproducibility and auditable model behaviour.

### ISO 27005 Enterprise Risk Assessment — Grade A
Enterprise risk assessment for fictional FlightOps Ltd with 14-risk register, ISO 27001 Annex A control mapping, and comprehensive security policies covering Access Control, BYOD, and Incident Response.

### Black-Box Penetration Test (Metasploitable3) — Grade A (91.8%)
Comprehensive black-box security assessment achieving root access through exploitation of 9 services and privilege escalation. Full MITRE ATT&CK kill-chain coverage (10/11 tactics) including initial access, persistence, privilege escalation, and data exfiltration.

### Monzo Intigriti AI-Orchestrated Bug Bounty Hunt — Active
Multi-agent offensive-security pipeline (Map / Authorisation / Logic / Report specialists coordinated by an Orchestrator) targeting Monzo's public Intigriti scope. Reproducible session logging and scope/asset enforcement keeps LLM-assisted recon inside program rules and fully auditable.

---

## 📈 Academic Highlights

- **Penetration Testing:** 91.8% (Grade A) — Root access on 9 services, full MITRE ATT&CK mapping
- **ISO 27005 Risk Assessment:** Grade A — 14-risk register, ISO 27001 controls
- **ML Intrusion Detection:** 96.5% F1-score — Random Forest + XGBoost + BiLSTM pipeline

---

## 🛠️ Technical Stack

**Security Tools:** Splunk, ELK, Wireshark, Nmap, Burp Suite, Metasploit, OWASP ZAP, Snort, Suricata, Gobuster, Kali Linux

**ML / Data Science:** Python, scikit-learn, XGBoost, TensorFlow/Keras, PyTorch, pandas, NetworkX, SMOTE

**Frameworks & Standards:** NIST CSF, NCSC CAF v4, ISO 27001, ISO 27005, MITRE ATT&CK, OWASP Top 10, UK GDPR, PCI DSS

**Cloud & Infrastructure:** AWS (EC2, S3, IAM, CloudWatch), Azure AD, Docker Compose, PostgreSQL, Redis, Alembic, GitHub Actions

**Programming:** Python, SQL, Bash, PowerShell | FastAPI, SQLAlchemy

**Systems:** Linux (Kali, Ubuntu), Windows

---

## 🏆 Certifications

- **CompTIA Security+** (SY0-701) — 2025
- **TryHackMe** — Pre-Security Path (Completed), SOC Level 1 (In Progress)
- Cyvant Ethical Hacking Bootcamp
- GoMyCode Cybersecurity Bootcamp

---

## 🎯 Current Focus

Targeting **Information Security Analyst** roles — risk methodology, governance, audit-readable measurement, and security operations — with particular interest in:

- **UK Public Sector Cyber Resilience** — Scottish councils, NHS Scotland, central government
- **Financial Services Cybersecurity** — banks, FinTech, payment processors
- **Cyber Risk and Compliance** — Big 4 advisory, specialist consultancies
- **Statutory financial-accountability frameworks** for cyber response (Section 95 / Section 151 territory)

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Cesco556&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Cesco556&layout=compact&theme=dark&hide_border=true)

---

## 📫 Connect

- **Email:** francescoojoko@gmail.com
- **LinkedIn:** [linkedin.com/in/francesco-ojoko](https://linkedin.com/in/francesco-ojoko)
- **Location:** Aberdeen, Scotland, UK

---

*Bridging Banking & Finance with Cybersecurity to make risk decisions that are technical, defensible, and audit-ready. Code speaks louder than CVs.*
