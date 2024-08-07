# Real-Time Customer Feedback Processing and Analytics Pipeline

## Overview

This project implements a real-time data processing pipeline to analyze customer feedback using various AWS services. The architecture is designed to ingest, process, and visualize customer feedback in real time, providing actionable insights to improve decision-making and strategy development.

## Architecture

![Architecture Diagram](Real_Time_Streaming_Architecture.pdf)

The architecture includes the following components:

- **Data Source:** SurveyMonkey Data API
- **Data Ingestion:** Python SDK Kafka Producer, Amazon MSK (Kafka)
- **Data Processing:** AWS Lambda, AWS EMR (PySpark Env)
- **Data Storage:** AWS S3, Amazon Redshift
- **Data Analytics:** AWS Kinesis, AWS Athena
- **Data Visualization:** Tableau
- **Monitoring and Logging:** Amazon CloudWatch
- **Security and Management:** AWS IAM, AWS VPC, Amazon CloudFormation

## Features

- **Real-Time Data Ingestion:** Stream customer feedback from SurveyMonkey using Kafka and process it with AWS Lambda.
- **Batch and Stream Processing:** Use PySpark on AWS EMR for batch processing and AWS Kinesis for real-time analytics.
- **Data Warehousing and Analytics:** Store processed data in Amazon Redshift and perform ad-hoc queries with AWS Athena.
- **Visualization:** Visualize insights and analytics with Tableau for better understanding and decision-making.
- **Scalability and Security:** Utilize AWS services for scalable, secure, and efficient data processing.

## Prerequisites

To run this project, you'll need:

- AWS Account
- SurveyMonkey API access
- AWS CLI installed and configured
- Python environment for the Kafka producer    
