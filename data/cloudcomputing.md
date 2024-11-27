# Cloud Computing


# Today's agenda

- There is no cloud, its just somebody else compter <!-- .element: class="fragment" data-fragment-index="2" -->
- Containerization and infrastructure as code <!-- .element: class="fragment" data-fragment-index="3" -->
- GitOps <!-- .element: class="fragment" data-fragment-index="4" -->
- ML/Ops <!-- .element: class="fragment" data-fragment-index="5" -->
- Open stage <!-- .element: class="fragment" data-fragment-index="6" -->


# Session 1: Understanding the Cloud


## What is Cloud Computing?
![cloud](./data/img/cloud.jpg)

- Simple Definition <!-- .element: class="fragment" data-fragment-index="3" -->
- Why it Matters <!-- .element: class="fragment" data-fragment-index="4" -->
- Real-world Analogy <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Simple Definition: Using someone else's computer to store data or run applications.
- Why it Matters: Cost savings, easy access, flexibility.
- Real-world Analogy: Renting an apartment instead of buying a house. 


## A Day in the Life of a DevOps Engineer

- Daily Standups <!-- .element: class="fragment" data-fragment-index="2" -->
- Monitoring and Alerts <!-- .element: class="fragment" data-fragment-index="3" -->
- Automating Workflows <!-- .element: class="fragment" data-fragment-index="4" -->
- Infrastructure as Code (IaC) <!-- .element: class="fragment" data-fragment-index="5" -->
- Troubleshooting and Optimization <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- **Daily Standups**: Describe standups as short, daily meetings where DevOps engineers align with other teams to discuss progress, upcoming changes, and any roadblocks, fostering cross-functional collaboration.
- **Monitoring and Alerts**: Emphasize monitoring as a key task where DevOps engineers track performance metrics and respond to alerts from monitoring tools (e.g., Grafana, Prometheus) to quickly resolve issues before they impact users.
- **Automating Workflows**: Explain how DevOps engineers focus on reducing manual tasks through automation, creating scripts and setting up CI/CD pipelines in tools like Jenkins or GitLab to speed up software deployment and updates.
- **Infrastructure as Code (IaC)**: Discuss IaC as a practice where infrastructure (e.g., servers, databases) is managed with code, using tools like Terraform or Ansible to maintain consistent configurations across environments and make resource management scalable and repeatable.
- **Troubleshooting and Optimization**: Highlight the continuous responsibility to troubleshoot issues and optimize performance, where DevOps engineers diagnose and resolve performance bottlenecks and look for ways to improve efficiency, stability, and security in the infrastructure.


## Evolution of Computing

- Centralized to Distributed <!-- .element: class="fragment" data-fragment-index="2" -->
- Rise of Shared Resources <!-- .element: class="fragment" data-fragment-index="3" -->
- Internet Era <!-- .element: class="fragment" data-fragment-index="4" -->
- Lets look at btop <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Centralized to Distributed: Transition from mainframes to web3 Explain the progression from centralized systems to the decentralized web3 era.
- Rise of Shared Resources: From individual machines to cloud ecosystems Discuss the concept of shared resources and how it laid the foundation for cloud computing.
- Internet Era: Accessing global resources over the internet Highlight how internet access enables cloud infrastructure to provide global reach.


## Types of '... as a Service'

- IaaS - Infrastructure <!-- .element: class="fragment" data-fragment-index="2" -->
- PaaS - Platform <!-- .element: class="fragment" data-fragment-index="3" -->
- SaaS - Software <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- IaaS: Infrastructure for flexibility and control
- PaaS: Platforms for streamlined development
- SaaS: Fully managed applications for ease of use


## Benefits and Challenges

