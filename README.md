# 📊 Global Layoffs Analysis using SQL

## 🔍 Project Overview
This project analyzes **2,000+ global layoff records** reported between **2020–2023**, covering companies across **60+ countries and 30+ industries**.  
The goal was to perform **end-to-end SQL data cleaning and exploratory analysis** to extract meaningful business insights from raw, inconsistent data.

---

## 🛠 Tools & Technologies
- SQL (MySQL)
- CSV / Excel
- SQL Techniques:
  - CTEs
  - Window Functions
  - Aggregations
  - Date functions
  - Ranking & trend analysis

---

## 📁 Dataset Summary
- Records: **2,000+**
- Companies: **1,000+**
- Countries: **60+**
- Industries: **30+**
- Time Range: **2020–2023**
- Metrics:
  - Total layoffs
  - % workforce laid off
  - Company stage
  - Industry & geography

---

## 🧹 Data Cleaning Process
Performed structured SQL-based cleaning to:
-- 1. check for duplicates and remove any
-- 2. standardize data and fix errors
-- 3. Look at null values and see what 
-- 4. remove any columns and rows that are not necessary - few ways

Result: **100% usable dataset for analytical querying**

---

## 📈 Exploratory Data Analysis (EDA)

### Key Analyses
- Aggregated **150K+ total layoffs** across all companies
- Identified **Top 10 companies contributing ~45–50% of total layoffs**
- Ranked industries by total layoffs to identify **high-impact sectors**
- Analyzed layoffs by funding stage (Seed → Public)
- Built monthly & yearly trends to capture macroeconomic impact

---

## 💡 Key Insights
-The analysis shows a strong concentration of layoffs among a small group of large firms. 
 Companies such as **Amazon, Meta, Google, Microsoft, Tesla, and Twitter** consistently
 appear in the top contributors, together accounting for ~45–50% of total layoffs.
- Technology and consumer-facing industries account for ~55–60% of overall layoffs.
- Peak downturn years show more than 2× increase in layoffs compared to stable years.
- Late-stage and publicly listed companies contribute ~65–70% of absolute layoffs.
- The top 5 countries represent ~70% of total layoffs, indicating geographic concentration.
- Monthly analysis shows abrupt correction periods with 30–40% MoM spikes.

---

## 📌 Key Learnings
- Real-world datasets require extensive preprocessing before analysis
- SQL window functions are critical for ranking and trend detection
- Business insights emerge from **structured aggregation, not raw data**
- SQL alone can deliver powerful insights without BI tools

---

## 🚀 How to Run
1. Load `layoffs.csv` into a SQL database
2. Execute `SQL data cleaning project.sql`
3. Run `EDA SQL project.sql` to reproduce insights

---

## 📎 Project Files
- layoffs.csv
- SQL data cleaning project.sql
- EDA SQL project.sql

---

## ⭐ Why This Project Matters
This project demonstrates **end-to-end SQL proficiency on a real-world dataset**, aligning directly with **Data Analyst and Business Analyst role requirements**.
