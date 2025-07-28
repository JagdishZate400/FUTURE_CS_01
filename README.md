# 🛡️ Web Application Security Testing Report  
✅ **Cyber Security Internship – Task 1**  
**Author**: Jagdish Zate  
**Track Code**: FUTURE_CS_01  

This repository presents a comprehensive security testing report for a sample web application using **DVWA (Damn Vulnerable Web Application)**. The objective was to identify and exploit common web vulnerabilities in a controlled lab setup to enhance understanding of real-world web security threats and their mitigations.

---

## 🔍 Report Highlights
✅ **SQL Injection** – Extracted user credentials and database schema details.  
✅ **Cross-Site Scripting (XSS)** – Exploited Reflected XSS vulnerabilities.  
✅ **Brute Force Simulation** – Performed automated login attacks using Burp Suite.

---

## 🧠 Skills Practiced
- Ethical Hacking & Penetration Testing  
- Vulnerability Analysis (SQLi, XSS, Brute Force)  
- Web Application Security Assessment  
- HTTP Request/Response Analysis using Burp Suite  

---

## 🛠️ Tools & Environment
- **Operating System**: Kali Linux  
- **Testing Platform**: DVWA (Damn Vulnerable Web Application)  
- **Technologies**: Apache, MySQL, PHP  
- **Tools Used**:  
  - Burp Suite  
  - SQLMap  
  - OWASP ZAP  
  - Custom Wordlists  

---

## 📁 Contents
### `Cyber_Security_Task_1_Report_With_Screenshots.docx`
- Full detailed report of the testing process, including:
  - Methodologies used  
  - Payloads executed  
  - Screenshots for evidence  
  - Key observations  
  - Final conclusions & recommendations  

---

## 🧪 Vulnerabilities Tested

### 1. SQL Injection (SQLi)
- Extracted user data and table/column names.  
- Retrieved usernames and hashed passwords using SQLMap and `' OR 1=1 --` injection.

### 2. Cross-Site Scripting (XSS)
- **Reflected XSS**: Input immediately reflected in HTTP response.  
- Confirmed using `<script>alert('XSS')</script>` payload.

### 3. Brute Force Attack
- Used Burp Suite Intruder to automate login attempts.  
- Identified weak passwords and absence of rate-limiting protections.

---

## 📚 Learning Outcomes
- Hands-on exploitation of web vulnerabilities  
- Practical experience using Burp Suite, SQLMap, and OWASP ZAP  
- Deepened understanding of input validation, output encoding, and secure authentication  

---

## ⚠️ Disclaimer
This project was conducted in a **safe, controlled lab environment** using intentionally vulnerable software for **educational purposes only**.  
❗ **Do not attempt these techniques on live or unauthorized systems.**  

---

## 🔗 Additional Resources
- 🔗 **Internship Site**: [Future Interns](https://futureinterns.com)  
- 🔗 **LinkedIn (Organization)**: [Future Interns](https://www.linkedin.com/in/jagdish-zate-0b07b5324/)  

---

## 👨‍💻 Connect with Me  
📌 [LinkedIn – Jagdish Zate](https://www.linkedin.com/in/jagdish-zate-0b07b5324/)

