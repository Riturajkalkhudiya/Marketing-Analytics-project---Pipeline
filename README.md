# End-to-End Marketing Analytics Project  
From BRD to SQL + Python + Power BI Dashboard

This project demonstrates a complete **end-to-end marketing analytics workflow**, starting from a **Business Requirements Document (BRD)** and ending with a **4-page interactive Power BI report**.

The focus of this project is to translate business goals into data pipelines, analytics, and actionable insights using **SQL, Python (NLTK), and Power BI**.

---

## 📌 Project Overview

Initially, only a BRD was provided outlining:
- Marketing goals
- Key performance metrics
- Expected insights

Based on this, I designed and implemented a full analytics solution that includes:
- ETL and data cleaning in SQL
- Sentiment analysis using Python (NLTK)
- Data modeling and visualization in Power BI

---

## 🛠️ Tech Stack

- **SQL Server** – ETL, data cleaning, transformations  
- **Python (pandas, NLTK)** – Sentiment analysis  
- **Jupyter Notebook** – Python workflow  
- **Power BI** – Data modeling, visualization, dashboards  
- **Excel** – Sentiment output integration  

---

## 🔁 End-to-End Workflow

### 1️⃣ SQL — ETL & Data Preparation
All SQL transformations and table creation logic are available in the `/sql_queries` folder, including:

- Data cleaning and standardization scripts  
- Fact and dimension table creation  
- Metric definitions aligned with BRD goals  
- Validation queries for row counts and integrity checks

---

### 2️⃣ Python — Sentiment Analysis
- Exported `fact_customer_reviews` from SQL Server to Jupyter Notebook
- Performed sentiment analysis using **NLTK**
- Classified reviews into sentiment categories
- Generated an output file:
- `customer_reviews_with_sentiment.xlsx`

---

### 3️⃣ Power BI — Analytics & Reporting
- Loaded cleaned SQL tables and sentiment output file
- Built a **4-page interactive Power BI report**:
  - Overview
  - Conversion Details
  - Social Media Details
  - Customer Review Details

---

## 📊 Power BI Report Screenshots

### 🔹 Overview Page
![Overview Report](images/overview.png)

### 🔹 Conversion Details Page
![Conversion Details](images/conversion_details.png)

### 🔹 Social Media Details Page
![Social Media Details](images/social_media_details.png)

### 🔹 Customer Review & Sentiment Page
![Customer Review Details](images/customer_review_details.png)

> 📌 *Note: Screenshots are stored in the `/images` folder.*

---

## 📈 Key Insights

- Conversion rates showed strong seasonal volatility
- Engagement declined during specific periods despite stable impressions
- Customer sentiment explained performance differences across products
- Certain products showed high traffic but negative sentiment
- Clear opportunities identified for campaign optimization and product improvements

---

## 🎯 Business Value Delivered

- Converted business requirements into a production-ready analytics system
- Enabled marketing teams to:
- Identify conversion drop-offs
- Understand customer sentiment drivers
- Optimize campaigns using data-backed insights
- Delivered a reusable and scalable analytics framework
