# 💰 Bank Personal Loan Analysis – Finance Project

An exploratory data analysis (EDA) project on personal loan acceptance using customer profile data from Thera Bank. The project aims to understand key factors that influence loan acceptance and help the bank improve its marketing strategy.

---

## 🔗 Quick Links

- 🔙 [Back to All Data Science Projects](https://github.com/ShivamMahto2105/Data-Science-Projects)
- 📄 [View this Project on GitHub](https://github.com/ShivamMahto2105/Data-Science-Projects/blob/main/1.%20Finance%20Loan%20Project/Bank_Loan_Analysis.pdf)
- 📥 [Download the Dataset (Bank.csv)](https://github.com/ShivamMahto2105/Data-Science-Projects/blob/main/1.%20Finance%20Loan%20Project/Bank.csv)
- 📘 [View Data Description](https://github.com/ShivamMahto2105/Data-Science-Projects/blob/main/1.%20Finance%20Loan%20Project/Data_Description.txt)

---

## 📁 Dataset Overview

- **File:** `Bank.csv`
- **Records:** 5,000 customers
- **Features:** 14
- **Includes:** Customer demographics, account info, credit card usage, and personal loan acceptance

---

## 🧪 Data Exploration Summary

- Removed unnecessary columns like `ID` and `ZIP Code`
- Detected and corrected 52 records with negative values in the `Experience` column
- Created new features for education level and account-holding type
- Visualized distributions, correlations, and key comparisons between customers who accepted and declined loans

---

## 🛠️ Key Analysis Steps

- Cleaned missing and incorrect values
- Created derived features: `EDU` (Education Label) and `Account_holder_category`
- Explored key relationships using box plots, distribution plots, and pie charts
- Used correlation matrix to identify strong predictors of personal loan acceptance

---

## 📊 Technologies Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- Jupyter Notebook

---

## 📌 Key Insights

- **Income** is the most significant feature — higher income = higher loan acceptance
- **CCAvg (credit card average spending)** also correlates positively with loan approval
- **Education level** matters — professionals and graduates are more likely to take loans
- Customers with **both CD and securities accounts** are more inclined to accept loans

---

## 🧑‍💻 Target Customers (For Bank Marketing)

- High-income individuals
- Customers with higher credit card spending
- Professional or graduate-educated customers
- Customers holding securities or CD accounts

---

## 🚀 Future Work

- Apply machine learning models (like Logistic Regression, Random Forest) to predict loan approvals
- Build customer segmentation dashboards using Plotly or Streamlit
- Monitor loan offer conversions over time to refine strategies

---

## ✅ **Conclusion**

As a beginner in data science, this project helped me understand how to clean and analyze real-world financial data. I explored relationships between income, credit card spending, education, and personal loan decisions.

Some key learnings:
- Customers with high income and credit card usage are more likely to accept personal loans.
- Education level and account-holding behavior also influence decisions.
- Data cleaning (like fixing negative experience values) is crucial for reliable analysis.

This project improved my Python, Pandas, and visualization skills, and gave me practical experience in using data to support business decisions.

---

## ▶️ How to Run

1. Clone the repo or download this project folder.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
