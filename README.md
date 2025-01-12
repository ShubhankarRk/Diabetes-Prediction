# Diabetes-Prediction
This project focuses on predicting diabetes in women using machine learning models. Leveraging a dataset of medical records, the project aims to identify individuals at risk of diabetes based on features such as glucose levels, blood pressure, BMI, and more. By employing advanced algorithms, we aim to improve early detection and prevention.

# Features:
Dataset Analysis: Comprehensive exploration and preprocessing of a dataset containing 2000 records with 9 attributes.

Machine Learning Models: Implementation of various models including Logistic Regression, SVM, KNN, Random Forest, and Naive Bayes.

Evaluation Metrics: Models are evaluated using metrics like accuracy, precision, recall, sensitivity, specificity, and ROC-AUC.

Categorical Insights: Categorization of attributes like BMI and blood pressure for better interpretability.

# Technologies Used:

Python Libraries: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning Frameworks: Scikit-learn

# Key Results:

## Model Performance:

Random Forest emerged as the best-performing model with an accuracy of 97.67%, ROC-AUC of 0.971, sensitivity of 95.7%, and specificity of 98.5%.

KNN achieved an accuracy of 82.83% and ROC-AUC of 0.814, showing strong performance among non-ensemble methods.

Logistic Regression provided interpretable results but had lower accuracy (81%) compared to ensemble methods.

## Feature Insights:
Glucose levels showed the strongest correlation with diabetes outcomes (r = 0.46).

BMI was another significant predictor (r=0.28), emphasizing its role in diabetes risk assessment.

## Categorization Findings:

Patients categorized as "Overweight" or "Obese" based on BMI showed a higher prevalence of diabetes.

Blood pressure categorization revealed that individuals with "Stage 2 Hypertension" were more likely to have diabetes.

These findings highlight the effectiveness of Random Forest in identifying at-risk individuals while emphasizing the importance of clinical features like glucose levels and BMI for prediction tasks.
