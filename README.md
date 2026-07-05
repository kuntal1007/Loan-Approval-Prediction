#  Loan Approval Prediction using Machine Learning

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** using multiple classification algorithms. The project covers the complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, model evaluation, and performance comparison.

## Project Overview

Financial institutions receive thousands of loan applications every day. Making accurate loan approval decisions is essential for reducing financial risk while approving eligible applicants efficiently.

This project applies various supervised machine learning algorithms to predict loan approval based on applicant information such as credit score, income, employment status, loan amount, loan term, and asset value.

## Objectives

- Perform data preprocessing and cleaning
- Explore relationships between variables using EDA
- Train multiple Machine Learning models
- Evaluate model performance using standard classification metrics
- Compare models to identify the best-performing classifier

#  Technologies Used

- R
- R Markdown
- dplyr
- caret
- recipes
- e1071 (Support Vector Machine)
- xgboost
- pROC
- ROCR

#  Dataset Features

The dataset contains the following features:

| Feature | Description |
|----------|-------------|
| CIBIL Score | Credit score of the applicant |
| Income | Applicant's annual income |
| Employment | Employment type |
| Loan Term | Duration of the loan |
| Loan Amount | Requested loan amount |
| Assets Value | Value of applicant assets |
| Loan Status | Target variable (Approved / Rejected) |


# Project Workflow

### 1. Data Preprocessing
- Data inspection
- Missing value analysis
- Outlier detection using IQR
- Categorical variable conversion
- Feature normalization
- Train/Test split

### 2. Exploratory Data Analysis (EDA)
Performed various visualization techniques including:
- Histograms
- Boxplots
- Scatter Plots
- Pearson Correlation Matrix
- Chi-Square Test
- Employment vs Loan Status Analysis

### 3. Machine Learning Models
The following classification algorithms were implemented and evaluated:
-  K-Nearest Neighbors (KNN)
-  Logistic Regression
-  Support Vector Machine (SVM)
-  XGBoost

#  Model Evaluation
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- Area Under Curve (AUC)

#  Model Comparison
The project compares all models using common evaluation metrics to determine the most effective approach for loan approval prediction.
Performance metrics include:
- Accuracy
- Error Rate
- Precision
- Recall
- F1 Score
A final comparison chart ranks all models based on their F1 Score.

#  How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/Loan-Approval-Prediction.git
```

2. Open the project in RStudio.

3. Install the required packages.
```r
install.packages(c(
  "caret",
  "dplyr",
  "recipes",
  "e1071",
  "xgboost",
  "pROC",
  "ROCR"
))
```

4. Run the R Markdown notebook.

#  Key Learning Outcomes

Through this project, I gained practical experience in:
- Machine Learning model development
- Data preprocessing techniques
- Feature engineering
- Exploratory Data Analysis
- Classification algorithms
- Model evaluation and comparison
- R programming for Machine Learning


## ⭐ If you found this project useful, consider giving it a star!
