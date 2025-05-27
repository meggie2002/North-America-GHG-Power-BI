# North America Greenhouse Gas Emissions: Exploratory, Statistical, and Visual Analysis (2000–2023)

## Overview

This project delivers a comprehensive analysis of greenhouse gas (GHG) emissions and economic indicators in North America from 2000 to 2023. Leveraging both Power BI and Tableau, I performed data cleaning, exploratory data analysis (EDA), statistical analysis, and developed interactive dashboards to uncover trends, sectoral contributions, and relationships between emissions, GDP, and energy use.

---
## Analysis Questions

_POWER BI_
1. How have total and per capita CO₂ emissions changed over time from 2000 to 2023?
2. How do greenhouse gas emissions correlate with economic indicators such as GDP and primary energy consumption?
3. Which sectors (coal, oil, gas, cement, land use change) contribute most to CO₂ emissions in different countries?
4. How does primary energy consumption per capita relate to GHG emissions per capita, and which countries have high energy use but low emissions intensity?
5. What is the contribution of methane and nitrous oxide to total GHG emissions across countries?
_TABLEAU_
1. How have total and per capita CO₂ emissions changed over time (2000–2023) by country?
2. What are the trends in sectoral CO₂ emissions (coal, oil, gas, cement, land use) over time?
3. How strongly are sectoral emissions correlated with total CO₂ emissions?
4. What is the correlation between GDP, energy consumption, and CO₂ emissions?
5. Which sector is the strongest predictor of CO₂ emissions based on linear trend analysis?
6. Are there significant differences in emissions intensity (CO₂ per GDP, CO₂ per capita) between countries?
7. What is the contribution of methane and nitrous oxide to total greenhouse gas emissions?

---

## Key Findings

- The US is the largest emitter; Trinidad and Tobago leads per capita emissions
- Coal emissions declined post-2010; gas emissions rose steadily
- Sectoral correlations with total CO₂ emissions vary by country and sector
- Emissions intensity and sectoral contributions differ widely across North America

---
## Data Sourcing and Justification

- **Source:** [Our World in Data: CO₂ and Greenhouse Gas Emissions](https://ourworldindata.org/co2-and-greenhouse-gas-emissions)
- **Coverage:** Annual, country-level data from 1750 to 2023, including emissions by gas, sector, GDP, population, energy use.
- **Why this dataset:** Comprehensive, reliable, integrates multiple authoritative sources. Enables cross-country and sectoral analysis.
- **Access:** Download instructions in `/data/README_Data.md`.

**Key columns include:**  
`country`, `year`, `population`, `gdp`, `co2`, `co2_per_capita`, `primary_energy_consumption`, `methane`, `nitrous_oxide`, etc.

---
## Data Cleaning

- **Null values:** Filled missing GDP with country median (Power BI Group By & Merge); replaced missing sector emissions/energy with 0.
- **Outlier handling:** Retained outliers as they reflect real differences (e.g., US vs. small countries).
- **Skewed data:** Used log transformations for highly skewed columns (Power BI custom columns).
- **Column consistency** 
- **Created new columns** for emissions intensity and sectoral shares

---

## Tools Used

- Power BI (for data cleaning, EDA, visualization)
- Tableau (statistical analysis, visualization)
- GitHub (for version control and sharing)
- Excel/CSV (for initial data handling)

---
## Limitations & Next Steps
- Only major greenhouse gases included.
- Future work: Expand to more countries, predictive modeling
---
## References

- [Our World in Data: CO₂ and Greenhouse Gas Emissions](https://ourworldindata.org/co2-and-greenhouse-gas-emissions)
- International Energy Agency (IEA): [North America Emissions](https://www.iea.org/regions/north-america/emissions)
- IPCC Reports

---


