# 🏦 Bank Loan Approval Prediction using Decision Tree 🌳

This project predicts whether a bank should **approve or reject a loan application** using a **Decision Tree Classification model** 🤖 based on customer financial and personal data.

It aims to support banks in making **fast, accurate, and interpretable** loan approval decisions.

---

## 📌 Project Overview

Banks receive thousands of loan applications every day 📄.  
Manual verification is slow and may lead to human errors ❌.

This project uses a **Decision Tree model 🌳** to automate loan approval decisions by learning patterns from historical data.

✔ Easy to understand  
✔ Rule-based decisions  
✔ High interpretability  

---

## 📂 Dataset Description

The dataset (`smart_loan_data.csv`) includes the following features:

- 👤 Age  
- 🚻 Gender  
- 🎓 Education  
- 💼 Employment Type  
- 💰 Monthly Income  
- 📊 Credit Score  
- 💵 Loan Amount  
- ⏳ Loan Term  
- 💳 Existing Loan  
- 🏠 Property Area  

🎯 **Target Variable**
- `Loan_Status`
  - `1` → ✅ Loan Approved  
  - `0` → ❌ Loan Rejected  

---

## ⚙️ Project Workflow

1. 📥 **Dataset Loading**
   - Load CSV file using Pandas.

2. 🧹 **Data Cleaning**
   - Remove duplicates.
   - Handle missing values.

3. 🔄 **Data Preprocessing**
   - Encode categorical variables using Label Encoding.
   - Split data into features and target.
   - Perform train–test split.

4. 🧠 **Model Training**
   - Train Decision Tree Classifier.
   - Use Gini Index and controlled tree depth.

5. 📊 **Model Evaluation**
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1-Score  

6. 🌳 **Decision Tree Visualization**
   - Visual interpretation of decision rules.

7. 🔮 **Prediction**
   - Predict loan approval for new customer data.

---

## 🧠 Machine Learning Model

- 🤖 **Algorithm:** Decision Tree Classifier  
- 📐 **Criterion:** Gini Index  
- 🌲 **Max Depth:** 4  
- 📦 **Library:** Scikit-learn  

---

## 📊 Model Performance

- ✅ **Accuracy:** 100%  
- 🧾 **Confusion Matrix:** Perfect classification  
- 🔍 **Interpretability:** High  

### 📝 Key Decision Rules
- If **Credit Score ≤ 649.5** → ❌ Loan Rejected  
- If **Credit Score > 649.5** AND **Monthly Income > 30,073** → ✅ Loan Approved  

---

## 🖼️ Visualization

The decision tree clearly shows how loan approval decisions are made using:
- 📊 Credit Score  
- 💰 Monthly Income  
- 🏠 Property Area  

---

## 🛠️ Technologies Used

- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 📈 Matplotlib  
- 🤖 Scikit-learn  
- 📓 Jupyter Notebook  

---

## 📁 Project Structure

bank-loan-approval-decision-tree/
│
├── README.md
├── bank_loan_decision_tree.ipynb
├── smart_loan_data.csv
└── Bank_Loan_Approval_Prediction_Decision_Tree_Report.pdf

---

## 🚀 Future Improvements

- 📈 Use larger real-world datasets  
- 🌲 Apply advanced models (Random Forest, XGBoost)  
- 🎯 Hyperparameter tuning  
- 🌐 Build a web app for live predictions  

---

## 👤 Author

**Anurag Kokate**  
📊 Aspiring Data Analyst | 🤖 Machine Learning Enthusiast  
