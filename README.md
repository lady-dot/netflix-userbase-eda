**Netflix User Base Analysis: Exploratory Data Analysis**

This repository contains an in-depth Exploratory Data Analysis (EDA) of a Netflix Userbase dataset. The analysis explores subscriber demographics, revenue patterns across different countries, and the popularity of various subscription tiers and devices.

📌 **Project Overview**
The objective of this project is to extract actionable insights from Netflix user data, focusing on:
 * Revenue Analysis: Identifying which subscription types and genders generate the most revenue.
 * Geographical Insights: Mapping user concentration by country.
 * Demographics: Analyzing the age distribution and device preferences of the global user base.
 * Behavioral Trends: Understanding the relationship between age, monthly revenue, and plan duration.

🛠️ **Tech Stack**
 * Python
 * Pandas: Data manipulation and group-by aggregations.
 * Matplotlib: Customizing plot aesthetics and layouts.
 * Seaborn: Creating advanced statistical visualizations (Scatter plots, Count plots, Pair plots).

📊 **Key Insights & Visuals**
 * Subscription Tiers: The "Basic" plan is the most popular, while "Premium" has the lowest count in this dataset.
 * Revenue Leaders: The United States and Spain represent the largest user segments.
 * Gender Metrics: Female users contribute a higher total monthly revenue compared to male users.
 * Device Usage: Analyzed preferences across Laptops, Tablets, Smart TVs, and Smartphones, finding that Laptop users tend to be slightly older on average.

📂 **Analysis Workflow**
 * Data Auditing: Used .info(), .describe(), and .nunique() to understand data types and unique constraints.
 * Aggregation: Performed complex groupby operations to calculate mean revenue per country and median age per plan duration.
 * Bivariate Analysis: Developed scatter plots (Age vs. Revenue) color-coded by gender to see if spending habits change with age.
 * Distribution Plots: Generated histograms with custom binning to visualize the spread of Monthly Revenue and User Age.

🚀 **How to Run**
 * Clone the repository:
   git clone https://github.com/lady-dot/netflix-user-eda.git

 * Install dependencies:
   pip install pandas seaborn matplotlib

 * Execute the analysis: Open the Jupyter Notebook to view the interactive plots and step-by-step code.

📈 **Sample Visualization**
One of the highlights of this project is the Seaborn Pair Plot, which provides a matrix-style view of the correlation between numerical variables like age and revenue.

**Found this analysis interesting? Give it a ⭐ to show your support!**
