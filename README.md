# Lead Scoring Case Study

## Project Overview
This project aims to help X Education, an online course provider, improve their lead conversion rate through the implementation of a lead scoring model. The goal is to identify the most promising leads, or "Hot Leads", that are most likely to convert into paying customers.

## Business Problem
X Education faces a low lead conversion rate of around 30%. The company wants to increase efficiency by focusing their sales efforts on the most potential leads. The target is to achieve a lead conversion rate of approximately 80%.

## Dataset
- The dataset contains about 9000 data points with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc.
- The target variable is 'Converted' (1 for converted, 0 for not converted).
- Data is at the customer level.

## Project Goals
1. Build a logistic regression model to assign a lead score between 0 and 100 to each lead.
2. Address additional problems presented by the company for future requirement changes.

## Approach
1. Data Understanding and Preparation
   - Perform data quality checks
   - Handle missing values and 'Select' levels in categorical variables
   - Create dummy variables where applicable
   - Derive new metrics if necessary

2. Exploratory Data Analysis (EDA)
   - Visualize distributions and relationships among variables
   - Analyze correlations

3. Feature Selection
   - Use techniques like Recursive Feature Elimination

4. Model Building
   - Implement Logistic Regression
   - Iterate and select the best features

5. Model Evaluation
   - Use metrics such as Accuracy, F1 Score, ROC-AUC, etc.

6. Model Prediction
   - Predict lead scores and verify model accuracy

## Deliverables
1. Jupyter Notebook with commented code
2. Word document with solutions to additional problems
3. Presentation summarizing the approach and results
4. 500-word summary report
5. This README file


