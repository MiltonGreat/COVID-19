# COVID-19 Data Analysis

## Overview

This project performs an extensive analysis of COVID-19 data in Canada, focusing on trends and insights derived from the data. The script processes the data, cleans it, and generates meaningful visualizations and summaries.

### EDA Questions

I want to answer the following questions:

1. What is the total number of COVID-19 cases reported in each province?
2. Which province has the highest average rate of COVID-19 per capita?
3. What is the average rate of COVID-19 deaths per capita?
4. What is the overall mortality rate of COVID-19 in Canada?
5. What is the mortality rate per province?
6. What are the total reported cases per year?
7. For each year in the dataset, find the month with the highest total number of cases.
8. For each year, find the month with the lowest total number of cases.
9. Which year had the highest mortality rate?
10. Which year had the lowest total number of cases?
11. Which year had the highest total number of cases?
12. In 2020, on which day did Quebec have the highest number of COVID-19 deaths?

### Dataset

The dataset used is `covid19-download.csv`, which contains COVID-19 case and death information across Canadian provinces over time. 

This dataset is obtained from the Government of Canada Public Health Infobase and contains information on daily reported COVID-19 cases as well as total COVID-19 deaths in all provinces of Canada.

Key columns include:

- `prname`: Province name
- `date`: Reporting date
- `totalcases`: Total reported cases
- `numdeaths`: Number of reported deaths
- Other columns capturing rates and demographic information

### Visualizations

- **Bar Chart:** Total cases by province.
- **Line Plot:** Total reported cases per year.
- **Heatmap:** Cases by month and year.
- **Rolling Averages:** 7-day averages for cases and deaths.

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

### Key Findings
      
- Total Number of Cases per Province: Ontario had the highest number of total COVID-19 cases (~223.5 million), followed by Quebec (~185.7 million). Nunavut reported the fewest cases (~6.4 million).
- Rate of Cases per Capita: Prince Edward Island had the highest average rate of COVID-19 cases per capita (15,328.76), while Quebec and Alberta also had high rates (8,916.04 and 8,436.12, respectively).
- Average Rate of Deaths per Capita: Quebec experienced the highest rate of COVID-19 deaths per capita (151.45), while Nunavut had the lowest (11.66).
- Overall Mortality Rate: The overall mortality rate of COVID-19 in Canada was 1.24%.
- Yearly Trends: The year with the highest total cases was 2023 (~244.5 million), while 2020 had the fewest (~6.5 million cases). The yearly mortality rate decreased from 5.12% in 2020 to 1.18% in 2024.
- Monthly Trends: The month with the highest total cases varied by year, with December 2023 reporting 24.3 million cases. February 2020 had the lowest monthly case total (52 cases).
- Quebec in 2020: December 26, 2020, was the deadliest day in Quebec, with 7662 deaths.

### Insight:

- The number of reported COVID-19 cases consistently increased over time, with 2024 showing the highest total number of cases. This can be attributed to the delayed identification of cases or large outbreaks in specific regions.
- December was the month with the highest cases across most years, which could suggest that colder weather or holiday-related gatherings contributed to the spread.

### Real-World Implications:

- The high mortality rate in Quebec (1.25%) suggests that healthcare infrastructure in this province may have faced significant strain, especially during peak months like December 2020.
- Provinces with lower per capita case rates, like Newfoundland and Labrador, could serve as case studies for public health interventions that successfully curbed the spread of the virus.
- The steady rise in cases across all provinces during colder months indicates that government-imposed restrictions and public awareness campaigns should be intensified in winter.

### Future Work

- Include regional breakdowns within provinces.
- Incorporate vaccination data for additional insights.
- Extend the analysis to include international comparisons.

### Source

Dataset: [Government of Canada Public Health Infobase on Kaggle](https://health-infobase.canada.ca/covid-19/visual-data-gallery/)
