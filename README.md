# secbyte-soar-security-automation-drift-governance-ctf-labs
A practical collection of cybersecurity CTF labs covering Security Orchestration, Automation, and Response (SOAR), automated threat response, automation drift, rogue bots, self-healing pipeline security, language-specific automation (Bash, PowerShell, Python), API token drift, compliance drift, and corporate governance audit incidents.
# SOAR Orchestration, Automation Drift, Security Governance & Threat Modeling CTF Labs

Welcome to the **SOAR Orchestration, Automation Drift, Security Governance & Threat Modeling CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on automated response platforms, script stability, operational drift, and enterprise security governance—spanning **SOAR Platforms & Automated Incident Response (Canary tokens, orchestrator incidents, automated playbooks)**, **Language-Specific Automation & Pipeline Execution (Bash, PowerShell, Python, API token drift)**, **Automation Drift & Rogue Systems (Self-healing pipeline security, rogue bot triage, FlowForge fallout)**, and **Enterprise Governance & Compliance Drift (Threat model drift, board audit incidents, build-breaking compliance)**.

---

## Lab Collection Index

### 1. SOAR Platforms & Automated Incident Response
* **SOAR Fundamentals: The Orchestrator Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soar-fundamentals-the-orchestrator-incident](https://learn.secbyte.org/ctf/soar-fundamentals-the-orchestrator-incident)  
  *Focus:* Core architecture of Security Orchestration, Automation, and Response (SOAR) platforms, dissecting failing playbooks, parsing orchestration engine execution logs, and fixing broken integration actions.

<Image src="image_agent_tag_13658012176850891320" alt="SOAR platform ecosystem diagram showing ingestion, orchestration, automation, and response" caption="SOAR Orchestration & Automated Incident Response Lifecycle" />

---

* **Automated Threat Response: Canary That Cried Wolf**  
  *Lab Link:* [https://learn.secbyte.org/ctf/automated-threat-response-canary-that-cried-wolf](https://learn.secbyte.org/ctf/automated-threat-response-canary-that-cried-wolf)  
  *Focus:* Investigating automated containment runbooks triggered by false-positive canary tokens, tuning canary alert thresholds, and preventing automated denial-of-service against internal hosts.

### 2. Multi-Language Automation & API Token Drift
* **API Automation: Token Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-automation-token-drift](https://learn.secbyte.org/ctf/api-automation-token-drift)  
  *Focus:* Tracking authorization token degradation in automated API integrations, managing OAuth2 token refresh workflows, securing stored API keys, and handling unexpected token revocations.

* **Bash Automation: Broken Deploy Pipeline**  
  *Lab Link:* [https://learn.secbyte.org/ctf/bash-automation-broken-deploy-pipeline](https://learn.secbyte.org/ctf/bash-automation-broken-deploy-pipeline)  
  *Focus:* Triaging broken deployment scripts in CI/CD pipelines, handling unhandled error states in Shell scripts (`set -eo pipefail`), preventing parameter injection, and restoring build stability.

* **PowerShell Automation: The Script That Slipped**  
  *Lab Link:* [https://learn.secbyte.org/ctf/powershell-automation-the-script-that-slipped](https://learn.secbyte.org/ctf/powershell-automation-the-script-that-slipped)  
  *Focus:* Auditing administrative PowerShell automation scripts, handling credential exposure in script parameters, enforcing ExecutionPolicy standards, and analyzing transcription logs.

* **Python Automation for Security: Log Sentry**  
  *Lab Link:* [https://learn.secbyte.org/ctf/python-automation-for-security-log-sentry](https://learn.secbyte.org/ctf/python-automation-for-security-log-sentry)  
  *Focus:* Developing resilient Python log sentry daemons, implementing memory-efficient file tailing, handling log rotation edge cases, and forwarding real-time alerts to SIEM endpoints.

### 3. Automation Drift & Rogue Automated Systems
* **FlowForge Fallout**  
  *Lab Link:* [https://learn.secbyte.org/ctf/flowforge-fallout](https://learn.secbyte.org/ctf/flowforge-fallout)  
  *Focus:* Investigating complex visual workflow automation compromises, auditing Node-RED / FlowForge pipeline security, and isolating backdoored automation nodes.

* **Automation Drift: Securing the Self-Healing Pipeline**  
  *Lab Link:* [https://learn.secbyte.org/ctf/automation-drift-securing-the-self-healing-pipeline](https://learn.secbyte.org/ctf/automation-drift-securing-the-self-healing-pipeline)  
  *Focus:* Identifying unintended behavior changes in self-healing infrastructure scripts, securing automated state reconciliation loops, and implementing safety circuit breakers.

* **Automation Drift: Night the Bots Went Rogue**  
  *Lab Link:* [https://learn.secbyte.org/ctf/automation-drift-night-the-bots-went-rogue](https://learn.secbyte.org/ctf/automation-drift-night-the-bots-went-rogue)  
  *Focus:* Responding to runaway automation bot loops, diagnosing race conditions across distributed microservice scripts, executing emergency bot kill switches, and auditing bot service accounts.

### 4. Enterprise Security Governance, Audit & Threat Modeling
* **Governance Drift: Board Audit Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/governance-drift-board-audit-incident](https://learn.secbyte.org/ctf/governance-drift-board-audit-incident)  
  *Focus:* Resolving discrepancies between corporate security policies and technical controls during executive board audits, identifying shadow IT practices, and remediating compliance gaps.

<Image src="image_agent_tag_13658012176850891513" alt="Data governance and security diagram detailing compliance, access control, and risk management" caption="Enterprise Security Governance & Compliance Management Framework" />

---

* **AtlasCorp Threat Model Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/atlascorp-threat-model-drift](https://learn.secbyte.org/ctf/atlascorp-threat-model-drift)  
  *Focus:* Auditing legacy threat models against modern infrastructure shifts (STRIDE methodology), identifying unmapped trust boundaries, and updating risk registries after cloud migrations.

* **Compliance Drift: Audit Broke Build**  
  *Lab Link:* [https://learn.secbyte.org/ctf/compliance-drift-audit-broke-build](https://learn.secbyte.org/ctf/compliance-drift-audit-broke-build)  
  *Focus:* Triaging build pipeline failures caused by aggressive automated compliance scanning tools, tuning static code analysis rules (SAST), and balancing speed with compliance enforcement.

---

## Learning Path

### Path A: SOAR & Automation Security Specialist
1. **Orchestration Foundations:** Start with [SOAR Fundamentals: The Orchestrator Incident](https://learn.secbyte.org/ctf/soar-fundamentals-the-orchestrator-incident) and [Automated Threat Response](https://learn.secbyte.org/ctf/automated-threat-response-canary-that-cried-wolf).
2. **Multi-Language Automation:** Secure automation code via [API Automation: Token Drift](https://learn.secbyte.org/ctf/api-automation-token-drift), [Bash Automation](https://learn.secbyte.org/ctf/bash-automation-broken-deploy-pipeline), [PowerShell Automation](https://learn.secbyte.org/ctf/powershell-automation-the-script-that-slipped), and [Python Automation for Security](https://learn.secbyte.org/ctf/python-automation-for-security-log-sentry).

### Path B: Automation Drift & Self-Healing Pipeline Engineer
1. **Pipeline & Rogue Bot Triage:** Triage automation failures using [FlowForge Fallout](https://learn.secbyte.org/ctf/flowforge-fallout), [Automation Drift: Securing the Self-Healing Pipeline](https://learn.secbyte.org/ctf/automation-drift-securing-the-self-healing-pipeline), and [Automation Drift: Night the Bots Went Rogue](https://learn.secbyte.org/ctf/automation-drift-night-the-bots-went-rogue).

### Path C: Enterprise Governance, Audit & Threat Modeling Specialist
1. **Governance & Auditing:** Align controls with board requirements in [Governance Drift: Board Audit Incident](https://learn.secbyte.org/ctf/governance-drift-board-audit-incident) and [Compliance Drift: Audit Broke Build](https://learn.secbyte.org/ctf/compliance-drift-audit-broke-build).
2. **Threat Modeling:** Update corporate risk boundaries in [AtlasCorp Threat Model Drift](https://learn.secbyte.org/ctf/atlascorp-threat-model-drift).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario requirements, SOAR playbook YAMLs, pipeline configuration scripts, or corporate threat model documents.
4. Debug broken SOAR orchestrator playbooks, isolate runaway automation bots, handle API token drift, or align pipeline compliance scans with corporate governance policies to capture flags.

---

## Target Audience

* **SOAR Engineers & SOC Automation Specialists:** Build and debug automated incident response playbooks, tune canary alert triggers, and manage orchestrator integrations.
* **DevSecOps Engineers & Site Reliability Engineers (SREs):** Secure self-healing pipelines, eliminate automation drift, manage API token rotation, and fix broken deployment scripts.
* **Security Governance & Risk Officers (GRC):** Audit enterprise threat models, manage compliance drift in CI/CD pipelines, and align technical controls with executive board standards.
* **Cybersecurity Students:** Acquire practical experience with modern SOAR platforms, security scripting across Bash/PowerShell/Python, and cloud threat modeling.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, script execution, or testing against external production infrastructure is strictly prohibited.
