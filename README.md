# FUTURE_CS_01
vulnerability assessment report on OWASP Juice Shop

Website Tested

The security assessment was conducted on the OWASP Juice Shop application, which is an intentionally vulnerable web application used for learning and practicing web security testing.

Scope of Assessment

The scope of this assessment was limited to an external vulnerability assessment, meaning:

Testing was performed without internal or privileged access
Focus was on identifying publicly exposed vulnerabilities and misconfigurations
Only known and detectable vulnerabilities were considered
The assessment was conducted within a defined time period (March 19, 2026 – April 19, 2026)

The following areas were covered:

Open ports and exposed services
Web application vulnerabilities
Security misconfigurations (headers, CSP, CORS, etc.)
Session management issues

A total of 8 vulnerabilities were identified:

High Severity: 2
Medium Severity: 6
Low Severity: 0

Tools Used

The following tools were used to perform the vulnerability assessment:

Nmap
Used for network scanning and port enumeration
Helped identify open ports and exposed services

OWASP ZAP (Zed Attack Proxy)
Used for automated web application security testing
Detected vulnerabilities like SQL Injection, CSP issues, and missing headers

Browser Developer Tools (Inspect Tools)
Used to analyze HTTP headers, cookies, and client-side behavior
Helped identify issues like:
Missing security headers
Session ID exposure
CORS misconfiguration

Disclaimer

This assessment reflects the security posture of the application at a specific point in time and within a limited scope. It may not cover all possible vulnerabilities. Continuous testing and monitoring are recommended to maintain security.
