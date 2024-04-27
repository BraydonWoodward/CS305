# CS305 - Braydon Woodward
This repository is for my Computer Science Journal, Class CS305: Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
    Artemis Financial is a client that sought assistance in enhancing the security of their software application. They required improvements to their existing codebase to address vulnerabilities related to input validation, error handling, and data integrity. Additionally, they needed guidance on implementing HTTPS configuration to ensure secure communication between the client and server.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
    When addressing the client's software security vulnerabilities, I conducted a thorough analysis of the codebase to identify potential weaknesses and implemented appropriate remediation measures. I employed Maven to conduct dependencey tests, physcially evaluated the code, and researched common vulnerabilites Artemis Finanial would be exposed to. Coding securely is crucial because it helps protect sensitive data, prevents unauthorized access, and safeguards against various cyber threats such as data breaches, malware injections, and denial-of-service attacks. By adhering to best practices in secure coding, we ensure that the software is resilient to exploitation and maintains the confidentiality, integrity, and availability of critical assets. Software security adds significant value to a company's overall wellbeing by instilling trust among users, safeguarding intellectual property, and mitigating financial and reputational risks associated with security breaches.
    
What part of the vulnerability assessment was challenging or helpful to you?
  Learning the different types and ways hacker can expoilt an application is invaluable knowledge I have learned, and is a good starting point for me to incoporate secure coding in all steps of the software lifecycle in parallel with development. 
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  
  To increase layers of security, we employed several strategies:

    -Input Validation: Implemented robust input validation mechanisms to sanitize user inputs and prevent common vulnerabilities such as SQL injection, cross-site scripting (XSS), and command injection.
    -Error Handling: Enhanced error handling to gracefully handle exceptions and prevent sensitive information leakage, thereby reducing the attack surface and improving application resilience.
    -Authentication and Authorization: Implemented strong authentication mechanisms, such as multi-factor authentication (MFA), and fine-grained authorization controls to ensure that only authorized users have access to sensitive resources and functionalities.
    -Secure Communication: Configured HTTPS to encrypt data transmitted between the client and server, thereby protecting against eavesdropping, data tampering, and man-in-the-middle attacks.
    -Security Testing: Conducted thorough security testing, including static code analysis, dynamic application security testing (DAST), and penetration testing, to identify vulnerabilities and assess the effectiveness of implemented security controls.
   
  In the future, to assess vulnerabilities and decide on mitigation techniques, we would utilize a comprehensive approach that integrates automated tools, manual code reviews, and threat modeling:

    -Automated Vulnerability Scanning: Utilize automated vulnerability scanning tools to identify common security issues and prioritize them based on severity levels.
    -Manual Code Reviews: Conduct manual code reviews by experienced security professionals to identify complex vulnerabilities, logic flaws, and architectural weaknesses that automated tools may overlook.
    -Threat Modeling: Perform threat modeling exercises to systematically identify potential threats, assess their likelihood and impact, and prioritize mitigation strategies based on risk analysis.
    -Security Standards and Guidelines: Adhere to established security standards and guidelines such as OWASP, NIST, and secure coding practices recommended by industry experts and regulatory bodies.
    
  By combining these approaches, we can comprehensively assess vulnerabilities, prioritize mitigation efforts, and enhance the overall security posture of the software application.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  To ensure that the code and software application were both functional and secure, we followed these steps:

  -Unit Testing: Conducted thorough unit testing to verify the functionality of individual components and ensure that they meet the specified requirements.
  -Security Testing: Conducted comprehensive security testing to identify and mitigate potential vulnerabilities in the codebase. 
  -Code Reviews: Engaged in thorough code reviews identify potential security flaws, adherence to secure coding practices, and compliance with security standards and guidelines.
  -Validation Against Requirements: Ensured that the refactored code met the client's requirements and specifications, including functional requirements as well as security requirements.
  -Risk Assessment: Conducted risk assessments to identify potential security risks associated with the refactored code and prioritized mitigation efforts based on the severity and likelihood of exploitation.
  
After refactoring the code, we checked for new vulnerabilities by:

  -Regression Testing: Re-executed existing test cases to ensure that the changes introduced during refactoring did not inadvertently break existing functionality or introduce regressions.
  -Automated Testing: Leveraged automated testing tools to perform static code analysis, vulnerability scanning, and other automated security tests to identify any new vulnerabilities introduced by the refactoring process.
  -Manual Inspection: Conducted manual inspection of the refactored codebase to identify any potential security weaknesses or misconfigurations that may have been overlooked during automated testing.

By following these practices, we ensured that the refactored code and software application remained both functional and secure, while also minimizing the risk of introducing new vulnerabilities during the refactoring process.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  Some useful tools we used were:
    -Maven dependency check
    -Eclipse Ide
    -OWASP Security guidelines
  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  
  From this assignment, there are several elements I could showcase to future employers to demonstrate my skills, knowledge, and experience:

    -Code Refactoring: I can showcase the refactored code, highlighting improvements in code readability, maintainability, and adherence to best practices. This demonstrates my ability to enhance existing codebases for better performance and security.
    -Security Assessment Reports: I can provide documentation detailing the security vulnerabilities identified in the initial codebase, along with mitigation strategies implemented to address these issues. This demonstrates my proficiency in identifying and mitigating       security risks.
    -HTTPS Configuration: I can demonstrate the configuration of HTTPS for secure communication between clients and servers, emphasizing the importance of data confidentiality and integrity in web applications.
    -Vulnerability Assessment Process: I can present a summary of the vulnerability assessment process followed, including the tools, methodologies, and best practices used to assess and mitigate security vulnerabilities. This showcases my ability to conduct thorough         security assessments and implement appropriate mitigation techniques.
    -Documentation and Reporting: I can showcase documentation created throughout the assignment, including reports, code comments, and README files. This highlights my ability to communicate effectively and document my work for stakeholders and team members.
    
