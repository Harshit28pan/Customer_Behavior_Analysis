# Customer_Behavior_Analysis
Data Analytics Project showcasing Customer Behavior Analysis using Python , SQL , PowerBI.

## 📌 Overview

This project focuses on analyzing customer behavior data using Python, SQL, and Power BI to extract meaningful insights and support data-driven decision-making.

The workflow includes loading the dataset, performing exploratory data analysis (EDA), cleaning the data, running SQL queries on a PostgreSQL database, building an interactive Power BI dashboard, generating an analytical report, and creating a presentation using Gamma.

This project demonstrates practical skills in **data analytics, SQL querying, visualization, and reporting**, making it suitable for real-world business analysis scenarios.

---

## 📂 Dataset

* **Dataset Name:** Customer Behavior Dataset
* **Source:** Public dataset / Kaggle / Internal dataset (update accordingly)
* **Format:** CSV
* **Key Features Include:**

  * Customer ID
  * Age
  * Gender
  * Purchase Amount
  * Product Category
  * Review Rating
  * Purchase Frequency
  * Location

The dataset was used to analyze customer purchasing trends, product performance, and user behavior patterns.

---

## 🛠 Tools & Technologies Used

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

* **Database**

  * PostgreSQL
  * SQL (for querying and data analysis)

* **Visualization**

  * Power BI

* **Reporting**

  * Microsoft Word / PDF (Analytical Report)
  * Gamma (Presentation Creation)

* **Environment**

  * Jupyter Notebook / JupyterLab
  * pgAdmin (PostgreSQL management)

---

## 🔄 Project Steps

### 1️⃣ Data Loading

* Imported dataset into Python using Pandas.
* Loaded cleaned data into PostgreSQL database using SQLAlchemy.

### 2️⃣ Exploratory Data Analysis (EDA)

* Checked dataset structure and summary statistics.
* Identified missing values and duplicates.
* Visualized trends using charts and graphs.
* Analyzed customer demographics and purchasing behavior.

### 3️⃣ Data Cleaning

* Handled missing values.
* Removed duplicates.
* Converted data types where required.
* Standardized column names and formats.

### 4️⃣ SQL Analysis (PostgreSQL)

* Created tables in PostgreSQL.
* Executed SQL queries to:

  * Identify top-performing products.
  * Calculate average ratings.
  * Analyze customer segments.
  * Detect high-value customers.

### 5️⃣ Dashboard Development (Power BI)

* Connected Power BI to PostgreSQL / CSV dataset.
* Created interactive dashboards including:

  * Sales overview
  * Product performance
  * Customer segmentation
  * Rating analysis

### 6️⃣ Report Generation

* Summarized findings in a structured analytical report.
* Included visual insights and business recommendations.

### 7️⃣ Presentation Creation

* Designed presentation slides using Gamma.
* Highlighted key insights and dashboard visuals.

---

## 📊 Dashboard Features

The Power BI dashboard includes:

* 📈 Sales Trend Analysis
* 🛒 Product Category Performance
* ⭐ Customer Rating Insights
* 👥 Customer Demographics
* 📍 Regional Purchase Distribution

Interactive filters allow users to explore data dynamically.

---

## 📈 Key Results & Insights

* Identified top-performing product categories.
* Discovered customer segments with highest purchase frequency.
* Found correlation between ratings and purchase trends.
* Highlighted regions with strong customer engagement.
* Provided actionable recommendations to improve product performance and customer satisfaction.

---

## ▶️ How to Run the Project

### Step 1 — Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

---

### Step 2 — Load Dataset in Python

```python
import pandas as pd

df = pd.read_csv("customer_data.csv")
df.head()
```

---

### Step 3 — Connect to PostgreSQL

```python
from sqlalchemy import create_engine

engine = create_engine(
"postgresql+psycopg2://username:password@localhost:5432/database_name"
)
```

---

### Step 4 — Load Data into PostgreSQL

```python
df.to_sql(
"customer",
engine,
if_exists="replace",
index=False
)
```

---

### Step 5 — Run SQL Queries

Execute SQL queries using pgAdmin or Python to analyze the data.

---

### Step 6 — Open Power BI Dashboard

* Open `.pbix` file in Power BI Desktop.
* Refresh dataset connection if required.

---

### Step 7 — View Report & Presentation

* Open Report document (`.pdf` / `.docx`)
* Open Gamma presentation slides

---

## 📁 Project Structure

```
project-folder/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── customer_dashboard.pbix
│
├── reports/
│   └── analytics_report.pdf
│
├── presentation/
│   └── presentation_gamma.pptx
│
└── README.md
```
## 🎯 Project Purpose

This project demonstrates:

* End-to-end data analytics workflow
* Data cleaning and transformation
* SQL-based data analysis
* Dashboard design using Power BI
* Business insight generation
* Professional reporting and presentation skills

Feel free to connect for feedback, collaboration, or opportunities.
