# Elevate-Labs-_-Task3
Hands-on Nessus vulnerability assessment of a local system, including detailed analysis, remediation recommendations, and scan evidence.
# Nessus Vulnerability Assessment – Internship Practical

**Author:** Shabnam Qureshi  
**Course:** BSc Cyber Security and Digital Forensics  
**Target:** Localhost (127.0.0.1)  
**Tool Used:** Nessus Essentials – Basic Network Scan  
**Scan Date:** [Insert Date]

---

## Overview

This repository contains the results and analysis of a **vulnerability assessment** performed on a local system using Nessus Essentials. The scan aimed to identify potential vulnerabilities and provide recommendations to improve system security.

---

## Repository Structure

- `README.md` – This file, providing a summary and navigation guide.  
- `Vulnerability_Report.pdf` – Exported detailed report (optional).  
- `Screenshots/` – Evidence of scan results, including scan summary and vulnerability details.  
- `Reports/` – Internship report documents: detailed and short versions.  
- `Tools/` – Notes about Nessus setup or scan configuration (optional).  
- `References/` – Useful links to CVEs, Nessus documentation, and other resources.

---

## Scan Summary

- **Total vulnerabilities detected:** 90  
  - Critical: 0  
  - High: 0  
  - Medium: 2  
  - Low: 0  
  - Info: 88  

**Medium Vulnerabilities:**

1. **SMB Signing Not Required** – Risk of man-in-the-middle attacks via unsigned SMB traffic.  
2. **SSL Certificate Cannot Be Trusted** – X.509 certificate is self-signed or broken, risking MITM attacks.

---

## Recommendations

- Enable SMB message signing on the host system.  
- Install a trusted SSL certificate from a recognized Certificate Authority.  
- Perform regular scans and maintain system updates.

---

## Screenshots

- `Screenshots/scan_summary.png` – Full scan overview.  
- `Screenshots/smb_vulnerability.png` – SMB vulnerability detail.  
- `Screenshots/ssl_vulnerability.png` – SSL certificate detail.

---

## References

- [Nessus Documentation](https://www.tenable.com/products/nessus/nessus-essentials)  
- [SMB Signing Guide](https://docs.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/microsoft-network-server-digitally-sign-communications-always)  
- [X.509 Certificate Overview](https://en.wikipedia.org/wiki/X.509)

---

## Notes

This repository is part of the internship practical for the **BSc Cyber Security and Digital Forensics course**. The repository demonstrates hands-on experience with vulnerability scanning and reporting.
