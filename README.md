# Churn-analysis-sql-project


🔁 Customer Churn Analysis & Prediction Project

Project Overview

Understanding why customers leave is as critical as acquiring them. In this project, I performed a Churn Analysis using Python to uncover customer behavior patterns, build predictive models, and generate actionable insights that businesses can use to reduce churn and improve retention.

I approached this analysis from both descriptive and predictive angles—telling the story behind churn using data, and then building models to anticipate and mitigate it.

🛠️ Tools and Technologies Used

•	Python (Jupyter Notebook) – Analysis and modeling

•	Pandas, NumPy – Data handling and feature engineering

•	Matplotlib, Seaborn – Visualizations and trend analysis

•	Scikit-learn – Classification models, performance metrics

•	SQLite (via Pandas) – Simulated database-style querying for churn metrics

❓ Key Business Questions Addressed

1.	What are the common traits of customers who churn vs. those who stay?

2.	Which features (e.g., Age, Credit Score, Balance) are strong churn predictors?

3.	Can we build a model that accurately predicts whether a customer will churn?

4.	How can the business segment and retain high-risk customers early?

🔄 Methodology

1.	Data Cleaning

•	Handled missing/null values and validated datatypes.

•	Removed duplicates and standardized column formats.

•	Checked for data leakage and label imbalance.

2.	Exploratory Data Analysis (EDA)

•	Explored distributions of key features (e.g., Age, Credit Score, Balance).

•	Created visual segments of customers (e.g., by Tenure, NumOfProducts, IsActive).

•	Analyzed correlations and outliers to find behavioral patterns.


3.	Feature Engineering

•	Created new features such as:

o	EngagementScore: Composite metric of activity level and tenure

o	HighValueCustomer: Based on balance, salary, and product usage

•	One-hot encoded categorical variables

4.	Model Building

•	Built and evaluated multiple models:

o	Logistic Regression

o	Random Forest

o	XGBoost

•	Used cross-validation, confusion matrix, ROC-AUC, and F1 Score to evaluate performance

5.	Segmentation & Insights

•	Clustered users by churn risk and value tier

•	Generated insight-rich tables and graphs to support decision-making



📊 Key Findings

•	💰 High balance but low product usage was a strong churn indicator.

•	🔢 Credit score < 600 and tenure < 3 years increased churn probability.

•	🧊 Inactive customers were 3.5x more likely to churn than active ones.

•	🚩 Churn was more common among customers with only one product or non-engaged behavior.

•	🧠 Random Forest outperformed other models with ~86% ROC-AUC and strong recall on the churn class.

📌 Business Impact

•	Helps target at-risk customers with personalized retention campaigns

•	Enables proactive interventions like loyalty offers or service upgrades

•	Supports product, marketing, and customer success teams in improving Customer Lifetime Value (CLV)

🧠 What This Project Demonstrates

•	My ability to extract insights from raw data and tell a compelling churn narrative

•	Solid grasp of EDA, feature selection, and classification modeling

•	Business-focused thinking with actionable outcomes

•	Experience translating models into stakeholder-friendly visuals and insights

•	Hands-on use of Python’s data stack for real-world classification tasks


