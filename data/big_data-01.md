# Welcome Back!
Today agenda:
- Review of past day
- "Ask me anything" Session
- Quick look into data storage and processing
- Visualizing data with Python
- Hands-on exercises


# "Ask me anything" Session
  - How did I manage fulltime job
  - How did I get freelancer
  - How is the environment in each area
  - Continue with ChatGPT suggestions
- Bag of words



# Data Storage and Processing
- Why big data needs special solutions

Speaker Notes:

- Discuss challenges in storing and processing large volumes of data.
- Introduce concepts like distributed systems and cloud storage.


# Overview of Data Storage
## Where and How We Keep Our Data Safe

Speaker Notes:

- Explain that data storage is the recording (storing) of information in a storage medium.
- Discuss different storage mediums like hard drives, SSDs, cloud storage, and distributed systems.
- Briefly mention the importance of choosing the right storage based on factors like speed, cost, scalability, and durability.


# Types of Data Storage
Which do you know?


# Local Storage (e.g., Hard Drives, SSDs)

Speaker Notes:

- Local Storage: Directly attached to the computer or server. Good for quick access but limited by physical capacity.


# Network Storage (e.g., NAS, SAN)

Speaker Notes:

- Network Storage: Storage devices connected over a network offering shared storage to multiple users or systems.


# Cloud Storage (e.g., AWS S3, Google Cloud Storage)

Speaker Notes:

- Cloud Storage: Off-site storage that provides scalability and remote access, managed by third-party providers.


# Distributed Systems (e.g., HDFS)

Speaker Notes:

- Distributed Systems: Storing data across multiple machines to improve fault tolerance and data access speed.



# Introduction to Data Processing
## Making Sense of Our Data

Speaker Notes:

- Define data processing as the collection and manipulation of items of data to produce meaningful information.
- Discuss different processing types like batch, real-time, stream processing, and explain why choosing the right type matters depending on the data application.


# Data Processing Technologies
- Batch Processing (e.g., Hadoop MapReduce)
- Real-time Processing (e.g., Apache Storm, Apache Flink)
- Stream Processing (e.g., Kafka Streams)

Speaker Notes:

- Batch Processing: Suitable for processing large volumes of data when time isn't a critical factor.
- Real-time Processing: Necessary when data needs to be processed quickly to produce immediate results.
- Stream Processing: Designed for data that continuously flows, allowing for incremental responses.


# Challenges in Data Storage and Processing
- Scalability
- Security
- Data Integrity
- Accessibility

Speaker Notes:

- Scalability: Handling growing data without performance loss.
- Security: Protecting data from unauthorized access and breaches.
- Data Integrity: Ensuring accuracy and consistency of data over its lifecycle.
- Accessibility: Making data available to users and systems as needed.



# Understanding Big Data Storage
## Comparing Storage Solutions: Home Library vs City Library
- Home: Small, limited space
- City: Large, organized for scale

Speaker Notes:

- Compare personal data management to handling big data at an organizational level.


# Home vs. City Library
- **Home Library:**
  - Small, limited space
  - Personal use, limited access
- **City Library:**
  - Large, organized for scale
  - Public access, extensive catalog

Speaker Notes:

- Home Library: local storage on a personal computer or a small server—suitable for less data and limited users.
- City Library: distributed systems like Hadoop's HDFS, which handle large, scalable amounts of data across multiple locations and for numerous users.


# Exploring Data Storage #1
## Practical Exercises with excel

Speaker Notes:

- Discuss the importance of understanding data storage systems like relational databases and NoSQL databases.
- Outline a basic exercise, such as setting up a small database and performing simple queries to demonstrate how data is stored and accessed.


**Exercise**: Setup an excel/google sheet with multiple row and columns. Add another view/sheet with a summary of the data.


# Big Data in Action
## Impacting Industries Worldwide

Speaker Notes:

- Introduce how big data is transforming various sectors by providing insights that were previously unattainable.


# Industries Benefiting from Big Data
Which do you know?


- **Healthcare:**
  - Predictive analytics for patient care
  - Personalized medicine based on patient data
- **Transportation:**
  - Optimization of logistics and routing
  - Real-time traffic condition analysis
- **Marketing:**
  - Consumer behavior analysis
  - Targeted advertising and customer segmentation

Speaker Notes:

- Healthcare: Discuss how big data helps in predicting diseases, customizing patient treatment plans, and managing healthcare resources more effectively.
- Transportation: Explain the use of big data in optimizing routes, reducing costs, and enhancing safety through predictive maintenance.
- Marketing: Talk about how big data allows for more precise marketing strategies, understanding customer preferences, and improving customer engagement through personalized experiences.



# Exploring Data Storage #2 (MySQL - hardcore)

Speaker Notes:

- Guide participants through basic data storage exercises using a simple database system.
- Encourage experimenting with different storage methods.


