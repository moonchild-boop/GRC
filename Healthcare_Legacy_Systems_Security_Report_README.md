# Healthcare Legacy System Security Assessment

## Overview

This project presents a comprehensive vulnerability assessment conducted on legacy systems belonging to Apex Healthcare Solutions. The assessment focuses on identifying exploitable vulnerabilities within Kioptrix 1 and Metasploitable 2 and evaluating their potential business impact.

The project combines technical security testing with Governance, Risk and Compliance (GRC) recommendations to demonstrate how vulnerability assessments support organizational security objectives.

---

## Objectives

The objectives of this assessment were to:

- Identify vulnerabilities present within legacy systems
- Evaluate their potential impact on confidentiality, integrity and availability
- Conduct qualitative risk assessments
- Recommend appropriate security controls
- Develop governance policy recommendations aligned with industry standards
- Present findings in a professional consulting report

---

## Skills Demonstrated

### Technical Skills

- Vulnerability Assessment
- Service Enumeration
- Network Reconnaissance
- Risk Assessment
- Security Control Mapping
- Security Testing Methodologies

### Governance Skills

- Vulnerability Management
- Patch Management
- Secure Configuration Management
- Cryptographic Key Management
- Security Policy Development
- Business Impact Analysis

### Framework Mapping

- NIST CSF 2.0
- ISO 27001
- CIS Controls Version 8
- NIST SP 800-57

---

## Tools Used

- Kali Linux
- Nmap
- Nessus Essentials
- Netdiscover
- GitHub
- VirtualBox

---

## Key Findings

The assessment identified six vulnerabilities across both systems including:

- VSFTPD 2.3.4 Backdoor (CVE-2011-2523)
- Java RMI Registry Remote Code Execution
- Samba Trans2Open Remote Code Execution
- Debian OpenSSL/OpenSSH RNG Weakness (CVE-2008-0166)
- SSL Version 2 & 3 Protocol Detection
- SMB Signing Not Required

Two vulnerabilities were successfully exploited within the lab environment to validate their potential impact.

---

## Security Recommendations

The report recommends implementing:

- Patch Management Policies
- Vulnerability Management Policies
- Secure Configuration Standards
- Cryptographic Key Management Policies
- Network Segmentation Controls
- Secure Baseline Hardening Procedures

---

## Disclaimer

All testing was performed within an authorized laboratory environment for educational and portfolio purposes. No production systems were targeted.

---

## Repository Structure

```
Healthcare-Security-Assessment
|
|-- Reports
|-- Screenshots
|-- Methodology
|-- Risk Assessments
|-- Security Controls
|-- Policy Recommendations
|
README.md
```

---

## Author

Aisha Duze

Cybersecurity | GRC | AI Governance | Security Consulting
