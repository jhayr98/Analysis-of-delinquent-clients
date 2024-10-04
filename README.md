# Customer Delinquency Profile Analysis

## Project Overview
This project aims to evaluate the profile of delinquent bank customers. The dataset includes information about credit history (both delinquent and current clients), balances, days in arrears, financial products, and customer details. These insights help analyze customer behavior with the financial institution and the broader financial system.

In addition to the study of customer characteristics, the project concludes with a supervised model designed to predict customers at risk of becoming delinquent.

## Objective
The primary objective is to understand the profile of delinquent customers and identify key factors that contribute to credit default. The analysis uses various data science tools and methods to explore and model this behavior.

## Tools and Libraries
The following libraries were used in this project:

- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- `numpy` for numerical computations
- `random` for random number generation
- `scikit-learn` for machine learning algorithms and evaluation metrics
  - Clustering: `KMeans`
  - Data splitting: `train_test_split`
  - Performance metrics: `accuracy_score`, `roc_curve`, `auc`, `precision_score`, `recall_score`, `f1_score`
  - Hyperparameter tuning: `GridSearchCV`
- `CatBoostClassifier` for building the supervised model

## Methodology
1. **Data Exploration**: Understanding the key features of both delinquent and non-delinquent customers.
2. **Feature Engineering**: Creating new variables to better capture customer risk.
3. **Modeling**: Using the `CatBoostClassifier` for supervised classification and identifying potential delinquent customers.
4. **Evaluation**: Models are evaluated using various metrics such as accuracy, precision, recall, F1 score, ROC curve, and AUC.

## Conclusion
The analysis provides valuable insights into customer profiles and develops a predictive model to help identify high-risk customers, enabling better decision-making in credit risk management.

## Instructions
To run this project:
1. Clone the repository.
2. Run the Jupyter Notebook to reproduce the analysis and model.


