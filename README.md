# Data Professional Survey Breakdown

The dynamic Power BI dashboard presented here utilizes the preprocessed Data Professional Survey dataset to showcase various visualizations enhanced by descriptive statistics.

## Table of Contents
- [Business Problem](#business-problem)
  * [Objective](#objective)
  * [Goal](#goal)
- [Data Source](#data-source)
- [Power BI Viz link](#power-bi-viz-link)
- [Methods](#methods)
- [Tech Stack](#tech-stack)
- [Preliminary Analysis](#preliminary-analysis)
- [Types of Graphs](#types-of-graphs)
- [Quick Analysis of Results](#quick-analysis-of-results)
  * [Preview: Power BI Dashboard](#preview-power-bi-dashboard)
  * [Key findings](#key-findings)
  * [Limitations and Suggestions for Optimization of the Dashboard](#limitations-and-suggestions-for-optimization-of-the-dashboard)



## Business Problem

The BI/Analytics teams at my consulting firm have informed me that we acquired a new client. They require actionable insights and visualizations derived from the Data Professional Survey dataset to drive data-driven decision-making, gain a comprehensive understanding of the data professional landscape, and support strategic initiatives.

### Objective 

To create a Power BI dashboard that effectively communicates key findings and trends within the Data Professional Survey dataset, enabling the BI/Analytics teams to explore, analyze, and derive valuable insights. The dashboard should facilitate data-driven decision-making, resource allocation, and workforce planning related to data professionals.

### Goal

My goal is to deliver a visually appealing and interactive Power BI dashboard that provides the BI/Analytics teams with a comprehensive overview of the data professional landscape. The dashboard should highlight essential metrics such as job titles, programming languages used, salary trends, and job satisfaction. It should empower the teams to conduct in-depth analysis, identify patterns, and extract meaningful insights to support strategic decision-making, resource allocation, and talent management initiatives within the organization.

## Data Source
- [Github data source containing Data Professional Survey dataset](https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx)

## Power BI Viz link
- [Link to my dynamic Power BI visualization dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjA3OWZhYmYtYTdjYS00NmZhLTkwODAtY2FjNmEyY2EyZTE4IiwidCI6ImZkNjYyMzZhLWE2ZTAtNGJhOC1hMzFjLTA4MjQ3MzYwNDU3MyJ9)

## Methods
- Data visualization
- Descriptive statistics (mean, median and mode)

## Tech Stack
- Power BI

## Preliminary Analysis

The technique used here will compose of a data visualization and descriptive statistics, in place of an exploratory data analysis. The selection of these techniques are predicated upon the assumption that the data has already been preprocessed and normalized. This thereby eliminates the need to conduct a more thorough analysis. However, where this need does arise, a more in-depth technique and granular analysis will be performed that is conducive to the business goals, or financial objectives of the company. 

Here, a data visualization and descriptive statistical techniques can help to identify patterns and trends in the data, as well as any potential outliers or anomalies that may need further investigation.

#### All salary information derived from the different countries has been converted to US dollars ($) to standardize the data.

## Types of Graphs
- Bar Chart: Comparison of job titles among data professionals. There is also another bar chart comparing programming languages used by respondents.
- Pie Chart: Distribution describing the level of difficulty to break into data.
- Gauge chart: Visually displays the average happiness level on a scale. The chart provides an intuitive representation of the happiness level, helping to convey the overall sentiment for individuals in their respective role, taking into account factors such as work/life balance and salary.
- Tree Map: The treemap visualization below presents a hierarchical view of data, where each rectangle represents a country.


## Quick Analysis of Results
### Preview: Power BI Dashboard
![Image Alt Text](./PowerBIVizDataPro.png)

### Key findings
- The majority of the survey respondents come from the United States
- Data Scientists have the highest salary by job title
- The overall sentiment for work/life balance is above average at 5.74 on a 10 point scale

### Limitations and Suggestions for Optimization of the Dashboard
#### Data Quality and Accuracy:
- The accuracy and quality of the data in the dataset can impact the reliability and validity of the insights generated in the Power BI dashboard. 
- Since this was a self-administered online survey and there was no direct observation by a surveyor, some respondents may deliberately misrepresent their answers in the survey and/or may intentionally provide inaccurate or misleading answers. This may compromise the reliability and validity of the collected data.

#### Bias and Representativeness:
- The dataset used in the Power BI dashboard may have inherent biases or limitations in terms of its representativeness. 
- Most respondents were from the US so the data may balance in favour of the opinions and averages of US employees.

#### Scalability:
- Power BI dashboards may face performance challenges when dealing with large datasets or complex calculations. Depending on the dataset size and complexity, the performance of the dashboard may be affected, leading to slower loading times or limitations in interactivity.
