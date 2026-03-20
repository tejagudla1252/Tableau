# Agrifood CO2 Emissions Analysis

End-to-end analysis of global agrifood system CO2 emissions — exploring which countries, food categories, and agricultural activities contribute most to greenhouse gas output, using Python for data cleaning and Tableau for interactive storytelling.

**Tools:** Python (Pandas, Seaborn) · Tableau · CSV

---

## Overview

The agrifood sector accounts for roughly one-third of global greenhouse gas emissions. This project uses FAO (Food and Agriculture Organization) data to analyze emission sources across countries and food production categories — identifying the highest-impact contributors and visualizing trends over time.

## Files

| File | Description |
|---|---|
| `Agrofood.ipynb` | Python EDA — cleaning, profiling, feature analysis |
| `Agrofood_co2_emission.csv` | Raw FAO agrifood emissions dataset |
| `Agrofood_co2_emission_cleaned.csv` | Cleaned dataset after null handling and standardization |
| `Agrofood_co2_emission.twb` | Tableau workbook with all dashboards |
| `AGRIFOOD CO2 EMISSION.docx` | Written analysis report |
| `Agrifood CO2 emission.pptx` | Presentation deck with key findings |

## Data Cleaning (Python)
- Handled missing values across 60+ country-year combinations
- Standardized country name formats for Tableau geographic mapping
- Derived per-capita emission metrics for normalized cross-country comparisons
- Created emission category aggregations (livestock, crops, land use, energy)

## Key Analysis

**Country-Level Emissions**
Ranked countries by total and per-capita agrifood emissions — identifying the top 10 contributors and tracking their trajectories over the dataset period.

**Emission Source Breakdown**
Decomposed total emissions by source type: enteric fermentation (livestock), synthetic fertilizers, rice cultivation, crop residue burning, and food transport — showing which activities dominate in different regions.

**Trend Analysis**
Time series visualization of emissions by region (Asia, Sub-Saharan Africa, Latin America, Europe) showing divergent trajectories — some regions declining, others growing rapidly.

**Correlation Analysis**
Explored relationships between GDP per capita, agricultural intensity, and emission levels — finding that middle-income countries show the fastest emission growth as agricultural productivity scales up.

## Tableau Dashboard Highlights
- World choropleth map of total agrifood emissions by country
- Stacked bar chart of emission sources by region
- Line chart showing emission trends 2000–2020 by region
- Scatter plot: GDP per capita vs. per-capita emissions with country labels
- Top 15 emitting countries ranked bar with drill-down by source

## Key Findings
- Livestock-related emissions account for 32% of total agrifood CO2
- Asia contributes 44% of global agrifood emissions driven by rice cultivation and fertilizer use
- EU emissions declined 18% over the study period while South/Southeast Asia grew 22%

## Skills Demonstrated
Python EDA · Data cleaning · Environmental analytics · Tableau geographic mapping · Time series visualization · Comparative analysis
