<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img src="assets/banner.svg" alt="Commit graph of the CMD126 repositories: one lane per repository, all converging on HEAD." width="830">
  </picture>
</p>

**Cybersecurity specialist in Portugal. I build security tooling and detection, with tests and CI.**

Currently at CROSS-INTEL. Before security, the Portuguese Special Forces (Comandos). The code below is public, and the pinned repositories sit right under this page.

[LinkedIn](https://linkedin.com/in/cmdmiguelsousa) | [TryHackMe](https://tryhackme.com/p/LexLucas) | [HackerOne](https://hackerone.com/lexlucas126)

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/CMD126/roost">roost</a></b><br>
Terminal SOC-lite for homelabs. Watches Docker containers, hosts and uptime, and keeps a triage queue of honeypot hits, new LAN devices and newly opened ports. Scans private ranges only unless told otherwise, and treats honeypot input as hostile.<br>
<sub>Python, Textual. 91 tests, CI on Python 3.10 to 3.13.</sub>
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/CMD126/Network_Tool">Network Tool Pro</a></b><br>
Network diagnostics in Bash: around 20 checks (ping, DNS, whois, Nmap scans, TLS, HTTP) from a menu or a headless CLI with JSON output. Input is validated against command injection and public targets are refused without consent.<br>
<sub>Bash, Nmap. 56 bats tests, ShellCheck-clean CI.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/CMD126/ICC-03-Personal-Repo">ICC-03 Cybersecurity Portfolio</a></b><br>
17 security tools written from scratch (13 Python, 4 Bash): SSH log analyzer, IOC scanner, AWS IAM policy analyzer, HTTP security headers checker, port scanner and a sandboxed ransomware simulator.<br>
<sub>Python, Bash. 193 offline tests with the optional packages installed, ruff and ShellCheck in CI.</sub>
</td>
<td width="50%" valign="top">
<b>Tracelight</b> (private repository)<br>
Local, case-centric OSINT tool with consent gates, a hash-chained audit log and a hardened web UI that only listens on 127.0.0.1. Happy to walk through it.<br>
<sub>Python, FastAPI. 550 tests, CI on Linux and Windows.</sub>
</td>
</tr>
</table>

## Team labs

- **[Purple Team Security Exercise](https://github.com/CMD126/Purple-Team-Project):** Active Directory lab with attack and detection on Elastic SIEM. The analysis found evidence of 6 of 14 mapped ATT&CK techniques (43%) and documented the gaps, including the LSASS dump. My part: I restructured the repository and wrote the red, blue and purple team documentation.
- **[SecureEdge Inc.](https://github.com/CMD126/SecureEdge-Inc.-Project):** enterprise lab with Active Directory, FreeRADIUS network access control, PowerShell provisioning and an internal Nginx portal. My part: the Nginx documentation portal and its deployment script, and the Python network tool.

Also: [bash-config](https://github.com/CMD126/bash-config), a small Bash aliases installer for Kali and Debian.

## Stack

Python, Bash, PowerShell, FastAPI, Textual, Nmap, Elastic SIEM, MITRE ATT&CK, OpenCanary, Active Directory, FreeRADIUS, Nginx, Docker, pytest, bats, ruff, ShellCheck, GitHub Actions.
Also used in labs: Kali Linux, Burp Suite, Metasploit, Wireshark, Suricata.

<details>
<summary>Certifications and training</summary>

- CRTA
- Segura® Deployment
- Ethical Hacking Penetration Testing
- Ethical Hacking Python
- GoHacking Security Essentials (GHSE)
- OSINT na prática: como transformar rastros digitais em inteligência acionável
- IA em Cibersegurança: como utilizar de forma adequada
- AWS Security Best Practices: Computing
- Cybersecurity Intensive Online Course

</details>

<details>
<summary>Community</summary>

- **BSides Porto 2026, Volunteer Coordinator:** coordinated more than 27 volunteers, handling schedules and team communication during event shifts
- **C-DAYS Portugal:** attendee and community contributor

</details>

## Contact

Open to conversations about cybersecurity roles and projects. The best way to reach me is a message on [LinkedIn](https://linkedin.com/in/cmdmiguelsousa).
