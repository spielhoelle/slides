# Big Data & storage


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
- SQL <!-- .element: class="fragment" data-fragment-index="2" -->
- Database terms <!-- .element: class="fragment" data-fragment-index="3" -->
- Mysql, PostgreSQL, CouchDB <!-- .element: class="fragment" data-fragment-index="4" -->
- Vector space <!-- .element: class="fragment" data-fragment-index="5" -->
- Cloud storage <!-- .element: class="fragment" data-fragment-index="6" -->
- Databases <!-- .element: class="fragment" data-fragment-index="7" -->
- Backups <!-- .element: class="fragment" data-fragment-index="8" -->


# Demystifying tabular data
- Comma seperated values <!-- .element: class="fragment" data-fragment-index="2" -->
- Most simple format <!-- .element: class="fragment" data-fragment-index="3" -->
- Portable <!-- .element: class="fragment" data-fragment-index="4" -->


# Exercise
- Create a simple file, change the filetype to `.csv` and then add CSV syntax
- Test that with excel, numbers or open office


# Data Modeling
- Entity-Relationship (ER) diagrams for data structures
- Foreign keys
- n-to-n/1-to-n relationships
- Optional fields, defaults, not null


# A carcompany and a ecommerce site
- Lets have a look at my example


# Normalization
- Normal forms (1NF, 2NF, 3NF)
- Applying normalization to tables
- Benefits of normalization for data integrity


# Data basics
- IAM Identity access management<!-- .element: class="fragment" data-fragment-index="2" -->
- RBAC Role base access mangement<!-- .element: class="fragment" data-fragment-index="3" -->
- SQL Structured query language <!-- .element: class="fragment" data-fragment-index="4" -->
- Schemas <!-- .element: class="fragment" data-fragment-index="5" -->
- Indexes <!-- .element: class="fragment" data-fragment-index="6" -->
- Sharding <!-- .element: class="fragment" data-fragment-index="7" -->
- Replication <!-- .element: class="fragment" data-fragment-index="8" -->
- Backups <!-- .element: class="fragment" data-fragment-index="9" -->
- Integration and APIs <!-- .element: class="fragment" data-fragment-index="10" -->
- Datawarehousing <!-- .element: class="fragment" data-fragment-index="12" -->
- Data lakes <!-- .element: class="fragment" data-fragment-index="13" -->
- Migrations


# Basic SQL Queries
## Lets Interact with SQL
- `CREATE DATABASE example;` <!-- .element: class="fragment" data-fragment-index="2" -->
  - to create a new database. <!-- .element: class="fragment" data-fragment-index="3" -->
- `USE example;`  <!-- .element: class="fragment" data-fragment-index="4" -->
  - to switch to the database. <!-- .element: class="fragment" data-fragment-index="5" -->
- `CREATE TABLE users (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255), email VARCHAR(255));`  <!-- .element: class="fragment" data-fragment-index="6" -->
  - to create a new table. <!-- .element: class="fragment" data-fragment-index="7" -->
- `INSERT INTO users (name, email) VALUES ('Alice', 'alice@example.com');`  <!-- .element: class="fragment" data-fragment-index="8" -->
  - to add a new entry. <!-- .element: class="fragment" data-fragment-index="9" -->
- `SELECT * FROM users;`  <!-- .element: class="fragment" data-fragment-index="10" -->
  - to retrieve and view the data. <!-- .element: class="fragment" data-fragment-index="11" -->

Speaker Notes:

- Set up a simple database environment (if live demo, provide a brief setup; if not, describe what should be pre-installed).
- Walk through some basic SQL commands:


<!--# Exercise-->

<!--- Ask TommyBot about the addtional commands like UPDATE or DELETE-->
# Real world example
### Comparing Storage Solutions: Home Library vs City Library
- Home: Small, limited space <!-- .element: class="fragment" data-fragment-index="2" -->
- City: Large, organized for scale <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:

- Compare personal data management to handling big data at an organizational level.


# Home vs. City Library
- Home Library: <!-- .element: class="fragment" data-fragment-index="2" -->
  - Small, limited space <!-- .element: class="fragment" data-fragment-index="3" -->
  - Personal use, limited access <!-- .element: class="fragment" data-fragment-index="4" -->
