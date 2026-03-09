# FUTURE_CS_03: API Security Risk Analysis

## 📌 Project Overview.....
This project is an ethical security analysis of the **JSONPlaceholder** API. [cite_start]The objective was to identify common API security risks and suggest remediation steps to secure modern SaaS integrations. [cite: 5, 12, 115]

## 🛠️ Tools Used
* [cite_start]**Postman**: For endpoint testing and response header inspection. [cite: 30, 93]
* **Browser DevTools**: For analyzing data formats and network requests.

## 🔍 Identified Security Risks.....
1. [cite_start]**Unauthenticated Access (Medium)**: Endpoints are accessible without API keys or tokens, risking unauthorized data scraping. [cite: 92, 94]
2. [cite_start]**Excessive Data Exposure (Low)**: The `/users` endpoint returns unnecessary geolocation data, increasing the information leakage surface. [cite: 97, 98]
3. [cite_start]**Lack of Rate Limiting (Medium)**: Absence of throttling makes the system vulnerable to automated abuse and application-layer DoS. [cite: 100, 102]

## 📂 Repository Structure.....
- [cite_start]`screenshots/`: Contains proof of API testing for `/users`, `/posts`, and `/comments`. [cite: 120, 121, 122]
- [cite_start]`Future_Interns_Task3_Vulnerability_Assessment.pdf`: The full professional audit report. [cite: 2]

## ⚖️ Ethical Disclosure
This analysis was conducted for educational purposes. [cite_start]Only safe, read-only GET requests were performed. [cite: 19, 116]
