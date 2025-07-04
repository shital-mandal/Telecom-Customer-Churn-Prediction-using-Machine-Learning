# Telecom-Customer-Churn-Prediction-using-Machine-Learning
This project focuses on building a predictive model to identify potential telecom customers likely to churn, using structured customer data and machine learning techniques. The aim is to help telecom providers proactively reduce churn and improve customer retention through data-driven insights.

Problem Statement
Customer churn is a significant business issue in the telecommunications sector. The objective of this project is to predict whether a customer is likely to churn based on their usage, billing, support interaction, and contract details.

Approach and Highlights
Data Cleaning & Preprocessing
Removed duplicates and irrelevant columns, handled missing values, applied label encoding for categorical features.

Feature Selection
Identified high-impact variables such as contract type, tenure, charges, and support history through correlation analysis.

Imbalanced Data Handling
Applied SMOTE-ENN to address class imbalance and improve generalization on the minority class.

Model Evaluation
Trained and compared multiple classifiers including Logistic Regression, Random Forest, and Gradient Boosting.
Selected the best model based on recall, precision, and F1-score due to the business importance of minimizing false negatives.

Performance
Achieved 96% precision, recall, and F1-score on the holdout set, ensuring strong identification of churners and non-churners.

Tools and Libraries Used
Python

pandas, NumPy, scikit-learn

SMOTE-ENN (from imblearn)

Matplotlib, Seaborn

Jupyter Notebook
