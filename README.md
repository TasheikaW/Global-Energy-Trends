# Assessing Global Energy Trends  

## Project Overview  
This project examines global energy trends, focusing on energy production, consumption, and their environmental impacts. The analysis explores changes in the shares of renewable energy, fossil fuel reliance, and their relationship with CO2 emissions. Additionally, the project emphasizes understanding statistical methods, analysis, and coding in R. Techniques such as hypothesis testing, bootstrapping, and regression analysis are applied to assess the significance of observed trends and correlations. The goal is to provide actionable insights into energy sustainability while enhancing technical proficiency in statistical analysis and data visualization.  click [here](https://github.com/TasheikaW/Global-Energy-Trends/blob/8368158f95f952d9935301966a73fd4a50ebc32f/Global%20Energy%20Trend%20Analysis.pdf) for full project.

## Data Sources  
- **Dataset**: Global energy statistics from Kaggle, sourced from Enerdata, covering 30 years (1990–2020).  
- **Key Metrics**:  
  - Emissions and energy intensity  
  - Energy production and consumption  
  - Fossil fuel production and consumption  
  - Shares of renewables in electricity production  
- **License**: World Bank Dataset Terms of Use.

## Guiding Questions  
1. **Has the share of renewable energy in electricity production significantly changed from 1990 to 2020?**  
   - Null Hypothesis: The average share in renewables in 2020 is less than or equal to that in 1990.  
   - Alternative Hypothesis: The  average share in 2020 is greater than that in 1990.  

2. **Does oil products domestic consumption (Mt) affect CO2 emissions in Canada?**  
   - Null Hypothesis: No significant relationship exists.  
   - Alternative Hypothesis: There is a positive relationship between oil consumption and CO2 emissions.

## Tools  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- R (ggplot2, dplyr)  
- Statistical techniques: Bootstrapping, regression analysis, and hypothesis testing  

## Data Cleaning  
- Addressed null values and converted non-numeric data to appropriate formats.  
- Filtered data to focus on relevant regions, countries, and timeframes.  
- Standardized variable names for consistency.  

## Data Analysis  
1. **Energy Production and Consumption**:  
   - Boxplots and line charts revealed disparities between energy production and consumption globally.  
   - Countries producing more energy than consumed (e.g., Russia) focus on exports, while others (e.g., China) rely on imports.  

2. **Natural Gas and Coal Trends**:  
   - Natural gas production is led by regions like North America and Europe, with the U.S. and Russia as top producers.
     <img width="788" alt="Image" src="https://github.com/user-attachments/assets/c013034e-4716-4664-84a6-6fd2b7647f2c" />
   - Coal consumption has declined since 2013, driven by a shift to renewables, though China remains the largest consumer.
     <img width="524" alt="Image" src="https://github.com/user-attachments/assets/a93fa8c7-212f-431e-9df5-b7c99fa39e7d" />

3. **Renewable Energy Trends**:  
   - Shares of renewables in electricity production increased significantly from 1990 to 2020, supported by policies and cost reductions in solar and wind technologies.

   - Brazil leads in renewable electricity shares, followed by Canada, while China produces the highest renewable energy in absolute terms.
   <img width="523" alt="Image" src="https://github.com/user-attachments/assets/70a8e2ae-8af3-43a4-bb8c-417da70a9fe7" />

4. **CO2 Emissions and Oil Consumption**:
   - Changes overtime was visualized.
   <img width="1037" alt="Image" src="https://github.com/user-attachments/assets/e57ab3e7-127b-4f1f-ba8f-29261795d636" />
   
   - Regression analysis showed a strong positive correlation (R² = 92.88%) between oil consumption and CO2 emissions in Canada.
     <img width="525" alt="Image" src="https://github.com/user-attachments/assets/5f0ab7ba-8c99-486f-b960-7dd940c8870d" />
   - For every unit increase in oil consumption, CO2 emissions rise by 4.13 MtCO2.  

## Results  
- Renewable energy shares have significantly increased, with a 95% confidence interval confirming the trend.  
- CO2 emissions are strongly linked to oil consumption, underscoring the environmental cost of fossil fuels.  
- Global energy trends highlight the gradual shift toward renewables, though fossil fuel dependency remains high in many regions.  

## Conclusion  
The analysis demonstrates significant progress in renewable energy adoption and its potential to reduce environmental impacts. However, fossil fuel reliance continues to drive CO2 emissions, particularly in oil-dependent economies. Integrating renewable energy more effectively requires coordinated policy efforts and technological advancements.  

## Recommendations  
1. **Improve Coal Consumption Analysis**: Adjust for population differences by analyzing per capita data.  
2. **Enhance Model Validity**: Address residual patterns in regression models using transformations like log or polynomial regression.  
3. **Expand Data Coverage**: Incorporate additional factors, such as policy changes and socioeconomic impacts, for a holistic view of energy trends.
