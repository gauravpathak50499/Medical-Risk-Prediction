#Medical-Risk-prediction
Medical-Risk-PredictionA machine learning project that estimates cardiovascular disease risk from patient clinical data and groups patients into Low, Moderate, and Severe risk tiers.


Overview

Cardiovascular disease is a leading cause of death worldwide, and early risk identification helps prioritize care. This project trains and compares several classifiers on the UCI Heart Disease dataset, selects the best performer, and converts its predicted probabilities into easy-to-interpret risk categories.

Dataset
Source: UCI Heart Disease Dataset
Size: 920 patient records
Features: demographic and clinical attributes such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, and ST depression
Target: presence of heart disease
Approach
Data preprocessing: handling missing values, encoding categorical variables, feature scaling
Exploratory analysis: distributions, correlations, class balance
Model training: Random Forest, Gradient Boosting, and SVM
Evaluation: compared using ROC-AUC (plus accuracy, precision, recall, F1)
Risk stratification: predicted probabilities mapped to Low / Moderate / Severe tiers
Results
Model	ROC-AUC
Random Forest	add score
SVM	add score
Gradient Boosting	0.8117

Gradient Boosting was selected as the final model.

Risk Tiers
Tier	Probability Range
Low	e.g. < 0.33
Moderate	e.g. 0.33 – 0.66
Severe	e.g. > 0.66


Tech Stack
Python
pandas, NumPy
scikit-learn
Matplotlib / Seaborn



Future Improvements
Hyperparameter tuning with cross-validation
Add SHAP-based explainability for individual predictions
Deploy as a Streamlit or Flask web app
Validate on additional external datasets
Disclaimer

This project is for educational purposes only and is not a substitute for professional medical diagnosis or advice.
pandas, NumPy
scikit-learn
Matplotlib / Seaborn
