# 📊 PaisaBazaar EDA & ML Project

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** on a financial dataset to predict customer credit scores.  
The goal was to identify key factors influencing creditworthiness and build predictive models to help financial institutions make better lending decisions.  

---

## 🔎 Key Objectives
- Perform **data wrangling**: handle missing values, outliers, and categorical encoding  
- Conduct **EDA**: univariate, bivariate, and multivariate visualizations  
- Perform **hypothesis testing** for insights validation  
- Engineer new features (e.g., Debt-to-Income Ratio, Savings Ratio)  
- Apply **feature selection** and scaling techniques  
- Train and evaluate ML models for credit score prediction  

---

## 📊 Exploratory Data Analysis
- **Univariate Analysis** → Distribution of age, income, debt, and credit scores  
- **Bivariate Analysis** → Relationships between income vs. credit score, debt vs. utilization ratio, repayment behavior vs. credit score  
- **Multivariate Analysis** → Correlation heatmaps and pairplots to detect feature interactions  
- **Key Insights**:  
  - High outstanding debt and utilization ratio strongly indicate poor credit scores  
  - Customers with disciplined repayment and higher savings are more likely to have good credit scores  

---

## 🤖 Machine Learning Models
Three models were trained and evaluated:  

1. **Logistic Regression** → Baseline model (~65–70% accuracy)  
2. **Decision Tree Classifier** → Captured non-linear patterns (~72–75% accuracy)  
3. **Random Forest Classifier** → Best performing (~70–73% accuracy, stable and robust)  

**Final Model Chosen**: ✅ **Random Forest Classifier**  
- Balanced accuracy, precision, and recall  
- Provided feature importance insights (key predictors: `Outstanding_Debt`, `Credit_Utilization_Ratio`, `Annual_Income`)  

---

## 🏆 Results & Business Impact
- Random Forest achieved **~70% accuracy** in predicting credit scores.  
- Key insights can help financial institutions:  
  - Improve credit risk models  
  - Identify risky customers early  
  - Reduce defaults and losses  
  - Offer personalized financial products  

---

## 📂 Repository Contents
- `PaisaBazaar_EDA_Report.ipynb` → Complete analysis & ML modeling notebook  
- `README.md` → Project documentation  
- (Optional) `dataset_sample.csv` → A sample dataset (if allowed to share)  

---

## 🚀 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Logistic Regression, Decision Tree, Random Forest  

---

## 📌 Author
👤 **Aditya Kumar**  
- 🎓 ECS Student, KIIT University (Expected 2027)  
- 🌐 [LinkedIn](https://www.linkedin.com/in/itsadityakumar27) | [GitHub](https://github.com/Aditya-kr24)  

---
