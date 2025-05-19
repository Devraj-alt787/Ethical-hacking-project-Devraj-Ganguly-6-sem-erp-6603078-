### AUTHOR - Devraj ganguly
### erp no- 6603078
### class- cse(cyber security) 6seM

### PROJECT OVERVIEV  -

## 🛡 Network Penetration Testing with Real-World Exploits and Security Remediation
This project simulates real-world network attacks and defense strategies using Kali Linux as the attacker machine and Metasploitable as the target.
It includes scanning, enumeration, exploitation, password cracking, and remediation — all performed in a controlled lab environment for ethical learning purposes.

### 🎯 Objectives
Understand and simulate real-world network attacks
Perform scanning, enumeration, and exploitation using tools like Nmap and Metasploit
Crack Linux password hashes using John the Ripper
Identify outdated services and recommend security remediations

## 💻 Lab Setup

### 🖥 Operating Systems

- Kali Linux – Attacker Machine
- Metasploitable 2 – Target Machine

### 🛠 Tools Used
- 'nmap' – Port and network scanning
- 'Metasploit' – Exploitation
- 'John the Ripper' – Password hash cracking
- 'Linux built-in' commands – user management and enumeration

## 🚀 Tasks Performed
### 🔍 Network Scanning
-'nmap -v IP' – Basic scan
- 'nmap -v -p- IP' – Full port scan
- 'nmap -sV IP' – Service version detection
- 'nmap -O IP' – OS detection

### 🔐 Hidden Ports Discovered
- Ports like 8787,36588, 53204, etc., 
- found through full port scans.

### Introduction:
Penetration testing (or ethical hacking) is a simulated cyberattack against
a system to uncover exploitable vulnerabilities. This project uses Kali Linux
as the attacking machine and Metasploitable as the target machine to carry out
a series of real-world exploits. The goal is not only to exploit
but also to propose suitable remediation to prevent future attacks.

### Theory About the Project:

# Penetration testing involves a systematic process:
- Scanning - Identify live hosts and open ports.

- Reconnaissance Gather intel about the target.

### 📡 Enumeration
# OS: Linux 2.6.x (Metasploitable)
Open services: vsftpd, OpenSSH, Apache, MySQL, Samba, etc.
Vulnerable ports: 21 (FTP), 445 (SMB), 512–514 (R Services)

### 💥 Exploitation
- vsftpd 2.3.4 backdoor
- SMB 3.0.20-Debian using Metasploit
- Rexec/Rlogin/Rsh services using script-based vulnerabilities

## 🎓 Major Learnings
Conducted deep network scans using Nmap
Performed real-world exploitation with Metasploit
Practiced password cracking and privilege escalation
Learned Linux system user management and service hardening
---

## ⚠ Disclaimer
- This project is strictly for educational purposes. 
- All activities were conducted in a closed virtual environment
  with no access to external or live systems.
