# World Layoffs Data Cleaning, Analysis & Tableau Dashboard

## Project Overview

This end-to-end data analytics project explores global layoff trends using SQL and Tableau. The project begins with data cleaning and transformation in MySQL, followed by exploratory data analysis (EDA) to uncover insights about layoffs across companies, industries, countries, and time periods. The cleaned dataset is then visualized through an interactive Tableau dashboard.

---

## Problem Statement

Mass layoffs have affected thousands of companies worldwide over the last few years. This project aims to analyze global layoff data to identify patterns, trends, and key insights regarding workforce reductions across industries and countries.

---

## Dataset

The dataset contains information about layoffs from companies around the world, including:

- Company
- Industry
- Location
- Country
- Date
- Total Employees Laid Off
- Percentage Laid Off
- Funding Raised
- Company Stage

**Source:** Kaggle World Layoffs Dataset

---

## Project Workflow


### 1. Data Cleaning (MySQL)

The raw dataset contained duplicates, inconsistent formatting, blank values, and incorrect data types.

Cleaning steps performed:

- Removed duplicate records using `ROW_NUMBER()`
- Standardized company names and country values
- Converted dates into proper SQL date format
- Handled blank and NULL values
- Populated missing industry values where possible
- Removed unnecessary records
- Created a clean analysis-ready dataset

---

### 2. Exploratory Data Analysis (EDA)

Business questions explored:

- Which companies laid off the most employees?
- Which industries were most affected?
- Which countries experienced the highest layoffs?
- How did layoffs change over time?
- Which companies had the highest layoffs each year?
- What are the cumulative layoff trends over time?

---

### 3. Data Visualization (Tableau)

The cleaned dataset was visualized using Tableau to create an interactive dashboard that enables users to:

- Analyze layoffs by company
- Compare layoffs across industries
- Explore country-wise layoff trends
- Track layoffs over time
- Identify top companies affected each year
- Monitor cumulative layoff trends

---

## SQL Concepts Used

- Common Table Expressions (CTEs)
- Window Functions
- `ROW_NUMBER()`
- `DENSE_RANK()`
- Aggregate Functions
- Date Functions
- Data Cleaning Techniques
- Data Transformation
- `GROUP BY`
- `ORDER BY`
- Joins

---

## Tableau Dashboard

### Dashboard Preview

<img width="1280" height="832" alt="dashboard-1" src="https://github.com/user-attachments/assets/132ff126-4c5c-41f5-8399-48ce62609c25" />


### Interactive Dashboard

**View Dashboard Here:**

[View Interactive Tableau Dashboard](https://public.tableau.com/views/World_Layoffs_tableau_dashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

---

## Key Insights

- Technology companies accounted for a significant portion of total layoffs.
- Several companies reported 100% workforce reductions.
- Layoffs peaked during specific economic periods.
- The impact varied considerably across industries and countries.
- Certain companies consistently appeared among the top layoffs year after year.

---

## Files Included

- `world_layoffs_analysis.sql` – Data cleaning and exploratory analysis queries
- `dashboard.png` – Tableau dashboard screenshot
- `README.md`

---

## Tools Used

- MySQL
- MySQL Workbench
- Tableau
- SQL

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Transformation
- Data Visualization
- Business Intelligence
- Dashboard Development
- SQL Query Optimization
- Analytical Thinking

---

## Project Outcome

This project transformed raw layoff data into actionable business insights through a complete analytics workflow involving data cleaning, SQL analysis, and interactive dashboard creation. The resulting dashboard enables stakeholders to quickly identify trends, compare industries, and understand the global impact of workforce reductions.

---

## Author

Aryan Soni

GitHub: https://github.com/aryan10000
