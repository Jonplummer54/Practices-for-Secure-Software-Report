# Practices for Secure Software Report

## Overview

This report documents the secure coding practices implemented for Artemis Financial’s software application. The focus was on enhancing the software's security by refactoring the codebase, securing communications, and managing dependencies in line with industry best practices.

## Client Summary

**Client:** Artemis Financial

Artemis Financial is a financial services company concerned about the security of its software applications. The company sought to address vulnerabilities that could potentially expose sensitive financial data.

## Reflection

1. **What did you do well when you found your client’s software security vulnerabilities?**
   I effectively used tools like the OWASP Dependency Check to identify critical vulnerabilities in the client’s software. This proactive approach allowed for the timely mitigation of risks.

2. **Why is it important to code securely?**
   Secure coding is essential to protect sensitive data and maintain the integrity of software systems. It adds significant value by safeguarding against cyber threats, thus maintaining the trust and confidence of clients and stakeholders.

3. **Which part of the vulnerability assessment was challenging or helpful to you?**
   The most challenging yet helpful part was the integration of SSL/TLS for secure communications. It provided a practical understanding of how encryption enhances data security during transmission.

4. **How did you increase layers of security?**
   Security layers were increased by implementing SSL/TLS encryption, performing static code analysis, and ensuring data integrity with SHA-256 checksums. In future assessments, I would use a combination of automated tools and manual testing to decide on mitigation techniques.

5. **How did you make certain the code and software application were functional and secure?**
   Post-refactoring, I performed rigorous testing, including unit tests, integration tests, and security audits using tools like OWASP Dependency Check, ensuring no new vulnerabilities were introduced.

6. **What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
   Tools such as Git for version control, OWASP Dependency-Check for vulnerability assessment, and best practices like the least privilege principle were invaluable. These will be beneficial in future software development and security tasks.

7. **Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
   I would showcase the detailed vulnerability assessment and secure coding practices implemented, demonstrating my ability to enhance software security effectively. This report highlights my proficiency in identifying vulnerabilities, refactoring code, and adhering to industry standards.

## Conclusion

The Practices for Secure Software Report demonstrates my capability to apply secure coding practices effectively, ensuring robust security for software applications. It reflects my commitment to continuous learning and application of industry-standard best practices.
