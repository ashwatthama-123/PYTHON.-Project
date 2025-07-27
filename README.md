
# 📊 Telecom Customer Churn Analysis

## 📌 Objective
**The objective of this project is to analyze and understand customer churn behavior within a telecom company using Python and data visualization libraries. This insight will help the business** 

---

## identify risk patterns, reduce customer attrition, and improve service quality.

| Tool             | Purpose                          |
| ---------------- | -------------------------------- |
| Python           | Data analysis and scripting      |
| Pandas           | Data cleaning and transformation |
| NumPy            | Numerical computation            |
| Matplotlib       | Static plotting                  |
| Seaborn          | Statistical data visualization   |
| Jupyter Notebook | Interactive coding environment   |

---

## 📥 Dataset Overview

**The dataset consists of 7,043 telecom customer records with 21 columns related to customer demographics, services subscribed, and billing information.**

---

**✅ Key Columns:**
customerID: Unique customer identifier
gender, SeniorCitizen, Partner, Dependents: Demographic details
PhoneService, MultipleLines, InternetService, OnlineSecurity, etc.: Services
Contract, PaperlessBilling, PaymentMethod: Billing terms
tenure, MonthlyCharges, TotalCharges: Duration and cost
Churn: Target variable (Yes/No) 

🔍 Exploratory Data Analysis (EDA)
🧾 Data Summary
Total Records: 7043
Columns: 21
Missing Values: Only a few in TotalCharges due to blank entries, handled via type conversion and filtering

---

## 📊 Visual Analysis & Findings
-1. Churn Distribution
-Churned customers: ~26%
-Pie and bar plots used to represent percentage split

-2. Gender vs Churn
-Both genders have similar churn rates
-Gender does not have a significant influence on churn

-3. Senior Citizen Analysis
-~16.2% customers are senior citizens
-Churn rate for senior citizens: ~42%
-Churn rate for others: ~26%
-Senior citizens churn at a much higher rate

-4. Partner & Dependents
-Customers without a partner churn at a higher rate (~32%) than those with partners (~20%)
-Customers without dependents churn more

-5. Contract Type
-Contract	Churn Rate
-Month-to-month	43.9%
-One year	11.5%
-Two year	2.8%
-Month-to-month contracts pose the highest risk
-Longer contracts retain customers better

-6. Payment Method
-Electronic check customers churn the most (~34%)
-Customers using automatic bank/credit card payments have lowest churn

-7. Internet Service Type
-Internet Service	Churn Rate
-DSL	19.5%
-Fiber optic	42.2%
-No Internet	7.3%
-Fiber optic users churn more — possibly due to higher pricing or dissatisfaction

-8. Tenure Distribution
-Most churn happens in the first 12 months
-As tenure increases, churn probability decreases
-Histogram plotted with hue='Churn' shows clear drop in churn beyond 24 months

-9. Monthly Charges
-Higher monthly charges often correlate with churn
-Customers paying >$70/month have higher risk
-Still, this variable needs to be evaluated alongside services used

---

**📈 Plots & Visuals Used**

📌 Count plots for gender, partner, dependents, contract

📌 Pie charts for churn proportion and senior citizen breakdown

📌 Stacked bar charts to show churn percentage among groups

📌 Histograms for tenure and monthly charges distributions

📌 Grouped bar charts for multi-variable comparisons

--- 

**All visuals use a custom color palette and annotations for better interpretation.**

---

**Key Insights**

💡 Early intervention is critical — churn peaks in early tenure.

💡 Senior citizens and customers without dependents/partners are high risk.

💡 Month-to-month contracts and electronic check payment correlate with high churn.

💡 Service combinations and billing methods are strong indicators of churn.

--- 

## 👤 Vishal Porla
## Aspiring Data Analyst skilled in Python, Power BI, Advanced Excel, and SQL

**📊 THANKYOU FOR VIEWING❤️**
