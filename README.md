# 📊 E-Commerce Sales Dashboard (End-to-End Analytics Project)

## 🧠 Project Overview
This project demonstrates a complete **end-to-end data analytics workflow** using a real-world e-commerce dataset.

Starting from **raw transactional data**, the project walks through:
- Data cleaning
- Data transformation
- Exploratory data analysis (EDA)
- Interactive dashboard creation

The objective is to generate **actionable business insights** that support decision-making in a retail environment.

---

## 📌 Data Source
- [Dataset: UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)  
- Period: December 2010 – December 2011  
- Records: 541,000+ transactions 
This dataset contains transactional data from a UK-based online retail company that sells gift items. 

---

## 📂 Dataset Description

Each row represents a transaction with the following columns:

- **InvoiceNo** → Unique transaction ID (starting with "C" = cancelled) 
- **StockCode** → Product code  
- **Description** → Product name  
- **Quantity** → Number of items purchased  
- **InvoiceDate** → Transaction date and time  
- **UnitPrice** → Price per item  
- **CustomerID** → Unique customer identifier  
- **Country** → Customer location 

---

## 🎯 Project Objectives

- Analyze sales performance and trends over time  
- Identify top-performing products and categories  
- Understand customer purchasing behavior  
- Explore geographical sales distribution  
- Build a professional interactive dashboard  

---

## 🧹 Data Cleaning Process

Before building any dashboard, the raw dataset was cleaned and prepared:

- Removed cancelled transactions (InvoiceNo starting with "C")  
- Filtered negative quantities and invalid prices  
- Removed missing product descriptions  
- Handled missing CustomerID values  
- Removed duplicate records  
- Created a new **Total_Sales column (Quantity × UnitPrice)**  
- Extracted **Month and Year** from InvoiceDate  

---

## 🔄 Workflow

1. **Data Collection** → Raw dataset from UCI  
2. **Data Cleaning** → Python / Pandas (Jupyter Notebook)  
3. **Data Transformation** → Feature engineering  
4. **EDA (Exploratory Analysis)** → Trends, patterns, anomalies  
5. **Visualization** → Power BI dashboard  
6. **Business Insights** → Recommendations  

---

## 📊 Dashboard Features

- KPI Metrics (Total Sales, Orders, Quantity)
- Top 10 products by revenue
- Sales distribution (Top vs Others)
- Monthly sales trends
- Country-level analysis
- Interactive filters (Month/year)

---

## 📈 Key Business Insights (Expected)

- Majority of revenue comes from the United Kingdom  
- Sales peak during November (holiday season demand)  
- Revenue is driven by high-volume, low-price products  
- A small percentage of customers contributes significantly to sales  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## 📁 Project Structure
```
data/
└── raw/              # Original dataset
notebooks/              # Data cleaning & analysis
dashboard/              # Power BI file
reports/                # Insights and findings
```
---

## 🚀 Project Status

✅ Data ingestion complete  
✅ Data cleaning (in progress)  
⬜ Exploratory analysis  
⬜ Dashboard development  

---

## 📷 Preview
*(To be added after dashboard creation)*

---

## 👨‍💻 Author
**Asres Analytics**

---

## 💡 About This Project

This project is designed to showcase:
- Real-world data cleaning skills  
- Analytical thinking  
- Business insight generation  
- Dashboard design for stakeholders  

It is part of a professional portfolio aimed at freelance data analytics opportunities.