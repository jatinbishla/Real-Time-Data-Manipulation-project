# Stock Market Kafka Real Time Data Tracking

## Introduction 
In this project, I have developed a real-time data pipeline using Apache Kafka to simulate stock market data processing. 

Streamed data from a CSV dataset with a Python producer and stored it in Amazon S3 via a Kafka consumer on an EC2 instance. 

Leveraged AWS Glue to catalog the data for querying with Amazon Athena, enabling efficient real-time analytics.

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka
