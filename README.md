# COVID-19 Data Analysis Report

## 1. Executive Summary

This report analyzes COVID-19 data from WHO 2019. Using Excel, SQL, and Power BI, we assess trends in infection and mortality rates across various countries and WHO regions, providing actionable insights for public health interventions.

## 2. Introduction

### 2.1 Background

The COVID-19 pandemic has resulted in significant global health challenges. Analyzing case and death data is crucial for understanding the impact and guiding response strategies.

### 2.2 Objectives:
1.	To track and analyze the spread of COVID-19, identifying its trends and patterns.
2.	Develop predictive models to forecast infection rates and mortality.
3.	Evaluate the effectiveness of public health interventions and policies.
4.	Create interactive dashboards for stakeholders, policymakers and general public.
### 2.3 Scope:
1.	Data collection: Aggregate data from reputable source (WHO) World Health Organization.
2.	Data analysis: Apply statistical techniques to identify key insights.
3.	Data visualization: Develop interactive dashboards and reports to communicate findings.

## 3. Methodology

### 3.1 Data Sources

Data was collected from WHO.

### 3.2 Dataset Overview

The dataset includes the following columns:

- Name of Countries
- WHO Regions
- Cumulative Cases Total
- Cumulative Cases within Last 7 Days
- Cumulative Cases within Last 24 Hours
- Cumulative Cases within 7 Days per 100,000 Population
- Cumulative Cases within 100,000 Population
- Cumulative Deaths Total
- Cumulative Deaths within Last 7 Days
- Cumulative Deaths within Last 24 Hours
- Cumulative Deaths within 7 Days per 100,000 Population
- Cumulative Deaths within 100,000 Population

### 3.3 Analytical Tools

- **Excel**: Data cleaning and preliminary statistical analysis.
- **SQL**: Querying and aggregating data for specific insights.
- **Power BI**: Visualization of trends and interactive dashboards.

### 3.4 Analytical Techniques

- Descriptive statistics to summarize key metrics.
- Time series analysis for trend identification.
- Comparative analysis using SQL to segment data by WHO regions and countries.
- Data visualization in Power BI for clearer insights.
- 
 Data format:  CSV (Comma separated value
  ### 4. Data Cleaning
  
 Data cleaning and preprocessing performed to handle missing values and inconsistencies.
 


## 5. Findings

### 5.1 Infection Rates

- **Cumulative Cases Total**: The NA Region had the highest total cases of COVID-19, with 6386504 cases.
- **Prevalence per Population**: Europe recorded the highest prevalence per 100,000 population.
- **Country Insights**: Vietnam exhibited the highest prevalence per 100,000 population.

### 5.2 Recent Trends

- **Cases in the Last 7 Days**: The NA Region had the highest recorded cases within the last 7 days, totaling.
- **Cases per 100,000 Population**: The Western Pacific Region showed the highest cases within 7 days per 100,000 population.
- **Incidence Rates**: Vietnam had the highest incidence of COVID-19 both within the last 7 days and the last 24 hours.

### 5.3 Mortality Rates

- **Cumulative Deaths**: The America Region had the highest mortality rates, with cumulative deaths.

### 5.4 Visualizations

Power BI dashboards provided insights into trends over time, highlighting peak infection days and corresponding mortality rates.

## 6. Discussion

### 6.1 Interpretation of Findings

The NA Region's high total cases suggest ongoing transmission dynamics that require targeted intervention. Europe’s high prevalence per 100,000 indicates potential underreporting or increased testing efforts. Vietnam's rising cases reflect an urgent need for enhanced public health measures.

### 6.2 Limitations

- Potential inconsistencies in reporting across countries may affect data accuracy.
- The analysis relies on the availability of up-to-date demographic data.

## 7. Conclusions

### 7.1 Summary of Key Insights

High cumulative cases in the NA Region and high prevalence in Europe and Vietnam necessitate focused public health strategies. The America Region’s elevated mortality rates highlight the need for comprehensive healthcare support.

### 7.2 Recommendations

1. **Targeted Public Health Campaigns**: Implement targeted awareness and vaccination campaigns in regions with high case rates, particularly in the NA and Europe.
2. **Enhanced Testing and Reporting**: Encourage comprehensive testing in Vietnam and similar countries to ensure accurate data reporting and timely interventions.
3. **Healthcare Resource Allocation**: Allocate healthcare resources and support to the America Region to address the high mortality rates effectively.

### 7.3 Suggestions for Future Research

- Investigate the effectiveness of vaccination strategies and public health interventions in regions with high prevalence.
- Monitor emerging variants and their impact on case and mortality trends, utilizing SQL for data extraction and analysis.
