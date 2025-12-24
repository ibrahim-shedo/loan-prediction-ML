# 🏦 Loan Approval Prediction using Logistic Regression

## 📌 Project Overview
This project focuses on predicting **loan approval status** using **Logistic Regression**, a supervised machine learning classification algorithm.  
The goal is to build a model that can determine whether a loan application will be **approved (Y)** or **rejected (N)** based on applicant and loan-related features.

The project demonstrates the **complete machine learning pipeline**, including data preprocessing, exploratory data analysis (EDA), feature encoding, model training, and evaluation.

---

## 🎯 Problem Statement
Financial institutions receive thousands of loan applications. Manually reviewing them is time-consuming and error-prone.

This project aims to:
- Automate loan approval decisions
- Reduce human bias
- Improve decision accuracy using data-driven methods

---

## 📂 Dataset Description
The dataset contains information about loan applicants, including:

| Feature | Description |
|---------|-------------|
| Loan_ID | Unique loan identifier |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Education level |
| Self_Employed | Employment type |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Loan amount requested |
| Loan_Amount_Term | Loan repayment term |
| Credit_History | Credit history (0 or 1) |
| Property_Area | Area of property |
| Loan_Status | Target variable (Y/N) |

---

## 🧹 Data Preprocessing
The following preprocessing steps were applied:

- Handling missing values using **mean, median, and mode**
- Encoding categorical variables:
  - Binary encoding for Yes/No variables
  - Numeric conversion for `Dependents`
  - One-hot encoding for `Property_Area`
- Converting target variable:
  - `Y → 1`
  - `N → 0`

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Distribution of categorical variables
- Relationship between features and loan approval status
- Impact of credit history, income, and education on loan approval

Visualizations used:
- Count plots
- Bar charts
- Statistical summaries

---

## 🤖 Machine Learning Model
### Logistic Regression
Logistic Regression was used to model the probability of loan approval.

- It predicts \( P(Y = 1 \mid X) \)
- Uses the **sigmoid function** to map predictions between 0 and 1
- A threshold of **0.5** is used for classification

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy score
- Confusion matrix
- Classification report (Precision, Recall, F1-score)

These metrics help assess how well the model distinguishes between approved and rejected loans.

---

## 🛠️ Technologies Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

