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

2. Customer Dashboard
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

