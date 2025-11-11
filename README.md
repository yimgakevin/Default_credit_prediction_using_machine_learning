Credit Default Risk Modeling – Binary Classification

🎯 Project Objectives

- Build a robust binary classification model to identify customers at risk of payment default.

- Analyze explanatory factors influencing this risk to better understand business drivers.

- Rigorously evaluate model performance and provide reliable local and global interpretation of predictions.

🏢 Business Problem

A financial company wants to anticipate customer payment defaults based on their characteristics (payment history, credit amount, employment status, etc.). The goal is to develop an accurate predictive model to identify risky customers, optimize collection strategies, and improve credit portfolio management.

🛠️ Skills Developed

- Mastery of logistic regression via statsmodels for rigorous statistical modeling and hypothesis testing.

- Implementation and hyperparameter tuning of boosting algorithms (LightGBM, XGBoost) using GridSearchCV and RandomizedSearchCV.

- Use of Random Forest for classification, with and without hyperparameter optimization.

- Application of advanced interpretability methods LIME and SHAP for local and global model explanation.

- Comprehensive performance evaluation with confusion matrices, ROC curves, AUC, and classical metrics (precision, recall, F1-score).

📂 Data

Dataset: Credit Card Default Dataset

Source: Kaggle
https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

Description: Customer data including payment history, credit limits, demographics, etc.

📝 Project Steps

1️⃣ Data Preparation

- Import and initial exploration of the dataset.

- Data quality checks (handling missing values, outlier detection and treatment, variable typing).

- Class balancing using oversampling, undersampling, and SMOTE techniques to address natural imbalance.

2️⃣ Modeling

a) Logistic Regression with Statsmodels

Rigorous selection of relevant explanatory variables.

Construction of a statistical model, interpretation of coefficients, and validation of assumptions (linearity, absence of multicollinearity, significance tests, detection of outliers, autocorrelation).

b) Boosting Models

- Implementation of LightGBM and XGBoost algorithms.

Hyperparameter optimization via exhaustive (GridSearchCV) and random search (RandomizedSearchCV).

c) Random Forest

Modeling with Random Forest and comparison of results with and without hyperparameter tuning.

3️⃣ Performance Evaluation

- Detailed analysis of confusion matrices (false positives, false negatives).

- Calculation and interpretation of metrics: precision, recall, F1-score.

- Plotting ROC curves and computing AUC to assess discriminative ability.

4️⃣ Model Interpretation

- Use of LIME for local, instance-level explanations.

- Use of SHAP for global interpretation and visualization of variable impacts.

📊 Key Visualizations

- Histograms of payment defaults by customer segments.

- Heatmaps of correlations between explanatory variables.

- Comparative ROC curves for all models.

- Regression coefficient plots to describe influential factors.

- LIME and SHAP plots illustrating variable importance at local and global levels.

📢 Conclusions & Recommendations

- Identification of the riskiest customer profiles with key explanatory variables.

- Assessment of model robustness and suitability for operational use.

 - Suggestions for future improvements: enriching the dataset, calibrating classification thresholds, integrating new explanatory variables.
