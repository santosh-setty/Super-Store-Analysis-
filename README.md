Customer Personality Analysis
End-to-End Data Analysis Project using Python, Pandas, Seaborn, Matplotlib
📌 Project Overview
This project performs complete Exploratory Data Analysis (EDA) on a Marketing Customer Dataset.
The goal is to understand customer behavior, spending habits, demographics, and campaign response patterns.

You will find:

Data Cleaning
Feature Engineering
Outlier Treatment
Numerical & Categorical Analysis
Visualizations
Business Insights
📁 Dataset Features
🔹 Demographics
Year_Birth
Education
Marital_Status
Income
Kidhome
Teenhome
🔹 Behavior
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
⚙️ Project Steps
✔ 1. Data Cleaning
Handling missing values
Fixing invalid date formats
Converting Dt_Customer to datetime
Creating Recency from join date
Outlier capping using IQR method
✔ 2. Feature Engineering
Created new columns:

Age
TotalSpend
Frequency (sum of purchases)
✔ 3. Exploratory Data Analysis
Performed analysis for:

Numerical columns
Categorical columns
Combined relationships
Correlation between variables
📊 Visualizations Used
Numerical:
Histograms
Boxplots
Heatmaps
Violin plots
Categorical:
Countplots
Barplots
Combined:
Scatterplots
Groupby visualizations
Pairplots
🔍 Key Insights
1️⃣ High-income customers spend the most.
2️⃣ Wine and Meat are the top spending categories.
3️⃣ Married & Together customers contribute highest revenue.
4️⃣ Lower Recency (recent buyers) → higher campaign response.
5️⃣ Website visits are high but conversions are low.
6️⃣ PhD & Graduate customers show stronger spending behavior.
7️⃣ Customers without kids spend more overall.

🎯 Business Recommendations
✔ Target customers with Recency < 30 days
✔ Promote premium bundles to high-income customers
✔ Improve website UI to increase purchase conversions
✔ Target Married/Together customers for high-value campaigns
✔ Promote Wine + Meat + Gold bundles

🛠 Technologies Used
Python
Pandas
NumPy
Seaborn
Matplotlib
Jupyter Notebook
