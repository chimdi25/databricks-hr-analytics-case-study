# HR Analytics Case Study (Databricks & PySpark)

This project is an HR analytics case study completed using **Databricks**, **PySpark**, and **Spark SQL**.  
The objective was to analyze employee demographics, salary patterns, tenure, and hiring trends using a large structured dataset.

---

## 📌 Project Overview

The analysis focuses on understanding workforce patterns, including:

- Salary distribution across regions
- Employee tenure and hiring trends over time
- Identification of top earners by gender
- Insights into potential regional pay differences and workforce composition

The project demonstrates the use of distributed data processing tools to generate meaningful business insights from large datasets.

---

## 🧰 Tools & Technologies

- Databricks
- Apache Spark (PySpark)
- Spark SQL
- Python
- DataFrame-based transformations
- Window functions for ranking and segmentation

---

## 📊 Analysis Performed

### 🔹 Data Ingestion & Preparation
- Loaded a CSV dataset from cloud storage into a Spark DataFrame
- Inspected schema and handled data types for time-based analysis

### 🔹 Hiring & Tenure Analysis
- Analyzed employee tenure (`Age in Company`) over time based on date of joining
- Identified hiring surges and workforce growth patterns

### 🔹 Salary Analysis by Region
- Computed average salary by geographic region
- Compared regional compensation levels

### 🔹 Top Earners & Gender Analysis
- Used Spark SQL window functions to identify top-paid employees by gender
- Explored potential pay distribution patterns and representation at higher salary levels

---

## 💡 Key Insights

- Certain regions exhibit higher average salaries, potentially reflecting cost-of-living or concentration of higher-paying roles
- Tenure trends highlight periods of increased hiring activity
- Salary ranking by gender reveals possible disparities or differences in seniority representation
