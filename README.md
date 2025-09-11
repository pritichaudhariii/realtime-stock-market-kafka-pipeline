# 📈 Stock Market Real-Time Data Engineering with Kafka


**📌 Introduction**

This project demonstrates an end-to-end real-time data engineering pipeline for stock market data using Apache Kafka and AWS services. The pipeline is designed to capture live stock data, process it in real time, and make it available for querying and analytics.

The solution integrates streaming, storage, cataloging, and querying layers to simulate a production-grade architecture.

fdggh
**🏗️ Architecture**

![Architecture](https://github.com/user-attachments/assets/d062636a-37cc-4153-ba61-6bb3677c964f)


The pipeline follows these high-level steps:

1. Stock market data is streamed in real-time using Apache Kafka.

2. Data is ingested and stored in Amazon S3.

3. AWS Glue Crawler organizes the data and updates the Glue Data Catalog.

4. Athena queries structured data directly from S3.

5. Processing and orchestration are handled on AWS EC2 with Python scripts.


**🛠️ Technologies Used**

 - Programming Language: Python

 - Cloud Platform: Amazon Web Services (AWS)

   - S3 (Simple Storage Service)

   - Glue Crawler

   - Glue Data Catalog
     
   - Athena

   - EC2

- Streaming Platform: Apache Kafka

     
**📊 Dataset**

Here is the dataset used: [dataset.csv](https://github.com/user-attachments/files/22228717/dataset.csv)
