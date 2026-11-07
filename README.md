
<div align="center">

# Hi, I'm Taoufiq Boulodan

### Cybersecurity · Cryptography · Security Engineering

**Master's student in Cryptology & Cybersecurity**  
Université Abdelmalek Essaâdi · Morocco · Class of 2027

[![GitHub](https://img.shields.io/badge/GitHub-ReHonor-181717?style=for-the-badge&logo=github)](https://github.com/ReHonor)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Taoufiq_Boulodan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/taoufiq-boulodan/)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:taoufiqboulodan@gmail.com)

**Interested in:** Blue Team · SOC & Threat Detection · Network Security · Secure Infrastructure · Applied Cryptography

*Seeking a final-year cybersecurity internship (PFE) starting February 2027.*

</div>

---

## About Me

I'm a cybersecurity and cryptography Master's student with a Bachelor's degree in Mathematics and Computer Science. I enjoy building practical security environments, investigating detection alerts, protecting infrastructure, and understanding the cryptographic foundations of secure systems.

My work spans **SIEM detection engineering, identity and secrets management, TLS/PKI, Linux and cloud hardening**, and security automation. I particularly value projects that can be reproduced, tested, and explained—not just demonstrated with screenshots.

- **Education:** Master's in Cryptology & Cybersecurity (2025–2027), Université Abdelmalek Essaâdi.
- **Previously:** Bachelor's degree in Mathematics & Computer Science (2022–2025).
- **Current focus:** Defensive security, SOC workflows, secure networks, and cryptographic protocols.
- **Languages:** Arabic (native), French (academic/professional), English (C1; EF SET 65/100).

---

## Featured Security Projects

### 1. ERP Threat Monitoring & Detection — Wazuh SIEM

**Stack:** `Wazuh` `Odoo` `PostgreSQL` `Nginx` `MITRE ATT&CK`

Built a monitoring lab around an ERP application to collect and analyze application, database, and reverse-proxy logs.

- Centralized logs from **Odoo, PostgreSQL, and Nginx** in Wazuh.
- Created detection rules for **brute-force attempts, privilege escalation, and large data exports**.
- Mapped relevant detections to **MITRE ATT&CK**.
- Added monitoring for financial write operations outside normal business hours.
- Investigated alerts from simulated brute-force activity and configured **active response** to block originating IP addresses.

**Security themes:** log correlation, threat detection, alert investigation, and automated response.

### 2. Zero Trust PostgreSQL Security — HashiCorp Vault

**Stack:** `HashiCorp Vault` `AppRole` `PostgreSQL` `TLS` `pgAudit`

Designed and tested a database access model built around short-lived credentials, encrypted connections, and least privilege.

- Issued **dynamic, time-limited database credentials** through Vault and AppRole, with automatic revocation.
- Enforced **TLS with a private certificate authority**, `verify-full` certificate validation, and `SCRAM-SHA-256` authentication.
- Enabled **pgAudit** to trace SQL activity.
- Defined **three group roles** and used a **non-superuser Vault account** to reduce privileges.
- Validated the setup through **seven test scenarios**, including temporary credential expiration.

**Security themes:** secrets management, identity, PKI, database security, and auditability.

### 3. Cloud Application & Infrastructure Security

**Stack:** `Oracle Cloud` `React` `Node.js` `SQLite` `TLS` `Linux`

As part of a **2025–2026 freelance assignment**, helped secure a financial management platform deployed on Oracle Cloud.

- Implemented protection for sensitive financial data through encryption.
- Protected network communications with **TLS**.
- Automated backups to support recovery after incidents.
- Worked with Linux server administration, **UFW/iptables**, `systemd`, and infrastructure monitoring.

**Security themes:** application security, infrastructure hardening, confidentiality, and resilience.

### 4. Multi-Source ELT Pipeline — Bachelor's Final-Year Project

**Stack:** `Python` `SQL` `PostgreSQL` `n8n` `Power BI`

Developed a multi-source data integration pipeline with automated processing and traceable execution.

- Consolidated multiple data sources into **PostgreSQL**.
- Automated processing stages and logged pipeline activity for traceability.
- Built **Power BI dashboards** for analysis and monitoring of integrated data.

**Engineering themes:** ELT design, automation, data workflows, and observability.

### 5. Additional Research & Prototypes

**SDN / Blockchain Access-Control Prototype**  
`Ryu` `Mininet` `Web3.py` `Solidity`

Explored network access control with mechanisms addressing **replay and DoS attacks**.

**AI Model Security Study**  
`Model Extraction` `Membership Inference` `DP-SGD` `Rate Limiting`

Studied model extraction and membership inference against an API, and compared potential defenses including DP-SGD and request rate limits.

---

## Technical Toolbox

| Area | Technologies & Topics |
| --- | --- |
| **Defensive Security** | Wazuh SIEM, EDR/XDR, IDS/IPS, MITRE ATT&CK, alert analysis |
| **Secrets & Data Security** | HashiCorp Vault, pgAudit, TLS, OpenSSL, PKI, least privilege |
| **Systems & Cloud** | Ubuntu/Linux, Docker, Kubernetes, Nginx, Oracle Cloud, systemd |
| **Networking** | TCP/IP, VLANs, ACLs, NAT, DNS/DHCP, VPN, Wireshark, GNS3 |
| **Programming & Automation** | Python, Bash, PowerShell, C/C++, JavaScript, Git, GitHub Actions |
| **Databases & Data** | PostgreSQL, SQLite, SQL, n8n, Power BI |
| **Cryptography** | Symmetric & asymmetric cryptography, ECC, post-quantum cryptography, finite fields |
| **Error-Correcting Codes** | BCH, Reed–Solomon, LDPC |

### Tools I Use

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

---

## What I'm Learning & Building Toward

- **Blue Team:** More rigorous detection content, investigation playbooks, and incident response workflows.
- **Infrastructure Security:** Stronger identity controls, safer secrets handling, and secure cloud deployments.
- **Applied Cryptography:** Translating mathematical concepts into implementable and testable security systems.
- **Security Automation:** Repeatable labs, documented validation scenarios, and CI/CD security checks.

---

## Education

**Master's — Cryptology & Cybersecurity**  
Université Abdelmalek Essaâdi | **2025–2027** *(in progress)*

**Bachelor's — Mathematics & Computer Science**  
Université Abdelmalek Essaâdi | **2022–2025**

---

## GitHub Activity

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=ReHonor&theme=github-dark-blue&hide_border=true)

</div>

---

## Let's Connect

I'm interested in opportunities involving **cybersecurity engineering, SOC/Blue Team, network defense, and applied cryptography**—especially a **PFE internship beginning February 2027**.

- **LinkedIn:** [linkedin.com/in/taoufiq-boulodan](https://www.linkedin.com/in/taoufiq-boulodan/)
- **Email:** [taoufiqboulodan@gmail.com](mailto:taoufiqboulodan@gmail.com)
- **GitHub:** [github.com/ReHonor](https://github.com/ReHonor)

<div align="center">

*Build securely. Validate carefully. Document clearly.*

</div>
