# Etl-YouTube-data-analysis-project
## Overview
This project focuses on analyzing trending YouTube videos by processing structured and semi-structured data sourced from Kaggle. The data captures daily trending videos across multiple regions, including the USA, Great Britain, Germany, Canada, France, Russia, Mexico, South Korea, Japan, and India. By leveraging AWS cloud services, the project aims to securely manage, process, and analyze this data to uncover trends based on video categories and engagement metrics such as views, likes, and comments.

## Project Goals
+ Data Ingestion: Implement a mechanism to ingest data from multiple sources.
+ ETL System: Transform raw data into a structured format for efficient analysis.
+ Data Lake: Centralize data storage for easy access and scalability.
+ Scalability: Design the system to handle growing data volumes seamlessly.
+ Cloud Integration: Utilize AWS services for storage, processing, and analytics.
+ Reporting: Develop a dashboard to visualize trends and metrics effectively.

## Tools and Services
This project uses the following AWS services to achieve its goals:

+ Amazon S3: Scalable object storage for centralized data management.
+ AWS IAM: Secure access control for AWS services and resources.
+ Amazon QuickSight: Business intelligence tool for creating dashboards and reports.
+ AWS Glue: Serverless service for data integration and transformation.
+ AWS Lambda: Serverless compute service to execute code efficiently.
+ AWS Athena: Interactive query service for analyzing data directly from S3.
## About the Dataset
+ Context:
YouTube tracks the top trending videos daily, which are ranked based on user interactions like views, shares, comments, and likes, rather than total views over the year. These top videos include music videos, celebrity performances, and viral content.
+ Content:
The dataset includes daily records of trending YouTube videos from multiple regions:

+ Regions covered: USA, Great Britain, Germany, Canada, France, Russia, Mexico, South Korea, Japan, and India.
Key features: Video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count.
+ Category information: Each video is linked to a category_id found in an associated JSON file for each region.
+ Acknowledgements
The dataset was collected using the YouTube API.

+ Potential Use Cases:
Sentiment analysis of comments.
Categorization of videos based on their metadata and statistics.
Training machine learning models (e.g., RNNs) to generate YouTube comments.
Statistical analysis of factors influencing video popularity.
Dataset Source: Kaggle - YouTube Trending Data

## Dataset Access
The dataset used for this project is available here:

Kaggle Dataset Download Link: [Upload Link]

## Architecture Diagram
(Insert your architecture diagram here)

## Project Scripts
The scripts used in this project can be accessed below:

Data Ingestion Script: [Upload Link]
ETL Pipeline Script: [Upload Link]
Dashboard Configuration Script: [Upload Link]
