# SF Crime Data Analysis and Modeling

## Introduction
This repository contains **Jinglei’s personal practice project** for analyzing the **San Francisco Police Department Crime Incident Reports (2003–2018)** using **Apache Spark on Databricks**.

During the analysis, Jinglei explored and solved several key questions:

1. Identified which crime categories were most common and tracked their frequency changes over time.  
2. Determined which police districts experienced the highest incident counts and how patterns varied geographically.  
3. Examined hourly and daily trends to find peak periods for crime activity.  
4. Analyzed yearly and monthly fluctuations to reveal long-term and seasonal trends.  
5. Calculated crime resolution rates by category, highlighting those with low clearance percentages.  
6. Visualized all findings using Databricks `display()` charts and additional **Matplotlib/Seaborn** plots.

The project demonstrates **OLAP-style big-data analysis** with both **Spark SQL** and **PySpark DataFrame APIs** to practice querying, aggregating, and visualizing large datasets.

---

## Dataset
- **Source:** [SF Open Data Portal](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry)  
- **Coverage:** Crime incident reports from **2003–2018**  
- **Size:** ~ **4.3 million records**, about **700 MB CSV file** after download  

---

## Files
- `Betty_project1.ipynb` – Main notebook for data preprocessing, OLAP analysis, visualization, and insights.  
- `SQL & Dataframe.docx` – Jinglei’s personal cheat-sheet for frequently used SQL and Spark DataFrame commands.

---

## Key Insights
- Peak crime activity by **district** and **hour**  
- Seasonal and long-term patterns over **2013–2018**  
- **Resolution-rate gaps** between crime categories, informing suggestions for better resource allocation

---

## How to Run
1. Open the notebook in Databricks or Jupyter  
2. Ensure a **PySpark environment** is available  
3. Follow the cells sequentially for preprocessing, analysis, and visualization

---

## Author
Developed by **Jinglei (Betty0218-Jinglei)** as part of personal practice in data analytics with Spark.
