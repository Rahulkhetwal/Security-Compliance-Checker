# Security Compliance Checker – Linux Shell Audit Tool

An automated shell script suite to audit Linux systems for misconfigurations, firewall issues, SSH access risks, and user permission errors. Reduces manual security checks and supports DevSecOps workflows.

## 🛠 Features

- Audit Linux system configurations automatically
- Check firewall settings and open ports
- Analyze SSH access and security risks
- Validate user permissions and privilege escalation risks
- Generate real-time logs for compliance tracking

## 💻 Tech Stack

- Linux Shell (Bash)
- WSL for Windows users
- Git & GitHub for version control

## 📂 Folder Structure

Security-Compliance-Checker/
│── scripts/
│   ├── audit.sh
│   ├── check_users.sh
│   ├── check_firewall.sh
│   └── check_ssh.sh
│── logs/
│── README.md
│── configs/
│── docs/



## ⚡ How to Run

1. Open terminal (or WSL on Windows).  
2. Go to the scripts folder:
   ```bash
   cd /mnt/d/Projects/Security-Compliance-Checker

3. Make scripts executable
   ```bash
   chmod +x scripts/*.sh


4. Run the audit:
   ```bash
    bash scripts/audit.sh

5. Check logs folder for output.
   ```bash
   logs/users_report.log  
   logs/firewall_report.log  
   logs/ssh_report.log

  📈 Impact / Results

 ⚡Reduced manual security audits by 80%

 ⚡Automated real-time reporting for compliance checks

 ⚡Supports continuous DevSecOps integration
