# Lung Cancer Risk Modeling

## Overview
This project explores the impact of various risk factors and demographic variables on lung cancer incidences across U.S. states. Using multiple linear regression and random forest models, we analyze key predictors, such as smoking rates, socioeconomic status, and ethnicity, to better understand their contributions to lung cancer rates and improve predictive accuracy.

## Project Structure
- **Data**: Public datasets from the National Cancer Institute, Bureau of Economic Analysis, and other credible sources provide state-level information on lung cancer incidences, smoking rates, air quality, socioeconomic factors, and demographic statistics.
- **Models**: 
  - **Multiple Linear Regression**: Used for straightforward interpretation of significant factors and prediction of cancer incidence.
  - **Random Forest**: Applied for non-linear analysis, capturing complex interactions between variables.
- **Evaluation**: Cross-validation techniques (five-fold) are used to evaluate model accuracy based on metrics like RMSE, R-squared, and MAE.

## Key Findings
- **Top Predictors**: Smoking rates, Hispanic ethnicity, and education level show significant predictive power for lung cancer incidence.
- **Model Performance**: The multiple linear regression model achieved an R² of 0.74, while the random forest model showed an R² of 0.70, with RMSE values of 5.70 and 6.82, respectively.

