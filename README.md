# Bassma Alaoui Sossey

Final-Year State Cybersecurity Engineering Student (**Diplôme d'Ingénieur d'État — EIDIA**) at **Université Euromed de Fès (UEMF)**, Morocco (2022–2027).  
Seeking a **6-month End-of-Studies Engineering Internship (PFE — 2027)** in France, Morocco, or Europe across Security Engineering, IAM, Detection/DFIR, DevSecOps, OT/ICS Security, AI Security, and GRC/Risk Engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bassma-alaoui-sossey-009565293)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bassmaalaoui04@gmail.com)

---

## Flagship Cybersecurity Engineering Portfolio

All six repositories ship with automated test suites, Ruff/Bandit security checks, GitHub Actions CI, threat models, and reproducible verification artifacts.

| System | Repository | Domain & Engineering Focus | Verified Evidence |
|---|---|---|---|
| **FORGE** | [`ai-devsecops-telegram-agent`](https://github.com/Bassma202/ai-devsecops-telegram-agent) | **Secure Software Supply Chain & DevSecOps** — OPA Rego v1 policy gates, CycloneDX v1.5 SBOM, Ed25519 artifact signing & tamper detection, hardened non-root containers, reusable GitHub Actions security gate | `8/8` real OPA v1.1.0 tests, `67`-component SBOM, Ed25519 1-byte tamper rejection, `9/9` pytest |
| **CONSERVA** | [`grc-compliance-automation-tool`](https://github.com/Bassma202/grc-compliance-automation-tool) | **Cyber Governance & Quantitative Risk** — Multi-tenant ISO/IEC 27001:2022 SoA (93 structural Annex A controls + 7 ISMS clauses), Moroccan Law 09-08/CNDP mapping, EBIOS RM 4x4, FAIR Beta-PERT Monte Carlo ALE | Analytical Monte Carlo validation (<3% error), cross-tenant 403 & unjustified-exclusion 422 enforcement, 4 fictional cross-sector orgs |
| **LIMEN** | [`zerotrust-iam-oidc-gateway`](https://github.com/Bassma202/zerotrust-iam-oidc-gateway) | **Zero-Trust Identity & Access Governance** — Asymmetric RS256/JWKS OIDC PEP, key rotation, JML lifecycle & temporary access expiration, preventive SoD engine, Jaccard role mining | Verified live against Keycloak 26.0.7 + PostgreSQL 16.6 (`401/200/403` real RS256 token & RBAC checks) |
| **AETHER** | [`scada-modbus-defense-lab`](https://github.com/Bassma202/scada-modbus-defense-lab) | **Industrial & Cyber-Physical Security** — Strict Modbus TCP MBAP framing, HMAC-authenticated process-aware gateway with physical safety interlocks, 3-tier comparative defense & Suricata 7 IDS | Real TCP benchmark (`p50=0.287 ms`, `3,131 req/s`), live port-502 PCAP (`50` pkts) triggering `4/4` Suricata 7.0.8 alerts (`0` false alerts on FC 03) |
| **ALETHEIA** | [`llm-guardrail-security-proxy`](https://github.com/Bassma202/llm-guardrail-security-proxy) | **LLM, RAG & Agent Security Evaluation** — Unicode/Base64 normalization, Luhn/FR-NIR/MA-CIN PII scrubber, pre-retrieval RAG ACLs, JSON-RPC 2.0 MCP symlink-safe tool guard, OWASP LLM 2025 | Live Ollama (`smollm2:360m`) 4-arch ablation: ASR reduced `93.3% -> 6.7%`, `0.0%` FPR, `0.097 ms` guardrail p50, honest failure analysis |
| **VESPER** | [`windows-dfir-atomic-lab`](https://github.com/Bassma202/windows-dfir-atomic-lab) | **Digital Forensics & Detection Engineering** — `pySigma` compilation (Splunk SPL & Elastic Lucene ECS), `python-evtx` + `defusedxml` ingestion, precision/recall/FPR regression, Windows PowerShell triage | `6` compiled MITRE ATT&CK Sigma rules, `100%` precision / `0%` FPR on 12-case regression, dual `ubuntu-latest` + `windows-latest` CI |

---

## Prior Industry Experience
- **Cybersecurity & Data Protection Intern — DataPathology (Casablanca, July–Sept. 2026):** Mapped digital pathology patient data flows, audited access permissions, evaluated Moroccan Law 09-08 / CNDP health-data compliance, and formalized RBAC and audit-logging requirements.

## Core Technical Stack
- **Languages:** Python 3.12, PowerShell, Bash, SQL, Rego (OPA), C
- **Security Engineering:** OAuth 2.0 / OIDC (Keycloak), RS256/JWKS, Ed25519, OPA, CycloneDX SBOM, Suricata 7, Modbus TCP, `pySigma`, `python-evtx`, Docker, GitHub Actions
- **Standards & Frameworks:** ISO/IEC 27001:2022, EBIOS Risk Manager, FAIR Quantitative Risk, Moroccan Law 09-08 (CNDP), IEC 62443, MITRE ATT&CK (Enterprise & ICS), OWASP LLM Top 10 (2025)
- **Languages Spoken:** Arabic (Native), French (Fluent), English (Professional Technical C1), German (Basic)
