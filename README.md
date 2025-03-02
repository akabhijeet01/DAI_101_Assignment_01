# DAI_101_Assignment_01
Customer Churn Analysis - Insights & Findings
This analysis explores customer churn behavior in the Churn_Modelling dataset using Exploratory Data Analysis (EDA) and statistical techniques.

Key Findings:
Data Cleaning & Preprocessing:

Missing values in CreditScore were replaced with the mean.
HasCrCard null values were removed.
Outliers were detected using the Z-score and treated using Winsorization (capping extreme values at the 5th & 95th percentile).
Univariate & Bivariate Analysis:

Histograms & KDE plots showed that EstimatedSalary follows a uniform distribution.
Boxplots helped detect skewness in numerical variables.
Cross-tabulations revealed that active members churn less compared to inactive ones.
Multivariate Analysis:

Correlation heatmaps identified weak correlations between most numerical features.
Grouped analysis of IsActiveMember & HasCrCard showed that inactive members are more likely to churn.
Conclusion:
Customers with low credit scores and inactive accounts have a higher risk of churn.
Active customers tend to stay longer, making them a key retention target.
This analysis can help businesses design better marketing strategies to reduce customer attrition.
