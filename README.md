# Security and Compliance Enhancement for Fielder Medical Center (FMC)

## Objective
This project focuses on addressing security gaps and improving compliance with industry standards at Fielder Medical Center (FMC). The aim is to develop a comprehensive strategy that ensures the protection of sensitive patient information, meets regulatory requirements, and mitigates identified risks.

## Skills Learned
- Risk Assessment and Management
- Regulatory Compliance (HIPAA, PCI DSS)
- Security Policy Development
- Continuous Monitoring and Incident Response

## Tools Used
- NIST SP 800-53 and SP 800-66r2 (Security and Privacy Controls)
- Risk Management Software
- Security Information and Event Management (SIEM) Systems
- Endpoint Protection Tools

## Steps

### 1. **Identify Security Gaps**
   - **Outdated Security Controls:** FMC's existing security controls are outdated, lacking adequate access control policies and proper account management. The System Security Plan (SSP) needs immediate updates to align with current compliance requirements.
   - **Inadequate Multi-factor Authentication (MFA):** The lack of MFA increases the risk of unauthorized access to the network and information systems.
   - **Deficient Risk Management:** FMC lacks a comprehensive risk assessment and system inventory that align with organizational needs.
   - **Weak Endpoint Protection:** Some workstations lack licensed antivirus software, while others have no antivirus protection at all.
   - **PCI DSS Compliance Intentions:** FMC needs to secure its network, particularly in preparation for the implementation of a Point-of-Sale (POS) system.

### 2. **Develop Remediation Strategies**
   - **Upgrade Security Controls:** Update the SSP and implement robust access control measures, ensuring adherence to the principle of least privilege.
   - **Implement Multi-factor Authentication (MFA):** Introduce MFA for all critical systems, particularly for administrative access and remote connections.
   - **Conduct Comprehensive Risk Assessments:** Regularly perform risk assessments using frameworks like NIST SP 800-30 to identify and mitigate potential threats.
   - **Enhance Endpoint Protection:** Ensure that all endpoints are equipped with up-to-date antivirus software and are continuously monitored.
   - **Ensure PCI DSS Compliance:** Develop a PCI DSS-compliant policy, including the implementation of a firewall, secure password practices, and ongoing monitoring.

### 3. **Establish Critical Controls**
   - **AC-6 (Least Privilege):** Implement Role-Based Access Control (RBAC) and privileged account management to restrict access to sensitive information.
   - **CA-5 (Plans of Action and Milestones):** Develop comprehensive documentation and use a remediation tracking tool to monitor progress.
   - **CA-7 (Continuous Monitoring):** Deploy advanced SIEM systems to monitor security alerts in real-time and conduct regular security assessments.
   - **RA-3 (Risk Assessment):** Adopt a structured risk assessment framework to regularly evaluate potential risks.
   - **RA-7 (Risk Response):** Create a risk response plan with a dedicated incident response team to manage and mitigate identified risks.

### 4. **Develop PCI DSS-Compliant Policy**
   - **Antivirus Protection:** Ensure all systems in the Cardholder Data Environment (CDE) have licensed antivirus software with the latest updates and that antivirus mechanisms cannot be disabled.
   - **Endpoint Protection:** Deploy host-based security software and ensure all security measures are centrally managed and reported through the SIEM system.
   - **Multi-factor Authentication (MFA):** Require MFA for all users with administrative access, especially for remote access to the CDE.

### 5. **Implementation and Compliance Monitoring**
   - **Regular Audits:** Conduct regular audits of user roles, permissions, and endpoint security to ensure compliance with the least privilege principle and endpoint protection policies.
   - **Training and Awareness:** Provide ongoing training for IT staff and users on security policies, including the importance of MFA and continuous monitoring.
   - **Policy Review and Update:** Review and update security policies annually or whenever significant changes occur, ensuring alignment with regulatory requirements.

## Conclusion
By addressing the identified security gaps and implementing the recommended strategies, FMC can significantly enhance its security posture, ensuring compliance with HIPAA, PCI DSS, and other relevant standards. The development of robust security policies and continuous monitoring practices will help protect sensitive patient information and maintain the integrity of FMC's operations.

## References
- NIST. (2024). Final SP 800-66r2: Implementing the Health Insurance Portability and Accountability Act (HIPAA) Security Rule. [NIST SP 800-66r2](https://www.nist.gov/news-events/news/2024/02/final-sp-800-66r2-implementing-hipaa-security-rule)
- NIST. (2020). NIST Special Publication 800-53, Revision 5: Security and Privacy Controls for Information Systems and Organizations. [NIST SP 800-53r5](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)
- NIST. (2012). NIST Special Publication 800-30, Revision 1: Guide for Conducting Risk Assessments. [NIST SP 800-30r1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)
- NIST. (2011). NIST Special Publication 800-137: Information Security Continuous Monitoring (ISCM) for Federal Information Systems and Organizations. [NIST SP 800-137](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-137.pdf)
