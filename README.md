# Loan Approval Prediction

## 📌 Project Overview
This project aims to predict whether a loan application will be **approved** based on applicant data.  
Using machine learning techniques, the model handles missing values, encodes categorical variables, and deals with class imbalance to improve prediction accuracy.  
The focus is on **precision, recall, and F1-score** to ensure reliable performance in real-world scenarios where false approvals or rejections can have significant consequences.

## 📂 Dataset
- **Source:** [Loan Approval Prediction Dataset (Kaggle)](https://www.kaggle.com/)
- **Description:** Contains applicant information such as income, loan amount, credit history, and more.
- Target variable: **Loan_Status** (Approved / Not Approved)

## 🛠 Tools & Libraries
- **Python**
- **Pandas**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**

## 🔍 Approach
1. **Data Preprocessing**
   - Handled missing values.
   - Encoded categorical features using label encoding and one-hot encoding.
   
2. **Handling Class Imbalance**
   - Applied **SMOTE** (Synthetic Minority Oversampling Technique) to balance the dataset.
   
3. **Model Building**
   - Compared **Logistic Regression** and **Decision Tree** classifiers.
   - Evaluated using **precision, recall, and F1-score**.

4. **Model Evaluation**
   - Confusion matrix and classification report for detailed performance insights.
   - Focused on improving recall for positive class (Approved) without compromising precision.

## 📊 Results
- Achieved balanced performance between precision and recall after applying SMOTE.
- Decision Tree provided better recall, while Logistic Regression had slightly better precision.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/shahzaib06042005/loan-approval-prediction.git
