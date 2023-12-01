# YouTube Data Engineering and Analysis Project

## Project Overview

This project is dedicated to efficiently managing, transforming, and analysing YouTube video data, focusing on structured and semi-structured information. The analysis is driven by video categories and key trending metrics.

## Project Objectives

1. **Data Ingestion:** Ingesting data from diverse sources.
2. **ETL System:** Transform raw data into a standardised and optimised format.
3. **Data Lake:** Establish a centralised data repository to accommodate diverse datasets.
4. **Scalability:** Ensure the system seamlessly scales with the growing volume of data.
5. **Cloud Integration:** Leverage AWS for efficient processing of large datasets.
6. **Reporting and Visualization:** Develop a dynamic dashboard to glean insights from the analysed data.

## AWS Services Utilised
- **Amazon S3:** Object storage service providing scalable, secure, and high-performance storage.
- **AWS IAM (Identity and Access Management):** Securely manage access to AWS services and resources.
- **Amazon QuickSight:** A scalable, serverless business intelligence service powered by machine learning.
- **AWS Glue:** Serverless data integration for streamlined data discovery, preparation, and combination.
- **AWS Lambda:** Compute service enabling code execution without the need for server management.
- **AWS Athena:** Interactive query service for S3, eliminating the need for data loading.

## Dataset Description
The project relies on a Kaggle dataset comprising daily statistics (in CSV files) on popular YouTube videos. The dataset includes essential information such as video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and a category_id field specific to each region.

## Dataset Source
[YouTube Trending Videos Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