- City Library: <!-- .element: class="fragment" data-fragment-index="5" -->
  - Large, organized for scale <!-- .element: class="fragment" data-fragment-index="6" -->
  - Public access, extensive catalog <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:

- Home Library: local storage on a personal computer or a small server—suitable for less data and limited users.
- City Library: distributed systems like Hadoop's HDFS, which handle large, scalable amounts of data across multiple locations and for numerous users.


# Exercise
- Setup an excel/google sheet and get used to "Dreisatz" operations
- Practice advanced calculations like we are now at the 3rd day on the course at hour 13.57, how much percent have we exactly done?


# Big Data in Action
## Impacting Industries Worldwide

Speaker Notes:

- Introduce how big data is transforming various sectors by providing insights that were previously unattainable.


# Industries Benefiting from Big Data
Which do you know?


- Healthcare: <!-- .element: class="fragment" data-fragment-index="2" -->
  - Predictive analytics for patient care <!-- .element: class="fragment" data-fragment-index="3" -->
  - Personalized medicine based on patient data <!-- .element: class="fragment" data-fragment-index="4" -->
- Transportation: <!-- .element: class="fragment" data-fragment-index="5" -->
  - Optimization of logistics and routing <!-- .element: class="fragment" data-fragment-index="6" -->
  - Real-time traffic condition analysis <!-- .element: class="fragment" data-fragment-index="7" -->
- Marketing: <!-- .element: class="fragment" data-fragment-index="8" -->
  - Consumer behavior analysis <!-- .element: class="fragment" data-fragment-index="9" -->
  - Targeted advertising and customer segmentation <!-- .element: class="fragment" data-fragment-index="10" -->

Speaker Notes:

- Healthcare: Discuss how big data helps in predicting diseases, customizing patient treatment plans, and managing healthcare resources more effectively.
- Transportation: Explain the use of big data in optimizing routes, reducing costs, and enhancing safety through predictive maintenance.
- Marketing: Talk about how big data allows for more precise marketing strategies, understanding customer preferences, and improving customer engagement through personalized experiences.


# Data Privacy and Protection Laws
- Compliance is Key <!-- .element: class="fragment" data-fragment-index="2" -->
  - GDPR <!-- .element: class="fragment" data-fragment-index="3" -->
  - HIPAA (for healthcare data) <!-- .element: class="fragment" data-fragment-index="4" -->
  - Other relevant regulations <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Importance of understanding and complying with data protection laws
- Mention key legislations like GDPR and HIPAA where applicable


# Data Governance
- Data governance policies
- Roles and responsibilities in data management systems
- Ensuring data quality and consistency environments


# API Integration
- What are API Gateways
- RESTful vs. GraphQL APIs in SAP environments
- API endpoints for managing data in SAP systems


# Data Privacy and Compliance
- Data protection regulations: GDPR, CCPA
- Compliance databases with privacy laws
- Electronic health card
- Data anonymization and access controls


# Data Integration using SAP Data Intelligence
- Capabilities of SAP Data Intelligence for integrating diverse data sources
- Building data pipelines and workflows for ML ingress
- Use cases for data integration big corporate environments


# Data Lifecycle Management
- Managing the data lifecycle within SAP HANA
- Data retention policies and archival strategies in SAP
- Tools for monitoring and maintaining data lifecycle in SAP solutions


# MySQL

- Open Source <!-- .element: class="fragment" data-fragment-index="2" -->
- High Performance <!-- .element: class="fragment" data-fragment-index="3" -->
- Scalable <!-- .element: class="fragment" data-fragment-index="4" -->
- Robust Security Features <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Open Source: means it's free to use and has a large community for support. <!-- .element: class="fragment" data-fragment-index="2" -->
- High Performance: performance optimizations for handling large databases efficiently. <!-- .element: class="fragment" data-fragment-index="3" -->
- Scalable: Mention capabilities to handle large amounts of data and its suitability for both small and large applications. <!-- .element: class="fragment" data-fragment-index="4" -->
- Robust Security Features: Outline MySQL's security features including encrypted data transmission and authentication. <!-- .element: class="fragment" data-fragment-index="5" -->


