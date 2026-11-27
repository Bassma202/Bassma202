# Bassma Alaoui Sossey

Final-Year State Cybersecurity Engineering Student (**Diplôme d'Ingénieur d'État — EIDIA**) at **Université Euromed de Fès (UEMF)**, Morocco (2022–2027).  
Seeking a **6-month End-of-Studies Engineering Internship (PFE — 2027)** in France, Morocco, or Europe across Security Engineering, IAM, Detection/DFIR, DevSecOps, OT/ICS Security, AI Security, and GRC/Risk Engineering.

[![Official Website](https://img.shields.io/badge/Official_Website-bassma202.github.io-0ea5e9?style=for-the-badge&logo=google-chrome&logoColor=white)](https://bassma202.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bassma-alaoui-sossey-009565293)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bassmaalaoui04@gmail.com)

---

## Flagship Cybersecurity Engineering Portfolio

All six repositories ship with automated test suites, Ruff/Bandit security checks, GitHub Actions CI, threat models, honest scope/limitation statements, and reproducible verification artifacts.

| System | Repository | Domain & Engineering Focus | Verified Evidence |
|---|---|---|---|
| **FORGE** | [`ai-devsecops-telegram-agent`](https://github.com/Bassma202/ai-devsecops-telegram-agent) | **Secure Software Supply Chain & DevSecOps** — Fail-closed Bandit/OPA Rego v1 gates, CycloneDX v1.5 SBOM, Ed25519 signing/tamper checks, live HTTP local release deploy/rollback, state-machine ChatOps, reusable SHA-pinned CI gate | `8/8` OPA `1.1.0` tests, `67`-component SBOM, Ed25519 1-byte tamper block, live HTTP deploy/broken-candidate/rollback, `13/13` pytest |
| **CONSERVA** | [`grc-compliance-automation-tool`](https://github.com/Bassma202/grc-compliance-automation-tool) | **Cyber Governance & Quantitative Risk** — Bearer-authenticated multi-tenant ISO/IEC 27001:2022 SoA (93 Annex A controls + 7 ISMS clauses), Law 09-08/CNDP, EBIOS RM, compound Poisson–Beta-PERT FAIR Monte Carlo | Analytical mean (`<3%`) & Law-of-Total-Variance std (`<4%`) checks, exact midrank Spearman, UUID SQLite persistence, cross-tenant `401/403` & `422` |
| **LIMEN** | [`zerotrust-iam-oidc-gateway`](https://github.com/Bassma202/zerotrust-iam-oidc-gateway) | **Zero-Trust Identity & Access Governance** — Client-scoped RS256/JWKS OIDC PEP, fail-closed tenant claims, live persistent JML revocation in PEP, atomic `BEGIN IMMEDIATE` cumulative SoD, Jaccard role mining | Verified live against Keycloak `26.0.7` + PostgreSQL `16.6` (`401/200/403` real RS256 token & tenant/RBAC checks), SHA-pinned FORGE CI |
| **AETHER** | [`scada-modbus-defense-lab`](https://github.com/Bassma202/scada-modbus-defense-lab) | **Industrial & Cyber-Physical Security** — Bounded Modbus TCP + HMAC/nonce replay-resistant gateway, default-deny read/write RBAC, deadlock-free locks, authoritative PLC safety interlocks, Suricata 7 IDS | Real TCP benchmark (`p50=0.292 ms`, `3,040 req/s`), 27-thread race safety verified, live port-502 PCAP (`50` pkts) triggering `4/4` Suricata `7.0.8` alerts (`0` FP) |
| **ALETHEIA** | [`llm-guardrail-security-proxy`](https://github.com/Bassma202/llm-guardrail-security-proxy) | **LLM, RAG & Agent Security Evaluation** — Server-derived Bearer auth, Unicode/Base64 guardrails, Luhn/FR-NIR/MA-CIN scrubber, pre-retrieval RAG ACLs, symlink-safe JSON-RPC 2.0 MCP guard, split datasets & immutable run ledger | Live Ollama (`smollm2:360m`) 40-case frozen held-out ablation: Actual Policy Violation `58.3% -> 0.0%` (95% Wilson CI `[0.0%, 13.8%]`), Guardrail Bypass `12.5%` (`3/24`), `0.0%` false refusal, `0.102 ms` guardrail p50 |
| **VESPER** | [`windows-dfir-atomic-lab`](https://github.com/Bassma202/windows-dfir-atomic-lab) | **Digital Forensics & Detection Engineering** — Isolated per-backend `pySigma` compilation (Splunk SPL & Elastic ECS), strict Sigma subset + logsource enforcement, `python-evtx`/`defusedxml`, manifest hash & evidence-gated case workbench | `6` compiled MITRE ATT&CK Sigma rules with static query parity, `100%` precision / `0%` FPR on 12-case regression, dual `ubuntu-latest` + `windows-latest` CI |

---

## Prior Industry Experience
- **Cybersecurity & Data Protection Intern — DataPathology (Casablanca, July–Sept. 2026):** Mapped digital pathology patient data flows, audited access permissions, evaluated Moroccan Law 09-08 / CNDP health-data compliance, and formalized RBAC and audit-logging requirements.

## Core Technical Stack
- **Languages:** Python 3.12, PowerShell, Bash, SQL, Rego (OPA), C
- **Security Engineering:** OAuth 2.0 / OIDC (Keycloak), RS256/JWKS, Ed25519, OPA, CycloneDX SBOM, Suricata 7, Modbus TCP, `pySigma`, `python-evtx`, Docker, GitHub Actions
- **Standards & Frameworks:** ISO/IEC 27001:2022, EBIOS Risk Manager, FAIR Quantitative Risk, Moroccan Law 09-08 (CNDP), IEC 62443, MITRE ATT&CK (Enterprise & ICS), OWASP LLM Top 10 (2025)
- **Languages Spoken:** Arabic (Native), French (Fluent), English (Professional Technical C1), German (Basic)
