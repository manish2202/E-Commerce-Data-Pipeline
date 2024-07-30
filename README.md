# E-commerce Data Pipeline

## Overview
This project involves building an efficient and automated e-commerce data pipeline using Microsoft Azure and Databricks. The pipeline is designed based on the medallion architecture, which leverages the power of Delta Lake to structure data into Bronze, Silver, and Gold layers. This design pattern ensures data quality and accessibility for analytics and reporting.

## Features
- **Cloud Platform**: Utilized Microsoft Azure to deploy and manage the e-commerce data pipeline.
- **Medallion Architecture**: Implemented a layered data architecture:
  - **Bronze Layer**: Raw data ingestion
  - **Silver Layer**: Data cleansing and transformation
  - **Gold Layer**: Optimized data for analytics and reporting, utilizing the concept of One Big Table (OBT) for simplified access and analysis.
- **Delta Lake**: Enabled the medallion architecture to ensure ACID transactions and scalable metadata handling.
- **Automation**: Employed Microsoft Azure Triggers to automate the pipeline, initiating data processing whenever new data is added.
- **PySpark**: Used PySpark for data processing and transformation within Databricks.

## Technologies
- **Microsoft Azure**: Cloud platform for infrastructure and services
- **Databricks**: Unified data analytics platform
- **Delta Lake**: Storage layer that brings reliability to data lakes
- **PySpark**: Python API for Apache Spark, used for data processing

## Getting Started
To set up and run this project, follow these steps:
- Set up an Azure account and configure necessary services (Azure Databricks, Azure Storage, etc.).
- Clone this repository to your local machine.
- Follow the provided notebooks and scripts to deploy the pipeline in your Azure environment.
