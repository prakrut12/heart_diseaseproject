Heart Disease Prediction (ML Project):

An end-to-end Machine Learning project that predicts the presence of heart disease using the UCI Heart Disease Dataset.
The project includes preprocessing, class balancing, model comparison, hyperparameter tuning, and stacking ensemble methods.

 Dataset:

- Source: UCI Machine Learning Repository (ID: 45)

- 303 patient records

- 14 medical features
  

Target converted to binary:

0 → No disease

1 → Disease


⚙️ Workflow

Data cleaning & missing value handling

Feature scaling & one-hot encoding using ColumnTransformer

Stratified train-test split


Model training:

Logistic Regression

Random Forest

XGBoost

LightGBM

SMOTE for class imbalance

Hyperparameter tuning (RandomizedSearchCV)

Stacking ensemble for improved performance


📊 Evaluation Metrics:

Accuracy

Precision, Recall, F1-score

ROC–AUC

Confusion Matrix


🛠 Tech Stack:

Python, Scikit-learn, XGBoost, LightGBM, Imbalanced-learn, Pandas, NumPy, Matplotlib, Seaborn

🚀 Goal:

Build a robust and optimized ML model to accurately predict heart disease using structured clinical data.
