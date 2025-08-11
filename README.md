# 🐧 Linux Privilege Escalation – TryHackMe

![TryHackMe Badge](https://tryhackme-badges.s3.amazonaws.com/achoudhary.aryan.png)  


## 📜 Overview
This repository documents my complete walkthrough and notes for the **Linux PrivEsc** room on [TryHackMe](https://tryhackme.com/room/linuxprivesc).  
The room covers **21 different privilege escalation techniques** on a vulnerable Debian VM, giving practical, hands-on experience in post-exploitation scenarios.

---

## 🗂 Room Details
- **Platform:** TryHackMe  
- **Room:** [Linux PrivEsc](https://tryhackme.com/room/linuxprivesc)  
- **Total Tasks:** 21  
- **Difficulty:** Medium  
- **Objective:** Escalate privileges from a low-level user to root using multiple Linux techniques.

---

## 📌 Skills Learned
- Service Exploits (MySQL UDF, misconfigured services)
- Weak File Permissions exploitation
- Sudo Misconfigurations
- Cron Job Exploits (PATH Hijacking, Wildcards, File Permissions)
- SUID/SGID Exploits (known binaries, shared object injection, environment abuse)
- Password & Key Harvesting
- NFS Exploitation
- Kernel Exploits
- Using automated privilege escalation scripts

---

## 📋 Task Breakdown

| Task No. | Topic | Key Learning |
|----------|-------|--------------|
| 1 | Deploy VM | Initial setup |
| 2 | Service Exploit 1 | MySQL UDF |
| 3 | Service Exploit 2 | Misconfigurations |
| 4 | Weak File Permissions 1 | Writable `/etc/passwd` |
| 5 | Weak File Permissions 2 | Writable scripts |
| 6 | Sudo 1 | Run as root misconfig |
| 7 | Sudo 2 | GTFOBins |
| 8 | Cron Jobs 1 | Writable cron script |
| 9 | Cron Jobs 2 | PATH Hijacking |
| 10 | Cron Jobs 3 | Wildcard injection |
| 11 | SUID 1 | Known exploits |
| 12 | SUID 2 | Shared object injection |
| 13 | SUID 3 | Environment variable abuse |
| 14 | SUID 4 | Shell features |
| 15 | SGID Exploit | Group misconfig |
| 16 | Passwords 1 | `.bash_history` |
| 17 | Passwords 2 | Config file leaks |
| 18 | Passwords 3 | SSH key theft |
| 19 | NFS Exploit | Root_squash bypass |
| 20 | Kernel Exploit | Local privilege escalation |
| 21 | Scripts | LinPEAS, LinEnum, LES |


