Close-to-Expiration Markdown 

Data science project analysing markdown strategies for close-to-expiration products in grocery retail, with the objective of reducing waste while protecting gross margins.



Project Overview

Grocery retailers face a constant challenge when managing products approaching expiration. Applying markdowns too late can lead to waste, while applying them too early can unnecessarily reduce margins.

This project analyses historical sales and labelling data to identify the factors that influence the sale of close-to-expiration products and to support more effective markdown decisions.

The project was developed as part of the Data Science & Business Analytics programme at EDIT.



Business Objective

The main objective was to optimise the daily markdown process by finding the right balance between:

Reducing product waste
Increasing conversion rates
Protecting gross margins
Improving the efficiency of markdown operations
Dataset

The analysis was based on more than 150,000 historical labelled SKU records, combined with store-level information.

The data included information related to stores, products, prices, discounts, labelling dates, expiration dates and sales.



Data Preparation

The data preparation process included:

Handling missing values and inconsistencies
Feature extraction and transformation
Standardisation of discount values
Date and data type transformations
Outlier removal
Validation of labelling and sales dates
Feature engineering

Key engineered features included:

days_until_expiration
is_weekend_labelling
is_brand_2
Business Intelligence & Visualisation

A Power BI dashboard was developed to analyse the performance of the markdown strategy.

Key business metrics included:

Conversion Rate
Waste Rate
Total Revenue
Lost Revenue
Total Profit
Loss
Discount Cost
Avoided Loss

The analysis explored how markdown timing, discount levels, brands, store locations and store characteristics affected sales performance.




Store Segmentation

Stores were segmented according to:

Store size
Expiration risk
Average discount
Average margin

Four distinct operating profiles were identified, including stores with unusually high discounts applied significantly earlier than necessary.




Machine Learning

Classification models were developed to predict whether a labelled SKU would be sold.

The modelling process included:

Feature selection
Feature engineering
Hyperparameter tuning
Model evaluation

Random Forest and XGBoost were evaluated as classification approaches.

The selected Random Forest model achieved:

Metric	Score
Accuracy  0.69
Precision  0.69
Recall	0.69
F1-score  0.69
ROC-AUC	0.758
Key Findings



The analysis showed that:

Markdown timing has a stronger impact on conversion than simply increasing the discount.
Applying markdowns within approximately 24–48 hours before expiration can improve effectiveness.
A small number of brands account for a substantial proportion of losses.
Store location appears to have a greater impact on conversion than physical store size.
Increasing the number of labelled products does not necessarily result in higher sales.
Business Recommendations



The project proposed several actions:

Adjust purchasing volumes and replenishment cycles for the most critical brands.
Standardise the markdown window to approximately 24–48 hours before expiration.
Replace mass labelling with more selective labelling based on sell-through potential.
Prioritise high-conversion districts when allocating markdown stock.



Technologies & Tools

Python · Pandas · Scikit-learn · Power BI · DAX · Machine Learning · Data Analysis · Data Visualisation



Project Presentation

The complete project presentation is available here: PresentationMarkdownProgram_GitHub_SN.pdf



Project Context

Data Science & Business Analytics — EDIT.
Porto, Portugal · July 2026
