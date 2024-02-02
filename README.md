# A-Comprehensive-Regression-Analysis-for-Home-Price-Prediction

## STEPS FOR REGRESSION PREDICTIVE ANALYSIS
* **LOADING DATA**
  - Loading both train and test dataset and applying preprocessing steps together
****************************************************
* **SUMMARY OF DATA**
  - Total Samples
  - Total Features
  - Total Categorical Features
  - Total Numerical Features
  - Stats of Numerical Features
  - Value Count of Categorical Features
  - Unique Values DataFrame
  - Null Values DataFrame
************************************************
* **PREPROCESSING**
  - Drop Duplicates
  - Drop Columns with more than 80% null values
  - Drop uninformative columns
  - Drop Columns with single unique values
  - Inpute Null Values
  - Create New Features
  - Outlier Analysis and Removal
  - Drop Columns with single unique values again after outlier analysis
*********************************************
* **VISUALIZE**
  - Scatterplot of numerical features
  - Distribution of numerical features
  - BarCharts of categorical features
  - Box plots to check the outliers
**********************************************
* **FEATURE TRANSFORMATION**
  - Changing the distribution of numerical features to Gaussian (Normal)
*********************************************
* **ENCODING**
  - Some of the categorical features are nominal and some are ordinal. We need to encode them separately.
  - For ordinal features, we will do label encoding
  - For nominal features, we will do dummy encoding
**********************************************************
* **MODEL TRAINING & EVALUATION**
  - Perform Scaling
      - MinMax Scaling
      - Variance Scaling (Standard Scaler)
  - Fitting Different Regression Models
      - Linear Regression
      - Polynomial Regression (with interaction features)
      - Ridge Regression
      - Lasso Regression
      - SGD Regression
      - Elastic Regression
      - Bayesian Ridge
      - Huber Regression (robust to outliers)
      - RANSAC Regression (robust to outliers)
      - XGB Regressor
      - Ensemble Regressor
          - Random Forest
          - Gradient Boosting
          - AdaBoosting
          - Bagging Regressor
          - ExtraTreesRegressor
*****************************************
* **FEATURE SELECTION**

  - Selecting strong numerical features using Pearson’s Correlation Coefficient
  - Selecting strong categorical using ANOVA
*****************************************
* **FEATURE EXTRACTION**

  - Using PCA to perform dimensionality reduction.
  - Don't forget to scale your data before doing PCA.
************************************************
* **MODEL TRAINING & EVALUATION WITH STRONG FEATURES ONLY**

  - Using the same models as stated above.
*************************************************
* **CONCLUSION**

  - Which model performed the best one with using all the features or the one with the strong features only ?
************************************************
* **HYPERPARAMETER TUNING**

  - Tuning the parameters of the best model.
***************************************************
* **PREDICTION**

  - Prediction on the test dataset using the top scorer model
  - Saving the results in submission.csv
****************************************************
* **FEATURE ENGINEERING ANALYSIS**

  - Comparison of the scores of the different feature engineering steps.
**************************************************
* **RESULT ANALYSIS**

  - Analysis of the results given by the model.
*******************************************
* **STORY TELLING FROM THE RESULT ANALYSIS**

  - Simple interpretation of the results in layman language.
