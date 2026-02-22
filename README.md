# Instacart Market Basket Analysis
### 🐍 Advanced Data Wrangling & Customer Profiling with Python

---

## 🎯 Business Context
Instacart is an online grocery store aiming to uncover deeper patterns in their sales data. This project involved a deep dive into over **32 million records** to segment users and identify key drivers of sales across different US regions and demographics.

## 🛠️ Technical Stack & Skills
* **Language:** Python 3.x
* **Key Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scipy`.
* **Methodology:** Professional Data Pipeline (Wrangling → Consistency → Profiling → Visualization).

## 📂 Data Analysis Workflow

### 1. Data Wrangling & Consistency Checks
* **PII Redaction:** Removed sensitive customer information (last names) to adhere to data privacy standards.
* **Consistency Audits:** Conducted rigorous checks for missing values, duplicates, and data type integrity.
* **Combining Data:** Merged multiple large-scale datasets (Orders, Products, Departments, Customers) into a unified analytical dataframe.

### 2. Feature Engineering & Derivation
Developed new business-centric variables to drive deeper insights:
* **Deriving Variables:** Created flags for loyalty (New/Regular/Loyal), spending (High/Low spender), and order frequency.
* **Grouping & Aggregating:** Performed complex aggregations (mean, min, max) to compare spending habits across different customer profiles.
* **Geographic Profiling:** Grouped states into 4 major US Regions to analyze regional market performance.

### 3. Performance Optimization
* **Large Scale Handling:** Processed datasets exceeding **32,434,212 rows**.
* **Sampling Strategy:** Implemented a **70/30 data split** to execute complex visualizations while managing system memory constraints.

## 🚀 Strategic Insights & Visualization
* **Segmented Analysis:** Correlated age, income, and family status with purchasing behavior.
* **Department Performance:** Identified the most popular product categories by region and time of day.
* **Strategic Reporting:** Translated technical findings into a final Excel report for executive stakeholders.

---

*Note: This project was developed as part of a professional Data Analytics certification by CareerFoundry.
