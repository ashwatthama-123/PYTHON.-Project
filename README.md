# 📊 Telecom Customer Churn Analysis
🔍 Project Overview
This project focuses on analyzing customer churn behavior in a telecom company using Python and powerful data visualization tools. The goal is to understand key trends and factors that contribute to customer attrition and provide actionable insights for reducing churn rates.

🧰 Tools & Libraries Used
Python 3

Pandas for data manipulation

NumPy for numerical operations

Matplotlib and Seaborn for data visualization

📥 Data Source
The dataset used in this project contains information about telecom customers, including their demographics, account information, and churn status. It includes features such as:

Gender, Senior Citizen, Partner, Dependents

Phone, Internet, Contract, and Payment Details

Tenure, Monthly & Total Charges

Churn (Yes/No)

🔎 Exploratory Data Analysis (EDA)
✅ Dataset Snapshot
Rows: ~7043

Columns: 21

Target Variable: Churn

👨‍👩‍👧‍👦 Gender Distribution
Gender	Count
Male	3555
Female	3488

Churn by gender shows a fairly equal distribution — No significant gender bias was observed.

🧓 Senior Citizens vs Churn
Senior Citizens in dataset: 1142 (16%)

Churn Rate among Seniors: Higher compared to non-seniors

💑 Partner & Dependents
Customers without partners and dependents are more likely to churn.

📶 Service Subscription
PhoneService, InternetService, Streaming Services all show varying churn trends.

Customers with Fiber optic internet show higher churn rates.

📈 Tenure Distribution
Customers with shorter tenures (<12 months) have significantly higher churn.

💳 Payment Methods & Contract Types
Month-to-month contract type has the highest churn.

Electronic check payment method users tend to churn more.

📊 Key Visuals
📉 Bar Charts: Show churn comparison across categorical variables like gender, contract type, and internet service.

🧩 Pie Charts: Used to represent churn proportionally.

🌈 Colorful Histograms: Illustrate tenure and charges distributions with churn overlay.

📚 Stacked Bars: Show churn percentage within groups (e.g., Senior Citizen, Contract Type).

💡 Key Insights
Customers with month-to-month contracts are more likely to churn.

Customers using electronic checks tend to churn more frequently.

Tenure plays a significant role — newer customers are at higher risk.

Senior citizens, customers without partners or dependents, and those using fiber optic services show elevated churn.

🏁 Conclusion
This analysis provides valuable insights into customer behavior, helping telecom companies:

Target at-risk customers with offers

Improve customer service for specific demographics

Encourage long-term contracts and auto-payment methods

📌 Project Structure
bash
Copy
Edit
Telecom-Customer-Churn/
│
├── telecom_churn_analysis.ipynb   # Jupyter Notebook with all code and visuals
├── README.md                      # Project documentation
├── churn_visuals/                 # Exported images/plots
└── data/
    └── Customer_Churn.csv         # Dataset (if publicly shareable)
📢 Author
Vishal Porla
Aspiring Data Analyst skilled in Python, Excel, SQL, and Power BI

🔗 LinkedIn | 📫 Email: your.email@example.com
