# Healthcare Insurance Analysis

## Overview

This project focuses on analyzing health and demographic factors that influence insurance claims. Using Python and data visualization techniques, the dataset was explored to uncover patterns and relationships between features like age, BMI, blood pressure, smoking status, and insurance claim amounts. 

## Objective

- Explore and analyze health and personal attributes to understand their impact on insurance claims
- Identify key factors associated with higher claim amounts
- Present meaningful insights through visualizations to support data-driven decisions

## Data Description

- Source : [Kaggle](https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health)
- Row : 1,340
- Columns : index, PatientID ,age, gender, bmi, bloodpressure, diabetic, children, smoker, region, claim

## Tools Used

- Python - Programming language
- Pandas - Data cleaning and analysis
- Matplotlb and Seaborn - Data visualizaton
- Jupyter Notebook - Interactive development environment

## Key Insights 

### Demographics
- Fewer men claim insurance below age 30 and above age 50.
- Most patients are between ages 18 and 60; insurance is rarely claimed by seniors or teenagers.
- Insurance claims are slightly higher in adults than young adults.
- 84.4% of claimants have fewer than three children; those with 2 or 3 children receive the highest claims — around 144,300 to 144,500 for adults and 16,000 to 16,500 for young adults, with 3 children slightly higher than others.

### Health Factors
- 81.8% of patients are overweight or obese, and obese individuals receive higher claims.
- Insurance claims increase with BMI for smokers.
- Smokers make up 20.4% of claimants and receive higher claims (around 32K).
- Most insurance holders have normal blood pressure.
- Individuals with blood pressure above 110 receive claims above 25,000; lower BP claims may depend on other factors like smoking.
- 47% of insurance claimants are diabetic, but diabetes does not significantly affect claim amount.

### Regional Trends & Claim Patterns
- The Southeast region has the highest total claims.
- The Northeast records the highest average claim: around 16K for males and 17K for females.
- Most individuals claimed between 1,000 and 20,000.

## Recommendations
- **Promote insurance among seniors** by offering tailored plans and targeted outreach, since no claims were observed above age 60.
- **Encourage healthy weight management** by providing wellness and fitness benefits, as overweight and obese individuals tend to claim higher amounts.
- **Support smoking cessation** through awareness programs and incentives, as smokers have significantly higher insurance claims .
- **Analyze high average claim costs in the Northeast** to understand the drivers and optimize regional policies accordingly.




