# ⚔️ Aegis-Breacher v1.0
**Automated Exploitation & Privilege Escalation Framework**

Aegis-Breacher is a specialized Python-based offensive security utility designed to automate the **Gaining Access** and **Maintaining Access** phases of the Cyber Kill Chain. This tool marks the 100% completion of **Module 06: System Hacking**.

## 🎯 Project Goals (Module 06)
* **Vulnerability Mapping**: Automatically cross-references detected service versions with real-world exploits to identify viable attack vectors.
* **Privilege Escalation**: Specialized auditing for **SUID misconfigurations**, identifying direct paths from standard user rights to Root/Admin access.
* **Access Persistence**: Provides the technical logic framework required to verify and maintain control over a target system.

## 🛡️ Key Features
* **Exploit Vector Mapping**: Maps service versions (e.g., vsftpd 2.3.4) directly to **Exploit-DB** repositories for rapid weaponization.
* **Local Security Auditor**: Scans for SUID (Set User ID) bit misconfigurations on Linux-based targets.
* **Evidence Engine**: Integrated logging system that records every audit step to ensure professional accountability and reporting.

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/this-is-the-invincible-meghnad/Aegis-Breacher.git](https://github.com/this-is-the-invincible-meghnad/Aegis-Breacher.git)
cd Aegis-Breacher
```

### 1. Environment Setup 
```bash
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

pip install -r requirements.txt
```
### 📂 Project Structure
* main.py: Core logic for exploit mapping and privilege escalation.
* requirements.txt: Project dependencies (requests, python-nmap).
* .gitignore: Configured to maintain a clean repository by ignoring local environments and logs.

### 📜 Disclaimer
This tool is for educational and ethical testing purposes only. Unauthorized access to computer systems is strictly prohibited.