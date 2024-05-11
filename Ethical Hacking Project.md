# Ethical Hacking Technical Report

**Client:** Sol  
**Date:** May 11, 2024  
**Prepared by:** Sean Howard N. Lim

---

## Executive Summary

This report presents the findings of a comprehensive security assessment conducted on Sol's network and systems. The primary objective of this assessment was to identify vulnerabilities and provide recommendations to enhance the overall security posture of the organization.

---

## Scope

The assessment focused on identifying vulnerabilities within the following areas:

- **Network Infrastructure:** Examination of network architecture, including routers, switches, and firewalls, to identify potential vulnerabilities and misconfigurations.
- **Web Applications:** Assessment of web applications for common vulnerabilities such as SQL injection, cross-site scripting (XSS), and CSRF.
- **Operating Systems:** Analysis of operating systems (e.g., Windows, Linux) for missing patches, misconfigurations, and weak password policies.
- **Wireless Networks:** Evaluation of wireless networks for open networks, weak encryption methods, and unauthorized access points.

---

## Methodology

- **Network Infrastructure:** Utilized automated scanning tools (e.g., Nmap, Nessus) to identify open ports, services, and potential vulnerabilities. Manual penetration testing was also conducted to validate findings.
- **Web Applications:** Conducted manual testing using OWASP Top 10 methodology to identify vulnerabilities in the web applications.
- **Operating Systems:** Utilized vulnerability scanning tools (e.g., Nessus, OpenVAS) to identify missing patches and misconfigurations. Manual verification was performed to ensure accuracy.
- **Wireless Networks:** Conducted wireless network scanning using tools like Aircrack-ng to identify open networks, weak encryption, and potential security issues.

---

## Findings

1. **Network Infrastructure:**
   - Open ports and services, including port 22 (SSH) and port 3389 (RDP), were discovered, which could be exploited for unauthorized access.
   - Lack of firewall rules and access controls could lead to unauthorized access and data breaches.

2. **Web Applications:**
   - SQL injection vulnerability found in the login page of the web application, allowing attackers to execute malicious SQL queries.
   - Cross-site scripting (XSS) vulnerability found in the search functionality of the web application, enabling attackers to inject malicious scripts into web pages viewed by other users.

3. **Operating Systems:**
   - Several critical vulnerabilities identified, including missing security patches and weak password policies, which could lead to unauthorized access and data breaches.
   - Insecure configurations, such as unnecessary services running, could expose the system to potential attacks.

4. **Wireless Networks:**
   - Open and unsecured wireless networks were discovered, posing a risk of unauthorized access and data interception.
   - Weak encryption methods (e.g., WEP) were used, making it easier for attackers to crack the encryption key and gain access to the network.

---

## Recommendations

1. **Network Infrastructure:**
   - Close unnecessary ports and services to reduce the attack surface.
   - Implement firewall rules to restrict access to sensitive ports and services.
   - Enable multi-factor authentication (MFA) for remote access to enhance security.

2. **Web Applications:**
   - Implement input validation to prevent SQL injection and XSS attacks.
   - Regularly update web application frameworks and libraries to patch known vulnerabilities.

3. **Operating Systems:**
   - Apply security patches and updates regularly to protect against known vulnerabilities.
   - Enforce strong password policies and regular password changes to prevent unauthorized access.

4. **Wireless Networks:**
   - Enable WPA2 or WPA3 encryption for wireless networks to protect against eavesdropping.
   - Disable SSID broadcasting and implement MAC address filtering to restrict access to authorized devices.

---

## Conclusion

The security assessment revealed several vulnerabilities that could be exploited by attackers to gain unauthorized access and compromise the integrity and confidentiality of Sol's network and systems. Implementing the recommendations outlined in this report is crucial to mitigating these risks and enhancing the overall security posture of the organization.

## Signature

LIM, SEAN HOWARD N.