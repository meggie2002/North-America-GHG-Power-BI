## New Column/Field Calculations  
• **Correlation Calculations**: Calculated the correlation coefficient between each sector’s 
emissions and total CO₂ emissions (e.g., CORR (Coal CO₂, Total CO₂)). <br>
•  **Country-Level Aggregations**: Calculated country-level totals for each greenhouse gas 
and emission sector using fixed aggregations. <br>
• **Calculating Sector Shares per Country**: Calculated the share of each sector’s emissions 
relative to total CO₂ emissions for each country. And calculated the share of nitrous 
oxide and methane to total GHG for each country (e.g., Oil CO₂ / Total CO₂). <br>

## Visualizations and Findings 
**How have total and per capita CO₂ emissions changed over time (2000–2023) by 
country?** 
<br>
![CO2 emission by country](https://github.com/user-attachments/assets/01b2847d-eb55-46d8-a53e-ba102319f082)
<br>
### Total CO₂ Emissions  <br>
• United States is by far the largest emitter, with over 133,000 units (million tonnes). <br>
• Mexico and Canada are next, but with much lower totals (11,032 and 13,539). <br>
• All other countries in the region emit far less, often under 1,000 units. <br>
### CO₂ Per Capita  <br>
• Trinidad and Tobago has the highest per capita emissions (27.92), despite relatively low 
total emissions, this means each person emits a lot on average.<br>
• United States (17.82) and Canada (16.28) also have high per capita emissions, reflecting 
high energy use and fossil fuel reliance. <br>
• Barbados, Bahamas, Antigua and Barbuda, and Saint Kitts and Nevis also have elevated 
per capita emissions, despite small populations. <br>
• Most other countries have per capita emissions below 3. <br>
**What are the trends in sectoral CO₂ emissions (coal, oil, gas, cement, land use) 
over time?** 
<br>
![Trend of each Sectors](https://github.com/user-attachments/assets/5d083366-a948-4353-8e5e-4bd5f3eeadee)
<br>
• **Cement CO₂**: Cement sector emissions have remained relatively constant, with only 
minor fluctuations. <br>
• **Coal CO₂** : Coal emissions have decreased significantly over the period, especially after 
2010, indicating a shift away from coal as an energy source. <br>
• **Gas CO₂**: Emissions from gas have risen steadily, shows a growth in natural gas in energy 
production. <br>
• **Land Use Change CO₂**: Emissions sharply dropped after 2000s then leveled off, mostly 
due to reduction of deforestation or land management. <br>
• **Oil CO₂**: Downward trend but remain stable, maybe due to minor reductions. <br>
**How strongly are sectoral emissions (coal, oil, gas, cement, land use) correlated 
with total CO₂ emissions?** 
<br>
![Correlation - Sectoral and CO2](https://github.com/user-attachments/assets/8aaf4cef-e0ef-4cf1-9021-6dc45772e8c5)
<br>
• **Land and Oil Correlations** with CO₂ extremely strong positive correlations across nearly 
all countries. CO2 emission increase when land use exploit (deforestation, poor land 
managements). Similarly, CO2 emission increase when oil use increases. <br>  
• **Cement Correlation**:  The correlation between cement-related CO₂ emissions and total 
CO₂ emissions varies by country: <br>  
  o **Dominican Republic**: Strong positive correlation (0.921) <br>  
  o **Honduras**: Strong positive correlation (0.850) <br>  
  o **Jamaica**: Strong negative correlation (-0.805) <br>  
The observed negative correlation between cement-related CO₂ emissions and total CO₂ 
emissions in Jamaica reflects the country's broader emission dynamics. While the 
cement industry has made strides in reducing its carbon footprint, significant emission 
reductions in larger sectors like power generation and alumina production have a more 
pronounced impact on the country's total emissions. Thus, even with slight increases in 
cement emissions, the overall CO₂ emissions can decline, resulting in the negative 
correlation observed. <br>  
• **Coal Correlation**: Coal-related CO₂ emissions show varying correlations with total CO₂ 
emissions: <br>  
  o **USA**: Strong positive correlation (0.952) <br>  
  o **Dominican Republic**: Strong positive correlation (0.885) <br>  
  o **Jamaica**: Negative correlation (-0.632) <br>  
  o **Costa Rica**: Negative correlation (-0.397) <br>  
These variations reflect differing reliance on coal for energy production across countries. 
For instance, the USA's strong positive correlation aligns with its historical dependence 
on coal, while Jamaica and Costa Rica's negative correlations may indicate a shift 
towards alternative energy sources. Both countries have minimal reliance on coal and 
are actively pursuing renewable energy initiatives, resulting in total CO₂ emissions trends 
that are largely independent of coal usage. <br>  
• **Gas Correlation**: Natural gas-related CO₂ emissions generally exhibit positive correlations 
with total CO₂ emissions; however, the USA presents a notable exception: <br>  
  o **USA**: Strong negative correlation (-0.895) <br>

<br>  
Although natural gas-related CO₂ emissions in the United States have increased, there 
exists a strong negative correlation (-0.895) between gas emissions and total CO₂ 
emissions. This indicates that as natural gas usage rises, overall CO₂ emissions tend to 
decline. This trend is primarily due to the substitution of coal with natural gas in 
electricity generation. Natural gas combustion produces significantly less CO₂ compared 
to coal. According to the U.S. Energy Information Administration (EIA), from 2005 to 
2019, coal's share in electricity generation dropped from 50% to 23%, while natural gas's 
share increased from 19% to 38%. This transition contributed to a 32% reduction in CO₂ 
emissions from the electric power sector during that period. <br>  

**What is the correlation between GDP, energy consumption, and CO₂ emissions?**
<br>
![Correlation - GDP,energy consumption, CO2](https://github.com/user-attachments/assets/b8b3295f-ee4c-4656-b240-b37f489d1b92)
## Energy Consumption and CO₂  <br>
_Strong positive correlation_ in most countries. <br>
  • **Mexico** (0.870): Mexico's heavy reliance on fossil fuels, particularly oil and natural gas, 
for energy generation, transportation, and industrial processes leads to substantial CO₂ 
emissions. Rapid urbanization has further increased energy demand, contributing to this 
strong correlation. <br>
  • **Canada** (0.847): Despite Canada's efforts to decouple economic growth from emissions, 
the energy sector remains a significant contributor to CO₂ emissions, accounting for 80% 
of the country's total GHG emissions in 2022. <br>
  • **Trinidad and Tobago** (0.913): The country's industrial sector, particularly metal refining 
and manufacturing, consumes a significant portion of energy, leading to high CO₂ 
emissions. This industrial energy use accounts for just under 50% of domestic 
consumption. <br>
_Negative correlations_: <br>
  • **Jamaica** (-0.138): Jamaica’s shift towards renewable energy sources and reduced 
reliance on fossil fuels have led to a decoupling of energy consumption from CO₂ 
emissions, resulting in a weak negative correlation. <br>
  • **United States** (-0.190) The U.S. has experienced a decoupling of energy consumption 
from CO₂ emissions, primarily due to a transition from coal to natural gas and 
renewables in electricity generation. This shift has contributed to a 32% reduction in CO₂ 
emissions from the electric power sector between 2005 and 2019. <br>
## GDP and CO₂  <br>
_Strong positive correlation_ in several countries <br>
Honduras (0.925), Haiti (0.889), Saint Lucia (0.873), Trinidad and Tobago (0.921): Implies that 
economic growth in these countries is strongly associated with increased CO₂ emissions. <br>
_Negative correlations_: <br>
United States (-0.779) and Canada (-0.240) show negative correlations, suggesting: 
Decoupling of economic growth from emissions, strong climate policies, shift to service-based 
economies or renewable energy.<br>

**Which sector is the strongest predictor of CO₂ emissions based on linear trend 
analysis?**
<br>
![Trend Analysis](https://github.com/user-attachments/assets/152b66ca-6af4-4cfe-80f5-6b4a907c4cbf)
<br>
![Regression Metrics](https://github.com/user-attachments/assets/182b9b40-ab24-48e3-8d44-831186dfe312)
<br>
**Oil CO₂** has the highest R-squared (0.999), it perfectly explains changes in CO₂ emissions. 
It also has the lowest standard error (808), indicating high precision. All other sectors 
(except Land Use Change) are also strong predictors, but Oil CO₂ is the best. <br>

Across countries and years, oil sector CO₂ emissions are the most reliable and precise predictor 
of CO₂ emissions, based on linear trend analysis. While coal, gas, and cement emissions are also 
closely related to CO₂, oil emissions stand out as the best single predictor.  <br>

Although the **correlation matrix** among North American countries reveals a strong positive 
relationship between Land Use Change CO₂ and total CO₂ emissions, the **linear trend model**
points to a weak relationship for Land Use Change CO₂ in relation to total CO₂ emissions, with 
low R² (0.05) and non-significant p-value (0.285). A Pearson correlation merely describes the 
way two variables are related, regardless of whether a cause-and-effect exists. if both total CO₂ 
and Land Use Change CO₂ are increasing and the later is a small part of the total, the 
correlation may still be strong. 
While land use change CO₂ emissions show a strong correlation with total CO₂ emissions across 
countries, their predictive power in regression models is limited due to their smaller magnitude, 
measurement uncertainties, and complex interactions with other emission sources.<br>

**Are there significant differences in emissions intensity (CO₂ per GDP, CO₂ per 
capita) between countries?** 
<br>
![Emissions Intensity Comparison](https://github.com/user-attachments/assets/0e8282c7-090c-438c-9b21-ad65a78f0610)
<br>
Yes, there are significant differences in emissions intensity among countries. <br>
**CO₂ per Capita**: <br>
_Highest emitters per capita_: <br>
  • Trinidad and Tobago, United States, Canada <br>
  • These are developed or high fossil fuel-exporting nations with high consumption 
patterns or industrial activity.<br>
_Lowest emitters per capita_: <br>
  • Haiti, Nicaragua, Guatemala — very low per capita emissions, likely due to lower energy 
consumption, limited industrialization, possibly greater reliance on non-fossil fuel 
sources. <br>
The disparity in per capita CO₂ emissions across North American countries highlights the 
influence of economic development, energy policies, and industrial activities on environmental 
impact. While countries like Trinidad and Tobago exhibit high emissions due to energy-intensive 
industries, nations like Haiti, Nicaragua, and Guatemala maintain low emissions, reflecting their 
limited industrialization and efforts towards renewable energy adoption. <br>

**CO₂ per GDP**: <br>
_Highest emitters per GDP_: <br>
  • Trinidad and Tobago again ranks highest — suggesting a carbon-intensive economy, likely 
due to oil and gas production. <br>
_Low emissions per GDP_: <br>
  • Most other countries have much lower values, with some virtually negligible. <br>
  • Indicates better carbon efficiency or less dependence on high-emission industries for 
GDP. <br>
The disparity in CO₂ emissions per GDP among North American countries underscores the 
impact of economic composition and energy policies on carbon intensity. Countries with 
economies heavily dependent on fossil fuels, like Trinidad and Tobago, tend to have higher 
emissions per economic output. In contrast, nations with diversified economies and proactive 
energy transitions demonstrate better carbon efficiency. <br>

**What is the share of each sector (coal, oil, gas, cement, land use) in total CO₂ 
emissions?** 
<br>
![Share of each sector in CO2](https://github.com/user-attachments/assets/aa7b8745-061e-4451-8853-f6c9bf109681)
<br>
  • **Coal**: <br>
The share is nearly zero for most countries, except the United States (0.3012), Canada 
(0.1554), Mexico (0.0801), and the Dominican Republic (0.1318), where coal makes a 
modest contribution. <br>
  • **Land use**: <br>
The proportion of total CO₂ emissions that comes from land use change and forestry over 
the period 2000–2023. Positive values indicate that land use change (such as 
deforestation or land conversion) is a net source of CO₂, contributing to the country’s 
overall emissions. Negative values indicate that land use and forestry act as a net sink, 
removing more CO₂ from the atmosphere than they emit, often due to reforestation or 
improved land management practices. Why Some Shares Are Greater than 1: If the land 
use share is above 1, it means that cumulative land use emissions over 2000–2023 are 
much higher than the sum of all other CO₂ emissions in that country. This can happen in 
countries where fossil fuel and industrial emissions are very low, but there have been 
major land use changes, such as extensive deforestation or land conversion. 
Land use change is a major source in a few countries, especially Haiti (9.76), Nicaragua 
(5.08), and Honduras (1.15). Negative values (e.g., Saint Vincent and the Grenadines, Saint 
Lucia, Dominica) indicate these countries are net sinks, absorbing more CO₂ than they 
emit from land use. <br>
  • **Cement**: Cement’s share is generally small, with the highest values in Guatemala 
(0.07792), the Dominican Republic (0.0701), and El Salvador (0.07079). <br>
  • **Gas**:<br>   
Gas is a significant contributor in Trinidad and Tobago (0.8785) and the United States 
(0.3512) but is negligible in most other countries. <br>
  • **Oil**:<br> 
Oil is the dominant source of CO₂ emissions for almost every country listed. In many 
Caribbean and Central American nations, oil accounts for nearly all emissions (shares of 
1.00).<br>

**What is the contribution of methane and nitrous oxide to total greenhouse gas 
emissions?** 
<br>
![methane and nitrous oxide](https://github.com/user-attachments/assets/e30d66de-fcef-4714-92c4-41467cc506ee)
<br>
Size of box represents the share of **methane** in total greenhouse gas emissions for each country. 
And color indicated the share of nitrous oxide in total GHG emissions. **Green**: Higher 
nitrous oxide shares and **Blue**: Lower nitrous oxide share. <br>
  • Mexico has high nitrous oxide share and medium methane share. <br>
  • **Countries with High Methane and Nitrous Oxide Shares**: Haiti, El Salvador, Cuba, 
Dominican Republic, Honduras and Costa Rica <br>
  • **Countries with High Methane but Lower Nitrous Oxide**: Trinidad and Tobago, 
Guatemala, Nicaragua, Panama <br>
  • **Countries with Low Methane and Nitrous Oxide Shares**: United States, Canada, 
Bahamas, Barbados, Jamaica have higher CO₂ emissions from fossil fuels, making non
CO₂ gases a smaller proportion of their total GHG profile.<br>