# MySQL Architecture
- Server <!-- .element: class="fragment" data-fragment-index="2" -->
- Storage Engines <!-- .element: class="fragment" data-fragment-index="3" -->
- SQL Interface <!-- .element: class="fragment" data-fragment-index="4" -->
- Client Programs <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Server: The core component that manages database services and connections. <!-- .element: class="fragment" data-fragment-index="2" -->
- Storage Engines: Highlight how MySQL allows you to choose different storage engines like InnoDB, MyISAM, based on the need for transaction safety or read speed. <!-- .element: class="fragment" data-fragment-index="3" -->
- SQL Interface: Discuss how users interact with MySQL through SQL commands.d. <!-- .element: class="fragment" data-fragment-index="4" -->
- Client Programs: Mention the various client programs provided by MySQL for database management. <!-- .element: class="fragment" data-fragment-index="5" -->


# Why Choose MySQL?
## Benefits Over Other Databases

Speaker Notes:

- Summarize why MySQL might be preferred over other databases:
-   Cost-Effective: No licensing fees, reducing the cost of database management.
-   Widely Used and Tested: Popular in the industry, ensuring compatibility and interoperability with many software and systems.
-   Extensive Documentation and Community Support: Rich resources and a large community help in troubleshooting and optimizing MySQL usage.


