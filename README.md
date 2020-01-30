# Predicting Customer Churn

## Project Overview
This project predicts likelihood of customer churn for a fake music streaming service using Spark and Python.  See this blog post for more in depth information regarding approach, structure, and outcomes.

## File Descriptions 
-Sparkify_Prelim_Notebook:  Notebook used for initial EDA to understand the data available and customer behavior
-Sparkify_Modularized:  Notebook adapted to production level code structure.  Builds pipeline to load, process, model, and evaluate.
-mini_sparkify_event_data.json: Raw data file used for the above two notebooks

## Problem Statement
The music streaming company, Sparkify, wants to identify customers who are likely to churn so they can take proactive retention measures to keep their business.

## Evaluation Metrics
Evaluation metrics used include F1, accuracy, precision, and recall.  Feature importance plots were also used when possible to assess which features most contributed to churn-related outcomes.  See the blog post for a more in-depth overview.

## Next Steps
With more time, I'd love to:
-add more engineered features, such as ratios or last 7 days behavior counts to flag more recent changes in customer interaction with the company
-model using balanced classes to see if and to what degree that may influence predictive behavior of the models



