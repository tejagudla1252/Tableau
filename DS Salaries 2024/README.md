# Data Science Salaries 2024 — Analysis & Dashboard

Comprehensive analysis of 2024 data science compensation data — benchmarking salaries by role, experience level, company size, remote ratio, and geography using Python and Tableau.

**Tools:** Python (Pandas, Matplotlib) · Tableau · CSV

---

## Overview

The data science job market has seen significant salary shifts driven by AI demand, remote work normalization, and tech sector consolidation. This project analyzes a 2024 dataset of DS/ML/AI compensation to surface actionable benchmarks for job seekers, hiring managers, and workforce planners.

## Files

| File | Description |
|---|---|
| `DS_Salaries_Cleaning.ipynb` | Python data cleaning and EDA notebook |
| `DataScience_salaries_2024.csv` | Raw salary dataset |
| `ds_salaries_cleaned.csv` | Cleaned dataset used in Tableau |
| `Book2.twb` | Tableau workbook with all dashboards |
| `DS Salaries_Report_5709.docx` | Full written analysis report |

## Data Cleaning (Python)
- Standardized job title variations (200+ raw titles to 15 normalized categories)
- Handled outliers in salary field (removed implausible values under $10K and over $1M)
- Decoded experience level codes (EN/MI/SE/EX to Entry/Mid/Senior/Executive)
- Mapped company size codes and employment type for clean Tableau filtering

## Key Analysis

**Role-Based Benchmarking**
Average and median salaries for 15 normalized roles: Data Scientist, ML Engineer, Data Engineer, Analytics Engineer, Data Analyst, Research Scientist, MLOps Engineer — with percentile bands.

**Experience vs. Compensation**
Salary progression from entry to executive level by role — quantifying the average premium at each seniority step and identifying roles with the steepest growth curves.

**Remote Work Premium**
Compared salaries for fully remote, hybrid, and on-site roles — showing whether remote positions command a premium or discount by role and company size.

**Geographic Analysis**
US vs. international salary comparison by country — identifying high-paying markets outside the US and regions with growing DS demand.

**Company Size Impact**
How salary scales with company size across roles — showing where small companies compete with large ones and where they cannot.

## Tableau Dashboard Highlights
- Salary heatmap by role and experience level
- Box plots showing salary distribution per role
- Bar chart: remote vs. on-site salary comparison
- Geographic map of median salaries by country
- Trend line: how top-10 roles shifted year-over-year 2020-2024

## Key Findings
- ML Engineers earn a 23% median premium over Data Scientists at the same experience level
- Fully remote roles for senior engineers average 8% higher than on-site equivalents
- Median Data Engineer salary grew 31% from 2020 to 2024 — fastest growth of any DS role
- Mid-size companies (50-250 employees) offer the most competitive pay relative to company size

## Skills Demonstrated
Python data cleaning · Salary benchmarking · Tableau advanced charts · Labor market analytics · Compensation analysis · Distribution visualization
