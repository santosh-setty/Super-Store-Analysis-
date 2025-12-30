📊 Customer Personality Analysis
End-to-End Exploratory Data Analysis using Python
📌 Project Overview

This project performs end-to-end Exploratory Data Analysis (EDA) on a marketing customer dataset to understand customer behavior, spending patterns, demographics, and campaign responses.

The objective is to extract actionable business insights that can help improve targeting strategies, customer segmentation, and marketing effectiveness.

🔍 What This Project Covers

Data Cleaning

Feature Engineering

Outlier Treatment

Numerical & Categorical Analysis

Data Visualization

Business Insights & Recommendations

📁 Dataset Description
🔹 Demographics

Year_Birth

Education

Marital_Status

Income

Kidhome

Teenhome

🔹 Customer Behavior

Dt_Customer

Recency

Complain

Response

🔹 Spending (Last 2 Years)

MntWines

MntMeatProducts

MntFruits

MntFishProducts

MntSweetProducts

MntGoldProds

🔹 Purchase Channels

NumDealsPurchases

NumWebPurchases

NumCatalogPurchases

NumStorePurchases

NumWebVisitsMonth

⚙️ Project Workflow
✔ 1. Data Cleaning

Handled missing values

Fixed invalid date formats

Converted Dt_Customer to datetime

Derived customer Recency

Treated outliers using the IQR method

✔ 2. Feature Engineering

Created new analytical features:

Age (from Year_Birth)

TotalSpend (sum of all product spending)

Frequency (total number of purchases)

✔ 3. Exploratory Data Analysis

Performed deep analysis on:

Numerical variables

Categorical variables

Relationships between variables

Correlation analysis

📊 Visualizations Used
🔹 Numerical Analysis

Histograms

Boxplots

Violin plots

Heatmaps

🔹 Categorical Analysis

Count plots

Bar plots

🔹 Combined Analysis

Scatter plots

Pair plots

Groupby-based visualizations

🔍 Key Insights

High-income customers spend significantly more

Wine and Meat products dominate customer spending

Married & Together customers generate the highest revenue

Lower Recency (recent buyers) leads to higher campaign response

Website visits are high, but conversion rates are low

PhD & Graduate customers show stronger spending behavior

Customers without kids spend more overall

🎯 Business Recommendations

🎯 Target customers with Recency < 30 days

💰 Promote premium bundles to high-income customers

🖥 Improve website UI/UX to boost purchase conversions

👨‍👩‍👧 Focus marketing campaigns on Married/Together customers

🛍 Promote bundled offers: Wine + Meat + Gold products

🛠 Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

Jupyter Notebook

✅ Project Outcome

This analysis provides data-driven insights to help businesses:

Improve campaign targeting

Increase customer lifetime value

Optimize product bundling strategies

Enhance digital sales channels
