# Cyber security


 # Timetable
- Class 9:00 - 10:30 (16.00 - 17.30 JST)
- Break 10:30 - 10:40 (17.30 - 17.40 JST)
- Class 10:40 - 11:50 (17.40 - 20.10 JST)
- Break 11:50 - 12:00 (20.10 - 20.20 JST)
- Class 12:00 - 13:05 (20.20 - 21.05 JST)
- `Lunch break`
- Class 14:05 - 15:35 (self paced learning)
- Break 15:35 - 15:45
- Class 15:45 - 17:15 (self paced learning)
- Break 17:15 - 17:25
- Class 17:25 - 18:10 (self paced learning) (00.25 - 01.10 JST)
<!--**Time** | **Block**-->
<!-----------|----------->
<!--09:30 - 10:30 | Lesson-->
<!--10:45 - 12:00 | Lesson-->
<!--12:00 - 13:00 | Lunch Break-->
<!--13:00 - 14:45 | Lesson-->
<!--15:00 - 16:30 | Lesson-->


# Today's agenda

- Test some AI code integrations <!-- .element: class="fragment" data-fragment-index="2" -->
- The simple world of shortcuts
- White hat, red team? A introduction <!-- .element: class="fragment" data-fragment-index="3" -->
- Networking and Privacy <!-- .element: class="fragment" data-fragment-index="4" -->
- Web Security and Online Safety <!-- .element: class="fragment" data-fragment-index="5" -->
- Security for Developers and DevOps <!-- .element: class="fragment" data-fragment-index="6" -->
- We have a look at many viruses <!-- .element: class="fragment" data-fragment-index="7" -->


# Exercise

## Test some shortcut automations

- Power user can copy paste fast, and strip fast things
- Search & replace
- Regex


# Session 1: Introduction to Cyber Security and Basic Security Concerns


# Introduction to Cyber Security

- [Meme](https://cloudisland.nz/@dillon/112767541388187298) <!-- .element: class="fragment" data-fragment-index="2" -->
- WhiteHat hacker/Red team <!-- .element: class="fragment" data-fragment-index="3" -->
- Definition and significance <!-- .element: class="fragment" data-fragment-index="4" -->
- Real-world implications <!-- .element: class="fragment" data-fragment-index="5" -->
- Security as a mindset <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Open with the meme to lighten the mood and grab attention.
- Define cybersecurity, emphasizing the role of ethical hackers (WhiteHat/Red Team) in testing security.
- Discuss the mindset needed for cybersecurity: a proactive approach and constant learning.


# Operating Systems and Security

- Overview of Windows, MacOS, Linux <!-- .element: class="fragment" data-fragment-index="2" -->
- Security features <!-- .element: class="fragment" data-fragment-index="3" -->
    - Microsoft criticism (Security Now podcast) <!-- .element: class="fragment" data-fragment-index="4" -->
- Common vulnerabilities <!-- .element: class="fragment" data-fragment-index="5" -->
- Importance of regular updates <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Explain key OS differences in terms of security architecture.
- Mention security features like macOS's Gatekeeper and Linux’s user permissions.
- Touch on the Security Now podcast's Microsoft criticism for awareness on controversial takes.
- Highlight common vulnerabilities and stress the importance of regular software updates to stay protected.


# Internet Structure and Security

- DNS (Domain Name System) <!-- .element: class="fragment" data-fragment-index="2" -->
- HTTP vs HTTPS <!-- .element: class="fragment" data-fragment-index="3" -->
- IP addresses <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Simplify DNS as the "phonebook of the internet" for ease of understanding.
- Differentiate HTTP from HTTPS, emphasizing the latter’s role in secure transactions.
- Briefly explain IP addresses and how they identify devices on the network, setting up for later network security discussions.


# Basic Security Concerns

- Passwords <!-- .element: class="fragment" data-fragment-index="2" -->
- Phishing ([Example](https://hachyderm.io/@urldna@infosec.exchange)) <!-- .element: class="fragment" data-fragment-index="3" -->
- Malware <!-- .element: class="fragment" data-fragment-index="4" -->
- SolarWinds breach <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Start with passwords as a first line of defense in security.
- Share the phishing link example to illustrate how convincing scams can be.
- Mention the SolarWinds attack to highlight real-world risks and the impact of cyber vulnerabilities on organizations.


# Password Security

- Importance of strong passwords <!-- .element: class="fragment" data-fragment-index="2" -->
- Techniques for creating strong passwords <!-- .element: class="fragment" data-fragment-index="3" -->
- Advantages of using password managers <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Stress why weak passwords are a major security risk.
- Provide simple rules for creating strong passwords (e.g., length, complexity, no reuse).
- Introduce password managers as a tool to improve security without the hassle of remembering multiple passwords.


# Strong Password Creation

- Use online tools for password strength testing <!-- .element: class="fragment" data-fragment-index="2" -->
- Analyze password strength in real-time <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:
- Show a couple of online tools and perform live demonstrations of weak vs. strong passwords.


# Terminal and Command Line Basics

- Opening terminal/CMD <!-- .element: class="fragment" data-fragment-index="2" -->
- Run basic commands like `whoami` and `ipconfig`/`ifconfig` <!-- .element: class="fragment" data-fragment-index="3" -->
- Practical exercise: finding IP address <!-- .element: class="fragment" data-fragment-index="4" -->
- Discuss StuxNet example <!-- .element: class="fragment" data-fragment-index="5" -->
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


# Session 3: Web Security and Online Safety


# Web Technologies and Security

- SSH <!-- .element: class="fragment" data-fragment-index="2" -->
- Importance of port security <!-- .element: class="fragment" data-fragment-index="3" -->
- Roles of SSH and SSL/TLS in web security <!-- .element: class="fragment" data-fragment-index="4" -->

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
- https://european-alternatives.eu/ <!-- .element: class="fragment" data-fragment-index="5" -->

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
