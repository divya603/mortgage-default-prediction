# Mortgage Default Prediction using Machine Learning

This project explores the use of machine learning models, particularly XGBoost and Decision Trees, to predict mortgage loan defaults. The focus was to enhance recall for identifying defaulted loans while maintaining overall accuracy. 

---

## Project Overview
Loan defaults pose significant risks in the financial industry, affecting banks, hedge funds, and investment strategies. This project tackles this challenge by:
1. Using a **Decision Tree** as a baseline model.
2. Implementing **XGBoost** to achieve superior performance.
3. Leveraging **SMOTE** for class balancing and **GridSearchCV** for hyperparameter optimization.

### Highlights:
- **Baseline Model (Decision Tree):** Achieved 85% accuracy but struggled with recall for defaulted loans (7%).
- **XGBoost Model:** Improved accuracy to 87% and recall to 27%.
- **With Undersampling:** Boosted recall for defaulted loans to 66%, with a trade-off in accuracy (75%).

---

## Features
- **Preprocessing:** Addressed missing data, anomalies, and inconsistent feature values.
- **Class Balancing:** Used **SMOTE** to handle imbalanced datasets effectively.
- **Hyperparameter Tuning:** Optimized model parameters with **GridSearchCV** for enhanced performance.

---

## Results
- **Baseline Decision Tree:**
  - Accuracy: 85%
  - Recall (Defaulted Loans): 7%
- **XGBoost Model:**
  - Accuracy: 87%
  - Recall (Defaulted Loans): 27%
- **XGBoost with Undersampling:**
  - Accuracy: 75%
  - Recall (Defaulted Loans): 66%

These results demonstrate a significant improvement in identifying defaulted loans, crucial for real-world financial applications.

---

## Report
A detailed project report describing methodology, preprocessing steps, models, and results is available in the repository:
[Download Project Report](project_report.pdf)

---

