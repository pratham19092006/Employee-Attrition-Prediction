# Employee Attrition Prediction

A machine learning project to predict whether an employee is likely to leave the company using the IBM HR Analytics dataset. The objective is to help organizations retain talent by identifying key attrition drivers and proactively managing employee engagement.

---

## Dataset

- *Source*: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- *Format*: CSV
- *Features*: Demographic, work-related, and satisfaction-related attributes of employees
- *Target*: Attrition (Yes / No)

---

## Problem Statement

To develop a supervised machine learning model that classifies whether an employee will leave the organization based on historical HR data. This will help HR departments make data-driven decisions to reduce turnover.

---

## Objectives

- Load and preprocess the IBM HR dataset
- Build classification models (Logistic Regression, Random Forest, SVM)
- Evaluate models using accuracy, precision, recall, F1-score, and confusion matrix
- Visualize feature importance to identify key drivers of attrition

---

## Tech Stack

- *Language*: Python
- *Libraries*:
  - pandas
  - numpy
  - scikit-learn
  - seaborn
  - matplotlib

---

## Methodology

1. *Data Preprocessing*
   - Handle missing values
   - Encode categorical variables (one-hot encoding)
   - Normalize features using StandardScaler
   - Split into train/test sets

2. *Model Training*
   - Train Logistic Regression, Random Forest, and SVM classifiers
   - Tune hyperparameters (if necessary)

3. *Model Evaluation*
   - Evaluate using classification metrics: accuracy, precision, recall, and F1-score
   - Generate and visualize the confusion matrix
   - Plot feature importance (especially for Random Forest)

---

## Results

- Random Forest classifier showed the best performance
- Key features influencing attrition:
  - OverTime
  - JobSatisfaction
  - YearsAtCompany
  - EnvironmentSatisfaction
  - WorkLifeBalance

---

## Conclusion

The model effectively predicts employee attrition and identifies critical factors contributing to it. The insights can be used by HR departments to implement targeted retention strategies. Further improvements can be made using advanced ensemble techniques and addressing class imbalance issues.

---

## References

- scikit-learn documentation: https://scikit-learn.org/
- pandas documentation: https://pandas.pydata.org/
- seaborn visualization: https://seaborn.pydata.org/
- Dataset source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
