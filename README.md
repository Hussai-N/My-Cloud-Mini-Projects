# My-Cloud-Mini-Projects

AWS-Based Cloud Projects

📌 Repository Overview

This repository contains multiple AWS-based cloud projects, demonstrating various use cases of Amazon S3, AWS Lambda, DynamoDB, and EC2 for hosting, automation, and data processing.

1️⃣ HOSTING & DEPLOYING A STATIC WEBPAGE IN AWS S3 (FREE OF COST)

🚀 Project Description

This project demonstrates how to host and deploy a static website in Amazon S3, utilizing AWS Free Tier.

✨ Key Features

Host HTML, CSS, JavaScript files in S3.

Configure Static Website Hosting.

Set up proper Bucket Policies to make the site publicly accessible.

Fully serverless deployment.

Cost-efficient (AWS Free Tier).

⚙️ Technologies Used

Amazon S3

AWS Management Console

HTML, CSS, JavaScript

📂 Folder Structure

📁 hosting-s3-static-webpage
├── 📄 index.html
├── 📄 style.css
├── 📄 script.js (if any)

2️⃣ AUTOMATED CSV DATA INGESTION FROM S3 TO DYNAMODB USING AWS LAMBDA

🚀 Project Overview

Automates ingestion of CSV data from an S3 bucket into an Amazon DynamoDB table using AWS Lambda.

✨ Key Features

Serverless and event-driven.

Real-time data ingestion from S3 to DynamoDB.

Scalable & cost-effective.

Supports custom CSV formats.

Secure IAM Role-based access.

⚙️ Technologies Used

Amazon S3 (Storage & Event Source)

AWS Lambda (Serverless Compute)

DynamoDB (NoSQL Database)

IAM Role (S3 & DynamoDB permissions)

Python (boto3)

CloudWatch (Logging)

📂 Folder Structure

📁 s3-csv-to-dynamodb
├── 📄 lambda_function.py  # Lambda logic
├── 📄 sample_data.csv      # Example CSV file
├── 📄 README.md

3️⃣ S3 EVENT-DRIVEN AUTOMATION USING AWS LAMBDA

🚀 Project Overview

Automatically triggers a Lambda function whenever a file is uploaded to an S3 bucket.

✨ Key Features

Fully automated & event-driven.

Real-time file processing.

Serverless & secure (IAM Role-based access).

Easily customizable.

📂 Example Use Cases

Real-time image resizing.

Metadata extraction.

Log processing.

Trigger notifications.

⚙️ Technologies Used

Amazon S3

AWS Lambda

IAM Role

Python

CloudWatch

📂 Folder Structure

📁 s3-event-driven-lambda
├── 📄 lambda_function.py  # Lambda logic
├── 📄 README.md

4️⃣ S3-BACKED FILE MANAGEMENT PROCESS ON EC2 USING IAM ROLE

🚀 Project Overview

This project demonstrates how an EC2 instance can securely manage files in an S3 bucket using an IAM role.

✨ Key Benefits

No hard-coded credentials.

Secure IAM Role-based access.

Simple automation with AWS CLI.

⚙️ Technologies Used

EC2 (Elastic Compute Cloud)

S3 (Simple Storage Service)

IAM Role

AWS CLI

📂 Example Commands

# Upload a file to S3
aws s3 cp /path/to/local/file.txt s3://your-bucket-name/

# Download a file from S3
aws s3 cp s3://your-bucket-name/file.txt /path/to/local/

# List files in the bucket
aws s3 ls s3://your-bucket-name/

📂 Folder Structure

📁 ec2-s3-file-management
├── 📄 setup-guide.md  # EC2 setup instructions

🚀 Getting Started

Clone this repository.

Navigate to the desired project folder.

Follow the README.md for each project to set it up.

🤝 Contributions

Feel free to submit pull requests or open issues for improvements.

🌟 Happy Cloud Computing! 🌟

