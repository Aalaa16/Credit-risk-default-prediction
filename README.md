** Credit Risk Default Prediction **

📌 Project Overview : 
This project aims to build a machine learning model that predicts the probability of customer loan default using historical credit card data.  
The goal is to help financial institutions assess credit risk and make informed lending decisions.


📊 Dataset : 
- Real-world credit card default dataset
- Contains demographic information, payment history, bill statements, and repayment behavior
- Binary target variable indicating default status



🧠 Problem Type : 
- Binary Classification
- Imbalanced Dataset



🔍 Exploratory Data Analysis (EDA) :
- Univariate and bivariate analysis
- Identification of class imbalance
- Analysis of ordinal vs nominal categorical features
- Outlier investigation with business-aware decision making



🛠 Feature Engineering & Preprocessing :
- Proper handling of categorical features:
  - One-Hot Encoding for nominal variables (SEX, EDUCATION, MARRIAGE)
  - Ordinal handling for payment status features (PAY_1 to PAY_6)
- Numerical feature scaling
- Class imbalance handled using SMOTE
- All preprocessing steps implemented within a unified pipeline



 🤖 Modeling
- Models used:
  - Random Forest
  - XGBoost
  - SVC


📈 Evaluation Metrics
- ROC-AUC (primary metric)
- Precision, Recall, F1-score
- Confusion Matrix

