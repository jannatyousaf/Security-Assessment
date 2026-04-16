# Cybersecurity Internship Task: Security Assessment

## Overview
This document details the security assessment conducted during the cybersecurity internship, utilizing automated scanning tools and manual testing to identify vulnerabilities in a web application.

## Objective
The goal of this task was to perform network scanning using OWASP ZAP and manual testing methodologies to detect and analyze potential security vulnerabilities.

## Tools Used
- **OWASP ZAP (Zed Attack Proxy)**: An open-source web application security scanner for automated vulnerability detection.
- **Docker**: A platform for developing, shipping, and running applications in containers, used to deploy the target web application.

## Methodology
1. **Installation**: Set up OWASP ZAP on the local environment.
2. **Scanning Execution**: Ran basic scan commands targeting the web application hosted via Docker.
3. **Analysis**: Reviewed scan results and performed manual verification of identified issues.

## Findings
The assessment revealed several critical vulnerabilities, including:
- Weak password policies allowing insecure authentication.
- SQL injection vulnerabilities enabling potential database manipulation.
- Cross-Site Scripting (XSS) issues that could lead to client-side attacks.

## Screenshots
Relevant screenshots capturing the scanning process, tool outputs, and vulnerability details are included in the attached folder.

## Conclusion
This task enhanced understanding of security assessment techniques, emphasizing the importance of proactive vulnerability scanning and remediation in cybersecurity practices.
