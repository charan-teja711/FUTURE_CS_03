# API Security Risk Analysis Report - Task 3

## Project Overview
This repository contains a professional security audit of the **JSONPlaceholder API**. The goal of this project was to identify common API vulnerabilities such as Broken Authentication, Excessive Data Exposure, and Security Misconfigurations.

## Tools Used
* **Postman**: For sending GET/POST requests and analyzing JSON responses.
* **Browser DevTools**: For inspecting HTTP response headers.
* **OWASP API Security Top 10**: Used as the primary framework for risk classification.

## Key Findings
1. **Broken Authentication**: Unauthorized access to the `/users` directory.
2. **Excessive Data Exposure**: PII (Personally Identifiable Information) including GPS coordinates leaked in responses.
3. **Security Misconfigurations**: Missing critical security headers (HSTS, CSP).
4. **Unauthorized Data Creation**: Ability to perform POST requests without a valid token.

## Repository Structure
* `/API_Security_Report.pdf`: The full technical audit report.
* `/Screenshots`: Evidence of Postman requests and header analysis.
