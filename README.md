# 🔐 VULNXPLOIT Machine – Penetration Testing

A hands-on CTF-style penetration testing assessment of the
**VULNXPLOIT Machine v1.0** vulnerable virtual machine.

The assessment was performed in an isolated lab environment using
**Kali Linux running in VirtualBox**.

---

## 📌 Project Overview

This project documents a complete penetration testing workflow against
the intentionally vulnerable VULNXPLOIT virtual machine.

The assessment covered:

- Reconnaissance and target discovery
- Network and service enumeration
- FTP enumeration
- Backup and hidden-file discovery
- Initial shell access
- Linux local enumeration
- SUID privilege escalation
- GTFOBins-style privilege escalation
- Bash history analysis
- TCP/4444 listener investigation
- Sudo privilege escalation
- Root access verification
- Flag collection
- Security findings and remediation recommendations

---

## 🎯 Objectives

The main objectives of the assessment were to:

1. Identify the target system and exposed services.
2. Enumerate FTP and web-related content.
3. Discover hidden files and backup artifacts.
4. Obtain an initial shell.
5. Identify privilege escalation opportunities.
6. Analyze shell history and suspicious services.
7. Escalate privileges to root.
8. Recover the challenge flags.
9. Document security findings and recommendations.

---

## 🧪 Lab Environment

| Component | Details |
|---|---|
| Target | VULNXPLOIT Machine v1.0 |
| Attacker | Kali Linux |
| Virtualization | Oracle VirtualBox |
| Target IP | 192.168.56.103 |
| Assessment Type | Black-box / CTF-style penetration test |
| Assessment Date | 10 August 2026 |

> ⚠️ The assessment was performed only against an intentionally
> vulnerable machine in a controlled lab environment.

---

## 🛠️ Tools & Technologies

- Kali Linux
- Nmap
- FTP
- Netcat
- Linux command-line tools
- SUID enumeration
- GTFOBins techniques
- Sudo privilege analysis
- VirtualBox

---

# 🔎 Methodology

The assessment followed the following penetration testing workflow:

```text
Reconnaissance
      ↓
Service Enumeration
      ↓
FTP Enumeration
      ↓
Backup / Hidden File Discovery
      ↓
Initial Shell Access
      ↓
Local Enumeration
      ↓
SUID Privilege Escalation
      ↓
Bash History Analysis
      ↓
TCP/4444 Listener Investigation
      ↓
Sudo Privilege Escalation
      ↓
Root Access
      ↓
Flag Collection
