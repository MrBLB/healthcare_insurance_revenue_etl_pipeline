Healthcare Insurance Revenue ETL Pipeline Project

Project Overview
A Health Care insurance company is facing challenges in enhancing its revenue and understanding the customers so it wants to take help from Big Data Ecosystem to analyse it's competitors company data received from varieties of sources, namely through scrapping and third-party sources. This analysis will help them to track the behaviour, condition of customers so that they can customise offers for them to buy insurance policies and also calculate royalties to those customers who buy policies in the past, this in turn will enhance their revenues.

The primary goal of this project is to leverage big data technologies like PySpark, Databricks, AWS S3, AWS Redshift and AWS EMR Studio to store, ingest, process and analyze large volumes of data from multiple sources. The insights gained will help the company stay competitive in the market by identifying trends, improving customer engagement, and offering targeted insurance products.

Data source:
Raw files in CSV and JSON format collected by web scraping tool, third party data providers and existing internal data repositories (e.g., customer databases, insurance claim systems).

Architecture
The architecture consists of:
1. Data Ingestion: The data pipeline performs data ingestion from various sources, including web scraping tools, third-party data providers, and existing internal data repositories (e.g., customer databases, insurance claim systems).
2. Data Processing: The data pipeline processes large volumes of data in distributed system using PySpark and Databricks to clean, transform, and format the data for analysis and uses AWS EMR and Databricks for scalability and efficient handling of Big Data workloads.
3. Data Storage: Raw data is stored in AWS S3 and the processed data is stored in S3 for long-term storage and in Amazon Redshift for structured querying and analysis.

Technologies Used:
PySpark: Distributed framework for data processing and transformation.
Databricks: Service for data processing and transformation providing scalability.
AWS S3: Data lake storing raw and processed data for long term storage
AWS Redshift: Data warehouse for storing processed data for structured querying and analysis.
AWS EMR: AWS Compute Cluster for big data analytics hosting the ETL Pipeline

Contact
Author: Bikash Lama Bamjan
Email: bikash.bamjan99@gmail.com
