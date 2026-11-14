# CMD126

**Cybersecurity Specialist at CROSS-INTEL · Former Portuguese Special Forces (Comandos)**

Security tooling, detection engineering and hands-on infrastructure labs.

[LinkedIn](https://linkedin.com/in/cmdmiguelsousa) · [TryHackMe](https://tryhackme.com/p/LexLucas) · [HackerOne](https://hackerone.com/lexlucas126)

## About

I'm a Cybersecurity Specialist at CROSS-INTEL. Before moving into security, I served in the Portuguese Special Forces (Comandos). I bring that discipline to security work.

I like building the tools I use: network diagnostics, monitoring and triage, log and IOC analysis. I ship them with tests, CI and safe defaults. This profile is the evidence: public code you can read, run and test.

## What I work on

- **Offensive security:** reconnaissance, scanning and exploitation in lab environments
- **Detection and response:** SIEM detections, honeypot alerts, MITRE ATT&CK mapping, triage workflows
- **Infrastructure security:** Active Directory, Group Policy, network access control, hardened services
- **Security tooling:** Python and Bash tools built to treat input as hostile and to be safe by default

## Featured projects

### [roost](https://github.com/CMD126/roost): terminal SOC-lite for homelabs
Monitors Docker containers, hosts and uptime, and keeps a persistent security triage queue of OpenCanary honeypot hits, new LAN devices and newly opened ports.
- Scans private ranges only unless told otherwise; `roost --demo` runs with made-up data
- Hardened against hostile input from the honeypot (markup and terminal escape injection)
- **Stack:** Python, Textual · **Proof:** 90+ tests, CI on Python 3.10–3.13, ruff

### [Network Tool Pro](https://github.com/CMD126/Network_Tool): network diagnostics suite
Around 20 checks (ping, traceroute, DNS, whois, Nmap port and service scans, TLS certificates, HTTP, bandwidth) from an interactive menu or a headless CLI with JSON output. Built for Linux, with macOS and BSD code paths.
- Strict input validation that blocks command injection; refuses to scan public targets without explicit consent
- **Stack:** Bash, Nmap · **Proof:** 52 bats tests, ShellCheck-clean CI, [terminal demo](https://github.com/CMD126/Network_Tool/blob/main/docs/demo.svg)

### [ICC-03 Cybersecurity Portfolio](https://github.com/CMD126/ICC-03-Personal-Repo): 17 security tools from scratch
13 Python and 4 Bash tools written during the ICC-03 cybersecurity program: SSH log analyzer, IOC scanner, AWS IAM policy analyzer, HTTP security headers checker, port scanner, crypto tools and a sandboxed ransomware simulator.
- **Stack:** Python, Bash · **Proof:** 193 offline tests, ruff and ShellCheck in CI

### [Purple Team Security Exercise](https://github.com/RODMS1/Purple-Team-Project): team project
Active Directory lab covering attack execution and detection with Elastic SIEM. The attack sequence was mapped to MITRE ATT&CK; the analysis found evidence of 6 of 14 techniques (43%) and documented detection gaps, including the LSASS dump.
- **My part:** restructured the repository and wrote the red team, blue team and purple team documentation, including the attack path summary and ATT&CK mapping
- **Stack:** Active Directory, Elastic SIEM, MITRE ATT&CK

### [SecureEdge Inc.](https://github.com/RODMS1/SecureEdge-Inc.-Project): team project
Enterprise infrastructure lab with Active Directory, DNS, DHCP, Group Policy, FreeRADIUS NAC, PowerShell user provisioning and an internal Nginx documentation portal.
- **My part:** the Nginx documentation portal and its PowerShell deployment script, the Python network tool and its setup script, plus README and script fixes across the project
- **Stack:** Active Directory, PowerShell, FreeRADIUS, Nginx, Python

<sub>Also: [bash-config](https://github.com/CMD126/bash-config), a small Bash aliases installer for Kali and Debian.</sub>

## Technical skills

| Area | Tools |
|---|---|
| Security testing | Nmap, Burp Suite, Metasploit, Kali Linux |
| Detection and analysis | Elastic SIEM, Wireshark, Suricata, MITRE ATT&CK, OpenCanary |
| Infrastructure | Active Directory, DNS, DHCP, Group Policy, FreeRADIUS, Docker, Nginx |
| Scripting and development | Python, Bash, PowerShell, Textual |
| Engineering practice | pytest, bats, ruff, ShellCheck, GitHub Actions CI |

## Certifications and training

- CRTA
- Segura® Deployment
- Ethical Hacking Penetration Testing
- Ethical Hacking Python
- GoHacking Security Essentials (GHSE)
- OSINT na prática: como transformar rastros digitais em inteligência acionável
- IA em Cibersegurança: como utilizar de forma adequada
- AWS Security Best Practices: Computing
- Cybersecurity Intensive Online Course

## Community

- **BSides Porto 2026, Volunteer Coordinator:** coordinated more than 27 volunteers, handling schedules and team communication during event shifts
- **C-DAYS Portugal:** attendee and community contributor

## Get in touch

Open to conversations about cybersecurity roles and projects. The best way to reach me is a message on [LinkedIn](https://linkedin.com/in/cmdmiguelsousa).
