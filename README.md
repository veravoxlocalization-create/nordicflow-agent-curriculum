# NordicFlow & VeraVox Agentic Curriculum & Localization Hub
## Purpose & Operational Loop
This repository serves as a dual-purpose engine:
1. **An Agent-Operable Study Harness:** AI agents read these files to proctor, simulate, and drill technical and regulatory scenarios.
2. **A Multilingual Localization Matrix:** A cross-lingual technical glossary spanning 7+ languages for software copy re-engineering under VeraVox.
---
## 1. Agent Boot Sequence & State Integration
When initiating an agent session, execute the following boot sequence:
1. **Read State:** Load `STUDY_STATE.md` to parse current mastery metrics and identified weak points.
2. **Calibrate Difficulty:** Set the Socratic proctoring level (1 to 5) based on the user's recorded mastery score for the selected module.
3. **Execute Drill:** Inject failure scenarios targeting the active study queue.
4. **Update State:** Upon session completion, append new mastery scores and weak points back into `STUDY_STATE.md`.
---
## 2. Repository Architecture

| File Name | Domain Focus |
| :--- | :--- |
| **`STUDY_STATE.md`** | Persistent cross-session progress tracker and weak-point registry. |
| **`SKILL_DACH_SOVEREIGN_INFRA.md`** | GDPR, DSGVO, Swiss FADP, EU AI Act compliance & sovereign infrastructure. |
| **`SKILL_DOCKER_K8S_INFRA.md`** | Containerization, kernel isolation (cgroups, seccomp), and vanilla Kubernetes. |
| **`SKILL_EMAIL_GEO_DELIVERABILITY.md`** | DNS engineering, SPF/DKIM/DMARC, CNAME alignment, and GEO optimization. |
| **`SKILL_REGIONAL_GTM.md`** | Regional positioning, "Mechanic" vs. "Wizard" copy, and Fachbegriffe. |
| **`SKILL_MULTILINGUAL_TERMINOLOGY.md`** | Cross-searching technical concepts across English, Spanish, German, Portuguese, Italian, French, and Japanese. |
