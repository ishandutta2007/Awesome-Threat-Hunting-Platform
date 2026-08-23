# Awesome-Threat-Hunting-Platform

## Top Threat Hunting Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Proactive Threat Hunting, Detection Engineering, Managed Hunting Services, XDR/SIEM Analytics & Adversary Tracking*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Threat Hunting**. These tools and services enable security teams (or managed providers) to proactively search for stealthy adversaries, develop detection content, investigate high-fidelity leads, and reduce dwell time beyond traditional alert-driven SOC operations.



**Examples** include Hunters, CrowdStrike Falcon OverWatch, Microsoft Defender Experts, SentinelOne Deep Visibility / Vigilance, Elastic Security, LogRhythm, Exabeam, Google SecOps, Devo Security, Uptycs, Huntress, Red Canary, Intezer, Cybereason, Arctic Wolf, and Mandiant Managed Defense (the category leaders and major managed offerings).



**Open-source emphasis**: The open-source ecosystem for threat hunting is robust. **Wazuh**, **Elastic Security**, **Security Onion**, **Sigma**, and related projects form the foundation of many self-hosted hunting stacks. This section is heavily expanded with practical open alternatives and supporting tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Hunters](https://www.hunters.security/)**  

  Data-agnostic threat hunting and detection platform that sits on top of existing data lakes/SIEMs, emphasizing detection-as-code and high-fidelity hunting workflows.



- **[CrowdStrike Falcon OverWatch](https://www.crowdstrike.com/)**  

  Elite 24/7 managed threat hunting service that operates on Falcon telemetry to uncover human-operated and stealthy attacks missed by automated detections.



- **[Microsoft Defender Experts / Microsoft Security Experts](https://www.microsoft.com/security)**  

  Managed hunting and expert services layered on Microsoft Defender XDR and Sentinel for organizations in the Microsoft ecosystem.



- **[SentinelOne Deep Visibility / Vigilance / WatchTower](https://www.sentinelone.com/)**  

  Deep endpoint and XDR visibility combined with managed threat hunting and MDR services on the Singularity platform.



- **[Elastic Security](https://www.elastic.co/security)**  

  Powerful SIEM and security analytics platform (open-source core available) with strong query languages (KQL/EQL), detection engine, and timeline investigation features ideal for hunting.



- **[LogRhythm](https://logrhythm.com/)**  

  SIEM and security operations platform with analytics and hunting capabilities for mid-to-large organizations.



- **[Exabeam](https://www.exabeam.com/)**  

  Security analytics and SIEM platform known for behavioral analytics, timelines, and support for detection and hunting workflows.



- **[Google SecOps (Chronicle)](https://cloud.google.com/security/products/secops)**  

  Google’s security operations platform offering high-speed search, detection, and hunting across large volumes of security telemetry.



- **[Devo Security](https://www.devo.com/)**  

  Cloud-native security analytics platform supporting real-time and historical hunting across diverse data sources.



- **[Uptycs](https://www.uptycs.com/)**  

  Unified CNAPP and security analytics platform with strong osquery-based telemetry useful for hunting across endpoints and cloud.



- **[Huntress](https://www.huntress.com/)**  

  Managed security platform popular with MSPs and mid-market organizations, combining EDR with human threat hunting and response.



- **[Red Canary](https://www.redcanary.com/)**  

  Managed detection and response provider with strong threat hunting and detection engineering capabilities across multiple EDR backends.



- **[Intezer](https://www.intezer.com/)**  

  Genetic malware analysis and threat detection platform that aids hunting and investigation of code reuse and advanced threats.



- **[Cybereason](https://www.cybereason.com/)**  

  Defense platform with hunting and investigation features focused on detecting and disrupting advanced attacks.



- **[Arctic Wolf](https://arcticwolf.com/)**  

  Managed detection and response / security operations platform delivering continuous monitoring and hunting as a service.



- **[Mandiant Managed Defense](https://www.mandiant.com/)**  

  Elite managed threat hunting and detection service from Mandiant (Google Cloud), leveraging frontline intelligence and expertise.



## Open-Source GitHub Projects

- **[Wazuh](https://github.com/wazuh/wazuh)**  

  Leading open-source XDR/SIEM platform with log analysis, file integrity monitoring, vulnerability detection, and extensible rules — widely used as a foundation for threat hunting.



- **[Elastic Security (ELK Stack)](https://github.com/elastic)**  

  Open-source search and analytics stack that powers many hunting environments; supports powerful queries, detection rules, timelines, and machine-learning jobs.



- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)**  

  Free and open Linux distribution purpose-built for threat hunting, network security monitoring, and log management (includes Suricata, Zeek, Elastic, etc.).



- **[SigmaHQ / Sigma rules](https://github.com/SigmaHQ/sigma)**  

  Generic open signature format and large community repository of detection rules that can be converted to many SIEM/query languages for hunting and detection engineering.



- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  Open-source cyber threat intelligence platform for structuring, storing, and visualizing threat knowledge that feeds hunting hypotheses.



- **[HEARTH (THOR Collective)](https://github.com/THORCollective/HEARTH)**  

  Community-driven library of threat hunting hypotheses and methodologies organized around structured frameworks.



- **[Threat Hunt Catalog and Sigma-to-query tools](https://github.com/)**  

  Projects that turn Sigma rules into actionable queries for OpenSearch/Elastic and help analysts launch multi-rule hunts quickly.



- **[Senrigan and cloud-specific hunting platforms](https://github.com/Yamato-Security/senrigan)**  

  Offline open-source platforms focused on AWS CloudTrail (and similar) DFIR and threat hunting with built-in hunts and dashboards.



- **[CrowdSec](https://github.com/crowdsecurity/crowdsec)**  

  Open-source, collaborative security engine that detects malicious behavior and shares signals, useful as a complementary detection and hunting data source.



- **[Quarry and agentic SOC experiments](https://github.com/)**  

  Emerging open-source AI-assisted security operations and hunting platforms that combine agents, graphs, and detection content.



### Additional Strong Open-Source Options

- OSQuery and Fleet for endpoint visibility and hunting queries.

- Zeek / Suricata + Arkime for network hunting.

- TheHive + Cortex for case management and observable enrichment during hunts.

- MISP for sharing and consuming threat intelligence that drives hunts.

- Custom Jupyter / notebook-based hunting environments on top of data lakes.

- Detection-as-code repositories and CI pipelines for testing hunting content.



**Frameworks for building custom systems**: Combine **Wazuh** or **Elastic Security** (or **Security Onion**) as the core data and detection platform, ingest endpoint/network/cloud telemetry, apply **Sigma** rules and custom hunting queries, enrich with **OpenCTI**/MISP intelligence, and manage investigations in TheHive or a similar open case system. Add hypothesis libraries from **HEARTH** and schedule recurring hunts. This stack provides a complete, self-hosted threat hunting capability with full data ownership and no per-endpoint hunting license fees, though it requires skilled analysts and ongoing detection engineering effort.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Threat hunting involves sensitive security data and high-stakes decisions. Open-source platforms offer excellent transparency and cost control but still require proper architecture, tuning, threat intelligence, and skilled operators to be effective. Managed hunting services add human expertise that pure tooling cannot fully replace.

- Always validate detections and hunting results in context before taking response actions.



---

**Made for threat hunters, detection engineers, and SOC teams building proactive defense capabilities.**

Let's make threat hunting more accessible, collaborative, and grounded in open tools and shared knowledge.