- Advantages: Cost savings, scalability, accessibility <!-- .element: class="fragment" data-fragment-index="2" -->
- Challenges: Data privacy, potential downtime <!-- .element: class="fragment" data-fragment-index="3" -->
- Risk Mitigation: Choosing the right deployment way and provider is key <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Advantages: Cost savings, scalability, accessibility
- Challenges: Data privacy, potential downtime
- Risk Mitigation: Choosing the right deployment way and provider is key


## Major Cloud Providers

- Main Players: AWS, Azure, Google Cloud <!-- .element: class="fragment" data-fragment-index="2" -->
- Differentiators: Market share, unique services <!-- .element: class="fragment" data-fragment-index="3" -->
- Choosing the Right Provider: AI capabilities, global reach <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Introduce the top cloud providers and their unique offerings.
- Offer insights on choosing a provider based on use case, such as AI or integration needs.


## Exercise

- Diagram the Cloud: Design a basic cloud architecture in draw.io <!-- .element: class="fragment" data-fragment-index="2" -->
- SSH Practice: Connect and explore a DigitalOcean droplet <!-- .element: class="fragment" data-fragment-index="4" -->
- Exploring the Console: Familiarize with the cloud dashboard <!-- .element: class="fragment" data-fragment-index="5" -->


# Session 2: Managing Data in the Cloud


## Cloud Storage Types

- Object, Block, and File Storage <!-- .element: class="fragment" data-fragment-index="2" -->
- Use Cases: Choosing the right storage type for specific needs <!-- .element: class="fragment" data-fragment-index="3" -->
- Access Methods: APIs, console, and command-line <!-- .element: class="fragment" data-fragment-index="4" -->
- Linux Permissions: Using 'ls -la' to check file permissions <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- **Object Storage**: Explain that object storage is ideal for large-scale, unstructured data like media files and backups, as it stores data in "objects" with metadata, making it highly scalable and accessible through APIs.
- **Block Storage**: Highlight block storage as a low-latency option for databases and applications requiring frequent read-write operations. Explain how it divides data into blocks, similar to a hard drive, giving high-speed access.
- **File Storage**: Describe file storage as best for structured data and files that need to be shared across multiple systems, using traditional file hierarchies with directory paths.
- **Use Cases**: Clarify that object storage is typically used in web applications, block storage for high-performance databases, and file storage for collaborative document sharing.
- **Access Methods**: Introduce common ways to access these storage types, emphasizing API use for object storage and CLI for block/file storage.
- **Linux Permissions with `ls -la`**: Demonstrate how to use `ls -la` to view file permissions in Linux, explaining each permission type (read, write, execute) and how it affects storage access.


## Introduction to Cloud Databases

