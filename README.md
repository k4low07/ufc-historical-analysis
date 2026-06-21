# UFC Historical Fight Analysis

## Project Overview

This project analyzes historical UFC fight data using Excel, Power Query and Linear Regression.

The objective was to answer business questions regarding UFC history, identify trends in fighter performance and determine which strike type is the strongest predictor of significant strikes landed.

## Tools Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Data Visualization
- Linear Regression

## Data Sources

The analysis was performed using three datasets:

- UFC Fights
- UFC Fighters
- UFC Locations

## Data Preparation

The following data transformations were performed:

- Removal of duplicate records
- Standardization of weight class names
- Merging datasets
- Conversion of imperial units to metric units
- Calculation of fighter age on fight day
- Creation of winner identification column
- Creation of fight year variable

## Key Findings

### UFC History

- 2122 unique fighters competed in UFC.
- UFC organized 555 events.
- Las Vegas hosted the largest number of events (152).

### Weight Divisions

Most active divisions:

1. Lightweight – 1056 fights
2. Welterweight – 1050 fights
3. Middleweight – 788 fights

### Top Fighters

Top 3 fighters by victories:

1. Donald Cerrone – 23 wins
2. Demian Maia – 22 wins
3. Jim Miller – 21 wins

### Fight Outcomes

Most common fight endings:

- Decision - Unanimous
- KO/TKO
- Submission

### Statistical Analysis

Research Question:

Which strike type is the strongest predictor of significant strikes landed?

Model:

sig_str = β0 + β1(head) + β2(body) + β3(leg)

Results:

- R² = 0.75
- Head strikes were the strongest predictor of significant strikes landed.

## Limitations

- Some fighters had missing birth dates.
- The regression model was built only for red-corner fighters.
- Historical records may contain incomplete information.

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Linear Regression
- Business Insight Generation
