This file documents the results of a Vulnerability Assessment Report for a Live Website conducted on http://testphp.vulnweb.com. This site is an intentionally vulnerable PHP application maintained by Acunetix, used for security training and tool validation. The assessment was performed using Nmap for network reconnaissance, OWASP ZAP for application-layer scanning, and Browser DevTools for header and cookie inspection.

The assessment identified 12 vulnerabilities across the application, with three rated Critical severity. These findings reflect the class of issues commonly encountered in real-world web applications and represent genuine security risk if present in a production environment.

The most severe findings are SQL Injection, Local File Inclusion, and an end-of-life PHP version (5.6), any one of which could individually result in a full database breach or server compromise. The three critical vulnerabilities should be remediated immediately before any other changes are made to the application.

**Disclaimer**

This vulnerability assessment report is a point-in-time assessment and new vulnerabilities may emerge over time.

