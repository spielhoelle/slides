# Cyber security


# Timetable

- Class 9:00 - 10:30 (17.00 - 18.30 JST)
- Break 10:30 - 10:40 (18.30 - 18.40 JST)
- Class 10:40 - 11:50 (18.40 - 20.10 JST)
- Break 11:50 - 12:00 (20.10 - 20.20 JST)
- Class 12:00 - 13:05 (20.20 - 21.05 JST)
- `Lunch break`
- Class 14:05 - 15:35 (self paced learning)
- Break 15:35 - 15:45
- Class 15:45 - 17:15 (self paced learning)
- Break 17:15 - 17:25
- Class 17:25 - 18:10 (self paced learning) (00.25 - 01.10 JST)


# Today's agenda

- White hat, red team? A introduction <!-- .element: class="fragment" data-fragment-index="3" -->
- Networking and Privacy <!-- .element: class="fragment" data-fragment-index="4" -->
- Web Security and Online Safety <!-- .element: class="fragment" data-fragment-index="5" -->
- Security for Developers and DevOps <!-- .element: class="fragment" data-fragment-index="6" -->
- We have a look at many viruses <!-- .element: class="fragment" data-fragment-index="7" -->


# Exercise

## Test some shortcut automations

- Power user can copy paste fast, and strip fast things <!-- .element: class="fragment" data-fragment-index="2" -->
- Search & replace in various environments <!-- .element: class="fragment" data-fragment-index="3" -->
- Basic understanding of regex <!-- .element: class="fragment" data-fragment-index="4" -->


# Session 1: Introduction to Cyber Security and Basic Security Concerns


# Introduction to Cyber Security

