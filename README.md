# Statistical Analysis on Cancer Patients Data in Python

## Introduction
This repository presents a comprehensive statistical analysis of cancer patients' data, focusing on lung cancer. 
The dataset includes information on 899 patients, uniquely identified by a patient ID. The goal is to identify significant risk factors and their impact on different levels of lung cancer.

## Data Description
The dataset includes a 'Level' column indicating the severity of cancer (low, medium, or high) and 21 risk factors scored on a scale of 1 to 9. 
After addressing data quality issues, the analysis explores the 'Level' column and eight relevant risk factors.

# Exploratory Data Analysis
## Summary Statistics
Descriptive statistics for risk scores are provided, including box plots illustrating the skewed distribution of the data.

## Normality Check
A Kolmogorov-Smirnov test was performed, revealing that the risk factor scores do not follow a normal distribution for all levels of cancer.

## Correlation Analysis
A heatmap highlights correlations between risk factors and identifies relevant independent variables.

# Regression Analysis
## Hypothesis
The hypothesis is that the combined risk factor scores significantly influence the likelihood of different levels of lung cancer.

## Regression Model Assumptions
'Level' is an ordered categorical variable (1 to 3).
Predictor variables (risk factor scores) are ordinal.
Proportional odds assumption is maintained.
Multicollinearity is addressed.
Logistic Ordinal Regression
The relationship between risk factors and 'Level' is modeled using ordinal logistic regression. The model's goodness of fit is assessed, and coefficients are interpreted.

## Results
Coefficients and p-values suggest a significant relationship between risk factors and cancer levels.
Odds ratios indicate the odds of being in high levels vs. combined low and medium levels are significantly higher.
Predicted Probabilities
Using cumulative logistic regression, predicted probabilities for high-level cancer are calculated for sample patients.

# Conclusion
# Findings
Identified risk factors significantly influence different levels of lung cancer.
Reduction in these factors may lower the overall risk and severity of lung cancer.
Individualized assessments based on risk factor scores can aid in early detection and intervention.

# Recommendations
Public health campaigns targeting modifiable risk factors are crucial.
Recommendations include avoiding secondhand smoke, maintaining a healthy weight, limiting alcohol consumption, and ensuring adequate sleep.
