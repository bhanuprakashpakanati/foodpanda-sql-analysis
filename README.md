# 🍴 Foodpanda Data Analysis (SQL)

## 📌 Project Overview
This repository contains a comprehensive **SQL-based analysis** of Foodpanda’s customer and order dataset.  
The project was developed to transform raw transactional data into actionable insights, supporting **business growth, customer retention, and operational efficiency**.

The analysis was carried out using **Microsoft SQL Server Management Studio (SSMS)** and is aligned with the client’s documented requirements.

---

## 🎯 Business Objectives
The analysis addresses the following core objectives:

1. **Customer Analysis** – Understand demographics and customer value.  
2. **Sales & Revenue Analysis** – Track performance and identify revenue drivers.  
3. **Customer Retention (Churn Analysis)** – Detect churn patterns and risk factors.  
4. **Restaurant & Menu Performance** – Evaluate best-performing restaurants and dishes.  
5. **Operational Efficiency** – Assess delivery performance and customer satisfaction.

---

## 📊 Key Questions Answered
The SQL script provides answers to these business-critical questions:

### 3.1 Customer Demographics
- Breakdown by **Gender** and **Age group**  
- Top cities by active customers  
- Customer distribution across cities  

### 3.2 Sales & Revenue Performance
- Total revenue & monthly revenue trend  
- Average Order Value (AOV)  
- Top restaurants by revenue  
- Best-selling dishes & categories  
- Most popular payment methods  

### 3.3 Customer Behavior & Loyalty
- Top 10 customers by spending and loyalty points  
- Relationship between order frequency & spending  
- Signup date cohort analysis  

### 3.4 Churn Analysis
- Overall churn rate  
- Characteristics of churned customers (city, age, frequency, rating)  
- Differences in last order date between active vs churned customers  

### 3.5 Operational & Service Analysis
- Distribution of delivery status (delivered, delayed, cancelled)  
- Delivery status vs average ratings  
- Top and bottom restaurants by rating  
- Restaurants with unusually high cancellation/delay rates  

---

## 🛠️ Technical Setup
- **Tool:** Microsoft SQL Server Management Studio (SSMS)  
- **Language:** T-SQL  
- **Dataset:** [`Foodpanda.csv`](./Foodpanda.csv)  
- **Script:** [`SQL.sql`](./SQL.sql)  

### Steps to Reproduce:
1. Import `Foodpanda.csv` into SQL Server (`dbo.Foodpanda`).  
2. Run the queries in [`SQL.sql`](./SQL.sql) sequentially.  
3. Export results (top customers, revenue reports, etc.) as needed to Excel/CSV or BI tools.  

---

## 📂 Repository Structure
├── SQL.sql # All SQL queries answering client requirements
├── Foodpanda.csv # Raw dataset
├── Client Requirements Document.pdf# Business objectives & key questions
└── README.md # Project documentation
