# COVID-19 Data Analysis

### Overview

This project performs an extensive analysis of COVID-19 data in Canada, focusing on trends and insights derived from the data. The script processes the data, cleans it, and generates meaningful visualizations and summaries.

## Dataset

The dataset used is `covid19-download.csv`, which contains COVID-19 case and death information across Canadian provinces over time. Key columns include:
- `prname`: Province name
- `date`: Reporting date
- `totalcases`: Total reported cases
- `numdeaths`: Number of reported deaths
- Other columns capturing rates and demographic information

## Features of the Analysis

### Data Cleaning and Preprocessing
- Converted date column to datetime format.
- Created additional columns for `year` and `month`.
- Interpolated missing values for numeric columns and filled categorical values using the most frequent value (mode).
- Removed records with invalid data (e.g., "Canada" as a province).
- Identified and removed outliers using the Z-score method.

### Key Outputs
1. **Total COVID-19 Cases by Province:**
   - Summed up the total cases for each province.

2. **Average Rate of Cases per Capita by Province:**
   - Computed the average rate of cases per capita.

3. **Province with the Highest Average Rate:**
   - Highlighted the province with the highest per-capita rate.

4. **Average Rate of Deaths per Capita:**
   - Calculated for each province.

5. **Overall Mortality Rate in Canada:**
   - Computed as the percentage of deaths among total cases.

6. **Yearly and Monthly Trends:**
   - Total cases and mortality rates by year.
   - Months with the highest and lowest case counts for each year.

7. **Day with the Highest Deaths for Quebec in 2020:**
   - Identified the day with the highest number of deaths in Quebec in 2020.

### Visualizations
- **Bar Chart:** Total cases by province.
- **Line Plot:** Total reported cases per year.
- **Heatmap:** Cases by month and year.
- **Rolling Averages:** 7-day averages for cases and deaths.

### Key Findings
      
- Total Number of Cases per Province: Ontario had the highest number of total COVID-19 cases (~223.5 million), followed by Quebec (~185.7 million). Nunavut reported the fewest cases (~6.4 million).
- Rate of Cases per Capita: Prince Edward Island had the highest average rate of COVID-19 cases per capita (15,328.76), while Quebec and Alberta also had high rates (8,916.04 and 8,436.12, respectively).
- Average Rate of Deaths per Capita: Quebec experienced the highest rate of COVID-19 deaths per capita (151.45), while Nunavut had the lowest (11.66).
- Overall Mortality Rate: The overall mortality rate of COVID-19 in Canada was 1.24%.
- Yearly Trends: The year with the highest total cases was 2023 (~244.5 million), while 2020 had the fewest (~6.5 million cases). The yearly mortality rate decreased from 5.12% in 2020 to 1.18% in 2024.
- Monthly Trends: The month with the highest total cases varied by year, with December 2023 reporting 24.3 million cases. February 2020 had the lowest monthly case total (52 cases).
- Quebec in 2020: December 26, 2020, was the deadliest day in Quebec, with 7662 deaths.

### Future Work
- Include regional breakdowns within provinces.
- Incorporate vaccination data for additional insights.
- Extend the analysis to include international comparisons.

### Source

https://health-infobase.canada.ca/covid-19/visual-data-gallery/

