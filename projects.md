---
layout: default
title: "Projects"
permalink: /projects/
---

# Projects

Here are some of the projects I have worked on, showcasing my expertise in data engineering and analytics:

---

### **1. Real-Time Data Streaming: Kafka to AWS S3**
- **Objective:** The objective of the Real-Time Data Streaming of Informatica C360 Data to AWS S3 project is to build a robust and scalable pipeline using Apache Kafka to stream customer data from Informatica Customer 360 to AWS S3 in real time. This ensures low-latency data availability for downstream analytics, reporting, and machine learning workflows while maintaining data integrity and optimizing performance.  
- **Tech Stack:** Spark, Kafka, AWS S3, AWS Glue Catalogue, Bitbucket, AWS Parameter store  
- **Outcome:**
  1. Achieved low-latency streaming of customer data to AWS S3, enabling faster access for analytics and decision-making.
  2. Delivered a highly scalable solution that can handle fluctuating data volumes from Informatica C360.
  3. Ensured fault tolerance through Kafka's distributed architecture and AWS S3's durability.
  4. Enabled real-time transformation of raw data during the streaming process for compatibility with downstream systems.
  5. Leveraged Parquet format and partitioning in AWS S3 to reduce storage costs and improve data retrieval performance.
  6. Utilized cost-effective AWS S3 storage with scalable Kafka architecture, reducing the overall infrastructure cost compared to traditional ETL processes.
  7. Integrated monitoring tools (e.g., Kafka Monitoring and AWS CloudWatch) to provide end-to-end visibility into the streaming pipeline and proactively address issues.

---

### **2. Data Enrichment and Movement Framework: AWS S3 to Redshift using Apache Spark**
- **Objective:** The objective of the Data Enrichment and Movement Framework: AWS S3 to Redshift using Apache Spark is to build a scalable and efficient data pipeline for enriching raw data stored in AWS S3 with reference data, transforming it into valuable datasets, and loading it into Amazon Redshift for advanced analytics and reporting. The framework aims to ensure data quality, optimize performance, and support business intelligence use cases with enriched and accessible data.  
- **Tech Stack:** Spark, AWS S3, AWS Glue Catalogue, Redshift, Bitbucket, AWS Parameter store 
- **Outcome:**
  1.  Delivered enriched datasets by integrating and transforming raw data with reference data stored in AWS S3.
  2.  Utilized Apache Spark for distributed data processing, ensuring scalability for large datasets.
  3.  Stored enriched data back into AWS S3 using optimized formats like Parquet for better query performance and cost-effectiveness.
  4.  Automated the data loading process into Amazon Redshift, making the enriched datasets readily available for analytics and reporting teams.
  5.  Leveraged Redshift’s scalability to support complex queries and large-scale data analysis.

---

### **3. AWS Cloud Transformation: Mainframe Migration and Batch Processing Framework**
- **Objective:** The primary objective of the AWS Cloud Transformation: Mainframe Migration and Batch Processing Framework is to modernize the existing legacy mainframe system by migrating workloads to the AWS Cloud, leveraging cloud-native services to enhance scalability, efficiency, and cost-effectiveness. This includes building a robust batch processing framework for handling large-scale data files and enabling seamless integration with downstream systems while ensuring security, reliability, and operational excellence.  
- **Tech Stack:** Python, AWS Batch, AWS S3, AWS Parameter Store, AWS Secret Manager, PostgreSQL, Bitbucket, IDP (CICD tool internal),  Fortify SAST, SonarQube, PrismaTwistlog, ElasticSearch 
- **Outcome:**
  1. Transition from a legacy mainframe to a flexible, scalable, and cost-efficient AWS Cloud environment.
  2. Elimination of mainframe hardware dependencies, reducing maintenance costs and improving agility.
  3. Implementation of AWS Batch to handle large-scale file processing, enabling faster and more reliable data handling.
  4. Automated and standardized deployments using Docker containers and CI/CD pipelines, resulting in faster time-to-market for updates.
  5. Secure and efficient data storage in cloud-native databases (Amazon RDS - PostgreSQL engine) to facilitate downstream processes.
  6. Improved accessibility and performance for analytics and reporting systems.
  7. Integrated monitoring and logging using AWS CloudWatch, enabling real-time performance tracking and proactive issue resolution.
  8. Integrated with Elasticsearch to automatically create ticket based on business or system error code.
  9. Adherence to security best practices, ensuring data integrity and compliance.
  10. Pay-as-you-go cloud model reduces costs compared to fixed mainframe operational expenses.

---

### **4. Data Validation and Reconciliation Framework**
- **Objective:** The project aims to deliver two independent solutions for data validation and reconciliation between Hive tables and external data sources. One solution uses Spark with Scala for row-level comparisons between Hive tables and CSV files, while the other uses Python for summary-level validation by aggregating Hive data and comparing it with Excel reports. Both solutions ensure data accuracy and consistency while generating detailed discrepancy reports.
- **Tech Stack:** Spark, Hive, Python, Jenkins, bitbucket, Autosys
- **Outcome:**
  1. A robust framework for row-level validation between Hive tables and golden CSV files.
  2. Efficient handling of large-scale data with high precision in discrepancy detection.
  3. A flexible tool to compare summary metrics between Hive tables and Excel reports.
  4. Comprehensive reports for both solutions to assist in troubleshooting and data validation.
  5. Reports saved in Excel formats for stakeholder review.
 
### **5. Automated Data Enrichment and Notification Bot**
- **Objective:** The project involves designing and deploying a UiPath bot to automate the process of reading emails, downloading attached CSV files, enriching them with additional data from a web source, and saving the enriched file to a shared folder. The bot then sends an email notification to the customer, ensuring the entire workflow is automated, efficient, and error-free.
- **Tech Stack:** Uipath, Python, RestAPI, CSV
- **Outcome:**
  1. An end-to-end automation pipeline that reduces manual intervention and ensures timely processing of data.
  2. Elimination of human errors in repetitive tasks like email handling, file downloading, and data enrichment.
  3. Prototype was created using Python and Rest API which got repurposed as backup solution in case of Uipath service is down.
  4. Saved 800K dollars with enrich data which helped analyst to make better decision.  

### **6. Sybase IQ to Amazon Redshift Data Warehouse Migration**
- **Objective:** The migration of 2000+ tables from Sybase IQ to Redshift using AWS Glue with Python shell and Spark demonstrates a robust approach to modernizing data platforms.
- **Tech Stack:** AWS (Redshift, Glue jobs, Glue catalogue table, Parameter store, Secret Manager, Lambda, KMS, Data Sync, IAM, Cloudwatch, EventBridge), Python, Pyspark
- **Outcome:**
  1. Redshift’s columnar storage and optimized query execution can significantly improve query performance.
  2. Potential reduction in storage and operational costs compared to on-premise Sybase IQ systems.
  3. Standardized and enriched data during the ETL process for better analytics readiness.

[Go Back to Home](/)
