# CodeAlpha - Unemployment Analysis with Python

## Project Overview
This project is part of my **CodeAlpha Data Science Internship**.
The project focuses on analyzing unemployment rate data in India using Python. The analysis includes data cleaning, exploratory data analysis, regional comparison, monthly trends, COVID-19 impact analysis, and data visualization.

## Objectives
- Analyze unemployment rates in India
- Clean and prepare the unemployment dataset
- Compare unemployment rates across different regions
- Analyze unemployment trends over time
- Study the impact of COVID-19 on unemployment
- Identify monthly unemployment patterns
- Identify periods and regions with higher unemployment
- Provide useful policy insights

## Dataset
Two datasets were used in this project.

### 1. Unemployment in India
This dataset contains unemployment information for different regions of India.
Main columns include:
- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

### 2. Unemployment Rate During COVID-19
The second dataset was used to analyze unemployment during the COVID-19 period.
Important columns include:
- Region
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib

## Project Workflow
### 1. Load the Dataset
The unemployment datasets were loaded using Pandas.

### 2. Data Cleaning
The datasets were checked and prepared for analysis.
The following steps were performed:
- Checked column names
- Removed unnecessary spaces from column names
- Checked missing values
- Removed missing records
- Checked duplicate records
- Removed duplicate records
- Converted the Date column into the proper date format

### 3. Exploratory Data Analysis
Basic statistical and descriptive analysis was performed to understand the unemployment data.
The overall average unemployment rate was calculated.

### 4. Regional Analysis
The average unemployment rate was calculated for each region.
A bar chart was created to compare unemployment rates across different regions.

### 5. Unemployment Trend Analysis
The unemployment rate was analyzed over time.
A line chart was created to identify changes and trends in unemployment rates.

### 6. COVID-19 Analysis
The second dataset was used to analyze unemployment during the COVID-19 period.
A line chart was created to visualize changes in unemployment during this period.

### 7. Monthly Analysis
The unemployment rate was analyzed month-wise.
A line chart was created to identify monthly unemployment patterns.

## Data Visualizations
The project contains the following visualizations:

### 1. Average Unemployment Rate by Region

A **bar chart** was created to compare the average unemployment rate across different regions of India.

### 2. Unemployment Rate Trend
A **line chart** was created to show the unemployment rate trend over time.

### 3. Unemployment Rate During COVID-19
A **line chart** was created to analyze changes in unemployment rates during the COVID-19 period.

### 4. Monthly Unemployment Rate Pattern
A **line chart** was created to compare the average unemployment rate across different months.
These visualizations help in understanding regional differences, overall trends, COVID-19 impact, and monthly unemployment patterns.

## Key Findings
- The average unemployment rate in the dataset was approximately **11.79%**.
- Unemployment rates varied significantly across different regions.
- The COVID-19 period showed a significant increase in unemployment.
- **May** had the highest average monthly unemployment rate at approximately **24.52%**.
- **November** had the lowest average monthly unemployment rate at approximately **8.14%**.
- Tripura had one of the highest average unemployment rates among the regions analyzed.
- Sikkim had one of the lowest average unemployment rates among the regions analyzed.

## Policy Insights
- Regions with higher unemployment rates may need targeted employment-generation programs.
- Skill development and training programs can be focused on areas with higher unemployment.
- The changes observed during the COVID-19 period show the importance of emergency employment and financial support during major economic disruptions.
- Monthly variations can help policymakers plan employment-support programs during periods of higher unemployment.
- Rural and urban areas can be considered separately when designing employment policies.

## Conclusion
The analysis identified differences in unemployment rates across regions and months and showed significant changes during the COVID-19 period.
The visualizations helped understand regional differences, unemployment trends, monthly patterns, and the impact of COVID-19.
These findings can help policymakers focus on employment generation, skill development, and financial support programs for highly affected regions and periods.

## Files in this Repository
- `CodeAlpha_Unemployment_Analysis.ipynb` - Jupyter Notebook containing the complete analysis, code, outputs, and visualizations
- `Unemployment in India(1).csv` - Main unemployment dataset
- `Unemployment_Rate_upto_11_2020(1).csv` - COVID-19 unemployment dataset
- `README.md` - Project documentation

## Internship
This project was completed as part of my **CodeAlpha Data Science Internship**.
