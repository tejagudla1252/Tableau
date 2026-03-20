# U.S. Department of Education — College Scorecard Analysis

Analysis of the U.S. Department of Education College Scorecard dataset — comparing 6,000+ institutions on graduation rates, student debt, post-graduation earnings, admission rates, and institutional characteristics to surface insights for students, policymakers, and education researchers.

**Tools:** Tableau · Excel · CSV · PDF

---

## Overview

Choosing a college is one of the highest-stakes financial decisions a person makes. The College Scorecard dataset enables evidence-based comparison across cost, outcomes, and selectivity. This project builds an analytical layer on top of the 2018-19 Scorecard data to answer: which institutions deliver the best post-graduation outcomes relative to cost?

## Files

| File | Description |
|---|---|
| `MERGED2018-19.xlsx` | Raw College Scorecard data (2018-19 academic year) |
| `Filtered_Dataset.csv` | Cleaned and filtered dataset for analysis |
| `CollegeScorecardDataDictionary.xlsx` | Official data dictionary for all 1,700+ variables |
| `Final_Project.pptx` | Presentation deck with findings and dashboard screenshots |
| `Project_Analysis.pdf` | Full written analysis report |
| `FinalProject_Instruction-4.pdf` | Project brief and methodology documentation |

## Dataset Scope
- 6,000+ U.S. institutions (4-year, 2-year, public, private non-profit, private for-profit)
- 2018-19 academic year
- Key variables: institution type, state, admission rate, graduation rate, median earnings 6 and 10 years post-enrollment, median student debt, SAT/ACT scores, enrollment size, tuition

## Key Analysis

**Return on Investment Framework**
Built an ROI metric combining median earnings at 6 years post-enrollment with median student debt at graduation — identifying institutions where graduates earn the most relative to what they borrowed.

**Graduation Rate Benchmarking**
Compared each institution's 6-year graduation rate against its sector average — surfacing which schools dramatically over- or under-perform relative to comparable institutions.

**Selectivity vs. Outcomes**
Scatter plot analysis of admission rate vs. median earnings — showing that selectivity predicts earnings but with significant outliers on both ends.

**Debt Load Analysis**
Mapped median student debt by institution type and state — identifying sectors with systematically higher debt burdens and examining the relationship with post-graduation default rates.

**Program Mix Impact**
Analyzed how STEM-heavy vs. humanities-heavy program concentrations affect median earnings — quantifying the earnings premium of STEM-dominant institutions.

## Tableau Dashboard Highlights
- Geographic map of median earnings by state with institution drill-down
- Scatter plot: admission rate vs. median 6-year earnings (colored by institution type)
- ROI ranking: top 50 institutions by earnings-to-debt ratio
- Graduation rate heatmap by state and institution type
- Debt distribution box plots by Carnegie classification
- Filter panel: state, institution type, size, public/private toggle

## Key Findings
- Engineering-focused institutions have earnings-to-debt ratios 3-4x the national median
- Community colleges in healthcare-heavy states show strong ROI despite low selectivity
- Private for-profit institutions have the worst graduation rates AND highest debt loads
- Public flagship universities in the Midwest offer the best combination of low cost and strong earnings outcomes

## Skills Demonstrated
Large dataset filtering · Multi-variable ROI analysis · Tableau advanced filtering · Education policy analytics · Consumer decision-support dashboard design · Scatter plot storytelling