- [Meme](https://caniphish.com/blog/cyber-security-memes) <!-- .element: class="fragment" data-fragment-index="2" -->
- WhiteHat hacker/Red teaming <!-- .element: class="fragment" data-fragment-index="3" -->
- Definition and significance <!-- .element: class="fragment" data-fragment-index="4" -->
- Real-world implications <!-- .element: class="fragment" data-fragment-index="5" -->
- Security as a mindset, checkout your risk assessments <!-- .element: class="fragment" data-fragment-index="6" -->
- Lets have a look at StuxNet <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:
- **WhiteHat Hacker/Red Teaming:** WhiteHat hackers simulate cyberattacks in controlled environments to identify vulnerabilities. Red teaming involves ethical hackers testing systems from the perspective of an attacker to ensure security.
- **Definition and Significance:** Cybersecurity is the practice of protecting systems, networks, and data from unauthorized access, attacks, or damage. It is crucial for safeguarding financial institutions from potential threats.
- **Real-world Implications:** Cyberattacks can lead to significant financial losses, loss of customer trust, and reputational damage. Understanding cybersecurity is essential for maintaining robust defenses.
- **Security as a Mindset:** Cybersecurity requires a proactive mindset, continuous learning, and a commitment to staying ahead of potential threats.


# Operating Systems and Security

- Overview of Windows, MacOS, Linux <!-- .element: class="fragment" data-fragment-index="2" -->
- Security features <!-- .element: class="fragment" data-fragment-index="3" -->
    - Microsoft criticism (Security Now podcast https://youtu.be/x9r-ONCydCA?list=PLdPwyUeH0mS566Y0YZ7oAGghzMgRlWTBf&t=108) <!-- .element: class="fragment" data-fragment-index="4" -->
- Common vulnerabilities <!-- .element: class="fragment" data-fragment-index="5" -->
- Importance of regular updates <!-- .element: class="fragment" data-fragment-index="6" -->
- Lets checkout crowdstrike incident <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:
- Explain key OS differences in terms of security architecture.
- Mention security features like macOS's Gatekeeper and Linux’s user permissions.
- Touch on the Security Now podcast's Microsoft criticism for awareness on controversial takes.
- Highlight common vulnerabilities and stress the importance of regular software updates to stay protected.


# Things happening across the Atlantic

- Tariffs against the EU <!-- .element: class="fragment" data-fragment-index="2" -->
- 8000 government websites taken down <!-- .element: class="fragment" data-fragment-index="3" -->
- access to government spending of 8 trillion denied, then fired <!-- .element: class="fragment" data-fragment-index="4" -->
- Dissolving USAID <!-- .element: class="fragment" data-fragment-index="5" -->
- What to do? https://european-alternatives.eu/ <!-- .element: class="fragment" data-fragment-index="6" -->


# Internet Structure and Security

- DNS (Domain Name System) <!-- .element: class="fragment" data-fragment-index="2" -->
- HTTP vs HTTPS <!-- .element: class="fragment" data-fragment-index="3" -->
- IP addresses <!-- .element: class="fragment" data-fragment-index="4" -->
- Browser rendering of 3rd party  <!-- .element: class="fragment" data-fragment-index="5" -->
- The power of documentation and journaling in general <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Simplify DNS as the "phonebook of the internet" for ease of understanding.
- Differentiate HTTP from HTTPS, emphasizing the latter’s role in secure transactions.
- Briefly explain IP addresses and how they identify devices on the network, setting up for later network security discussions.
- Rendering youtube videos not inline without embeds, facebook like buttons, google fonts
- Silo knowledge, on/offboarding employees, HR workflows


# Exercise

- Analyse network manager while browsing your favorite shoppingsite of devtools


# Basic Security Concerns

- Passwords <!-- .element: class="fragment" data-fragment-index="2" -->
- Phishing ([Example](https://hachyderm.io/@urldna@infosec.exchange)) <!-- .element: class="fragment" data-fragment-index="3" -->
- Malware <!-- .element: class="fragment" data-fragment-index="4" -->
- Never give out information if you dont have to  <!-- .element: class="fragment" data-fragment-index="5" -->
- SolarWinds breach <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Start with passwords as a first line of defense in security.
- Share the phishing link example to illustrate how convincing scams can be.
- Mention the SolarWinds attack to highlight real-world risks and the impact of cyber vulnerabilities on organizations.


# Password Security

- Importance of strong passwords <!-- .element: class="fragment" data-fragment-index="2" -->
- Techniques for creating strong passwords <!-- .element: class="fragment" data-fragment-index="3" -->
- Advantages of using password managers <!-- .element: class="fragment" data-fragment-index="4" -->
- Future of passkeys  <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Stress why weak passwords are a major security risk.
- Provide simple rules for creating strong passwords (e.g., length, complexity, no reuse).
- Introduce password managers as a tool to improve security without the hassle of remembering multiple passwords.


# Strong Password Creation

- Use online tools for password strength testing <!-- .element: class="fragment" data-fragment-index="2" -->
- Analyze password strength in real-time <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:
- Show a couple of online tools and perform live demonstrations of weak vs. strong passwords.


# Email

- SMTP base protocol
- Gmail bad example of privacy
- Main place for fishing
- Spam and how to avoid


# The illusion

- Marketing of Apple is security, but google brings the safety features out
- Sam Altmaln said: We have been on the wrong side of history
- But OpenAis security is quite bad
- Microsofts remote-desktop


# Terminal and Command Line Basics

- Opening terminal/CMD <!-- .element: class="fragment" data-fragment-index="2" -->
- Run basic commands like `whoami` and `ipconfig`/`ifconfig` <!-- .element: class="fragment" data-fragment-index="3" -->
- Practical exercise: finding IP address <!-- .element: class="fragment" data-fragment-index="4" -->
- Exercise: build confidence by deleting folders <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Introduce the terminal as a powerful interface for system control.
- Use `whoami` and `ifconfig` commands to explore system information.
- Walk participants through a basic folder deletion to build familiarity with the terminal.


# Introduction to Password Managers

- Choosing a password manager <!-- .element: class="fragment" data-fragment-index="2" -->
- Setting up a basic password manager <!-- .element: class="fragment" data-fragment-index="3" -->
- Benefits of password managers <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Give criteria for selecting a password manager.
- Briefly demonstrate how to set up a password manager.
- Conclude with the advantages: secure, simple, and promotes good password habits.


# Exercise: Add a password field to our app

- Prompt for secure password usage <!-- .element: class="fragment" data-fragment-index="2" -->
- Integrate with our app: hands-on exercise <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:
- Engage participants in applying password knowledge by adding a password prompt to a sample app.
- Encourage reflection on how security practices can enhance user trust and app reliability.


# AI security

- Jailbreaks in AI <!-- .element: class="fragment" data-fragment-index="2" -->
- Backdoor Attack <!-- .element: class="fragment" data-fragment-index="3" -->
- Data Privacy Concerns <!-- .element: class="fragment" data-fragment-index="4" -->
- Extracting Model Parameters <!-- .element: class="fragment" data-fragment-index="5" -->
- Model Distillation Risks <!-- .element: class="fragment" data-fragment-index="6" -->
- Lets test a uncensored model <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:

- **Jailbreaks in AI**: Unauthorized access to AI systems for extracting sensitive information or reverse-engineering algorithms without permission.
- **Backdoor Attacks**: Targeted methods that allow attackers to gain unintended access to AI models, enabling data extraction or control over system behavior.
- **Data Privacy Concerns**: Companies may inadvertently share personal user data with third parties due to software vulnerabilities or accidental data leaks.
- **Extracting Model Parameters**: Techniques used by attackers to steal specific parameters from AI models, compromising the confidentiality of trained algorithms.
- **Model Distillation Risks**: The process of extracting knowledge from a large AI model (teacher) to create a smaller, simpler version (student) can potentially expose sensitive information or vulnerabilities if reverse-engineered by attackers.


# Audits

- Objective of Security Audits <!-- .element: class="fragment" data-fragment-index="2" -->
- Methods Used <!-- .element: class="fragment" data-fragment-index="3" -->
- Common Tools Employed <!-- .element: class="fragment" data-fragment-index="4" -->
- Types of Risks Explored <!-- .element: class="fragment" data-fragment-index="5" -->
- Collaboration with DevSecOps <!-- .element: class="fragment" data-fragment-index="6" -->
- Risk Levels Assessed <!-- .element: class="fragment" data-fragment-index="7" -->
- Frequency of Audits <!-- .element: class="fragment" data-fragment-index="8" -->
- Common Issues Found <!-- .element: class="fragment" data-fragment-index="9" -->
- Mitigation Strategies <!-- .element: class="fragment" data-fragment-index="10" -->
- Compliance Considerations <!-- .element: class="fragment" data-fragment-index="11" -->
- Impact on Reputation <!-- .element: class="fragment" data-fragment-index="12" -->
- Future Trends in Auditing <!-- .element: class="fragment" data-fragment-index="13" -->

Speaker Notes:

- **Objective of Security Audits**: Identify vulnerabilities, assess risk levels, ensure compliance with regulatory standards, and improve overall system resilience.
- **Methods Used**: Manual testing, automated tools like OWASP ZAP, penetration testing, and ethical hacking to uncover weaknesses.
- **Common Tools Employed**: Platforms such as OWASP ZAP, Burp Suite, and frameworks like Dependency-Isolation Testing (DIT) for comprehensive security assessments.
- **Types of Risks Explored**: Application vulnerabilities, network security flaws, user authentication issues, privilege escalation risks, and penetration testing exercises.
- **Collaboration with DevSecOps**: Security audits often involve cross-functional teams to ensure consistent application updates and patches are applied promptly.
- **Risk Levels Assessed**: High-risk vulnerabilities (e.g., SQL injection) vs. medium-risk issues (e.g., misconfigurations), guiding immediate action or long-term strategies.
- **Frequency of Audits**: Typically conducted quarterly, annually, or following specific incidents or compliance breaches.
- **Common Issues Found**: Buffer overflows, SQL injection attempts, misconfigured firewalls, and outdated libraries.
- **Mitigation Strategies**: Immediate fixes for critical issues, system hardening to prevent future attacks, and training employees on security best practices.
- **Compliance Considerations**: Audits often focus on standards like GDPR, HIPAA, or ISO 27001 to ensure organizational adherence.
- **Impact on Reputation**: Finding significant vulnerabilities can damage an organization’s reputation, leading to increased scrutiny from regulators and customers.
- **Future Trends in Auditing**: Increased adoption of automated tools for efficiency, expanded scope to cover cloud environments, and integration with DevSecOps practices.


# Corporate security
- NDA's and consequences <!-- .element: class="fragment" data-fragment-index="2" -->
- Third-Party Risk Management <!-- .element: class="fragment" data-fragment-index="3" -->
- Compliance & Legal Requirements <!-- .element: class="fragment" data-fragment-index="4" -->
- Incident Response Plan <!-- .element: class="fragment" data-fragment-index="5" -->
- Threat Intelligence <!-- .element: class="fragment" data-fragment-index="6" -->
- Access Control <!-- .element: class="fragment" data-fragment-index="7" -->
- Disaster Recovery & Business Continuity <!-- .element: class="fragment" data-fragment-index="8" -->
- Secure Development Practices <!-- .element: class="fragment" data-fragment-index="9" -->
- Continuous Monitoring & Logging <!-- .element: class="fragment" data-fragment-index="10" -->
- Incident Response Drill <!-- .element: class="fragment" data-fragment-index="11" -->

Speaker Notes:
- **Third-Party Risk Management**: Protecting sensitive financial information shared with external partners or providers.
- **Compliance & Legal Requirements**: Adhering to industry regulations (e.g., Sarbanes-Oxley Act) to ensure client trust and avoid legal risks.
- **Incident Response Plan**: Developing and implementing strategies to mitigate risks posed by cyberattacks on SAP systems.
- **Threat Intelligence**: Monitoring for potential threats specific to financial consulting environments using SAP.
- **Access Control**: Implementing strict access controls to limit unauthorized users from accessing financial data within SAP.
- **Disaster Recovery & Business Continuity**: Planning for recovery of financial operations in case of system failures or cyberattacks.
- **Secure Development Practices**: Adhering to best practices for secure development of SAP applications to minimize vulnerabilities.
- **Continuous Monitoring & Logging**: Regularly monitoring SAP systems and logs to detect and respond to security incidents promptly.
- Incident: Regularly conduct cyber incident response drills to prepare employees and management on how to handle real-life incidents.


# Session 2: Network Security and Privacy


# Network Protocols and Security

- TCP/IP overview <!-- .element: class="fragment" data-fragment-index="2" -->
- Security implications of TCP/IP <!-- .element: class="fragment" data-fragment-index="3" -->
- Common protocol vulnerabilities <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Begin by explaining TCP/IP as the foundational language of the internet.
- Discuss the main security concerns in these protocols, like IP spoofing and data interception.
- Share examples of known vulnerabilities in common protocols (e.g., ARP spoofing) to illustrate risks.


# Firewalls, Routers, and Switches

- Roles in network security <!-- .element: class="fragment" data-fragment-index="2" -->
- Basic configurations for security <!-- .element: class="fragment" data-fragment-index="3" -->
- Practical implications for users <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Define the roles of firewalls, routers, and switches in creating network boundaries and controlling data flow.
- Cover basic configurations and best practices to harden these devices.
- Discuss scenarios showing how small security changes can prevent significant risks.


# Privacy Concerns

- The 'trillion trillion' example ([Article](https://kyivindependent.com/russian-court-fines-google-2-5-trillion-trillion-trillion/)) <!-- .element: class="fragment" data-fragment-index="2" -->
- Data collection and online tracking <!-- .element: class="fragment" data-fragment-index="3" -->
- Personal digital privacy <!-- .element: class="fragment" data-fragment-index="4" -->
- Mitigating privacy risks <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Begin with the humorous “trillion trillion” example to highlight the magnitude of data privacy concerns.
- Explain data collection practices by companies and potential risks for individuals.
- Provide tips to limit tracking (e.g., browser extensions, private mode) and discuss legislative protections for privacy.


# Encryption and Decryption

- Practical exercise: Convert your name to binary <!-- .element: class="fragment" data-fragment-index="2" -->
- Role of encryption in security <!-- .element: class="fragment" data-fragment-index="3" -->
- Basic encryption techniques <!-- .element: class="fragment" data-fragment-index="4" -->
- Real-world applications of encryption <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Engage participants by converting their name into binary to make encryption tangible.
- Explain why encryption is crucial in protecting sensitive information.
- Demonstrate simple techniques like Caesar Cipher, then discuss real-world applications (e.g., SSL/TLS for web security).


# Virtual Private Networks (VPNs)

- How VPNs work to secure browsing <!-- .element: class="fragment" data-fragment-index="2" -->
- Benefits of using a VPN <!-- .element: class="fragment" data-fragment-index="3" -->
- Tips for choosing a VPN service <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Describe VPNs as private tunnels that encrypt internet traffic.
- Emphasize the benefits, especially for public Wi-Fi users and traveling professionals.
- Give guidelines for choosing trustworthy VPN providers, highlighting transparency and no-logs policies.


# Configuring Firewalls

- Basic firewall setup <!-- .element: class="fragment" data-fragment-index="2" -->
- Practical exercise: configuring a firewall <!-- .element: class="fragment" data-fragment-index="3" -->
- Understanding firewall rules <!-- .element: class="fragment" data-fragment-index="4" -->
- Example: "Malicious Life" incident <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Walk through a basic firewall setup, explaining inbound and outbound rules.
- Use a live configuration exercise for practical learning.
- Share the “Malicious Life” example to illustrate the power of firewalls in blocking unauthorized access.


# Setting Up a VPN

- Choosing the right VPN <!-- .element: class="fragment" data-fragment-index="2" -->
- Steps to install a VPN <!-- .element: class="fragment" data-fragment-index="3" -->
- Configuring VPN settings for privacy <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Guide participants in evaluating VPNs and what to look for in terms of privacy and speed.
- Demonstrate VPN installation steps, with time for participants to follow along.
- Cover best settings for ensuring privacy, like kill-switch and DNS leak protection.


# Encrypting and Decrypting Files

- Using OpenSSL for encryption <!-- .element: class="fragment" data-fragment-index="2" -->
- Practical exercise: password-protect a zipped file <!-- .element: class="fragment" data-fragment-index="3" -->
- Decrypting files securely <!-- .element: class="fragment" data-fragment-index="4" -->
- Discuss AI in future encryption <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Introduce OpenSSL and demonstrate basic file encryption with it.
- Guide participants in zipping a file with a password as a practical exercise.
- Mention AI's potential role in advancing encryption methods for end-to-end security.


# Two-Factor Authentication (2FA)

- Why 2FA matters for security <!-- .element: class="fragment" data-fragment-index="2" -->
- How 2FA adds protection <!-- .element: class="fragment" data-fragment-index="3" -->
- Setting up 2FA <!-- .element: class="fragment" data-fragment-index="4" -->
- Examples of 2FA in real life <!-- .element: class="fragment" data-fragment-index="5" -->
- UbiKeys <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Start by explaining 2FA as an additional layer of security, reducing the risk of unauthorized access.
- Walk through setting up 2FA on a sample service.
- Share examples from widely used apps, like Gmail and Instagram, where 2FA has prevented breaches.


# Single Sign-On (SSO)

- SSO providers <!-- .element: class="fragment" data-fragment-index="2" -->
- How SSO architecture works <!-- .element: class="fragment" data-fragment-index="3" -->
- SAP solutions for SSO <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain the convenience and security benefits of SSO.
- Cover popular providers like Google and Microsoft.
- Briefly introduce SAP’s SSO solutions for enterprise contexts to show how SSO scales in large organizations.


# Exercise 
- Let simprove our app with a simple encryption meachism
- Introducing base64
- advanced concept: md5, sha256


# API security

- API keys <!-- .element: class="fragment" data-fragment-index="2" -->
- Public/Private keys <!-- .element: class="fragment" data-fragment-index="3" -->
- Google credentials.json <!-- .element: class="fragment" data-fragment-index="4" -->
- Lets speak about Tommy's JSON -> CSV fauxpas <!-- .element: class="fragment" data-fragment-index="5" -->


# Session 3: Web Security and Online Safety


# Web Technologies and Security

- SSH <!-- .element: class="fragment" data-fragment-index="2" -->
- Importance of port security <!-- .element: class="fragment" data-fragment-index="3" -->
- How is tracking working <!-- .element: class="fragment" data-fragment-index="4" -->
- Roles of SSH and SSL/TLS in web security <!-- .element: class="fragment" data-fragment-index="5" -->
- Secretkeys in action pipelines <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Explain SSH for secure server access
- Cover port security basics, such as limiting open ports to reduce attack surfaces.


# Common Web Vulnerabilities

- Overview of common web vulnerabilities ([Resource](https://www.google.com/search?client=firefox-b-d&q=Common+Web+Vulnerabilities)) <!-- .element: class="fragment" data-fragment-index="2" -->
- SQL injection: risks and defenses <!-- .element: class="fragment" data-fragment-index="3" -->
- Cross-Site Scripting (XSS) <!-- .element: class="fragment" data-fragment-index="4" -->
- Other critical vulnerabilities <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Begin with an overview of the most common vulnerabilities affecting web applications.
- Provide examples of SQL injection and XSS attacks and discuss prevention techniques.
- Highlight additional vulnerabilities such as CSRF and insecure deserialization.


# Online Safety

- Identifying spear phishing <!-- .element: class="fragment" data-fragment-index="2" -->
- Social engineering tactics <!-- .element: class="fragment" data-fragment-index="3" -->
- Managing online harassment <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Discuss how spear phishing is a targeted form of phishing and ways to recognize it.
- Explain social engineering as a psychological manipulation technique.
- Offer advice on dealing with online harassment and protecting digital identity.


# The cryptoworld

- Drops <!-- .element: class="fragment" data-fragment-index="2" -->
- Integrations <!-- .element: class="fragment" data-fragment-index="3" -->
- Wallets <!-- .element: class="fragment" data-fragment-index="4" -->
- Whales and other scams <!-- .element: class="fragment" data-fragment-index="5" -->


# Secure Coding Practices

- Avoiding common pitfalls in code <!-- .element: class="fragment" data-fragment-index="2" -->
- Best practices for handling keys <!-- .element: class="fragment" data-fragment-index="3" -->
- Techniques to prevent keylogging <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Share coding practices that reduce vulnerabilities (e.g., input validation).
- Discuss secure methods for storing and handling API keys.
- Mention tips to prevent keylogging, such as securing devices and using anti-keylogging software.


# Test-Driven Development (TDD)

- Overview of TDD methodologies <!-- .element: class="fragment" data-fragment-index="2" -->
- Role of TDD in improving security <!-- .element: class="fragment" data-fragment-index="3" -->
- Practical benefits of TDD <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain TDD as a development practice that emphasizes writing tests before code.
- Highlight how TDD can catch security issues early in the development process.
- Discuss the real-world security benefits of TDD, including bug reduction and code resilience.


# Vulnerability Scanning

- Basics of using nmap for scanning <!-- .element: class="fragment" data-fragment-index="2" -->
- Web application vulnerability scanning <!-- .element: class="fragment" data-fragment-index="3" -->
- Techniques for analyzing scan results <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Introduce nmap as a popular tool for network scanning and vulnerability detection.
- Demonstrate web application scanning with tools like OWASP ZAP or Nikto.
- Teach participants to interpret scan results and prioritize found vulnerabilities.


# Setting Up HTTPS

- Why HTTPS is essential for security <!-- .element: class="fragment" data-fragment-index="2" -->
- Using Certbot to set up HTTPS <!-- .element: class="fragment" data-fragment-index="3" -->
- Step-by-step implementation <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain HTTPS as a layer that encrypts data between client and server.
- Walk participants through installing Certbot and obtaining an SSL certificate.
- Include a step-by-step implementation for a practical setup experience.


# JWT Token Authentication

- Introduction to JWT (JSON Web Tokens) <!-- .element: class="fragment" data-fragment-index="2" -->
- Hands-on: analyzing the structure of a JWT <!-- .element: class="fragment" data-fragment-index="3" -->
- Understanding token components: header, payload, signature <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Define JWT and its role in secure stateless authentication.
- Conduct an exercise where participants decode and inspect a JWT to understand its structure.
- Discuss the three components of a JWT and how each part contributes to security.


# Exercise 
- Continue making our website


# Session 4: Security for Developers and DevOps


# Secure Coding and SDLC

- Best practices for secure coding <!-- .element: class="fragment" data-fragment-index="2" -->
- Overview of SDLC (Software Development Life Cycle) <!-- .element: class="fragment" data-fragment-index="3" -->
- Salting and hashing techniques <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Emphasize secure coding principles, like input validation and avoiding hard-coded secrets.
- Introduce SDLC phases and how security can be integrated from planning to maintenance.
- Explain the importance of salting and hashing, especially for passwords, to prevent attacks like rainbow tables.


# DevOps and Security

- Integrating security in CI/CD pipelines <!-- .element: class="fragment" data-fragment-index="2" -->
- Enhancing security in DevOps workflows <!-- .element: class="fragment" data-fragment-index="3" -->
- Examples: Security tools and automation <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Show how DevOps tools, like Jenkins or GitLab, can integrate security steps.
- Discuss specific techniques, like secret management and dependency scanning.
- Provide real-world examples of CI/CD security tools, such as Snyk or Aqua Security.


# Security Testing

- Introduction to static and dynamic analysis <!-- .element: class="fragment" data-fragment-index="2" -->
- Penetration testing essentials <!-- .element: class="fragment" data-fragment-index="3" -->
- Overview of commonly used tools <!-- .element: class="fragment" data-fragment-index="4" -->
- https://www.clearview.ai/ <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Explain the difference between static analysis (code-level) and dynamic analysis (runtime).
- Discuss the role of penetration testing in discovering security gaps.
- List tools like SonarQube for static analysis and OWASP ZAP for dynamic testing.


# Agile and Waterfall Methodologies

- Secure development within Agile <!-- .element: class="fragment" data-fragment-index="2" -->
- Comparing Agile vs Waterfall in security contexts <!-- .element: class="fragment" data-fragment-index="3" -->
- Practical implications of each methodology <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Describe how Agile’s iterative approach supports continuous security testing.
- Contrast with Waterfall’s linear nature, highlighting benefits for high-risk environments.
- Discuss how to adapt security practices based on methodology and project needs.


# Secure Coding Practice

- Advanced exercises in secure coding <!-- .element: class="fragment" data-fragment-index="2" -->
- Secure code examples in Python <!-- .element: class="fragment" data-fragment-index="3" -->
- GolfCode challenge <!-- .element: class="fragment" data-fragment-index="4" -->
- Code review for security <!-- .element: class="fragment" data-fragment-index="5" -->
- If the cat is out of the bag https://joindeleteme.com/ <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Facilitate coding exercises that emphasize secure structures and error handling.
- Provide Python examples illustrating secure programming techniques.
- Introduce GolfCode (code golf for security) as a fun way to optimize secure code.
- Discuss the importance of regular code reviews to catch security flaws early.


# Using Security Testing Tools

- Introduction to Metasploit <!-- .element: class="fragment" data-fragment-index="2" -->
- Using VMs for safe testing environments <!-- .element: class="fragment" data-fragment-index="3" -->
- Burp Suite for web application security <!-- .element: class="fragment" data-fragment-index="4" -->
- ClamAV for malware detection <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Brief overview of Metasploit for testing exploits in a controlled way.
- Encourage using virtual machines for isolating tests.
- Demonstrate how Burp Suite is used to secure web applications and perform vulnerability scans.
- Introduce ClamAV as a simple, effective antivirus tool for DevOps environments.


# Setting Up Secure CI/CD Pipelines

- Security considerations in CI/CD <!-- .element: class="fragment" data-fragment-index="2" -->
- Using Jenkins, GitLab CI/CD, CircleCI for secure deployments <!-- .element: class="fragment" data-fragment-index="3" -->
- Step-by-step guide for a secure CI/CD pipeline <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Discuss the concept of shifting security left in CI/CD.
- Provide specific steps for securing builds, testing, and deployments in CI/CD.
- Offer a practical guide, from setting up access controls to automating security scans.


# Agile vs Waterfall

- Methodology-specific security exercises <!-- .element: class="fragment" data-fragment-index="2" -->
- Comparing Agile and Waterfall through hands-on scenarios <!-- .element: class="fragment" data-fragment-index="3" -->
- Key security considerations in each approach <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Facilitate exercises that show Agile’s iterative security integration vs. Waterfall’s planned checkpoints.
- Use scenarios to help participants understand how each methodology impacts security.
- Summarize which method to choose based on project type, emphasizing flexibility vs. structure.


### Wrap-Up and Q&A

Speaker Notes:
- Summarize each session highlight for reinforcement.
- Reiterate key security practices, from SDLC to secure coding.
- Encourage participants to review their practices and apply what they’ve learned.


# Open Floor for Questions

Speaker Notes:
- Open the floor for questions and engage with participants’ thoughts.
- Provide resources like OWASP, security blogs, and recommended tools.
- Encourage participants to keep exploring security in development and DevOps practices.
- Address remaining queries
- Suggest additional resources for further learning
- Encourage continued learning and exploration


# Tomorrow: Cloud Computing

Speaker Notes:
- Mention cloud security as a follow-up topic for upcoming sessions.
- Highlight the importance of understanding cloud infrastructure, access control, and compliance in cloud environments.