# Key Features of MySQL
- **Open Source**
- **High Performance**
- **Scalable**
- **Robust Security Features**

Speaker Notes:

- Open Source:  means it's free to use and has a large community for support.
- High Performance: performance optimizations for handling large databases efficiently.
- Scalable: Mention capabilities to handle large amounts of data and its suitability for both small and large applications.
- Robust Security Features: Outline MySQL's security features including encrypted data transmission and authentication.


# MySQL Architecture
## Understanding Its Components

Speaker Notes:

- Server: The core component that manages database services and connections.
- Storage Engines: Highlight how MySQL allows you to choose different storage engines like InnoDB, MyISAM, based on the need for transaction safety or read speed.
- SQL Interface: Discuss how users interact with MySQL through SQL commands.
- Client Programs: Mention the various client programs provided by MySQL for database management.


# Practical Exercise: Basic SQL Queries
## Let’s Interact with MySQL
- CREATE DATABASE example; to create a new database.
- USE example; to switch to the database.
- CREATE TABLE users (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255), email VARCHAR(255)); to create a new table.
- INSERT INTO users (name, email) VALUES ('Alice', 'alice@example.com'); to add a new entry.
- SELECT * FROM users; to retrieve and view the data.

Speaker Notes:

- Set up a simple database environment (if live demo, provide a brief setup; if not, describe what should be pre-installed).
- Walk through some basic SQL commands:


# Why Choose MySQL?
## Benefits Over Other Databases

Speaker Notes:

- Summarize why MySQL might be preferred over other databases:
-   Cost-Effective: No licensing fees, reducing the cost of database management.
-   Widely Used and Tested: Popular in the industry, ensuring compatibility and interoperability with many software and systems.
-   Extensive Documentation and Community Support: Rich resources and a large community help in troubleshooting and optimizing MySQL usage.


Exercise: Run some [mysql queryies](https://onecompiler.com/mysql)



# Key Features of Local Storage and Cookies
- **Local Storage:**
  - Stores data with no expiration date
  - Data does not get transferred with every server request
- **Cookies:**
  - Data gets transferred with every server request
  - Limited to 4KB size
  - Can set expiration dates

Speaker Notes:

- Discuss the differences in capacity and persistence between local storage and cookies.
- Mention security considerations such as susceptibility to XSS attacks in local storage and security flags in cookies.


# Introduction to Browser Local Storage and Cookies
## Temporary and Persistent Client-Side Storage

Speaker Notes:

- Explain the concept of client-side storage which includes both browser local storage and cookies.
- Local storage provides a way to store data persistently on the client's browser, whereas cookies are primarily used for session management, personalization, and tracking user behavior.



# Introduction to PostgreSQL
## Advanced Open-Source Relational Database

Speaker Notes:

- Introduce PostgreSQL as a powerful, open-source object-relational database system.
- Emphasize its advanced features, reliability, and strong community support which make it a favorite among developers.


# Key Features of PostgreSQL
- **ACID Compliant**
- **Extensive Indexing Options**
- **Support for Advanced SQL Queries**
- **High Customizability**

Speaker Notes:

- Detail key features such as ACID compliance for reliable transactions, various indexing techniques for performance optimization, and its capability to handle complex SQL queries.
- Mention the support for custom data types and extensible system functions.



# Introduction to CouchDB
## Scalable NoSQL Database

Speaker Notes:

- Explain that CouchDB is an open-source NoSQL document database.
- Focus on its primary feature of storing data in JSON documents, which makes it highly flexible and scalable.


# Key Features of CouchDB
- **JSON-based Document Format**
- **RESTful HTTP API**
- **Built-in Conflict Resolution**
- **Offline First Design**

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
- _id, _rev, race conditions, conflicts, etc.



# Introduction to Big Data Best Practices
## Essential Tips for Handling Big Data

What do you know?

Speaker Notes:

- Backups, VPN's, and data encryption.


# Regular Data Backups
- **Why Backup?**
  - Protect against data loss
  - Ensure data recovery

Speaker Notes:

- Importance of regular backups
- Use automated tools for scheduled backups


# Using VPNs for Secure Data Transfers
- **Enhance Security**
  - Encrypt data in transit
  - Protect data from interceptions

Speaker Notes:

- Benefits of VPNs in securing data transfers
- Recommend reliable VPN services


# Leveraging Cloud Storage
- **Advantages**
  - Scalability
  - Cost-effectiveness
  - Accessibility

Speaker Notes:

- Explain cloud storage benefits
- Suggest popular cloud storage providers like AWS, Google Cloud, and Azure


# Data Privacy and Protection Laws
- **Compliance is Key**
  - GDPR
  - HIPAA (for healthcare data)
  - Other relevant regulations

Speaker Notes:

- Importance of understanding and complying with data protection laws
- Mention key legislations like GDPR and HIPAA where applicable

