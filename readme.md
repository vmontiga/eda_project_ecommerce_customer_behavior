# Customer Analytics & Churn Analysis Project

## Project Overview

This project explores customer behavior, customer lifetime value (CLV), engagement, and churn patterns using Python, SQL, and data visualization techniques. The goal is to identify the key drivers of customer value and retention while showcasing end-to-end analytical workflows including data cleaning, feature engineering, statistical analysis, SQL querying, and business storytelling.

---

# Analytical Questions & Methodology

| # | Question | Main Columns Used | Preferred Tools | Visualization Methods |
|---|---|---|---|---|
| 1 | What is the distribution of Customer Lifetime Value (CLV)? | `Lifetime_Value` | Python (EDA) | Histogram + Boxplot |
| 2 | How can customers be segmented based on Lifetime Value? | `Lifetime_Value`, `LV_Tier` | Python + SQL | Boxplot, Countplot, Barplot |
| 3 | Which factors are most associated with higher Lifetime Value? | `Total_Purchases`, `Average_Order_Value`, `Session_Duration_Avg`, `Login_Frequency`, `Lifetime_Value` | Python | Correlation Heatmap, Scatterplots with Regression Line |
| 4 | How do high-value customers behave differently from lower-value customers? | `LV_Tier`, `Login_Frequency`, `Session_Duration_Avg`, `Wishlist_Items`, `Product_Reviews_Written`, `Mobile_App_Usage` | SQL + Python | Boxplots, Heatmaps, Countplots |
| 5 | What factors drive customer engagement? | `Login_Frequency`, `Pages_Per_Session`, `Session_Duration_Avg`, `Email_Open_Rate`, `Social_Media_Engagement_Score` | Python | Correlation Heatmap, Scatterplots |
| 6 | Which behavioral variables are associated with churn? | `Churned`, `Days_Since_Last_Purchase`, `Login_Frequency`, `Customer_Service_Calls`, `Total_Purchases` | SQL + Python | Boxplots, Correlation Heatmap |
| 7 | Is there a statistical relationship between churn and categorical variables? | `Churned`, `Gender`, `Signup_Quarter`, `Payment_Method_Diversity` | Python (Statistical Analysis) | Heatmaps, Crosstabs |
| 8 | How does customer fidelity (membership duration) affect CLV and churn? | `Membership_Years`, `Fidelity`, `Lifetime_Value`, `Churned`, `LV_Tier` | SQL + Python | Barplots, Stacked Barplots |
| 9 | How do purchasing patterns influence Lifetime Value? | `Total_Purchases`, `Average_Order_Value`, `Lifetime_Value` | SQL + Python | Scatterplots with Regression Line |
| 10 | How do demographic characteristics influence customer value and churn? | `Age`, `Age_Group`, `Gender`, `Country`, `Lifetime_Value`, `Churned` | SQL + Python | Barplots, Countplots, Heatmaps |

---

# Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib
  - SciPy

- **SQL**
  - SQLite
  - DB Browser for SQLite

- **Visualization**
  - Seaborn
  - Matplotlib
  - Tableau (optional dashboarding)

---

# Key Analytical Techniques

- Data Cleaning & Missing Value Imputation
- Feature Engineering
- Customer Segmentation
- Correlation Analysis
- Chi-Square Testing
- Cramér’s V Analysis
- Exploratory Data Analysis (EDA)
- SQL Aggregation & Window Functions

---

# Business Objectives

- Identify high-value customer segments
- Understand customer engagement patterns
- Detect churn indicators
- Evaluate the impact of customer loyalty
- Generate actionable business insights for retention and growth strategies
