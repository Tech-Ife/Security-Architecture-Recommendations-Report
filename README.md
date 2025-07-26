# Security Architecture Recommendations Report - NexaCart Inc

##  Project Overview
This repository contains a **comprehensive cybersecurity architecture assessment and recommendation report** prepared for **NexaCart Inc.**, a **growing e-commerce startup** facing increased cybersecurity threats. The project is designed to provide **strategic, actionable guidance** using the **NIST Cybersecurity Framework (CSF)** and key regulatory standards, including **PCI DSS** and **GDPR**.

As NexaCart expands its digital footprint and collects more sensitive customer data, it requires a resilient security architecture to protect its assets, maintain compliance, and support business continuity.

##  Summary

The assessment uncovered critical vulnerabilities such as a flat network architecture, lack of MFA, outdated antivirus software, and no incident response capabilities. This report presents a phased remediation roadmap that aligns with business goals, scalability requirements, and industry-standard compliance.

##  Methodology

The project followed a structured approach:

1. **Assessment of Current Security Posture**: Evaluated existing network and system architecture.
2. **Risk and Vulnerability Analysis**: Identified high-impact vulnerabilities and attack surfaces.
3. **Framework Alignment**: Mapped findings and action plans using the NIST CSF:
   - Identify
   - Protect
   - Detect
   - Respond
   - Recover
4. **Prioritized Recommendations**: Ranked tasks based on risk severity and impact.
5. **Implementation Roadmap**: Phased plan—short, medium, and long term.

##  Security Architecture Goals

- Protect sensitive customer and payment data.
- Minimize operational disruptions and downtime.
- Ensure compliance with PCI DSS and GDPR.
- Support scalability and future growth.

##  Table: Security Implementation Action Plan

| Task                               | Responsible Party       | Timeline     | Priority |
|------------------------------------|--------------------------|--------------|----------|
| Network Segmentation               | IT Infrastructure Team   | 1–3 months   | High     |
| MFA and RBAC Implementation       | IT Security Team         | 1–3 months   | High     |
| Endpoint Security (EDR/MDM)        | IT Security Team         | 3–6 months   | High     |
| Data Encryption and Backup         | Data Management Team     | 3–6 months   | Medium   |
| IDS/IPS Deployment                 | IT Security Team         | 6–9 months   | Medium   |
| Cloud Security Enhancements        | Cloud Services Team      | 6–9 months   | Medium   |
| Incident Response Planning         | IT Security & Legal Team | 6–9 months   | Medium   |

##  Recommended Architecture

- **Network Segmentation**: DMZs for public-facing systems; firewalled subnets for internal assets.
- **SIEM and IDS/IPS**: Deployed for real-time monitoring and alerting.
- **MFA and RBAC**: Required for all critical user access points.
- **Cloud Security**: Encryption, DLP, and audit logging implemented.

##  Outcomes

- Enhanced protection of customer and payment data.
- Reduced exposure to ransomware, phishing, and malware.
- Regulatory alignment with GDPR and PCI DSS.
- Scalable cybersecurity infrastructure for long-term growth.

##  Tools & Standards Used

- NIST Cybersecurity Framework (CSF)
- PCI DSS v4.0
- GDPR
- EDR, SIEM, IDS/IPS, MFA Solutions

##  Skills Gained

- Cybersecurity risk analysis
- Network segmentation planning
- NIST CSF implementation
- Security roadmap development
- Technical writing and executive reporting
- Regulatory compliance alignment

##  Project Files

- [Security Architecture Recommendations Report.pdf](Doc/Security_Architecture_Recommendations_Report.pdf)
- [Presentation Slides (Google Slides)](Doc/Security_Architecture_Recommendations_Presentation_Slides.pdf)
  


##  References

- [NIST CSF 1.1](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf)
- [PCI DSS 4.0](https://www.pcisecuritystandards.org)
- [IBM Cost of a Data Breach Report (2023)](https://www.ibm.com/reports/data-breach)
- [CISA E-Commerce Best Practices](https://www.cisa.gov)

---
  

## Author

**Ifeanyi Christian Edeh**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/ifeanyiedeh)   

---

>  *This project was completed as part of a cybersecurity strategy portfolio. It simulates real-world analysis and recommendations for a growing e-commerce company with evolving security needs.*

