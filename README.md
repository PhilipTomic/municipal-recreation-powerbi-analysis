# Municipal Recreation Programs Analysis (2018)

## Project Overview

This project investigates municipal recreation programming, seasonal scheduling patterns and planned registration capacities using municipal recreation data from 2018 and Microsoft Power BI.

The objective is to explore how recreation programming varies across seasons, facilities and activity categories through descriptive statistical analysis and interactive data visualization.

## Dashboard

### Municipal Recreation Programs Analysis

<img width="1274" height="710" alt="Municipal Recreation Programs Dashboard" src="https://github.com/user-attachments/assets/972e0dc8-41c3-42cf-8c9a-d47d2282ea88" />

### Statistical Analysis Dashboard

<img width="1276" height="711" alt="Statistical Analysis Dashboard" src="https://github.com/user-attachments/assets/d6055111-35aa-45e3-9246-1081fe36a282" />

## Research Objectives

- Examine seasonal variations in municipal recreation programming.
- Identify recreation facilities with the highest number of program records.
- Compare planned registration capacities across activity categories.
- Investigate differences in average program capacity across recreation facilities.
- Explore how recreation programming data can support scheduling and resource allocation decisions.
- Develop an interactive business intelligence dashboard to communicate analytical findings.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- Python
- Pandas
- SciPy
- Statsmodels
- DAX
- Descriptive Statistics
- Exploratory Data Analysis
- Business Intelligence
- Data Visualization
- Interactive Data Filtering

## Data Sources

- Publicly available municipal recreation program dataset (2018).
- Recreation program records containing facility locations, seasons, activity categories, program codes and maximum registration capacities.

## Methodology

### 1. Data Preparation and Transformation

- Imported municipal recreation program data into Microsoft Power BI.
- Organized relevant variables for recreation programming and capacity analysis.
- Structured program records by season, facility and activity category.
- Prepared the dataset for aggregation, comparison and interactive visualization.

### 2. Data Modelling and KPI Development

- Calculated the total number of recreation program records.
- Identified the number of distinct recreation locations.
- Calculated average maximum registration capacity.
- Aggregated program records by season and facility.
- Compared planned registration capacities across activity categories and locations.
- Developed interactive filters to support more detailed analysis.

### 3. Statistical Analysis

The following analytical methods were applied:

- **Descriptive Statistics:** Summarized recreation program records, facility coverage and average registration capacity.
- **Frequency Analysis:** Examined the distribution of recreation program records across seasons and facilities.
- **Arithmetic Mean:** Calculated average maximum registration capacities.
- **Comparative Analysis:** Evaluated differences in recreation programming and planned capacities across locations and activity categories.
- **Facility Benchmarking:** Compared recreation facilities based on program counts and average planned registration capacity.

### 4. Advanced Statistical Analysis

The second dashboard extends the exploratory analysis of 23,903 municipal recreation program records using statistical modelling and hypothesis testing.

#### Statistical Methods and Results

| Method | Result |
|---|---:|
| Mean Capacity | 14.16 |
| Median Capacity | 6 |
| Standard Deviation | 49.09 |
| Maximum Capacity | 6,000 |
| Pearson Correlation | 0.12 |
| Simple Regression R² | 0.01 |
| One-Way ANOVA | F = 162.80, p < 0.001 |
| Chi-Square Test | χ² = 3,185.97, p < 0.001 |
| Multiple Regression R² | 9.52% |
| Adjusted R² | 9.45% |

## Key Findings

| **Metric** | **Result** |
|---|---:|
| Total Recreation Program Records | 23,903 |
| Total Recreation Locations | 85 |
| Average Maximum Registration Capacity | 14.16 |

### Seasonal Recreation Programming

Summer recorded the highest number of recreation program records, followed by fall, spring and winter.

March Break recorded the lowest number of program records. However, differences in the duration of each seasonal period should be considered when interpreting these results.

### Recreation Facility Distribution

