# Clickstream Data Pipeline

This project implements a **cloud-based data pipeline** to capture, transform, and analyze **website clickstream data** using various AWS services. It was developed as part of the **CS524 Cloud Computing course** at Stevens Institute of Technology.

---

## 📚 Project Overview

AnyCompany Café wants to gather insights about customer behavior on its website.  
This pipeline simulates and analyzes clickstream data using AWS services to help the business make smarter decisions.

---

## 🏗️ Architecture Diagram

> **(Paste or upload your diagram image here.)**

---

## 🛠️ AWS Services Used

- **Amazon EC2**: Host a web server and generate clickstream logs.
- **Amazon CloudWatch**: Collect, monitor, and store logs.
- **AWS Lambda**: Transform clickstream logs into structured data.
- **Amazon Kinesis Data Streams**: Stream processed data.
- **Amazon S3**: Store raw and processed clickstream logs.
- **Amazon CloudWatch Logs Insights**: Query and visualize logs.
- **AWS Identity and Access Management (IAM)**: Manage permissions securely.

---

## 🚀 Pipeline Flow

1. Website activity is simulated using an Apache HTTP server running on EC2.
2. CloudWatch Agent collects the web server logs.
3. Lambda functions transform raw logs into structured events.
4. Kinesis streams the processed events.
5. S3 stores transformed logs for longer-term analysis.
6. CloudWatch Insights and Dashboards visualize user behavior and trends.

---

## 📈 Key Features

- **Real-time ingestion** of website clickstream data.
- **Log transformation** to JSON structured format.
- **Visitor behavior analysis** (menu visits, order submissions).
- **Geolocation-based dashboards** (top cities, top regions).
- **Cost-optimized** use of AWS Free Tier resources.

---

## 🧰 Project Structure