- <span>[ Meme ](https://programmerhumor.io/programming-memes/whyihatewritingdatabasequeries/)</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- Database Types: SQL vs NoSQL <!-- .element: class="fragment" data-fragment-index="3" -->
- Popular Options: MySQL, PostgreSQL, MongoDB, Cassandra <!-- .element: class="fragment" data-fragment-index="4" -->
- Choosing Based on Needs: SQL for structure, NoSQL for flexibility <!-- .element: class="fragment" data-fragment-index="5" -->
- <span>Some [big](https://www.wheelhouse.com/resources/the-top-10-largest-databases-in-the-worldfamiand-present-a7843) ones </span> <!-- .element: class="fragment" data-fragment-index="6" -->
- <span>Another [ big player ](https://search.brave.com/search?q=elastic+search&source=desktop)</span> <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:
- Outline the differences between SQL and NoSQL databases.
- Describe scenarios for each type, such as SQL for transactional data and NoSQL for unstructured data.


## Migrations in data
### Or how do I move my users to a new table?

- Why Do We Need Migrations? <!-- .element: class="fragment" data-fragment-index="2" -->
    - Modernization: Moving to newer, more efficient technologies or cloud platforms <!-- .element: class="fragment" data-fragment-index="4" -->
    - Cost and Performance: Reducing costs and optimizing performance by moving to cloud or managed services <!-- .element: class="fragment" data-fragment-index="5" -->
    - Scalability and Flexibility: Enabling the system to grow and adapt to future requirements <!-- .element: class="fragment" data-fragment-index="6" -->
- Managing Migrations Effectively <!-- .element: class="fragment" data-fragment-index="7" -->
    - Planning: Assessing current infrastructure, identifying dependencies, and creating a migration roadmap <!-- .element: class="fragment" data-fragment-index="8" -->
    - Data Integrity: Ensuring data consistency and security throughout the migration process <!-- .element: class="fragment" data-fragment-index="9" -->
    - Phased Approach: Rolling out changes incrementally to minimize downtime and manage risks <!-- .element: class="fragment" data-fragment-index="10" -->
- Incident Rollback <!-- .element: class="fragment" data-fragment-index="11" -->
    - Version Control: Using Git or other tools to track changes and enable easy rollbacks <!-- .element: class="fragment" data-fragment-index="12" -->
    - Backups and Snapshots: Taking regular snapshots or backups before major changes to recover quickly if needed <!-- .element: class="fragment" data-fragment-index="13" -->
    - Rollback Procedures: Documenting and testing rollback steps to restore previous versions quickly during issues <!-- .element: class="fragment" data-fragment-index="14" -->

Speaker Notes:
- **Why Do We Need Migrations?**: Explain how migration helps organizations move to more modern infrastructure, reduce costs, and increase scalability. Use examples like transitioning from monolithic on-premise systems to microservices in the cloud.
- **Managing Migrations Effectively**: Highlight the importance of planning, such as mapping dependencies and assessing data requirements. Emphasize a phased approach for handling larger migrations, allowing small portions to go live, be tested, and adjusted before a complete rollout.
- **Incident Rollback**: Describe rollback as an essential part of migration, where things may need to revert to a previous state if errors arise. Explain version control for tracking changes, and the importance of thorough rollback procedures and regular backups to ensure minimal data loss or downtime in case of failure.


## Nextcloud and Open Source Benefits

- What is Nextcloud? <!-- .element: class="fragment" data-fragment-index="2" -->
    - Self-hosted cloud platform for file sharing, collaboration, and data storage <!-- .element: class="fragment" data-fragment-index="3" -->
    - Alternative to proprietary solutions like Google Drive or Dropbox, but hosted on your own servers <!-- .element: class="fragment" data-fragment-index="4" -->
- Benefits of Open Source <!-- .element: class="fragment" data-fragment-index="5" -->
    - Full Control: Users own their data and server configurations, enhancing privacy and security <!-- .element: class="fragment" data-fragment-index="6" -->
    - Customization and Flexibility: Easily extend with plugins and integrate with other open-source tools <!-- .element: class="fragment" data-fragment-index="7" -->
    - Community and Cost Efficiency: Supported by a community-driven ecosystem without licensing fees <!-- .element: class="fragment" data-fragment-index="8" -->

Speaker Notes:
- **What is Nextcloud?**: Introduce Nextcloud as a self-hosted, open-source cloud solution for securely sharing and managing data.
- **Benefits of Open Source**: Emphasize Nextcloud’s privacy advantages and customization options, along with the cost-saving benefits of using a community-supported platform.


## Introduction to Containers and Docker

- <span>[meme](https://programmerhumor.io/python-memes/docker-is-born/)</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- Docker: Tool for app deployment in containers <!-- .element: class="fragment" data-fragment-index="3" -->
- Containers vs VMs: Lightweight and resource-efficient <!-- .element: class="fragment" data-fragment-index="4" -->
- Benefits: Scalability, consistency, and easy management <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Introduce Docker as a foundational tool for cloud app deployment.
- Compare containers to VMs and highlight container advantages in cloud environments.


## Data Consistency and Availability

- Importance: Why consistency and availability are essential for cloud systems <!-- .element: class="fragment" data-fragment-index="2" -->
- Key Techniques: Replication and load balancing <!-- .element: class="fragment" data-fragment-index="3" -->
- Best Practices: Strategies for achieving high availability <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- **Importance**: Define consistency as keeping data accurate across systems, and availability as ensuring systems are always accessible. Emphasize their role in reliable cloud services.
- **Techniques**: Explain replication as the process of copying data across multiple servers for reliability and load balancing as distributing requests to prevent overloads, improving performance and fault tolerance.
- **Best Practices**: Highlight combining replication and load balancing, along with monitoring and failover processes, to ensure data is both accurate and accessible even during high demand or failures.


## Security Considerations

- Encryption: Securing data both at rest and in transit <!-- .element: class="fragment" data-fragment-index="2" -->
- Access Control: Importance of strong authentication <!-- .element: class="fragment" data-fragment-index="3" -->
- Regular Backups: Protecting against data loss <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- **Encryption**: Describe how encrypting data at rest (stored data) and in transit (data moving across networks) protects against unauthorized access.
- **Access Control**: Emphasize multi-factor authentication and strong password policies as essential for preventing unauthorized access.
- **Backups**: Explain the role of backups in disaster recovery, ensuring data can be restored in case of corruption, accidental deletion, or security breaches.


## The World of Proxies

- Raspberry Pi Proxies: Affordable, DIY proxy servers <!-- .element: class="fragment" data-fragment-index="2" -->
- Port Forwarding: Directing external traffic to internal network services <!-- .element: class="fragment" data-fragment-index="3" -->
- Web Scraping: Using proxies to avoid IP blocks and gather data <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- **Raspberry Pi Proxies**: Introduce the idea of setting up a Raspberry Pi as a low-cost, personal proxy server, useful for learning and small-scale projects.
- **Port Forwarding**: Explain port forwarding as a method to route traffic from the internet to specific devices or services on a private network, useful in accessing servers or applications remotely.
- **Web Scraping**: Discuss the role of proxies in web scraping, where rotating IPs help prevent blocking, making it easier to gather public data from websites without restrictions.


## Exercise

- Cloud Storage: Upload and manage files <!-- .element: class="fragment" data-fragment-index="2" -->
- GitHub Setup: Create and secure a GitHub account <!-- .element: class="fragment" data-fragment-index="3" -->
- Implementing Security: Configure permissions, encryption, 2FA <!-- .element: class="fragment" data-fragment-index="4" -->
- Explore online code editors like vscode online, glitch, codepen or stackblitz <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Practice file management in the cloud, such as uploading and accessing files.
- Set up GitHub for collaborative coding and review best practices for securing accounts.


# Session 3: Connecting and Managing Cloud Resources


## Introduction to GitOps

- [ Example ](/Users/tommy/Downloads/deployment-methods.drawio.png) <!-- .element: class="fragment" data-fragment-index="3" -->
- Infrastructure as code
- Purpose compared to procedual

Speaker Notes:
- Definition: GitOps is a practice where Git is the single source of truth for application and infrastructure configurations.
- Purpose: It combines Git version control with automated deployments, ensuring that all changes to applications and infrastructure are tracked, versioned, and auditable.


## GitOps Principles

- Declarative Descriptions <!-- .element: class="fragment" data-fragment-index="2" -->
- Automatic Reconciliation <!-- .element: class="fragment" data-fragment-index="3" -->
- Auditability <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Declarative Descriptions: Use declarative descriptions of the system’s desired state (YAML/JSON files in Git).
- Automatic Reconciliation: Automation tools (like ArgoCD) continuously ensure the actual state matches the desired state in Git.
- Auditability: All configuration changes are tracked in Git, allowing for easy rollbacks and transparency in deployments.


## Benefits of GitOps

- Simplified Rollbacks <!-- .element: class="fragment" data-fragment-index="2" -->
- Increased Reliability <!-- .element: class="fragment" data-fragment-index="3" -->
- Improved Collaboration <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Simplified Rollbacks: Reverting to a previous version is as easy as checking out an older Git commit.
- Increased Reliability: Git’s version control helps avoid "configuration drift" by enforcing consistency across deployments.
- Improved Collaboration: GitOps encourages collaboration since all configurations are in Git, making it easy to review, approve, and discuss changes.


## Practical Activity ( watch tommy doing it practically ):

- Show how to trigger an ArgoCD deployment by simply pushing a new commit to Git. This demonstrates the automation and simplicity of GitOps in action.


## Other procedual strategies

- Ansible <!-- .element: class="fragment" data-fragment-index="2" -->
- Its agentless <!-- .element: class="fragment" data-fragment-index="3" -->
- It uses yaml <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Ansible: Focuses on configuration management, provisioning, and automation of servers and applications
- Ansible: Does not require agents to be installed on target systems, making it agentless.


## VIM 
### and other religious beliefs


## Cloud Networking Basics

- Virtual Networks: Like your wifi at home <!-- .element: class="fragment" data-fragment-index="2" -->
- Subnets and Security Rules: Network segmentation <!-- .element: class="fragment" data-fragment-index="3" -->
- VPN (Virtual Private Network) <!-- .element: class="fragment" data-fragment-index="4" -->
- VLAN (Virtual Local Area Network) <!-- .element: class="fragment" data-fragment-index="5" -->
- VXLAN (Virtual Extensible LAN) <!-- .element: class="fragment" data-fragment-index="6" -->
- Checkout GCP VPC network interface <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:
- how virtual networks work
- Walk through a basic setup to configure a secure, segmented network.
- VPN (Virtual Private Network): Uses the internet to connect two or more existing networks, allowing users to access physical networks from anywhere while ensuring secure browsing.
- VLAN (Virtual Local Area Network): A software-defined network that divides a physical network into multiple logical networks, improving network segmentation and security.
- VXLAN (Virtual Extensible LAN): A network virtualization technology that extends Layer 2 (Ethernet) networks over Layer 3 (IP) networks, enabling communication between virtual machines and physical devices.


## Load Balancing and Auto-Scaling

- Load Balancing Basics: Traffic distribution <!-- .element: class="fragment" data-fragment-index="2" -->
- Auto-Scaling: Dynamic resource adjustment <!-- .element: class="fragment" data-fragment-index="3" -->
- Lets look at replicaCount in Tommy's cluster <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Define load balancing and auto-scaling and their importance in handling traffic surges.
- Demonstrate setting up a load balancer with auto-scaling to show scalability in action.


## Monitoring and Alerts

- Monitoring Tools: Tracking resources <!-- .element: class="fragment" data-fragment-index="2" -->
- Setting Alerts: Notifications for conditions <!-- .element: class="fragment" data-fragment-index="3" -->
- Continuous Monitoring: Strategies for consistent tracking <!-- .element: class="fragment" data-fragment-index="4" -->
- Lets see a prometheus instance <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Introduce basic monitoring tools and alerts to track cloud performance.
- Discuss strategies for continuous monitoring to ensure cloud health.


## Understanding Cloud Costs

- [ Meme ](https://www.google.com/search?sca_esv=ac1a0fd35070d5f1&q=aws+bill+meme&udm=2&fbs=AEQNm0Aa4sjWe7Rqy32pFwRj0UkWd8nbOJfsBGGB5IQQO6L3J_86uWOeqwdnV0yaSF-x2jon2iao6KWCaVjfn7ahz_sf_uPKlBgHiXUTxuTOrBgkEHAZKBArNMIg_JaUOYCTVNreNhAlJbFKEmzPuAQkoiBtIhrPYKQR3WHGzgZYwxf2NkHIa-s&sa=X&ved=2ahUKEwjX_fvBgdiJAxX3oa8BHSWoHIYQtKgLegQIEhAB&biw=1368&bih=790&dpr=2.5) <!-- .element: class="fragment" data-fragment-index="2" -->
- Pay-as-You-Go: Cloud pricing models <!-- .element: class="fragment" data-fragment-index="3" -->
- Cost Management: Tips to optimize costs <!-- .element: class="fragment" data-fragment-index="4" -->
- Expense Tracking: Tools for monitoring cloud costs <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Explain cloud pricing, emphasizing cost-effective usage.
- Discuss strategies to reduce expenses, such as monitoring unused resources.


## Exercise

- Diagram a e-commerce shop with web server, database, payment gateway <!-- .element: class="fragment" data-fragment-index="2" -->
- Compare to car-company example <!-- .element: class="fragment" data-fragment-index="3" -->
- Cloud Applications: Explore Gmail, Google Calendar <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Guide participants in setting up and managing virtual machines.
- Demonstrate real-time collaboration tools to showcase the cloud’s utility in teamwork.


# Session 4: Cloud Performance Optimization and Monitoring


## Importance of Performance Optimization in Cloud Environments

- Why Optimize?: Cost efficiency, faster response times, better user experience <!-- .element: class="fragment" data-fragment-index="2" -->
- Key Metrics: CPU usage, memory utilization, network latency <!-- .element: class="fragment" data-fragment-index="3" -->
- Real-World Use Cases: E-commerce, streaming services, cloud gaming <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain why performance optimization is critical for cost savings and ensuring fast response times.
- Introduce key metrics to monitor, like CPU, memory, and network latency, to understand resource usage.
- Provide examples across various industries, like reducing load times for e-commerce and minimizing lag in cloud gaming.


## Monitoring Tools and Techniques

- Prometheus and Grafana: Collecting and visualizing metrics <!-- .element: class="fragment" data-fragment-index="2" -->
- Cloud Provider Monitoring: AWS CloudWatch, Google Cloud Monitoring <!-- .element: class="fragment" data-fragment-index="3" -->
- Setting Alerts: Immediate notifications for anomalies <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Introduce Prometheus for collecting data points and Grafana for creating visual dashboards.
- Highlight native monitoring tools from cloud providers, such as AWS CloudWatch and Google Cloud Monitoring.
- Explain the importance of alerts in maintaining high availability, as they notify DevOps teams when certain thresholds are exceeded.


## Content Delivery and Latency Reduction

- CDNs: How Content Delivery Networks reduce latency <!-- .element: class="fragment" data-fragment-index="2" -->
- Edge Computing: Processing data closer to the user <!-- .element: class="fragment" data-fragment-index="3" -->
- Cache Management: Using caching for faster data access <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain how CDNs store content closer to end-users to reduce latency, benefiting applications from websites to cloud gaming.
- Introduce edge computing, where compute resources are deployed closer to users, reducing travel time for data.
- Discuss cache management, using strategies like in-memory caches to serve frequently accessed data faster.


## Cost Management and Optimization

- Pay-as-You-Go Model: Understanding cloud billing and resource costs <!-- .element: class="fragment" data-fragment-index="2" -->
- Scaling Approaches: Auto-scaling and right-sizing resources <!-- .element: class="fragment" data-fragment-index="3" -->
- Reserved Instances and Spot Pricing: Long-term savings <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain cloud’s pay-as-you-go pricing model and how to monitor costs based on usage.
- Introduce auto-scaling for demand-based resource management, and right-sizing for eliminating underused resources.
- Discuss ways to reduce costs, such as using reserved instances or spot pricing for non-critical workloads.


## Incident Response and Troubleshooting in the Cloud

- Incident Detection: Using monitoring tools to identify issues <!-- .element: class="fragment" data-fragment-index="2" -->
- Root Cause Analysis: Tools and strategies for diagnosing problems <!-- .element: class="fragment" data-fragment-index="3" -->
- Automation in Incident Response: Reducing time to resolution <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Describe the importance of prompt incident detection to minimize impact on users.
- Introduce root cause analysis (RCA), with tools like AWS CloudTrail for investigating issues in cloud infrastructure.
- Discuss automation as a way to streamline response times, using scripts and tools to resolve common issues automatically.


## SRE Concepts in Cloud Infrastructure

- Site Reliability Engineering (SRE): Ensuring stability and reliability <!-- .element: class="fragment" data-fragment-index="2" -->
- Service Level Objectives (SLOs): Setting performance goals for uptime <!-- .element: class="fragment" data-fragment-index="3" -->
- Blameless Postmortems: Learning from incidents without assigning blame <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Define SRE and its role in maintaining cloud system reliability, minimizing downtime, and addressing user issues.
- Explain SLOs as measurable performance goals (e.g., 99.9% uptime), helping teams gauge and improve reliability.
- Introduce blameless postmortems, where teams analyze incidents to prevent future ones, focusing on solutions rather than fault.


## Hands-on Activity

- Create a Monitoring Dashboard: Track resource usage with Grafana <!-- .element: class="fragment" data-fragment-index="2" -->
- Configure Auto-Scaling: Set up basic auto-scaling for a cloud instance <!-- .element: class="fragment" data-fragment-index="3" -->
- Simulate a Load Test: Use a tool like `hey` or `Apache Benchmark` to simulate high traffic <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Guide students to create a Grafana dashboard to monitor metrics such as CPU and memory usage, helping visualize cloud performance.
- Demonstrate basic auto-scaling setup, where students can see how resources adjust automatically with load.
- Perform a load test to show how cloud environments handle traffic spikes, discussing the impact on resources and scaling behaviors.


# Session 5: AI and Gaming in the Cloud


## AI in the Cloud

- Introduction to Cloud AI <!-- .element: class="fragment" data-fragment-index="2" -->
- Applications: AI use cases across industries <!-- .element: class="fragment" data-fragment-index="3" -->
- Hands-On: Simple AI project in Google Colab <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Introduce AI in the cloud and its scalable capabilities.
- Walk through a hands-on AI project using Google Colab to showcase cloud computing power.


## Cloud Gaming

- Cloud Gaming Basics: Streaming games to devices <!-- .element: class="fragment" data-fragment-index="2" -->
- Benefits: Accessibility and low latency <!-- .element: class="fragment" data-fragment-index="3" -->
- Exploring Platforms: NVIDIA GeForce NOW, Google Stadia <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Explain cloud gaming as a way to play games without powerful hardware.
- Demonstrate popular cloud gaming platforms and discuss accessibility benefits.


## Combining AI and Gaming

- AI in Games: Dynamic content and NPC behavior <!-- .element: class="fragment" data-fragment-index="2" -->
- Future Trends: AI and cloud integration <!-- .element: class="fragment" data-fragment-index="3" -->
- Hands-On: Explore AI-enhanced game mechanics <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Discuss AI’s role in making games more interactive and engaging.
- Explore hands-on experiences with AI-enhanced gaming to showcase future possibilities.


# Wrap-Up and Q&A


## Workshop Summary

- Key Takeaways: Recap main topics <!-- .element: class="fragment" data-fragment-index="2" -->
- Resources for Further Learning <!-- .element: class="fragment" data-fragment-index="3" -->
- Open Q&A: Address any questions <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Summarize the main points and learning outcomes.
- Provide additional resources for continued exploration of cloud topics.
- Open the floor for questions to close the workshop effectively.


# Retrospective


## Feedback and Next Steps

- Review Basic Commands and Concepts <!-- .element: class="fragment" data-fragment-index="2" -->
- Overview of Workshop Infrastructure <!-- .element: class="fragment" data-fragment-index="3" -->
- Recommendations for Future Learning <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:
- Recap core commands and infrastructure introduced.
- Ask for feedback to improve future sessions and suggest next learning steps.
