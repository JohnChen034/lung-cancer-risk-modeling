# Lung Cancer Risk Modeling

## Overview
This project explores the impact of various risk factors and demographic variables on lung cancer incidences across U.S. states. Using multiple linear regression and random forest models, we analyze key predictors, such as smoking rates, socioeconomic status, and ethnicity, to better understand their contributions to lung cancer rates and improve predictive accuracy.

##Abstract. 
Lung cancer has been the leading cause of cancer deaths worldwide since the spread of smoking and the decline in air quality. This paper analyzes the risk factors and demographic variables that contribute to lung cancer incidences in the United States. Risk factors include smoking and environmental pollution, while demographic variables include education, income level, age group, and ethnicity. Multiple linear regression model and random forest model are used for variable interpretation and lung cancer prediction. In the model evaluation, the multiple linear regression model is found with better prediction accuracy than the random forest model by using cross-validation with resampling. The random forest model has 6.82, 0.70, and 5.21 of RMSE, R squared, and MAE, while the multiple linear regression model has 5.70,  0.74, and 4.70. Smoking is the most contributing risk factor based on the result, and the most significant demographic variables are Hispanic and high school education proportions. The discussion section includes the interpretation of the groups of variables, potential limitations in the models, and the future direction of finding deeper correlations between lung cancer incidences and the selected risk and demographic variables. This analysis illustrates the importance of demographic variables in cancer and shows more directions for research on demographic variables.

### Keywords: lung cancer, random forest model, linear regression, smoking, socioeconomic status (SES).


## Project Structure
- **Data**: Public datasets from the National Cancer Institute, Bureau of Economic Analysis, and other credible sources provide state-level information on lung cancer incidences, smoking rates, air quality, socioeconomic factors, and demographic statistics.
- **Models**: 
  - **Multiple Linear Regression**: Used for straightforward interpretation of significant factors and prediction of cancer incidence.
  - **Random Forest**: Applied for non-linear analysis, capturing complex interactions between variables.
- **Evaluation**: Cross-validation techniques (five-fold) are used to evaluate model accuracy based on metrics like RMSE, R-squared, and MAE.

## Key Findings
- **Top Predictors**: Smoking rates, Hispanic ethnicity, and education level show significant predictive power for lung cancer incidence.
- **Model Performance**: The multiple linear regression model achieved an R² of 0.74, while the random forest model showed an R² of 0.70, with RMSE values of 5.70 and 6.82, respectively.

