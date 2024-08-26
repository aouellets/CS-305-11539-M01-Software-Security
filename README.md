# CS-305-11539-M01-Software-Security


Overview

This repository contains the Artemis Financial Practices for Secure Software Report, which was completed as part of the CS 305 course at Southern New Hampshire University. This document demonstrates my ability to conduct a thorough vulnerability assessment, refactor code to enhance security, and ensure the functionality of the software application while adhering to industry best practices.

Client Overview and Software Requirements

Client: Artemis Financial is a consulting company that specializes in developing personalized financial plans for its clients, including savings, retirement, investments, and insurance.

Software Requirements: The company required a secure web application that would protect client data and financial information. Specifically, Artemis Financial needed to add a file verification step to ensure secure communication through a checksum mechanism, along with ensuring the use of secure communication protocols like HTTPS.

Project Summary

1. Software Security Vulnerabilities and Resolution
In this project, I conducted a vulnerability assessment of Artemis Financial's existing software. I successfully identified and resolved security vulnerabilities by implementing a cryptographic hash function (SHA-256) for data verification, generating self-signed certificates, and configuring the application to enforce HTTPS communication.

Importance of Secure Coding: Secure coding is crucial to protect sensitive data and prevent unauthorized access, which can lead to financial and reputational damage for a company. By ensuring the software is secure, the company can maintain trust with its clients and meet regulatory compliance requirements.

2. Challenges and Learning
Challenges: One of the challenges I faced was ensuring that the refactored code did not introduce new vulnerabilities. The vulnerability assessment process was particularly helpful in identifying and addressing potential issues.

Learning: This project enhanced my understanding of how layers of security can be added to a software application. I learned the importance of thorough testing, both manually and with tools like OWASP Dependency-Check, to ensure the software's security and functionality.

3. Ensuring Functionality and Security
Process: After refactoring the code to include the new security features, I conducted functional testing to ensure that the application was still operating as intended. I also ran secondary testing using the OWASP Dependency-Check tool to verify that no new vulnerabilities were introduced.

Tools and Resources: I used Java Keytool for certificate generation, OWASP Dependency-Check for vulnerability assessment, and Spring Boot for building and testing the application. These tools and practices will be valuable in future assignments and professional tasks.

4. Future Employer Showcases
Showcasing Skills: This project is an excellent example of my ability to assess and enhance the security of software applications. I would showcase this report and the associated code as evidence of my skills in secure coding, vulnerability assessment, and secure software development practices.

Repository Contents

Artemis Financial Practices for Secure Software Report: The final report documenting the vulnerability assessment and code refactoring process.
Source Code: The refactored source code demonstrating the implementation of the secure communication and checksum verification features.
Conclusion

This project highlights my ability to secure software applications, conduct thorough vulnerability assessments, and ensure the functionality of refactored code. The skills and knowledge gained from this project will be invaluable in my future work as a software developer.

