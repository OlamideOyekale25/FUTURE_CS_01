OWASP Juice shop Security Assessment

This project presents a web application vulnerability assessment of OWASP Juice Shop, an intentionally insecure platform designed for security training and testing. The assessment was conducted during a cybersecurity internship to gain hands-on experience in identifying, analyzing, and mitigating common web application vulnerabilities.

🔍 Tools & Methodology

Burp suite was utilized for automated scanning, spidering, and active testing.

Both automated and manual testing were performed to confirm findings and understand their potential impact.

Vulnerabilities were classified according to the OWASP Top 10 categories.

🛡️ Key Findings

The following vulnerabilities were identified during the assessment:

Replay and Impersonation - Enables duplicate submissions and feedback impersonation.

SQL Injection - An authentication flaw that granted unauthorized users administrative access.

User enumeration and Information Leakage - System responses reveal valid accounts and sensitive details that aid targeted attacks.

Insecure Token Design - Tokens expose weakly hashed credentials, enabling cracking and account compromise.

Insecure Direct Object Reference - Manipulating identifiers grants unauthorized access to other users’ data.

Business Logic Exploitation - Business logic flaws allow illegitimate credit manipulation through refunds.


🎯Learning Outcomes

Through this project, I enhanced my knowledge and skills in:

Conducting structured web application penetration testing.

Identifying, validating, and documenting common web vulnerabilities.

Applying secure coding practices and remediation strategies.

Utilizing OWASP ZAP for effective security assessments.

Building practical experience in ethical hacking and penetration testing methodologies.
