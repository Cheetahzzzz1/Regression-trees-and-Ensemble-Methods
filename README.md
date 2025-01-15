# Regression Trees and Ensemble Methods

# Overview

The objective of this project is to compare different machine learning models for regression analysis. Specifically, we analyze:

1. A regression tree for understanding feature importance and basic prediction.

2. Ensemble methods such as Bagging, Random Forest, and XGBoost for improving predictive performance.

3. Performance metrics such as Mean Squared Error (MSE) to evaluate the models.

# Dataset Description

The dataset used in this project contains predictor and response variables for regression analysis. Key features include:

1. **Price** : Numerical feature indicating product price.

2. **ShelveLoc** : Categorical feature indicating shelf location (Good, Medium, Bad).

3. **Advertising** : Numerical feature indicating advertising expenditure.

4. **Age** : Numerical feature indicating the product age.

The dataset is preprocessed for categorical encoding and normalization.

# Methodology

<ins> Data Preprocessing </ins>

1. Handle missing values.

2. Normalize numerical features.

3. Encode categorical features using one-hot encoding.

<ins> Model Implementation </ins>

1. Regression Tree : Provides insights into feature importance and predictions.

2. Bagging Regressor : Reduces variance and improves accuracy.

3. Random Forest : Uses multiple decision trees amd offers feature importance analysis.

4. XGBoost : Employs gradient boosting for optimal performance.

<ins> Evaluation </ins>

1. Test models on the test set.

2. Compare MSE values for performance assessment.

# Models and Results

**1. Regression Tree**

1. Test MSE : 4.99498

2. Provides a simple, interpretable tree structure.

**2. Bagging Regressor**

1. Test MSE : 2.53525

2. Combines predictions of multiple trees to reduce variance.

**3. Random Forest**

1. Test MSE : 2.54512

2. Top Features:
     1. Price (31.47%)
  
     2. ShelveLoc_Good (19.49%)
  
     3. Age (12.72%)
  
**4. XGBoost**

1. Test MSE : 2.25371

2. Outperforms other models in terms of accuracy.

# Dependencies

1. pandas

2. numpy

3. matplotlib

4. scikit-learn

5. xgboost

# Conclusion

This project demonstrates the power of ensemble methods in regression tasks. XGBoost emerges as the best performing model, achieving the lowest MSE. The analysis highlights the importance of feature selection and advanced modeling techniques to achieve high predictive accuracy.
