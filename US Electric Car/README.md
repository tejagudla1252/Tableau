# U.S. Electric Vehicle Market — Data Analysis and Dashboard

Analysis of U.S. electric vehicle registration and adoption data — exploring state-level EV penetration, make/model distribution, geographic adoption patterns, and market trends using Python EDA and Tableau.

**Tools:** Python (Pandas, Matplotlib, Seaborn) · Tableau · CSV

---

## Overview

Electric vehicle adoption in the U.S. has accelerated dramatically since 2020, driven by federal incentives, falling battery costs, and expanding charging infrastructure. This project analyzes U.S. EV registration data to understand where adoption is concentrated, which manufacturers are leading, and what factors correlate with high EV penetration rates.

## Files

| File | Description |
|---|---|
| `US_ELECTRIC_CAR_DATA_ANALYSIS.ipynb` | Full Python EDA — cleaning, profiling, visualizations |
| `us_car_data.csv` | U.S. electric vehicle registration dataset |
| `US_Car.twb` | Tableau workbook with EV analysis dashboards |

## Dataset Features
The dataset covers U.S. EV registrations with fields: VIN, county, city, state, postal code, model year, make, model, EV type (BEV/PHEV), CAFV eligibility, electric range (miles), base MSRP, and legislative district.

## Python EDA Highlights

**Data Profiling**
- Dataset shape, null rate analysis, data type validation
- Distribution analysis of electric range, model year, and MSRP
- BEV vs. PHEV split identification across the full dataset

**Geographic Distribution**
- State and county-level registration counts
- Mapping concentration by zip code for dense vs. sparse adoption areas

**Manufacturer Analysis**
- Market share by make: Tesla, Chevrolet, Nissan, BMW, Ford, and others
- Top 10 models by registration volume
- Model year trends showing fleet age distribution

**Electric Range Analysis**
- Range distribution across BEV and PHEV categories
- How average range improved across model years 2015-2023
- Range vs. MSRP relationship by manufacturer

## Tableau Dashboard Highlights
- U.S. state choropleth map — EV registrations per capita
- Market share chart by manufacturer
- BEV vs. PHEV split over time (stacked area)
- Electric range distribution histogram by model year
- Top 15 EV models ranked by registration count
- County-level heatmap for Washington State (highest adoption)
- CAFV eligibility breakdown

## Key Findings
- Washington State leads in EV registrations per capita driven by strong state incentives
- Tesla accounts for 52% of all BEV registrations in the dataset
- Average electric range increased from 84 miles (2015 models) to 247 miles (2023 models) — a 194% improvement
- PHEV registrations are declining as a share of total EVs — BEVs now represent 78% of new registrations
- King County (Seattle) alone accounts for 31% of all registrations in the dataset

## Skills Demonstrated
Python EDA · Geographic mapping · Market share analysis · Automotive data analytics · Tableau choropleth and trend visualization · Time series analysis
