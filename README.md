# bWAPP-Security-Assessment
Complete Web Application VAPT case study on bWAPP documenting environment setup, reconnaissance, testing methodology, vulnerability discovery, PoCs, exploitation, remediation, and professional reporting. Conducted in a controlled lab using industry-standard tools and OWASP testing practices for educational purposes.
# 🛡️ bWAPP Web Application VAPT Case Study

## 📌 Project Overview

This repository contains a complete Web Application Vulnerability Assessment and Penetration Testing (VAPT) case study performed on **bWAPP (Buggy Web Application)** in a controlled laboratory environment.

The project documents the complete security assessment lifecycle, including environment setup, reconnaissance, attack surface analysis, vulnerability discovery, proof-of-concept (PoC) demonstrations, exploitation techniques, impact analysis, remediation recommendations, and professional reporting.

> ⚠️ This assessment was conducted only on a deliberately vulnerable application for educational and authorized security research purposes.

---

# 🎯 Objectives

* Perform a structured web application security assessment.
* Identify and analyze common web vulnerabilities.
* Practice manual and automated penetration testing techniques.
* Develop professional vulnerability documentation and reporting skills.
* Understand the impact and mitigation of real-world security issues.

---

# 🧪 Testing Environment

| Component          | Details                          |
| ------------------ | -------------------------------- |
| Target Application | bWAPP                            |
| Testing Type       | Gray Box / Authenticated Testing |
| Operating System   | Linux                            |
| Web Server         | Apache                           |
| Database           | MySQL / MariaDB                  |
| Testing Machine    | Kali Linux / Parrot Security OS  |
| Browser            | Firefox / Chrome                 |

---

# 🛠️ Tools Used

* Burp Suite
* Nmap
* SQLMap
* Gobuster
* Dirsearch
* Nikto
* cURL
* Browser Developer Tools
* Wireshark
* Linux Command Line Tools

---

# 🔬 VAPT Methodology

```
1. Environment Setup
          ↓
2. Information Gathering & Reconnaissance
          ↓
3. Attack Surface Mapping
          ↓
4. Authentication & Authorization Testing
          ↓
5. Input Validation Testing
          ↓
6. Session Management Testing
          ↓
7. Vulnerability Identification
          ↓
8. Exploitation & Proof of Concept
          ↓
9. Risk Assessment
          ↓
10. Reporting & Remediation
```

---

# 🔎 Vulnerabilities Covered

| Vulnerability                     | Status        |
| --------------------------------- | ------------- |
| SQL Injection (SQLi)              | ⏳ In Progress |
| Cross-Site Scripting (XSS)        | ⏳ In Progress |
| Cross-Site Request Forgery (CSRF) | ⏳ In Progress |
| Local File Inclusion (LFI)        | ⏳ In Progress |
| Remote File Inclusion (RFI)       | ⏳ In Progress |
| Command Injection                 | ⏳ In Progress |
| File Upload Vulnerabilities       | ⏳ In Progress |
| Authentication Weaknesses         | ⏳ In Progress |
| Session Management Issues         | ⏳ In Progress |
| XML External Entity (XXE)         | ⏳ In Progress |

---

# 📁 Repository Structure

```
bWAPP-VAPT-Assessment/
│
├── README.md
│
├── Methodology/
│
├── Vulnerabilities/
│   ├── SQL-Injection/
│   ├── Cross-Site-Scripting/
│   ├── Authentication-Issues/
│   ├── File-Inclusion/
│   ├── File-Upload/
│   ├── Command-Injection/
│   ├── CSRF/
│   └── XXE/
│
├── PoC-Screenshots/
│
├── Reports/
│
└── Notes/
```

---

# 📝 Vulnerability Documentation Format

Each vulnerability assessment includes:

* Vulnerability Name
* Severity Level
* CVSS Score
* Description
* Affected Function/Parameter
* Testing Methodology
* Tools Used
* Payloads
* HTTP Requests & Responses
* Proof of Concept (PoC)
* Impact Analysis
* Root Cause
* Remediation Steps
* References

---

# 📊 Findings Summary

| Severity      | Number of Findings |
| ------------- | ------------------ |
| Critical      | 0                  |
| High          | 0                  |
| Medium        | 0                  |
| Low           | 0                  |
| Informational | 0                  |

*This table will be updated as the assessment progresses.*

---

# 📸 Proof of Concept (PoC)

Screenshots and evidence of successful testing are stored in the `PoC-Screenshots` directory.

Each PoC includes:

* Vulnerability discovery process
* Burp Suite requests and responses
* Payload execution results
* Application behavior after exploitation
* Evidence supporting the finding

---

# 📚 References & Standards

* OWASP Web Security Testing Methodology
* OWASP Top 10 Security Risks
* CVSS Scoring Framework
* Web Application Security Best Practices

---

# 🎓 Learning Outcomes

Through this project, I aim to improve my understanding of:

* Web application attack surfaces
* Manual penetration testing methodologies
* Vulnerability exploitation techniques
* Security impact analysis
* Professional VAPT reporting
* Defensive recommendations and remediation practices

---

# 🔒 Ethical Statement

This repository is created strictly for educational purposes. All security testing was performed on a controlled lab environment using intentionally vulnerable applications. No unauthorized testing was conducted against production or third-party systems.

---

# 👨‍💻 Author

**Abhijeet Yadav**

Cybersecurity Student | Web Application Security Enthusiast | VAPT Learner

---

⭐ If you find this repository useful, feel free to explore the documentation and follow the progress of this complete web application VAPT journey.

