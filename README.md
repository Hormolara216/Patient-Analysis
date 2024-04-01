# Patient-Analysis

## Project Overview:
This Power BI project aims to analyze and track the current status of patient waiting lists, focusing on both Inpatient and Outpatient categories. By leveraging historical data spanning from 2018 to 2021, the project offers insights into monthly trends, detailed specialty-level analysis, and age profiles of patients on the waiting list.

## Project Goals:
1. **Track current status of patient waiting list:** Monitor and visualize the current status of the patient waiting list to identify trends and fluctuations.
2. **Analyze historical monthly trend of waiting list:** Analyze historical data to understand monthly trends in both Inpatient and Outpatient waiting lists.
3. **Detailed specialty level & age profile analysis:** Provide granular analysis by specialty and age to identify patterns and demographics of patients on the waiting list.

## Data Scope:
- **Time Frame:** 2018 - 2021

## Metrics Required:
1. **Average & Median Waiting List:** Calculate and visualize the average and median waiting times for patients.
2. **Current Total Wait List:** Display the current total number of patients on the waiting list.

## Views Required:
1. **Summary Page:** Provide an overview of key metrics and trends at a glance.
2. **Detailed Page for Granular Analysis:** Offer detailed insights with drill-down capabilities for specialty-level and age-profile analysis.

## Dashboards
*Summary view*
![Summary](https://github.com/Hormolara216/Patient-Analysis/blob/main/Summary%20view.png?raw=true)

*Detailed view*
![Detailed](https://github.com/Hormolara216/Patient-Analysis/blob/main/Detailed%20view.png?raw=true)

# DAX Measures Used:
1. **CALCULATE:** Utilized to modify or filter the context in which a calculation is made.
2. **SUM:** Employed to calculate the sum of values in a column or a table to obtain the total wait list.
3. **SWITCH:** Used for conditional logic to dynamically display titles based on selected calculation methods.
4. **ISBLANK:** Employed to check whether a value is blank and replace it with a specified value after filters are applied.
5. **EDATE:** Used to calculate the date of the previous month of wait list update, providing a reference for analysis.

