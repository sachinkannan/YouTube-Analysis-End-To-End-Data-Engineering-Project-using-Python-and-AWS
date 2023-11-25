# YouTube-Data-Analysis-End-To-End-Data-Engineering-Project-using-Python-and-AWS

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
1. ETL System — We are getting data in raw format, transforming this data into the proper format
1. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
1. Scalability — As the size of our data increases, we need to make sure our system scales with it
1. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
1. Reporting — Build a dashboard to get answers to the question we asked earlier

## Architecture
![](https://github.com/sachinkannan/YouTube-Analysis-End-To-End-Data-Engineering-Project-using-Python-and-AWS/blob/main/architecture_youtube.png)

## Objective
* Data Ingestion: Develop a robust mechanism for seamlessly ingesting data from diverse sources.
* ETL System: Transform raw data into the required format for analysis and storage.
* Data Lake: Establish a centralized repository to efficiently store data obtained from multiple sources.
* Scalability: Ensure that our system can dynamically scale to handle growing data volumes effectively.
* Cloud Integration: Utilize AWS to process and manage vast datasets that exceed local computing capabilities.
* Data Sources Employed

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Services used
* Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
* AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
* QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
* AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
* AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
* AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