Erin Meadows Community Centre, Meadowvale Community Centre and River Grove Community Centre appear among the facilities with the highest number of recreation program records.

These differences demonstrate variations in recorded programming activity across recreation locations.

### Program Capacity and Activity Categories

Sport leagues demonstrate higher average planned registration capacities than drop-in activities and social activities in the displayed comparison.

These differences highlight variations in planned group sizes across recreation activity categories.

### Facility Capacity Benchmarking

Average maximum registration capacities vary across recreation locations, reflecting differences in the types and sizes of programs offered.

These findings provide an exploratory overview of planned recreation programming capacity rather than actual facility utilization.

### Key Statistical Findings

- Program hours have a weak positive linear relationship with planned registration capacity.
- Average planned capacity differs significantly across program types under the conventional ANOVA test.
- Program type and season demonstrate a statistically significant association.
- Program hours, season and program type collectively explain 9.52% of the variation in planned capacity.

## Business Applications

- Recreation program planning
- Seasonal resource allocation
- Facility capacity analysis
- Identification of unusual capacity records
- Data-driven operational decision-making

## Dashboard Features

### Page 1: Municipal Recreation Programs Analysis

- Three statistical KPI cards
- Interactive season filter
- Interactive program type filter
- Interactive recreation location filter
- Recreation programs by season column chart
- Program capacity by activity type bar chart
- Top recreation facilities by program count
- Average program capacity by location
- Detailed recreation program records table
- Interactive visual filtering

### Page 2: Statistical Analysis

- Six statistical KPI cards
- Program hours versus planned capacity scatter plot
- Linear regression trend line
- Pearson correlation analysis
- Coefficient of determination (R²)
- Average capacity by program type bar chart
- Program type distribution by season stacked column chart
- One-way ANOVA results
- Chi-square test of independence results
- Multiple regression analysis summary
- Extreme capacity values and program records table

## Limitations

- The analysis is limited to recreation program records from 2018.
- Maximum registration capacity represents planned capacity rather than actual attendance or participation.
- Program counts do not necessarily represent unique participants or individual program sessions.
- Differences in seasonal duration may influence comparisons of program counts.
- Facility operating costs, staffing levels and resource requirements are not included.
- The dataset does not establish actual program demand, occupancy or utilization rates.
- The findings are exploratory and have not been independently validated.

### Statistical Limitations

Extreme values, unequal group variances and small expected cell counts limit statistical inference. The findings are exploratory and do not establish causation. Planned registration capacity does not represent actual attendance or demand.

## Future Improvements

- Further outlier detection and investigation
- Seasonal programming trend analysis
- Integration of actual registration and attendance data
- Facility utilization and occupancy analysis
- Recreation programming demand forecasting
- Integration of municipal recreation budgets and operating costs
- Staffing and scheduling optimization
- Resource allocation and operational efficiency analysis

## Skills Demonstrated

- Business Intelligence
- Data Analytics
- Descriptive Statistical Analysis
- Exploratory Data Analysis (EDA)
- Data Preparation and Transformation
- Data Aggregation
- Comparative Analysis
- Frequency Analysis
- Facility Benchmarking
- KPI Development
- Interactive Dashboard Development
- Operational Analysis
- Analytical Problem-Solving
- Data Storytelling
- Pearson Correlation Analysis
- Hypothesis Testing
- One-Way ANOVA
- Chi-Square Test of Independence
- Multiple Linear Regression
- Statistical Modelling
- DAX Calculations

## Personal Project & Disclaimer

This project was developed in my spare time as part of my ongoing professional development and personal interest in data analytics, business intelligence and statistical analysis.

The project is intended for educational and portfolio purposes, allowing me to apply analytical techniques to real-world, publicly available datasets while strengthening my technical, statistical and problem-solving skills.

This project is not affiliated with, commissioned by, or endorsed by any municipality. The findings are exploratory and should not be interpreted as official statistics, validated predictions or policy recommendations.

## Author

**Philip Tomic**

Personal Data Analytics & Business Intelligence Portfolio

November 2026
