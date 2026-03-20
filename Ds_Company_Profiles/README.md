# Data Science Company Profiles — Comparative Analysis

Comparative analysis of data science companies using HDI-linked economic indicators and company profile data — exploring how company characteristics, industry, and geography shape DS hiring patterns and skill requirements.

**Tools:** Python (Pandas) · Tableau · Excel · CSV

---

## Overview

This project combines company profile data with Human Development Index (HDI) contextual indicators to analyze how data science teams are structured across company types, industries, and geographies — producing a Tableau dashboard that helps job seekers understand where DS talent concentrates and what skills different company profiles demand.

## Files

| File | Description |
|---|---|
| `DS_Company_5709_project.ipynb` | Python analysis and data preparation notebook |
| `project_5709_DS_Company.twb` | Tableau workbook with company profile dashboards |
| `HDR21-22_Statistical_Annex_HDI_Table.xlsx` | UN HDI contextual data used for geographic enrichment |
| `Data Science Company Profile by Slidesgo.pptx` | Presentation deck with key findings |

## Data Sources
- Company profile dataset: company name, industry, size, location, DS team size, primary tools and stack
- UN Human Development Report 2021-22 HDI Statistical Annex for country-level enrichment

## Key Analysis

**Company Type Breakdown**
Classified companies into tech-native, enterprise, consulting, startup, and research categories — analyzing how DS team structure and tool preferences differ by type.

**Industry Distribution**
Mapped DS company concentration by industry: Finance, Healthcare, Retail, Manufacturing, Media — showing which sectors have the deepest DS investment.

**Geographic Intelligence**
Combined company location data with HDI indicators to show how DS opportunity clusters in high-HDI countries and emerging tech hubs.

**Tool Stack Analysis**
Analyzed which programming languages, cloud platforms, and BI tools appear most frequently across company profiles by industry and size.

**Team Size vs. Company Size**
Explored the ratio of DS headcount to total employees — showing that mid-size tech companies often have disproportionately large DS teams.

## Tableau Dashboard Highlights
- Treemap of companies by industry and size
- Bubble chart: DS team size vs. company revenue by industry
- Geographic map with HDI overlay showing DS company density
- Stacked bar: tool stack frequency by company type
- Filter panel: industry, size, and geography drill-down

## Key Findings
- Finance and healthcare companies have the highest DS-to-total-headcount ratios
- Python + SQL + cloud (AWS/Azure/GCP) is the dominant stack across 78% of profiled companies
- DS team sizes grow non-linearly — companies crossing 500 employees show a step-change in DS investment
- High-HDI countries (HDI above 0.85) host 71% of profiled DS companies

## Skills Demonstrated
Python data preparation · Multi-source data integration · Tableau treemap and geographic visualization · Company research analytics · HDI contextual analysis
