# External-Black-Box-Web-Application-Penetration-Test-mediroza-hospital

# Mediroza General Hospital — Web Application Penetration Test

## 📌 Overview

This project was completed as part of a **cybersecurity internship** and involved an authorized external black-box penetration test of the public-facing web application of **Mediroza General Hospital**.

The assessment focused on identifying security weaknesses within the application's publicly accessible attack surface and documenting the security posture of the tested environment.

> **⚠️ Confidentiality Notice**
>
> This repository contains a sanitized overview of the assessment. Detailed findings, exploitation procedures, sensitive evidence, and confidential information from the original penetration testing report are intentionally excluded.

---

## 🎯 Assessment Scope

The engagement covered the publicly accessible web application, including:

* Patient Portal
* Staff Portal
* Associated public-facing web endpoints

The assessment was conducted under **written authorization** and within the scope defined for the engagement.

---

## 🔍 Assessment Type

**External Black-Box Web Application Penetration Testing**

The assessment was performed without access to the application's source code or internal infrastructure.

---

## 🛡️ Key Finding

### SQL Injection

A **SQL Injection vulnerability** was identified within the web application's authentication functionality.

**Severity:** Critical

The vulnerability represented a significant authentication security risk and was therefore classified as a critical finding within the original assessment.

No exploitation details or sensitive evidence are included in this public repository.

---

## 🧰 Tools & Technologies

The assessment involved a combination of security testing and analysis tools, including:

* Burp Suite Community Edition
* Nmap
* WhatWeb
* DNSRecon
* WAFW00F
* Gobuster
* ExifTool
* QPDF / PikePDF

---

## 📋 Methodology

The assessment followed a structured penetration-testing process covering areas such as:

* Reconnaissance
* Web application assessment
* Authentication security testing
* Vulnerability identification
* Risk assessment
* Security recommendations

Detailed testing procedures and exploitation techniques are intentionally omitted from this public repository.

---

## 📊 Risk Assessment

The original assessment used the following severity classification:

| Severity | Finding       |
| -------- | ------------- |
| Critical | SQL Injection |

The overall engagement risk was assessed as **Critical** in the original confidential report.

---

## 💡 Security Recommendations

The assessment highlighted the importance of:

* Using parameterized queries / prepared statements
* Implementing secure input validation
* Avoiding verbose database errors in production
* Applying secure coding practices throughout authentication functionality
* Conducting regular security assessments
* Implementing secure development and code-review processes

---

## 📄 Deliverable

The complete penetration testing assessment was documented in a separate report.

This GitHub repository intentionally provides only a **sanitized project overview** and does not contain the confidential technical evidence or detailed exploitation information from the original report.

---

## ⚖️ Authorization & Disclaimer

All security testing described in this project was conducted as part of an **authorized educational cybersecurity internship engagement**.

No testing was performed against systems without authorization.

The information presented in this repository is intended for **educational and portfolio purposes only**.

---

## 👤 Author

**Ammar Abadou**
Cybersecurity Intern
Computer Security Student
