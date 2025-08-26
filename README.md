📊 Telecom Customer Churn Analysis (Power BI Project)


🔍 Project Overview

Customer churn is one of the most critical problems faced by subscription-based businesses. Retaining existing customers is far more cost-effective than acquiring new ones.
In this project, I developed a Power BI dashboard that analyzes telecom customer data and highlights key churn drivers. The dashboard also integrates a machine learning churn prediction model (built using Python & Scikit-learn), which provides customer-level churn probabilities.
This enables businesses to identify at-risk customers and take proactive retention measures.

⚙️ Project Workflow

1) Data Preparation:-

. Cleaned and preprocessed telecom customer dataset (~7,000+ records).

. Features include demographics, contract type, phone/internet services, and billing details.

Machine Learning Model (Python)

. Built a churn prediction model using Random Forest.

. Achieved ~93% accuracy.

. Exported churn probabilities (predict_proba) for each customer to a CSV file.

2) Power BI Dashboard

. Connected customer probability data with original customer details.

. Designed two dashboards:

. Churn Analysis Dashboard → Overall churn trends & drivers.

. Customer Dashboard → Individual churn risk score & profile.

📈 Dashboard Features
1. Churn Analysis Dashboard

. Demographics distribution (gender, age groups, partner status).

. Phone & internet service adoption.

. Contract types and payment methods.

. Key KPIs: Total customers, churn count, average monthly charges, total charges.

3. Customer Dashboard
. Churn Index: Customer-specific churn probability (0–1).

. Risk Type: Categorized as Non-risky / Risky based on probability threshold.

. Customer details (contract type, payment method, phone service, etc.).

. Drill-down insights into individual customer profiles.

🚀 Business Impact

3) Insights:-
. Identify customers with high churn risk.

. Support targeted marketing campaigns to improve retention.

. Reduce customer acquisition costs by preventing churn.

. Provide leadership with clear insights into why customers leave.

🛠️ Tools & Technologies
. Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

. Power BI (Data modeling, DAX, Visualizations, KPI Cards)

. Excel/SQL (for preprocessing and initial exploration)


🔑 Insights & Solutions

-- Demographics

. Male and female customers churn almost equally.

. Senior citizens show higher churn rates.

✅ Solution → Provide loyalty discounts and dedicated support for senior citizens.

-- Contract Type

. Month-to-month contract customers have the highest churn.

. 1-year and 2-year contract customers are more loyal.

✅ Solution → Offer discounts and benefits to promote long-term contracts.

-- Phone & Internet Services

. Customers without Online Security, Tech Support, or Device Protection churn more.

 . Bundled services reduce churn risk.

✅ Solution → Create bundled service packages with discounts to increase adoption.

-- Payment Method

. Customers using electronic checks have the highest churn.

. Credit card, bank transfer, or mailed check users are more stable.

✅ Solution → Promote secure digital payment methods with cashback or rewards.

--Tenure (Customer Age with Company)

. New customers (0–2 years) churn the most.

. Long-tenure customers are significantly more loyal.

✅ Solution → Implement a welcome/retention program with early-stage offers and free add-ons.

-- Billing & Charges

. Higher monthly charges correlate with higher churn.

. Total charges are less important compared to monthly affordability.

✅ Solution → Introduce tiered/downgrade plans to retain price-sensitive customers.



📊 Business Impact

. By applying the above strategies, the telecom company can:

. Reduce churn by 15–20% through targeted retention campaigns.

. Improve customer lifetime value (CLV).

. Optimize marketing spend by focusing only on high-risk customers (identified via churn index).


Screenshot :-
Screenshot
![alt text](https://github.com/vikkashh/telco_churn_prediction_dashboard/blob/main/telco_churn_page_1_SS.png)


