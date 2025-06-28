# Credit Risk Analysis

##  Objective
Build a machine learning model to assess the creditworthiness of customers and flag high-risk individuals for financial institutions. This helps reduce default rates by identifying potentially risky loan applicants before approval.


##  Dataset
**Source:** [Give Me Some Credit Dataset](https://www.kaggle.com/c/GiveMeSomeCredit)  
This dataset contains anonymized financial and demographic information used to predict the likelihood of a serious delinquency within two years.


##  Project Steps

### 1. Data Preprocessing
- Handle missing values.
- Normalize or scale numerical features.
- Address class imbalance using **SMOTE** (Synthetic Minority Oversampling Technique).

### 2. Feature Engineering
- Create meaningful features from:
  - Monthly income
  - Revolving utilization of unsecured lines
  - Number of delinquencies and late payments
- Remove redundant or low-variance features.

### 3. Model Training
- Train and compare the following models:
  - Random Forest
  - Gradient Boosting
  - XGBoost

### 4. Model Evaluation
- Evaluate using:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC Curve
  - Confusion Matrix


##  Outcome
A robust credit risk scoring system capable of:
- Flagging high-risk customers.
- Helping financial institutions minimize default rates.
- Supporting data-driven loan decision-making.


## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- imbalanced-learn (SMOTE)
- XGBoost
- Matplotlib / Seaborn for visualization


