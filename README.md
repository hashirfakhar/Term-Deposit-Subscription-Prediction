# Task 6 - Term Deposit Subscription Prediction

## Objective
Analyze bank marketing campaign data to predict whether a client will subscribe to a term deposit (`yes` or `no`).

## Approach
- Loaded the dataset `Bank Marketing.csv`.
- Performed data cleaning:
  - Handled missing values where necessary.
  - Encoded categorical variables using label encoding.
- Conducted Exploratory Data Analysis (EDA) using **seaborn** and **matplotlib**:
  - Distribution of the target variable (`y`).
  - Subscription rates by job type, marital status, and other categorical features.
  - Relationship between numeric variables and subscription.
- Built a **Logistic Regression** model as a baseline classifier.
- Evaluated the model using accuracy score, confusion matrix, and classification report.

## Results & Insights
- Clients with certain jobs (e.g., management, retired) had higher subscription rates.
- Clients contacted via cellular channels and in certain months showed better conversion.
- The logistic regression model provides a 90% accuracy; further improvements can be made using advanced models like RandomForest or XGBoost.
