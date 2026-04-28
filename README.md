# Vulnerability Assessment Report for a Live Website

This file documents the results of a Vulnerability Assessment Report for a Live Website conducted on http://testphp.vulnweb.com. This site is an intentionally vulnerable PHP application maintained by Acunetix, used for security training and tool validation. 

**Tools Used**:

Nmap – basic port & exposure analysis

OWASP ZAP (Passive Scan) – identify vulnerabilities without attacking

Browser DevTools – inspect headers, cookies, and client-side issues

**Key Findings**:

The assessment identified 12 total vulnerabilities. The most severe findings include:  

SQL Injection (VULN-001): Found to be a Critical Risk with a CVSS score of 9.8.  

Local File Inclusion (VULN-003): Confirmed as a Critical Risk that allowed credentials to be read from server configuration files.  

End-of-Life PHP 5.6 (VULN-002): Identified as a Critical Risk due to over 100 unpatched CVEs.  

**Disclaimer**

This vulnerability assessment report is a point-in-time assessment and new vulnerabilities may emerge over time.

Vulnerability Assessment Report: A comprehensive PDF containing the executive summary, detailed methodology , and embedded sample technical evidence (screenshots) of all findings.