# Exercise
Run some [mysql queryies](https://onecompiler.com/mysql)


# Introduction to BI Tools
- ### Working with BI Tools (e.g., Power BI, Tableau)
  - Loading data from relational databases into BI tools  
  - Basic visualization techniques  


# SQL for Business Intelligence
- ### Foundations of SQL for Analytics
  - Common SQL functions for business use cases (e.g., SUM, AVG, COUNT)  
  - GROUP BY and HAVING clauses for aggregating data  
  - Join operations for combining datasets  


# Real-World Applications of Data Analytics
- ### Case Studies in Business Intelligence
  - Retail, finance, healthcare, and marketing examples.  


# PostgreSQL

## Advanced Open-Source Relational Database

Speaker Notes:

- Introduce PostgreSQL as a powerful, open-source object-relational database system.
- Emphasize its advanced features, reliability, and strong community support which make it a favorite among developers.


# Key Features of PostgreSQL
- ACID Compliant <!-- .element: class="fragment" data-fragment-index="2" -->
- Extensive Indexing Options <!-- .element: class="fragment" data-fragment-index="3" -->
- Support for Advanced SQL Queries <!-- .element: class="fragment" data-fragment-index="4" -->
- High Customizability <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Detail key features such as ACID compliance for reliable transactions, various indexing techniques for performance optimization, and its capability to handle complex SQL queries.
- Mention the support for custom data types and extensible system functions.


# PGAdmin

- Aggregates <!-- .element: class="fragment" data-fragment-index="2" -->
- Collations <!-- .element: class="fragment" data-fragment-index="3" -->
- Domains <!-- .element: class="fragment" data-fragment-index="4" -->
- FTS Configurations <!-- .element: class="fragment" data-fragment-index="5" -->
- FTS Dictionaries <!-- .element: class="fragment" data-fragment-index="6" -->
- FTS Parsers <!-- .element: class="fragment" data-fragment-index="7" -->
- FTS Template <!-- .element: class="fragment" data-fragment-index="8" -->
- Foreign Table <!-- .element: class="fragment" data-fragment-index="9" -->
- Functions <!-- .element: class="fragment" data-fragment-index="10" -->
- Materialized Views <!-- .element: class="fragment" data-fragment-index="11" -->
- 0perators <!-- .element: class="fragment" data-fragment-index="12" -->
- Procedures <!-- .element: class="fragment" data-fragment-index="13" -->
- Sequences <!-- .element: class="fragment" data-fragment-index="14" -->
- Tables <!-- .element: class="fragment" data-fragment-index="15" -->
- Trigger Functions <!-- .element: class="fragment" data-fragment-index="16" -->
- Types <!-- .element: class="fragment" data-fragment-index="17" -->
- Views <!-- .element: class="fragment" data-fragment-index="18" -->


# NoSQL
## Scalable NoSQL Database example CouchDB or MongoDB

Speaker Notes:

- Explain that CouchDB is an open-source NoSQL document database.
- Focus on its primary feature of storing data in JSON documents, which makes it highly flexible and scalable.


# Key Features of CouchDB
- JSON-based Document Format <!-- .element: class="fragment" data-fragment-index="2" -->
- RESTful HTTP API <!-- .element: class="fragment" data-fragment-index="3" -->
- Built-in Conflict Resolution <!-- .element: class="fragment" data-fragment-index="4" -->
- Offline First Design <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Highlight the use of JSON for document storage, which simplifies data interchange between server and clients.
- Discuss the RESTful HTTP API that allows all operations to be performed with HTTP requests.
- Explain its unique approach to handle data conflicts and its offline-first design which is ideal for applications that require reliable performance offline.


# Example
## Thow more trash on the landfill 🚮

```
curl -X POST \
  http://admin:password@localhost:5984/test \
  -H "Content-Type: application/json" \
  -d '{"_id":"mydoc","name":"My First Document","description":"This is my first document."}'
```
Respsone:
```json
{"ok":true,"id":"mydoc","rev":"1-bf0358641532f40c5193b259a0932fbf"}
```

Speaker Notes:
- `_id`, `_rev`, race conditions, conflicts, etc.


# Graph Databases

- Flexible Schema
- Graph Query Language
- High Performance
- Native Support for Relationships

Speaker Notes:

- Store and query complex relationships between data entities without a fixed schema <!-- .element: class="fragment" data-fragment-index="2" -->
- Use languages like Cypher or Gremlin to query and traverse graph structures <!-- .element: class="fragment" data-fragment-index="3" -->
- Optimize for fast query performance, even with large amounts of data <!-- .element: class="fragment" data-fragment-index="4" -->
- Store relationships between entities as first-class citizens, rather than relying on joins or foreign keys <!-- .element: class="fragment" data-fragment-index="5" -->


# Vectors

```
curl http://localhost:11434/api/embeddings -d '{
  "model": "mxbai-embed-large",
  "prompt": "Llamas are members of the camelid family"
}'
```


# Vector Databases

- Efficient Storage and Querying
- Approximate Nearest Neighbor (ANN) Search
- Support for Various Distance Metrics
- Scalability and Performance

Speaker Notes:

- Store and query dense and sparse vectors in high-dimensional spaces, optimized for similarity search and nearest neighbor queries <!-- .element: class="fragment" data-fragment-index="2" -->
- Use algorithms like KD-Trees or Ball Trees to quickly find approximate nearest neighbors in high-dimensional spaces <!-- .element: class="fragment" data-fragment-index="3" -->
- Support multiple distance metrics such as Euclidean, Cosine, and Manhattan distances for flexible similarity searches <!-- .element: class="fragment" data-fragment-index="4" -->
- Designed to handle large volumes of vector data and provide fast query performance, often using distributed architectures <!-- .element: class="fragment" data-fragment-index="5" -->


# Data Storage
- Why big data needs special solutions <!-- .element: class="fragment" data-fragment-index="2" -->

Speaker Notes:

- Discuss challenges in storing and processing large volumes of data.
- Introduce concepts like distributed systems and cloud storage.


# Overview of Data Storage
## Where and How We Keep Our Data Safe

Speaker Notes:

- Explain that data storage is the recording (storing) of information in a storage medium.
- Discuss different storage mediums like hard drives, SSDs, cloud storage, and distributed systems.
- Briefly mention the importance of choosing the right storage based on factors like speed, cost, scalability, and durability.


# Local Storage
- Pen & Paper <!-- .element: class="fragment" data-fragment-index="2" -->
- Hard Drives <!-- .element: class="fragment" data-fragment-index="3" -->
- SSDs <!-- .element: class="fragment" data-fragment-index="4" -->
- USB drives <!-- .element: class="fragment" data-fragment-index="5" -->
- DNA  <!-- .element: class="fragment" data-fragment-index="6" -->


# Network Storage

- Network Attached Storage (NAS) <!-- .element: class="fragment" data-fragment-index="2" -->
- Storage Area Network (SAN) <!-- .element: class="fragment" data-fragment-index="3" -->
- Direct-Attached Storage (DAS) <!-- .element: class="fragment" data-fragment-index="4" -->
- Router-attached Storage <!-- .element: class="fragment" data-fragment-index="5" -->
- Cloud Storage <!-- .element: class="fragment" data-fragment-index="6" -->
- Local Server Storage <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:

- Network Attached Storage (NAS): A dedicated file-level data storage device connected to a network. <!-- .element: class="fragment" data-fragment-index="2" -->
- Storage Area Network (SAN): A block-level data storage network that provides access to disk arrays and tape libraries. <!-- .element: class="fragment" data-fragment-index="3" -->
- Direct-Attached Storage (DAS): A hard drive or solid-state drive attached directly to a server or workstation over a local interface like SATA or USB. <!-- .element: class="fragment" data-fragment-index="4" -->
- Router-attached Storage: A hard drive or NAS device attached to a router, providing shared storage for devices on the network. <!-- .element: class="fragment" data-fragment-index="5" -->
- Cloud Storage: Remote storage provided by a third-party cloud provider, accessible over the internet. <!-- .element: class="fragment" data-fragment-index="6" -->
- Local Server Storage: Shared storage provided by a company's local servers, such as Windows File Servers or Linux-based file servers. <!-- .element: class="fragment" data-fragment-index="7" -->


# Cloud Storage
- Dropbox
- AWS S3
- Google Cloud Storage
- FTP/SFTP

Speaker Notes:

- Cloud Storage: Off-site storage that provides scalability and remote access, managed by third-party providers.


# Distributed Systems

- Distributed File Systems (DFS) <!-- .element: class="fragment" data-fragment-index="2" -->
- Object Storage <!-- .element: class="fragment" data-fragment-index="3" -->
- Distributed Key-Value Stores <!-- .element: class="fragment" data-fragment-index="4" -->
- NoSQL Databases <!-- .element: class="fragment" data-fragment-index="5" -->
- Data Grids <!-- .element: class="fragment" data-fragment-index="6" -->
- Cloud-based Distributed Storage <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:

- Distributed File Systems (DFS): Designed to store and manage large amounts of data across multiple machines, such as Hadoop Distributed File System (HDFS) or Google's Colossus.
- Object Storage: Stores data as objects, which can be distributed across multiple nodes, providing high scalability and availability, examples include Amazon S3 or OpenStack Swift.
- Distributed Key-Value Stores: Designed to store large amounts of key-value pairs across multiple machines, such as Riak or Apache Cassandra.
- NoSQL Databases: Built to handle large amounts of unstructured or semi-structured data, often using distributed architectures, examples include MongoDB or Couchbase.
- Data Grids: Provide a distributed infrastructure for storing and processing large amounts of data in memory, such as Hazelcast or Apache Ignite.
- Cloud-based Distributed Storage: Offers scalable storage solutions that can be easily integrated with cloud-based applications, examples include Amazon Elastic Block Store (EBS) or Microsoft Azure Blob Storage.


# Key Features of Local Storage and Cookies

- [Meme](https://tech.lgbt/@Natasha_Jay/112960501913519712)
- Local Storage: <!-- .element: class="fragment" data-fragment-index="2" -->
  - Stores data with no expiration date <!-- .element: class="fragment" data-fragment-index="3" -->
  - Data does not get transferred with every server request <!-- .element: class="fragment" data-fragment-index="4" -->
- Cookies: <!-- .element: class="fragment" data-fragment-index="5" -->
  - Data gets transferred with every server request <!-- .element: class="fragment" data-fragment-index="6" -->
  - Limited to 4KB size <!-- .element: class="fragment" data-fragment-index="7" -->
  - Can set expiration dates <!-- .element: class="fragment" data-fragment-index="8" -->
- Tip: Clear your cookies <!-- .element: class="fragment" data-fragment-index="9" -->

Speaker Notes:

- Discuss the differences in capacity and persistence between local storage and cookies.
- Mention security considerations such as susceptibility to XSS attacks in local storage and security flags in cookies.


# Exercise
- Delete your cookie from one specfic website


# Regular Data Backups
- Why Backup? <!-- .element: class="fragment" data-fragment-index="2" -->
  - Protect against data loss <!-- .element: class="fragment" data-fragment-index="3" -->
  - Ensure data recovery <!-- .element: class="fragment" data-fragment-index="4" -->
- Example: `Apple Timemachine`, `Windows backup`, `sigtop`, `rsync`

Speaker Notes:

- Importance of regular backups
- Use automated tools for scheduled backups


# Exercise

- Trigger a backup


# RAID

- Raid 1
- Raid 6


# Using VPNs for Secure Data Transfers
- Enhance Security <!-- .element: class="fragment" data-fragment-index="2" -->
  - Encrypt data in transit <!-- .element: class="fragment" data-fragment-index="3" -->
  - Protect data from interceptions <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:

- Benefits of VPNs in securing data transfers
- Recommend reliable VPN services


# Leveraging Cloud Storage
- Advantages <!-- .element: class="fragment" data-fragment-index="2" -->
  - Scalability <!-- .element: class="fragment" data-fragment-index="3" -->
  - Cost-effectiveness <!-- .element: class="fragment" data-fragment-index="4" -->
  - Accessibility <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Explain cloud storage benefits
- Suggest popular cloud storage providers like AWS, Google Cloud, and Azure


# ETL Processes
- Extract, Transform, Load (ETL) with SAP Data Services
- ETL tools in the SAP ecosystem: SAP Data Intelligence
- Best practices for data integration in SAP


# Indexing Strategies
- Importance of indexes for query performance in SAP HANA
- Types of indexes in SAP HANA: B-tree, Hash, Composite
- Creating and managing indexes on SAP tables


# Query Optimization
- Techniques for optimizing SQL queries in SAP HANA
- Analyzing query execution plans with SAP tools
- Optimizing joins and subqueries in SAP databases


# Security in Databases
- IAM and RBAC in SAP systems
- Data encryption at rest and in transit with SAP solutions
- Protecting against SQL injection and common vulnerabilities in SAP


# Data Visualization
- Tools for visualizing data with SAP Analytics Cloud
- Dashboards for monitoring key metrics using SAP tools
- Visual reports for various SAP data sources


# Big Data Technologies
- Hadoop ecosystem for large-scale data processing in SAP
- Apache Spark for real-time data analytics with SAP HANA
- Benefits of big data technologies for SAP transaction handling


# Cloud Database Services
- Cloud-based databases offered by SAP: SAP HANA Cloud
- Advantages of SAP cloud services: scalability and reliability
- Strategies for migrating SAP databases to the cloud


# Data Backup and Recovery
- Strategies for backing up SAP data regularly
- Automated backup solutions with SAP tools
- Recovery plans for business continuity in case of data loss


# Real-time Data Processing
- Real-time analytics with SAP HANA
- Real-time data streaming technologies in SAP: SAP Stream Processing
- Use cases of real-time data for enhancing business processes in SAP


# Machine Learning with Databases
- Leveraging SAP HANA data for machine learning models
- Examples: recommendation systems, sales forecasting with SAP tools
- Integrating machine learning workflows with SAP databases


# Scalability and Performance
- Scaling SAP databases horizontally and vertically
- Load balancing and database clustering in SAP environments
- Monitoring performance metrics and optimizing resources with SAP tools


# Transaction Management
- ACID properties with SAP transaction examples
- Handling concurrent transactions and avoiding deadlocks in SAP
- Transaction isolation levels within SAP databases


# Advanced SQL Features
- Stored procedures, triggers, and views in SAP HANA
- Window functions for complex queries in SAP
- Full-text search capabilities in SAP databases


# Migration and Version Control
- Migrating SAP databases between environments
- Version control systems for SAP database schema changes
- Tools for managing database migrations in SAP: SAP Transport Management


# Data Governance Policies
- Importance of data governance in SAP solutions
- Creating and enforcing data governance policies with SAP tools
- Maintaining data stewardship and accountability in SAP environments


# SAP HANA Architecture
- In-memory computing architecture of SAP HANA
- Components and layers of SAP HANA
- High-performance data processing supported by SAP HANA
