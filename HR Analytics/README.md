# HR Analytics — Workforce Attrition and Performance Dashboard

End-to-end HR analytics project analyzing workforce attrition drivers, employee performance patterns, and departmental health metrics — using Python for data cleaning and Tableau for executive-ready people analytics dashboards.

**Tools:** Python (Pandas, Matplotlib, Seaborn) · Tableau · CSV

---

## Overview

Employee attrition costs organizations 50-200% of an employee's annual salary in replacement costs. This project analyzes a real HR dataset to identify the key drivers of attrition, surface at-risk employee segments, and build dashboards that HR leadership can use to prioritize retention interventions.

## Files

| File | Description |
|---|---|
| `HR_Analytics_cleaning.ipynb` | Python data cleaning and EDA notebook |
| `HR_Analytics.csv` | Raw HR dataset |
| `Cleaned_HR_Analytics.csv` | Cleaned dataset used in Tableau |
| `Book1.twb` | Tableau workbook with HR dashboards |
| `Analysis on HR Analytics Data based on various features.docx` | Full written analysis with recommendations |

## Dataset Features
The HR dataset covers 1,470 employees across fields: age, department, job role, education, years at company, years since last promotion, job satisfaction score, work-life balance rating, overtime flag, monthly income, performance rating, and attrition label (Yes/No).

## Data Cleaning (Python)
- Removed zero-variance columns (EmployeeCount, StandardHours, Over18)
- Encoded ordinal variables (Education, JobSatisfaction, WorkLifeBalance) preserving order
- Flagged and investigated outliers in YearsAtCompany and MonthlyIncome
- Created derived features: tenure_band, income_quartile, satisfaction_composite

## Key Analysis

**Attrition Rate by Department and Role**
Sales Representatives showed the highest attrition rate at 39.8%, followed by HR at 23.1%. R&D had the lowest at 13.8% — suggesting role-specific retention challenges in customer-facing positions.

**Attrition Drivers**
Top factors correlated with attrition:
1. Overtime — employees working OT attrite at 2.3x the rate
2. Monthly income — bottom income quartile: 29% attrition vs. 8% in top quartile
3. Years since last promotion — above 4 years without promotion: 24% attrition rate
4. Job satisfaction score — score 1-2: 22% attrition vs. 4% at score 4
5. Work-life balance rating

**Tenure Analysis**
Attrition peaks at two points: years 1-2 (onboarding failure) and years 5-7 (mid-career stagnation). Employees past year 10 have very low attrition regardless of other factors.

**Performance vs. Satisfaction Quadrant**
Segmented employees into 4 quadrants: High Performance/High Satisfaction (retain), High Performance/Low Satisfaction (flight risk), Low Performance/High Satisfaction (manage up), Low Performance/Low Satisfaction (PIP candidates).

## Tableau Dashboard Highlights
- Attrition rate by department and job role
- Satisfaction composite heatmap by department
- Tenure distribution showing attrition peaks
- Overtime vs. attrition comparison
- Income quartile attrition waterfall chart
- KPI summary cards: overall attrition %, average tenure, avg satisfaction

## Key Recommendations
- Introduce structured check-ins at the 18-month mark — highest risk window
- Audit overtime assignment in Sales — strongest attrition predictor
- Create promotion transparency policy — employees above 3 years without promotion show measurably higher flight risk
- Salary band review for bottom income quartile roles

## Skills Demonstrated
Python EDA · HR analytics · Attrition analysis · Feature correlation · Tableau people analytics · Executive reporting · Workforce segmentation
