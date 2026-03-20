# Dallas 311 Street Service Request Analysis

Analysis of Dallas city 311 service request data — identifying response time patterns, service bottlenecks, and geographic disparities across the city using Python EDA and Tableau dashboards.

**Tools:** Python (Pandas, Matplotlib) · Tableau · CSV

---

## Overview

The City of Dallas receives thousands of 311 service requests daily covering pothole repairs, graffiti removal, code violations, illegal dumping, and more. This project explores the cleaned 311 dataset to surface operational insights for city service performance monitoring.

## Files

| File | Description |
|---|---|
| `INFO 5709 311 EDA.ipynb` | Full Python EDA — cleaning, profiling, visualizations |
| `311_service_cleaned.csv` | Cleaned dataset used for Tableau and analysis |
| `311_Project_report.docx` | Written analysis report with findings and recommendations |
| `5709_Analysis of Dallas Street Service Requests.pptx` | Presentation deck summarizing key insights |

## Key Analysis

**Response Time Analysis**
Calculated actual vs. expected resolution times by service type and department — identifying which request categories consistently breach SLA targets.

**Geographic Distribution**
Mapped request density by zip code and council district to identify underserved areas with high open request volumes and low resolution rates.

**Department Performance**
Compared resolution rates and average handling time across city departments — surfacing which teams are overloaded relative to request volume.

**Trend Analysis**
Examined monthly and seasonal patterns in request volume by category — showing predictable demand spikes that could inform resource pre-positioning.

## Tableau Dashboard Highlights
- Request volume by type and district (bar + map)
- Average resolution time by department (heatmap)
- Open vs. closed request ratio over time (trend line)
- Top 10 most frequent request types (ranked bar)

## Key Findings
- Street/pothole repair requests had the longest average resolution time at 14.3 days vs. a 7-day target
- 3 council districts accounted for 42% of all open unresolved requests
- Request volume peaks consistently in March–May and October — suggesting seasonal staffing needs

## Skills Demonstrated
Python data cleaning · EDA · Tableau dashboard design · Public sector analytics · Geographic analysis · KPI reporting
