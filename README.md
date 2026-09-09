# 📊 Customer Shopping Behavior Data Analyst Project

## 📌 Project Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data loading and cleaning to SQL analysis and interactive dashboard development.

The project uses **Python, PostgreSQL/MySQL/SQL Server, and Power BI** to transform raw data into meaningful business insights.

### 🔄 Project Workflow

**Raw Dataset → Python → EDA → Data Cleaning → SQL Analysis → Power BI Dashboard → Business Report**

---

## 🛠️ Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **SQL**

  * PostgreSQL
  * MySQL
  * SQL Server
* **Power BI**

  * Data modeling
  * DAX
  * Interactive dashboards
* **Jupyter Notebook**
* **Git & GitHub**


## 🔍 Project Steps

### 1. Data Loading

The dataset is loaded into Python using **Pandas**.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
```

Initial checks are performed to understand:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Basic statistics

---

### 2. Exploratory Data Analysis (EDA)

EDA is performed to identify patterns, trends, relationships, and potential data-quality issues.

Key activities include:

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Correlation analysis
* Trend analysis
* Outlier detection
* Data visualization

Example:

```python
df.info()
df.describe()
df.isnull().sum()
df.duplicated().sum()
```

---

### 3. Data Cleaning

The raw dataset is cleaned and prepared for analysis.

Main cleaning activities include:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column names
* Handling inconsistent values
* Detecting and treating outliers
* Creating calculated/derived columns

The cleaned dataset is then prepared for SQL analysis and Power BI.

---

### 4. SQL Analysis

The cleaned data is loaded into a relational database and analyzed using SQL.

SQL analysis includes:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* Aggregate functions
* `CASE WHEN`
* Joins
* Subqueries
* Common Table Expressions (CTEs)
* Window functions

Example:

```sql
SELECT
    category,
    SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
```

SQL queries are available in the `/sql` folder.

---

### 5. Power BI Dashboard

An interactive **Power BI dashboard** is created to present key findings in an easy-to-understand format.

The dashboard includes:

* KPI cards
* Charts and graphs
* Filters and slicers
* Trend analysis
* Category/segment analysis
* Interactive visualizations

The Power BI file is available in:

```text
powerbi/dashboard.pbix
```

---

### 6. Business Report

A final report summarizes the analysis and highlights the most important findings.

The report covers:

* Project objective
* Dataset overview
* Data cleaning process
* Key analysis
* Important insights
* Business findings
* Recommendations
* Dashboard summary

The report is available in:

```text
reports/analysis_report.pdf
```

---

## 📈 Key Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* SQL Querying
* Relational Databases
* Data Modeling
* DAX
* Power BI Dashboard Development
* Business Intelligence
* Insight Generation
* Business Reporting

---

## 📊 Project Outcome

The project converts raw data into **actionable business insights** through a complete analytics pipeline.

It demonstrates the ability to:

> **Collect → Clean → Analyze → Query → Visualize → Report → Recommend**

---

## ⭐ If You Find This Project Useful

If this project helped you understand an end-to-end data analytics workflow, consider giving the repository a ⭐.

