# Diwali-Sales-Analysis
The Diwali Sales Analysis project is a comprehensive data analytics project aimed at understanding customer purchasing patterns during the Diwali festival season. The primary objective is to generate business insights that can help companies improve their marketing, product placement, and customer targeting strategies.

The dataset contains customer demographic details like gender, age group, marital status, occupation, state, product category, number of orders, and amount spent. This information is used to identify high-value customer segments and popular product categories.

🔶 1. Data Loading and Inspection

The project begins by importing essential libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
The dataset is then loaded using pd.read_csv() with the unicode_escape encoding to avoid special character errors.

Initial exploration includes:

Viewing dataset shape

Displaying initial rows

Checking data types

Identifying null values

This helps in understanding the dataset structure and potential issues.

🔶 2. Data Cleaning and Preprocessing

Data cleaning is one of the most crucial steps:

✔ Removing Irrelevant Columns

Columns like Status and unnamed1, which provide no analytical value, are removed.

✔ Handling Missing Values

Null values are identified and removed using df.dropna() to ensure a clean dataset.

✔ Data Type Conversion

The Amount column is originally stored as an object type.
It is converted to integer type for accurate aggregation and analysis.

After these steps, the dataset becomes consistent, organized, and ready for analysis.

🔶 3. Exploratory Data Analysis (EDA)

A detailed Exploratory Data Analysis (EDA) is conducted to understand customer behavior and sales patterns.
Several visualizations are created using Seaborn and Matplotlib.

✔ Gender-Based Analysis

Countplots show that females dominate in total purchases.
Further analysis reveals females have a higher contribution to total sales amount.

✔ Age Group Analysis

The age group 26–35 years emerges as the highest purchasing demographic.
Visuals also show strong buying patterns among females in this age group.

✔ State-Wise Analysis

Sales are aggregated by states to identify top contributors.
Results show Uttar Pradesh, Maharashtra, and Karnataka generate the highest sales numbers.

✔ Marital Status Analysis

A clear insight from the data is that married individuals, especially married women, have higher purchasing power during Diwali.

✔ Occupation Analysis

Buyers from IT, Healthcare, and Aviation sectors contribute the most to total sales, indicating strong purchasing capacity among professionals in these industries.

✔ Product Category Analysis

The most purchased product categories include:

Food

Clothing & Apparel

Electronics

These categories account for a major portion of total sales during the festival.

✔ Top Selling Products

Using groupby operations on the Product_ID, the project identifies the top 10 most sold products.
This helps businesses focus on inventory planning and demand forecasting.

🔶 4. Key Insights from the Analysis

From the visual exploration and aggregated results, the following key insights are drawn:

Married women are the most active buyers.

The major buying age group is 26–35 years.

UP, Maharashtra, and Karnataka contribute the most in terms of revenue.

High-spending customers belong to the IT, Healthcare, and Aviation sectors.

Popular product categories are Food, Clothing, and Electronics, making them crucial for festive season inventory.

Several product IDs consistently appear in the top sales lists, helping identify best sellers.

These insights can directly assist businesses in targeted marketing, promotional planning, and inventory optimization.

🔶 5. Tools & Technologies Used

Python

Pandas → Data cleaning and transformation

NumPy → Numerical computation

Matplotlib & Seaborn → Visualization

Jupyter Notebook → Development environment

🔶 6. Business Value of the Project

This project helps businesses in the retail and e-commerce sectors by:

Understanding which customer groups shop the most

Identifying high-demand product categories

Preparing better marketing strategies for festive seasons

Improving customer segmentation

Making data-driven decisions based on spending behavior

Such insights can significantly improve customer targeting, sales forecasting, and campaign effectiveness.

⭐ Conclusion

The Diwali Sales Analysis project provides a deep understanding of consumer behavior during one of India’s biggest shopping seasons. Through effective data cleaning, preprocessing, and visualization, the analysis reveals patterns that can help companies enhance sales strategy, focus on high-value customer segments, and improve product planning for festive periods.
