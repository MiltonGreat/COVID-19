# COVID-19

### Summary and Recommendations

#### 1. Overview

This project performs exploratory data analysis (EDA) on a COVID-19 dataset using Python. The aim is to investigate key trends and statistics such as the total number of cases, mortality rates, and provincial variations in the impact of the pandemic. The questions asked include the following:

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
  12. In 2020, on which day did Quebex have the highest number of COVID-19 deaths?

#### 2. Data

This dataset is obtained from the 'Government of Canada Public Healht Infobase' and contains information on daily reported COVID-19 cases as well as total COVID-19 deaths in all provinces of Canada. The data contained in the table describes COVID-19 in Canada in terms of number of cases and deaths at the provincial and national levels from January 31, 2020 to present time. You will be working with the `covid19-can.csv` file located in the `Data` folder.

#### 3. Exploratory Data Analysis Process
   
  1. Data Loading
  2. Handling Missing Data
  3. Date Handling
  4. Province-Level Data Aggregation
  5. Exploratory Data Analysis
      - Total Cases by Province
      - Rate of Cases per Capita
      - Mortality Rate
      - Yearly Analysis
      - Quebec in 2020
#### 4. Key Findings
      
- Total Number of Cases per Province: Ontario had the highest number of total COVID-19 cases (~223.5 million), followed by Quebec (~185.7 million). Nunavut reported the fewest cases (~6.4 million).
- Rate of Cases per Capita: Prince Edward Island had the highest average rate of COVID-19 cases per capita (15,328.76), while Quebec and Alberta also had high rates (8,916.04 and 8,436.12, respectively).
- Average Rate of Deaths per Capita: Quebec experienced the highest rate of COVID-19 deaths per capita (151.45), while Nunavut had the lowest (11.66).
- Overall Mortality Rate: The overall mortality rate of COVID-19 in Canada was 1.24%.
- Yearly Trends: The year with the highest total cases was 2023 (~244.5 million), while 2020 had the fewest (~6.5 million cases). The yearly mortality rate decreased from 5.12% in 2020 to 1.18% in 2024.
- Monthly Trends: The month with the highest total cases varied by year, with December 2023 reporting 24.3 million cases. February 2020 had the lowest monthly case total (52 cases).
- Quebec in 2020: December 26, 2020, was the deadliest day in Quebec, with 7662 deaths.

#### 5.  Source

https://health-infobase.canada.ca/covid-19/visual-data-gallery/

