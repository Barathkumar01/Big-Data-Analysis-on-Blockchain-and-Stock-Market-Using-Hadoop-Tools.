# Big-Data-Analysis-on-Blockchain-and-Stock-Market-Using-Hadoop-Tools.

## Copyright (c) 2024 Barath Kumar Dhanasekar. All rights reserved.

**This project is for academic use only and cannot be used, copied, modified, or distributed without explicit permission from the author.**


This project leverages the Hadoop ecosystem to analyze and process blockchain and stock market data, focusing on transaction volumes, stock prices, and market trends. Using tools such as Apache Pig, Hive, and Apache Spark, over 10 GB of data was handled, and key insights were derived.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Data Processing Metrics](#data-processing-metrics)
- [Setup and Installation](#setup-and-installation)
- [How to Use](#how-to-use)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

This project demonstrates how big data tools like Hadoop, Pig, Hive, and Spark can be used to analyze large-scale blockchain and stock market data. The analysis identifies key insights such as transaction volumes, stock price fluctuations, and market trends. The project improves data processing capabilities by 20x times, enabling better decision-making and data-driven insights.

## Key Features

- **Data Ingestion**: 
  - Utilized Apache Flume for streaming data ingestion from stock market APIs.
  - Transferred blockchain data into HDFS using direct file transfers and Sqoop.
  
- **Data Analysis**: 
  - Used Apache Pig for initial data summarization and transformation.
  - Employed Hive for querying and deeper analysis of stock prices and blockchain data.
  
- **Insights Generation**: 
  - Identified key patterns in stock prices, transaction volumes, and market behaviors.
  - Used Spark for faster analysis and insights processing.
  
- **Documentation**: 
  - All steps were documented with code snippets, logs, and screenshots in Jupyter Notebooks for reproducibility.

## Technologies Used

- **Apache Hadoop**: For distributed data storage and processing.
- **Apache Pig**: For data transformation and analysis.
- **Apache Hive**: For managing and querying large datasets.
- **Apache Spark**: For fast processing and big data analytics.
- **Jupyter Notebooks**: For documenting the analysis steps and findings.
- **Python**: For scripting and data extraction.
- **Apache Flume**: For data streaming.
- **Sqoop**: For transferring data from MySQL to HDFS.

## Data Processing Metrics

- **Data Processed**: Over 10 GB of data analyzed.
- **Data Ingestion**: Time taken for data transfer into HDFS (via Flume, Sqoop, and file transfers).
- **Processing Efficiency**: Achieved 20x improvement in data processing time.
- **Query Performance**: Optimized HiveQL queries to reduce execution time.
- **Key Insights**: 
  - Transaction volume analysis for blockchain data.
  - Stock market trends and fluctuations.
- **Scalability**: The solution can be scaled to handle larger datasets.

## Setup and Installation

### Prerequisites
- Ensure that you have Hadoop and all necessary tools (Pig, Hive, Spark, Flume, Sqoop) installed on your system.

