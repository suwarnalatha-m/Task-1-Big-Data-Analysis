# BIG DATA ANALYSIS USING PYSPARK

## 📌 Project Overview
This project demonstrates **Big Data Analysis** using PySpark on a retail transaction dataset.  
The objective is to perform scalable data processing, extract business insights, and demonstrate distributed computation compared with traditional data processing tools.


## 🎯 Objective
- Perform analysis on a large dataset using **PySpark**
- Apply data cleaning and transformation techniques
- Generate business insights from transactional data
- Demonstrate **scalability** using distributed processing
- Compare performance between **Pandas** and **PySpark**


## 🗂 Dataset Information
**Dataset Name:** Online Retail Dataset  
**Source:** UCI Machine Learning Repository  
**Format:** Excel (.xlsx) converted to CSV  
**Records:** ~500,000 transactions  

The dataset contains online retail transactions including product details, quantity, price, and customer country.


## 🛠 Tools & Technologies Used
- Python
- PySpark
- Pandas
- Google Colab
- Matplotlib & Plotly
- GitHub



## ⚙️ Project Workflow

### Step 1: Environment Setup
- Installed PySpark
- Created Spark Session for distributed computation

### Step 2: Data Loading
- Converted Excel dataset into CSV format
- Loaded dataset using PySpark DataFrame

### Step 3: Data Cleaning
- Removed missing values
- Removed duplicate records
- Verified schema and dataset size

### Step 4: Feature Engineering
- Created new column:
  
  **Revenue = Quantity × UnitPrice**

### Step 5: Data Analysis
Performed multiple analytical operations:
- Top selling products
- Country-wise revenue contribution
- Monthly revenue trends
- Transaction exploration by country

### Step 6: Data Visualization
Generated visual insights using:
- Bar charts
- Interactive Plotly graphs
- Revenue trend analysis

### Step 7: Scalability Demonstration
- Distributed data using Spark partitions
- Compared execution time between:
  - Pandas (single-machine processing)
  - PySpark (distributed processing)


## 📊 Key Insights
- Certain products contributed significantly to total sales volume.
- European countries generated the highest revenue contribution.
- Revenue trends showed seasonal variation across months.
- Distributed processing enables scalable analytics for large datasets.


## ⚡ Scalability Result
PySpark distributed the dataset across multiple partitions enabling parallel computation.

Although Pandas executed faster for this dataset due to smaller size, PySpark becomes significantly more efficient when handling large-scale datasets exceeding memory limits.

## ✅ Conclusion
This project demonstrates how PySpark enables scalable big data analytics through distributed computation. The workflow highlights real-world data engineering practices including cleaning, transformation, visualization, and performance comparison.



