# flaws.cloud
🚀 Just completed the flaws.cloud AWS hashtag#Capture-the-Flag challenge!

# 🔐 Cybersecurity Internship Projects – Cloud & Mobile App Security

- `📱 DIVA Android App Vulnerability Assessment`
- `☁️ flAWS.cloud AWS Capture the Flag (CTF) Challenge`

This repository contains two major projects completed during my **Cybersecurity & Digital Forensics Internship at Cyber Secured India**. These hands-on tasks focused on identifying real-world vulnerabilities in both mobile applications and cloud environments.

---

## 📁 Table of Contents

- [Overview](#overview)
- [Project 1: DIVA Android App Assessment](#project-1-diva-android-app-assessment)
  - [Challenges & Vulnerabilities](#challenges--vulnerabilities)
  - [Tools & Technologies](#tools--technologies)
- [Project 2: flAWS.cloud AWS CTF](#project-2-flawscloud-aws-ctf)
  - [Levels Solved](#levels-solved)
  - [Tools & Techniques](#tools--techniques)
- [Key Takeaways](#key-takeaways)
- [Author](#author)

---

## 🧾 Overview

- 🔍 Mobile App Testing: Assessed and documented 13+ vulnerabilities in the **DIVA Android app** (intentionally insecure).
- ☁️ Cloud Security: Solved multiple levels of **flAWS.cloud**, an AWS-based CTF challenge focusing on real-world misconfigurations.

---

## 📱 Project 1: DIVA Android App Assessment

**DIVA (Damn Insecure and Vulnerable App)** is designed for Android security training. I analyzed source code, used ADB, and performed black-box testing to uncover security issues.

### ⚠️ Challenges & Vulnerabilities

| Challenge No. | Title                            | CWE Reference             | Severity |
|---------------|----------------------------------|---------------------------|----------|
| 1             | Insecure Logging                 | CWE-532                   | High     |
| 2             | Hardcoded Secrets (Part 1)       | CWE-798                   | Medium   |
| 3             | Insecure Data Storage - Part 1   | CWE-312                   | Medium   |
| 4             | Insecure Data Storage - Part 2   | CWE-313                   | Medium   |
| 5             | Insecure Data Storage - Part 3   | CWE-314                   | Medium   |
| 6             | Insecure Data Storage - Part 4   | CWE-313                   | Medium   |
| 7             | Input Validation - Part 1        | CWE-89 (SQL Injection)    | Medium   |
| 8             | Input Validation - Part 2        | CWE-264                   | Medium   |
| 9             | Input Validation - Part 3        | CWE-190                   | Medium   |
| 10            | Access Control - Part 1          | CWE-285                   | High     |
| 11            | Access Control - Part 2          | CWE-306                   | High     |
| 12            | Access Control - Part 3          | CWE-284                   | High     |
| 13            | Hardcoded Secrets (Part 2)       | CWE-798                   | Medium   |

> Each issue was documented with:
> - Impact assessment  
> - Steps to reproduce  
> - Proof of Concept (PoC)  
> - Remediation suggestions  
> - CWE mapping  

### 🛠️ Tools & Technologies

- Android Debug Bridge (ADB)  
- Android Emulator / APK  
- Java & XML code review  
- Logcat Monitoring  
- SQLite / Shared Preferences  
- Linux CLI

---

## ☁️ Project 2: flAWS.cloud AWS CTF

**flAWS.cloud** is a security challenge built by Scott Piper to help users learn how to spot and exploit common misconfigurations in AWS services.

### ✅ Levels Solved

- **Level 1:** Public S3 bucket enumeration  
- **Level 2:** Insecure bucket listings  
- **Level 3:** IAM policy misconfiguration  
- **Level 4:** Unsecured Git repo exposing credentials  
- **Level 5:** Accessible EBS snapshot exposing sensitive data  
- **Level 6:** Metadata and HTTP GET/POST request inspection

### 🧠 Skills Demonstrated

- AWS CLI Usage: `aws s3 ls`, `aws configure`, `aws iam list-users`, etc.
- Credential Profile Handling
- Public Bucket Enumeration
- Snapshot Analysis & Data Extraction
- Policy Misconfiguration Detection
- Security Auditing of AWS Resources

### 🧠 Tools & Techniques

- AWS CLI: `aws s3 ls`, `aws configure`, `aws iam list-roles`, etc.  
- IAM role analysis & JSON policy inspection  
- GitHub repo analysis  
- EBS snapshot mounting  
- Metadata access via HTTP  
- Network capture (.pcap) using Wireshark

---

## 🎓 Key Takeaways

- Real-world exposure to **cloud misconfiguration exploitation** and **mobile app penetration testing**  
- Improved skills in **PoC creation**, **CWE classification**, and **secure coding practices**  
- Built structured vulnerability reports with clear remediation strategies  
- Developed awareness of OWASP Mobile Top 10 and AWS Security Best Practices

---

## 👨‍💻 Author

**Ayush Thakur (Hunter001x)**  
Cybersecurity & Digital Forensics Intern – Cyber Secured India  
GitHub: [@aayushthakur001](https://github.com/aayushthakur001)  
LinkedIn: [linkedin.com/in/ayush-thakur-001](#)

---

> ⚠️ This repository is intended strictly for **educational** and **ethical research** purposes. Do not use these techniques on systems without permission.
