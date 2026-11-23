<div align="center">

**Blue teamer · SOC analyst · infrastructure builder**

CS + Cybersecurity Systems dual degree @ Florida Atlantic University · Class of 2028

[![Portfolio](https://img.shields.io/badge/Portfolio-parkerrubin.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://parkerrubin.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-parkerrubin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parkerrubin)
[![Email](https://img.shields.io/badge/Email-pdrrubinn%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pdrrubinn@gmail.com)

</div>

---

I hunt threats, harden boxes, and automate the boring parts. I spent six months in a SOC triaging close to 10,000 EDR alerts, now I build and run infrastructure as code on an enterprise network team, and on weekends I'm usually defending a network against a live red team.

- 🛠️ **Now:** IT Infrastructure Intern, Platform & Network Engineering @ **NCCI** (Terraform, Ansible, OCI)
- 🛡️ **Before:** SOC Analyst Intern @ **Arete IR** (SentinelOne, Microsoft Sentinel, Entra ID)
- 🏆 **Latest win:** 1st of 33 teams at SFISSA Hack the Flag 2026
- 🏠 **Tinkering with:** a k3s Kubernetes homelab that runs DNS for my whole house

---

## 🔭 Featured Projects

### 🏠 [Homelab](https://github.com/ParkerRubin/homelab)
Single-node **k3s** cluster on an Intel NUC, deployed with declarative YAML and Helm. Runs network-wide DNS filtering for the house (AdGuard Home), **Prometheus + Grafana** monitoring with custom alert rules, Jellyfin, and a self-hosted Vaultwarden password manager. Reachable from anywhere through a **Tailscale** subnet router with split DNS and TLS.

### 🧰 [SOC Competition Scripts](https://github.com/ParkerRubin/CCDC-Script)
Cross-platform Blue Team toolkit for CCDC/WRCCDC. PowerShell scripts snapshot baseline state, cross-reference open ports against firewall rules, flag persistence and unsigned binaries, and harden Windows with a deny-by-default firewall policy. Includes a Linux triage module and a Sysinternals installer, all built around a snapshot-before-hardening workflow so rollback and tamper detection stay intact.

### 🔍 [SentryOS: EDR Platform](https://parkerrubin.github.io/EDR-Project/index.html)
Three-part EDR: a Windows Service agent running **Sysmon**, a **FastAPI** backend for threat evaluation, and a console for reviewing detections. Real-time process lineage, cross-host incident correlation, a custom rules engine, and an AI analyst (Groq) for alert triage.

### 🤖 [JARVIS @ ShellHacks 2026](https://parkerrubin.github.io/competitions/shellhacks/index.html)
Voice-controlled desk robot with face tracking and gesture recognition, built at Florida's largest hackathon with ElevenLabs, Gemini vision, OpenCV, and an Arduino-driven servo. Drew visits from Waymo and Blackstone reps.

---

## 💼 Experience Highlights

**Arete IR · SOC Analyst Intern** (Jan 2026 to Jun 2026)
- Triaged **~9,600 SentinelOne alerts**, pivoting through Storyline across process, file, and network events
- Wrote a custom **S1QL hunting query** that surfaced malware hiding in AppData\Local, closing a detection gap across ~20 endpoints and 15 client accounts
- Authored the investigation playbook for flagged files and PDF-embedded riskware using RemoteOps
- Investigated Sentinel and Entra ID sign-in logs and escalated **~50 client-impacting incidents**

**NCCI · IT Infrastructure Intern** (Nov 2026 to Present)
- Infrastructure as code with Terraform and Ansible, Python and Bash automation, and monitoring and SRE work on Linux
- Contributing to an enterprise **Oracle Cloud (OCI) migration**

---

## 🏆 Competitions

| Event | Role | Result | Writeup |
|---|---|---|---|
| SFISSA Hack the Flag 2026 | CTF | 🥇 **1st / 33** | [Read →](https://parkerrubin.github.io/competitions/sfissa/index.html) |
| DOE CyberForce 2026 | Blue Team, ICS/PLC defense | 32nd / 100 | [Read →](https://parkerrubin.github.io/competitions/cyberforce/index.html) |
| Horse Plinko Cyber Challenge 4 (UCF) | Blue Team vs. live Red Team | Competitor | [Read →](https://parkerrubin.github.io/competitions/hpcc4/index.html) |
| CCDC Qualifiers | Blue Team | 15th overall · IR 7th/45 | [Read →](https://parkerrubin.github.io/competitions/ccdc/index.html) |
| ShellHacks 2026 (FIU) | Hackathon | Built JARVIS | [Read →](https://parkerrubin.github.io/competitions/shellhacks/index.html) |
| CPTC 12 Southeast Regional | Web app pentester | Competitor | |
| NCAE Cyber Games · Red vs. Blue | Blue Team | Competitor | |

Officer, Competitor, and Social Media Manager for the **FAU Cybersecurity Club** · Member, NSCS

---

## 🧠 Toolbox

**Detection & Response**

![SentinelOne](https://img.shields.io/badge/SentinelOne-6B2FBA?style=flat-square)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysinternals%20%2F%20Sysmon-00A4EF?style=flat-square&logo=windows&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-E31B23?style=flat-square)

**Infrastructure & Cloud**

![Kubernetes](https://img.shields.io/badge/Kubernetes%20(k3s)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Code & Offense**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)

---

## 📜 Certifications

- **SentinelOne IR Engineer (SIREN):** S1QL threat hunting, Singularity blocklist/exclusion admin, incident handling, false-positive tuning
- **Governance, Risk, Compliance & Data Privacy** · IBM
- **Foundations of Cybersecurity** · Google
- **Microsoft Security Essentials Professional Certificate** · Microsoft & LinkedIn *(in progress)*

<div align="center">

---

*Always down to talk detection engineering, CCDC war stories, or homelab rabbit holes.*

</div>
