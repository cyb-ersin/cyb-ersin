# Hey, I'm Ersin. 👋

**Career changer. 4 CompTIA exams in 10 months. Building toward SOC Operations.**

I don't just study for certifications — I build labs, break things, and document what I find.

[![CompTIA A+](https://img.shields.io/badge/CompTIA-A%2B%20Verified-E31837?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/94b63de0-5ae2-493a-8aa6-7c662843be81/public_url)
[![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B%20Verified-E31837?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/918c6ff2-8d25-4c22-a515-4b8ad013470b/public_url)
[![CompTIA CySA+](https://img.shields.io/badge/CompTIA-CySA%2B%20Certified-E31837?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/580a44f1-f2c6-4c75-88b2-9ffe97a60461/public_url)
[![CompTIA CSAP](https://img.shields.io/badge/CompTIA-CSAP%20Stackable-E31837?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/5c632258-2ad5-4b89-b882-1bac71b78b3b/public_url)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-51%25%20Complete-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/ersinuyanik)

---

### 🎯 Where I'm headed

I'm building a career in **Security Operations** — learning how attacks work in order to detect, analyze, and respond to them effectively.

My goal is to work as a SOC Analyst, contributing to threat detection, alert triage, incident response, and continuous security improvement. The best defenders understand how systems can be broken, so I build labs that reflect realistic attack scenarios and document every finding.

---

### 🛠️ Core Skills

Every tool listed below has been used hands-on in a documented lab — not just read about.

| Area | Tools & Techniques |
| :-- | :-- |
| **Network Analysis** | Wireshark, tcpdump, protocol analysis (ICMP/DNS/HTTP/ARP/TLS), JA3 fingerprinting, TCP lifecycle |
| **Offensive Security** | nmap, hydra, aircrack-ng suite, hcxdumptool, hashcat, MAC spoofing |
| **Detection & Monitoring** | Suricata (IDS), Wazuh (SIEM), MITRE ATT&CK mapping, alert triage |
| **System Hardening** | ufw, iptables, network segmentation, firewall rule design |
| **Forensics** | PCAP analysis, log correlation, timeline reconstruction |
| **Incident Response** | Alert investigation, evidence collection, attack timeline reconstruction, remediation planning |
| **Scripting & Documentation** | Bash, Python (basics), Markdown, Git |

---

### 🔒 Certifications

| Certification | Status | Date |
| --- | --- | --- |
| [CompTIA A+](https://www.credly.com/badges/94b63de0-5ae2-493a-8aa6-7c662843be81/public_url) | ✅ Passed | Jan 2026 |
| [CompTIA Security+](https://www.credly.com/badges/918c6ff2-8d25-4c22-a515-4b8ad013470b/public_url) | ✅ Passed | Mar 2026 |
| [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) | ✅ Passed — 794/900 | Jul 2026 |
| [CompTIA Security Analytics Professional (CSAP)](https://www.credly.com/org/comptia/badge/comptia-security-analytics-professional-csap-stackable-certification) | ✅ Stackable Credential | Jul 2026 |

> The CSAP is a CompTIA stackable credential earned through Security+ and CySA+. It is not a separate exam.

---

## 🧪 Hands-on Labs

I learn by doing. My lab work is split into separate repositories — each with a clear focus, built from scratch and documented end-to-end.

### 📘 [HomeLab Foundation](https://github.com/cyb-ersin/HomeLab_Foundation)
*Networking and security fundamentals — built from scratch, documented end-to-end.*

| # | Lab | Focus | Tools | Status |
| :-- | :-- | :-- | :-- | :--: |
| 0 | Network Discovery | Topology mapping, port scanning, MAC analysis | `nmap` `arp` `ifconfig` | ✅ |
| 1 | Traffic Analysis | ICMP/DNS/HTTP/ARP/TLS, TCP lifecycle, JA3 fingerprinting | `Wireshark` `curl` `nslookup` | ✅ |
| 2 | WiFi Security | WPA2 handshake capture, PMKID attack, deauth, MAC spoofing | `aircrack-ng` `hcxdumptool` `hashcat` | ✅ |
| 3 | Firewall & Segmentation | Host firewall, zone segmentation, brute force detection | `ufw` `iptables` `hydra` | ✅ |

### 🛡️ [HomeLab Project Aegis](https://github.com/cyb-ersin/HomeLab_Project_Aegis)
*Advanced attack/defense series — an organization with zero security visibility, built up chapter by chapter into a fully instrumented detection pipeline.*

| # | Chapter | Scenario Question | Status |
| :-- | :-- | :-- | :--: |
| 01 | IDS Deployment & First Detection | Can we detect a port scan and brute force in real time? | ✅ |
| 02 | Active Defense & Detection Engineering | Can we automatically block an attacker — and detect it in the SIEM? | ✅ |
| 03 | Network Forensics & PCAP Analysis | What does the attack look like at packet level? Can we reconstruct the timeline? | ✅ |
| 04 | Exploitation & Detection | If Metasploit gets a shell, does the IDS see it? | 🔜 |
| 05 | Lateral Movement | Can the SIEM detect movement between hosts after compromise? | 🔜 |
| 06 | Detection Rule Writing | Can we write a Suricata rule that catches a specific threat? | 🔜 |
| 07 | Incident Response | Can we build a full IR timeline and harden the environment? | 🔜 |

### 🚧 HomeLab Vanguard — *Planned*
*Self-built SOC Analyst simulation covering the full detection engineering lifecycle in my own lab.*

Going beyond pre-packaged SOC courses: deploy Splunk, ELK, and Security Onion, generate telemetry with MITRE ATT&CK techniques, write Sigma and SPL detections, and run timed L1 triage shifts with realistic mixed traffic. Built as a capstone on top of Aegis.

| # | Chapter | Focus | Status |
| :-- | :-- | :-- | :--: |
| 01 | Splunk Deployment & Ingestion | SPL fundamentals, data inputs, dashboards | 🔜 |
| 02 | ELK Stack & Kibana | Same data, different stack — KQL practice | 🔜 |
| 03 | Security Onion Evaluation | Integrated NSM distribution with Zeek logs | 🔜 |
| 04 | Telemetry with Atomic Red Team | MITRE ATT&CK adversary emulation | 🔜 |
| 05 | Detection Engineering — Sigma, SPL, Regex | Write once, deploy across platforms | 🔜 |
| 06 | L1 Triage Simulation | Timed two-hour shifts with noise and real attacks | 🔜 |
| 07 | Case Reporting & Methodology | 5W, IOC, MITRE, and remediation templates | 🔜 |

### 🔬 HomeLab Forensics — *Planned*
*Digital forensics and incident response — disk imaging, filesystem analysis, and timeline reconstruction.*

Post-mortem investigation of compromised systems using industry-standard DFIR tools and public sample datasets from Digital Corpora and NIST CFReDS.

| # | Chapter | Focus | Status |
| :-- | :-- | :-- | :--: |
| 01 | Disk Imaging Fundamentals | `dd`, hashing, chain of custody | 🔜 |
| 02 | Sleuth Kit CLI | `fls`, `icat`, `mmls` — filesystem analysis from the command line | 🔜 |
| 03 | Autopsy GUI | Analyze the same image through a structured GUI workflow | 🔜 |
| 04 | Timeline Reconstruction | `mactime`, MAC times, event correlation | 🔜 |
| 05 | Memory Forensics | Volatility 3 on memory captures | 🔜 |
| 06 | Full Case Study | Infected image → IOCs → timeline → root cause report | 🔜 |

---

### 📌 Currently

- ✅ CompTIA CySA+ certified with a score of **794/900**
- 🛠️ Next up: **Aegis Ch.04 — Exploitation & Detection**
- 🎯 Preparing for a **Junior SOC Analyst / SOC Analyst L1** role
- 📂 Continuing to build hands-on Blue Team, detection, and incident response projects
- 🎓 Cybersecurity **Weiterbildung** in Germany — finishing in November 2026
- 💻 **TryHackMe** Cybersecurity 101 — 51% complete

---

### 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ersin%20Uyanik-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ersin-uyanik)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-ersinuyanik-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/ersinuyanik)
[![Website](https://img.shields.io/badge/Web-ersinuyanik.de-4A90E2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.ersinuyanik.de)

---

*Started from zero. 4 exams in 10 months. Still learning, still building.* 🚀
