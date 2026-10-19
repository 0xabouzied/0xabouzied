# Hi, I'm Youssef Abouzied 👋

Aspiring Penetration Tester 🎯 | Web App Security | Computer Engineering Student @ Al-Azhar

- 🎓 Computer Engineering student — Al-Azhar University, Computers & Systems (2023–present)
- 🐞 Active on bug bounty — participating in programs such as **HackerOne**
- 🧪 Hands-on with **XSS, SQL Injection, IDOR, Broken Authentication** and full attack-chain reporting
- 📫 youssefabouzied33@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-youssef--abouzied-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youssef-abouzied-219331325/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-youssefabouzied-212C52?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/youssefabouzied)
[![HackerOne](https://img.shields.io/badge/HackerOne-0xabouzied-494649?style=flat-square&logo=hackerone&logoColor=white)](https://hackerone.com/0xabouzied)
[![GitHub](https://img.shields.io/badge/GitHub-Web--Pentesting--Writeups-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/0xabouzied/Web-Pentesting-Writeups)

---

## 📚 Penetration Testing Reports & Writeups

### 1️⃣ DevHub — HackTheBox Penetration Testing Report 🆕

Full **black-box penetration test** of the DevHub HackTheBox machine — complete
attack chain from **unauthenticated RCE** (MCPJam Inspector v1.4.2 —
CVE-2026-23744, CVSS 9.8) → Jupyter token disclosure via process listing →
hard-coded root SSH key leaked from an internal API dump → **full root compromise**.
Published as a professional-format, sanitized report (Markdown + 17-page PDF).

| | |
|---|---|
| **Findings** | 3 vulnerabilities — 2 Critical · 1 Medium (CVSS scored) |
| **Chain** | Unauthenticated RCE → SSH persistence → Lateral Movement → Root |
| **Deliverables** | Executive summary, per-finding PoC & reproduction steps, remediation, sanitization note |

📁 [Report overview](https://github.com/0xabouzied/Web-Pentesting-Writeups/tree/main/DevHub-Pentest-Report) · 📄 [Full report (REPORT.md)](https://github.com/0xabouzied/Web-Pentesting-Writeups/blob/main/DevHub-Pentest-Report/REPORT.md) · 🗎 [PDF](https://github.com/0xabouzied/Web-Pentesting-Writeups/blob/main/DevHub-Pentest-Report/report/DevHub_Report_Redacted.pdf)



### 2️⃣ SQL Injection — Login Bypass (PortSwigger, Lab 2)

Classic **authentication bypass**: single-quote probe → 500 error →
`administrator'--` payload → logged in as admin, then reproduced professionally
through **Burp Suite Repeater**. Includes root-cause analysis and the fix
(parameterized queries / prepared statements).

📄 [Read the writeup](https://github.com/0xabouzied/Web-Pentesting-Writeups/blob/main/PortSwigger/SQL-Injection/login-bypass-lab2.md)

> ⚠️ All content covers **intentionally vulnerable training labs only**
> (PortSwigger Academy · HackTheBox). No real targets were used.


### 3️⃣ Session Management — The Restricted Sessions (CyberTalents)

Classic **session manipulation**: inspecting source code and cookies → 
identifying unprotected session variables → manipulating parameters via **Burp Suite** 
→ bypassing access controls and extracting the flag. Includes session security principles 
and secure token implementation fixes.

📄 [Read the writeup](https://github.com/0xabouzied/Web-Pentesting-Writeups/blob/main/CyberTalents/Cyber%20Talent%20The%20Restricted%20Sessions.md)

> ⚠️ All content covers **intentionally vulnerable training labs only**
> (CyberTalents · CTF). No real targets were used.


### 4️⃣ Computer Networking — CCNA Introduction to Networks

Core **networking fundamentals**: IP addressing & subnetting (VLSM) calculations → 
configuring static and dynamic routing protocols (RIP) → hands-on network topologies 
simulated in **Cisco Packet Tracer**. Includes summary notes and practical lab configurations.

📄 [View the repository](https://github.com/0xabouzied/CCNA-Notes)

> ⚠️ All content covers **educational and academic networking labs only**
> (NTI · Cisco CCNA).
-----

## 🛠️ Tools & Technologies

`Burp Suite` `Nmap` `Wireshark` `Metasploit` `Linux` `OWASP Top 10` `Git & GitHub` `Python`

## 🎓 Certifications & Courses

- CompTIA Security+ (Network Security) — NTI
- Offensive Security & Defensive Security — Raya Academy
- Ethical Hacking / Network Fundamentals / Introduction to Network Security — MaharaTech
- Pre Security — TryHackMe
- OOP & Data Structures — University
- CCNA - NTI
- Penetration Testing & Application Security
