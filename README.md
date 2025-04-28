# Artemis Financial Secure Software Portfolio

## Overview

This repository showcases my expertise in secure software development and vulnerability assessment through a deliverable from a coursework project for Artemis Financial. The included artifact demonstrates my ability to implement secure coding practices, conduct secondary testing, and enhance software security to protect sensitive data. The repository contains:

- **Project Two**: The Practices for Secure Software Report (`Practices_for_Secure_Software_Report.docx`), detailing the process of adding SHA-256 checksums, HTTPS, and secure coding practices to Artemis Financial’s application, along with dependency checks and functional testing.

This artifact highlights my skills in Java, Spring Boot, cryptographic techniques, and secure software engineering, reflecting a commitment to building robust and secure applications.

## Project Description

### Project Two: Practices for Secure Software Report

The `Practices_for_Secure_Software_Report.docx` documents the process of enhancing the security of Artemis Financial’s Spring Boot application. Key activities include:

- **Algorithm Cipher**: Implemented SHA-256 for checksum hashing to verify data integrity and recommended AES-256 for encryption, aligning with OWASP standards.
- **Certificate Generation**: Created a self-signed certificate to enable HTTPS, securing client-server communications.
- **Deploy Cipher**: Added a checksum verification endpoint to ensure data integrity.
- **Secure Communications**: Configured HTTPS to protect data transmission, verified via a secure webpage.
- **Secondary and Functional Testing**: Conducted dependency checks using OWASP’s dependency-check tool and tested refactored code to ensure no errors or new vulnerabilities were introduced.

The report demonstrates my ability to follow a vulnerability assessment process, apply secure coding practices, and maintain code quality while meeting client security requirements.

## Reflections

### Client Summary and Software Requirements

Artemis Financial, a financial services company, required a secure Spring Boot application to protect client data and financial transactions. The issue was to enhance security by adding data integrity checks (SHA-256 checksums) and secure communications (HTTPS) to meet modern security standards.

### Strengths in Addressing Vulnerabilities and Importance of Secure Coding

I effectively identified and mitigated vulnerabilities by implementing SHA-256 checksums and HTTPS, ensuring data integrity and secure transmission. Secure coding is critical to prevent breaches, protect client trust, and avoid financial losses, adding value by enhancing Artemis Financial’s reputation and compliance.

### Challenges and Benefits of Vulnerability Assessment

The dependency check was challenging due to interpreting complex reports but helpful in identifying outdated libraries. It guided targeted updates to reduce vulnerabilities, improving overall security.

### Increasing Layers of Security and Future Assessment

I added security layers via SHA-256 for integrity, HTTPS for encryption, and dependency checks to eliminate weak components. In the future, I’d use OWASP ZAP for dynamic testing and CVSS scoring to prioritize mitigation techniques.

### Ensuring Functionality and Security Post-Refactoring

I ensured functionality through unit tests and verified security with dependency checks and manual reviews after refactoring. These confirmed no new vulnerabilities, such as injection risks, were introduced.

### Helpful Resources and Practices

I used Java’s `keytool` for certificate generation, OWASP dependency-check for vulnerability scanning, and secure coding practices like avoiding hardcoded secrets. These tools and techniques will be valuable for future secure development tasks.

### Examples for Employers

I’d showcase the Practices for Secure Software Report to demonstrate my ability to implement cryptographic solutions, secure communications, and conduct thorough vulnerability assessments, highlighting my skills in secure software engineering.

## Conclusion

This portfolio reflects my proficiency in secure software development and vulnerability mitigation for Artemis Financial. The Practices for Secure Software Report showcases my ability to enhance application security through SHA-256, HTTPS, and dependency checks, ensuring robust and compliant software. This artifact demonstrates a disciplined approach to building secure, functional applications, with a strong foundation in industry-standard security practices.
