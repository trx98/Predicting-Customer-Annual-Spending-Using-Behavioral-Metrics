🛍️ Predicting Customer Annual Spending Using Behavioral Metrics
📖 Overview

This project analyzes user engagement behavior on EliteShoppers.com, a leading e-commerce platform operating via both mobile app and website. The goal is to understand how customer interaction patterns influence annual spending and provide data-driven recommendations for platform-focused marketing and development efforts.

Conducted as part of Analytica Insights, the study involves a complete regression-based predictive modeling pipeline — from exploratory data analysis to model evaluation — aimed at quantifying the relationship between user activity and spending behavior.

🎯 Business Objective

The primary goals of this analysis are to:

Predict each customer’s yearly amount spent based on behavioral metrics.

Compare the impact of mobile app versus website usage on spending.

Provide strategic insights to guide EliteShoppers’ investment decisions between app and website improvements.

📊 Dataset Description

The anonymized dataset provided by EliteShoppers contains customer-level behavioral and demographic metrics.

| **Column**              | **Description**                                      |
|--------------------------|------------------------------------------------------|
| Email                   | Unique customer identifier                           |
| Address                 | Customer’s physical address                          |
| Avatar                  | Categorical variable (visual representation)         |
| Avg. Session Length     | Average duration (minutes) per session               |
| Time on App             | Average time (minutes) spent on the mobile app       |
| Time on Website         | Average time (minutes) spent on the website          |
| Length of Membership    | Total number of years the customer has been active   |
| Yearly Amount Spent     | Annual spending amount (Target variable)             |


🧠 Methodology
1️⃣ Data Preprocessing

Cleaned and prepared the dataset for regression modeling.

Handled irrelevant columns (like Email and Address) that do not contribute to spending prediction.

Verified null values and ensured numerical consistency.

2️⃣ Exploratory Data Analysis (EDA)

Visualized correlations between user behavior and spending patterns.

Compared Time on App vs Time on Website with Yearly Amount Spent.

Used pair plots, heatmaps, and distribution charts to uncover relationships.

3️⃣ Feature Engineering

Focused on key predictors: Avg. Session Length, Time on App, Time on Website, and Length of Membership.

Scaled features where required for improved regression performance.

4️⃣ Model Development

Implemented and compared multiple regression models:

Linear Regression – baseline model

Train-Test Split (70–30 ratio)

Evaluated using metrics: R², MAE, and RMSE

5️⃣ Model Evaluation

Achieved high R² values, indicating a strong relationship between user engagement and annual spending.

Residual analysis confirmed a well-fitted linear model.

📈 Key Insights

Time on App showed a stronger correlation with yearly spending than Time on Website.

Customers with longer membership duration tend to spend more annually.

The mobile app emerged as the dominant driver of revenue, suggesting that EliteShoppers should prioritize app-based experience enhancements and targeted mobile marketing campaigns.

🧩 Technologies Used

Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for data visualization

Scikit-learn for modeling and evaluation

Jupyter Notebook for interactive analysis

🚀 Results

Developed a regression model capable of predicting annual customer spending with high accuracy.

Delivered actionable insights for platform investment strategy — highlighting the mobile app as a more influential spending driver.

📬 Conclusion

This project provides a quantitative foundation for EliteShoppers to make informed decisions about resource allocation, enhancing customer engagement, and boosting revenue.
