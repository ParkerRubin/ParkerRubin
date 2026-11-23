# Parker Rubin

CS and Cybersecurity Systems (BSAI) dual degree student at Florida Atlantic University (Class of 2028, GPA 3.8, Dean's List). IT Infrastructure Intern on NCCI's Platform & Network Engineering team, previously a SOC Analyst Intern at Arete IR. Blue Team competitor for FAU's Cybersecurity Club and 1st place at SFISSA Hack the Flag 2026.

Focus areas: SOC operations, incident response, threat hunting, and infrastructure as code.

## Work Experience

**IT Infrastructure Intern, Platform & Network Engineering, NCCI** (Nov 2026 - Present)
- Provisioning and managing infrastructure as code with Terraform and Ansible, building Python and Bash automation, and refining monitoring, alerting, and site reliability across Linux systems
- Contributing to an enterprise Oracle Cloud (OCI) migration, rotating onto the Network & Telecom team at the midpoint

**SOC Analyst Intern, Arete IR** (Jan 2026 - Jun 2026)
- Triaged and resolved ~9,600 SentinelOne EDR alerts, pivoting across process, file, and network events in Storyline to speed up true/false-positive calls
- Built a custom Deep Visibility (S1QL) hunting query that surfaced malware hidden in endpoint AppData\Local, closing a detection gap across ~20 endpoints spanning 15 client accounts
- Authored the investigation playbook for flagged files and PDF-embedded riskware, using RemoteOps to locate, collect, hash, and block them
- Investigated Microsoft Sentinel and Azure/Entra ID sign-in logs for anomalous logins and cloud IOCs, and escalated ~50 client-impacting incidents with detailed write-ups
- Mapped adversary behavior to MITRE ATT&CK and validated IOCs with VirusTotal and Joe Sandbox
- Wrote SOC training documentation supporting analyst onboarding

## Projects

**[Homelab](https://github.com/ParkerRubin/homelab)** (Nov 2026 - Present)
Single-node k3s Kubernetes cluster on an Intel NUC, deployed with declarative YAML and Helm. Runs network-wide DNS filtering for the house (AdGuard Home), Prometheus and Grafana monitoring with custom alert rules, Jellyfin, and a self-hosted Vaultwarden password manager. Remote access through a Tailscale subnet router with split DNS and TLS.

**SOC Competition Scripts** (Nov 2025 - Present)
Cross-platform Blue Team toolkit for CCDC/WRCCDC-style competitions: PowerShell scripts that snapshot baseline system state, cross-reference open ports against firewall rules, flag persistence mechanisms and unsigned binaries, and harden Windows with a deny-by-default firewall policy, plus a Linux enumeration module for fast triage under time pressure. Includes a Sysinternals installer for deeper investigation, built around a snapshot-before-hardening workflow so rollback and tamper detection stay intact.

**SentryOS, EDR Platform** (Sep 2026)
Three-component EDR platform: a Windows Service agent running Sysmon for telemetry, a FastAPI backend for threat evaluation, and a server-rendered console for reviewing detections. Real-time detection with process lineage visualization, incident correlation across hosts, a rules engine for custom detections, and an AI analyst (Groq) for context-specific alert triage.

**JARVIS, ShellHacks 2026** (Sep 2026)
Voice-controlled desk robot with face tracking and gesture recognition, built at Florida's largest hackathon with ElevenLabs conversational AI, Gemini vision, OpenCV, and an Arduino-driven servo in Python.

## Competitions & Leadership

- **SFISSA Hack the Flag 2026** (Sep 2026): 1st place out of 33 teams at South Florida's biggest annual CTF, sponsored by AWS, Horizon3.ai, and TORQ
- **DOE CyberForce 2026** (Nov 2026): Defended the OpenPLC/Modbus host of a geothermal utility; patched 5 OpenPLC vulnerabilities including an unauthenticated RCE, and removed a PAM backdoor. 32nd of 100 teams
- **CPTC 12 Southeast Regional** (Nov 2026): Web application tester in an 8-hour penetration test of a mock client; built a Bash web recon and vulnerability-probe toolkit
- **Horse Plinko Cyber Challenge 4, UCF** (Oct 2026): Blue Team on a five-box Windows and Linux network against a live Red Team; removed cron backdoors and duplicate-UID accounts and closed an Apache webshell path
- **CCDC Qualifiers** (Sep 2025): 15th place overall; Incident Response 7th/45, Injects 15th/45
- **NCAE Cyber Games** and **Red vs. Blue** (Spring 2026): Blue Team competitor in national Linux and Windows defense events
- **FAU Cybersecurity Club**: Officer, Competitor, Social Media Manager
- Member, National Society of Collegiate Scholars (NSCS)

## Certifications

- SentinelOne IR Engineer (SIREN): Deep Visibility/S1QL threat hunting, Singularity blocklist/exclusion administration, incident handling, and false-positive tuning
- Governance, Risk, Compliance, and Data Privacy, IBM
- Foundations of Cybersecurity, Google
- Microsoft Security Essentials Professional Certificate, Microsoft & LinkedIn (In Progress)

## Skills

**Threat Hunting & Detection:** MITRE ATT&CK mapping, IOC analysis & enrichment, threat intelligence, Windows hardening, log monitoring

**EDR/SIEM:** SentinelOne (Deep Visibility/S1QL, Storyline, RemoteOps Forensics), Microsoft Sentinel, Azure/Entra ID

**Infrastructure & Cloud:** Kubernetes (k3s), Helm, Docker, Terraform, Ansible, Oracle Cloud (OCI), Prometheus, Grafana, Tailscale, Linux

**Scripting & Tools:** Python, PowerShell, Bash, Git, Sysinternals Suite, Wireshark, Snort

**Offensive Security (TryHackMe):** Nmap, Gobuster, Hydra, John the Ripper, enum4linux, smbclient, Netcat, LinPEAS

## Contact

- Email: pdrrubinn@gmail.com
- Portfolio: [parkerrubin.github.io](https://parkerrubin.github.io)
- LinkedIn: [linkedin.com/in/parkerrubin](https://www.linkedin.com/in/parkerrubin)
