# Loan Approval Prediction

## 📌 Project Overview
This project predicts whether a loan application will be approved or not using machine learning.  
It demonstrates a full end-to-end ML workflow including data cleaning, preprocessing, feature encoding, model training, evaluation, and model persistence.

The goal is to help financial institutions reduce risk by identifying applicants who are more likely to repay a loan.

---

## 📊 Dataset
The dataset contains loan application records with information such as:
- Applicant income
- Coapplicant income
- Loan amount and term
- Credit history
- Education and employment status
- Property area

Target variable:
- **Loan_Status** (`Y` = Approved, `N` = Not Approved)

---

## 🛠️ Approach
1. **Data Cleaning**
   - Handled missing values using appropriate imputation strategies
   - Converted categorical values into ML-friendly formats

2. **Feature Engineering & Preprocessing**
   - Numerical features: median imputation + scaling
   - Binary categorical features: mode imputation + ordinal encoding
   - Nominal categorical features: one-hot encoding
   - All preprocessing steps are automated using `scikit-learn` pipelines

3. **Modeling**
   - Logistic Regression (baseline, interpretable)
   - Random Forest Classifier (non-linear model)

4. **Evaluation**
   - Accuracy
   - Precision, Recall, F1-score
   - Focus on **Recall for approved loa**


