# Miguel Mendes 👋
Software Engineering student • Cybersecurity enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel--Emidio-blue?logo=linkedin)](https://www.linkedin.com/in/miguel-emidio-6b8680409)  
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## Table of Contents
- [About me](#about-me)
- [Technologies](#technologies)
- [Projects](#projects)
- [Usage example](#usage-example)
- [Security best practices](#security-best-practices)
- [Contact](#contact)
- [License](#license)


## About me
I am a cybersecurity-focused Software Engineering student specializing in applied offensive and defensive security. My primary interests are vulnerability discovery, security automation, and building practical tools for assessments and incident response. I prefer hands‑on security work—penetration testing, threat hunting, and hardening systems—while using programming as a means to automate and scale security tasks.

## Technologies & tools
- **Languages:** Python  
- **IDE/editor:** PyCharm (also recommend VS Code)  
- **Platforms:** Windows, Linux  
- **Tools:** Git, virtualenv/venv

## Projects
- **Password Strength Validator** — https://github.com/MiguelEm-dev/password-strength-validator  
  A bilingual (PT/EN) Python script that validates password security requirements: minimum length, uppercase/lowercase characters, digits, symbols, and optional check against compromised password lists.

*(Add other projects here with a 1–2 line description and a link.)*

**Usage Example**
Clone the repository:
**git clone:** https://github.com/MiguelEm-dev/password-strength-validator.git
cd password-strength-validator

Create and activate a virtual environment:
python -m venv .venv

# Linux / macOS
source .venv/bin/activate

# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# Windows (CMD)
.venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Run the validator:
python validator.py --password "Example@123"


**Security best practices**
- Never include real passwords in commits, issues, or public examples.
- Store keys and secrets in environment variables or a .env file and add .env to .gitignore.
- Run security tools only in controlled environments (VMs/containers) and with explicit authorization.
- Clearly document project scope and responsible use (include a disclaimer if the tool can be used offensively).

**Contact**

    LinkedIn: https://www.linkedin.com/in/miguel-emidio-6b8680409

_**This project is licensed under the MIT License — see the LICENSE file for details.**_
