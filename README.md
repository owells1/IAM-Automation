# IAM-Automation-Students
Overview

This project demonstrates an automated Identity Lifecycle Management workflow using PowerShell.

The script provisions Active Directory accounts directly from a Student Information System (SIS) based on enrollment eligibility.


## 🔧 Features
- Automated AD account provisioning
- SQL Server integration (SIS data)
- Username generation
- Random password generation + reset at first login
- Group assignment inheritance
- Duplicate account detection
- CSV reporting & logging
- Error handling

## 🏗️ Architecture

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/b272801d-f004-4737-b2d7-2fc6c31f43e0" />


## ▶️ Usage
1. Update `config.json`
2. Run script:
   ```powershell
   .\Provision-Students.ps1

