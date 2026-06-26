# Task 1: Exploratory Data Analysis (EDA) on Retail Sales Data

**Internship:** OASIS Infobyte - Data Analytics  
**Level:** Level 1  
**Task:** 1  
**Folder:** 01-Retail-Sales

## Project Overview
This project performs Exploratory Data Analysis on a Retail Sales dataset containing 5000 records. The goal is to uncover patterns, trends, and insights in customer purchasing behavior to help the retail business make data-driven decisions.

## Dataset Information
**Dataset:** Retail Sales Data  
**Shape:** 5000 rows × 11 columns  
**Features:** CustomerID, Age, Gender, Category, ItemPurchased, Amount, Season, PaymentMethod, ItemRating, DiscountApplied(%), PreviousPurchases  
**Missing Values:** 0

## Key Analysis Performed
1. **Data Loading & Basic Stats**: Loaded dataset, checked shape, null values, and generated descriptive statistics for Age, Amount, ItemRating, DiscountApplied(%), PreviousPurchases
2. **Category Analysis**: Analyzed sales count by category. Footwear and Sports had highest sales
3. **Gender Analysis**: Compared average spending between Male and Female customers. Males showed higher average spending
4. **Seasonal Analysis**: Studied spending distribution across Autumn, Spring, Winter, Summer using boxplots
5. **Product Analysis**: Identified Top 10 Most Purchased Items - Sandals, Formal Shoes, and Sneakers lead
6. **Correlation Analysis**: Generated correlation heatmap between variables like Age, Amount, ItemRating, DiscountApplied(%), PreviousPurchases
7. **Payment Method Analysis**: Identified most used payment method - Card payments dominate over Cash on Delivery

## Key Insights
- Footwear category has maximum sales count
- Male customers spend more on average than Female customers  
- Card is the most preferred payment method
- Sandals are the most purchased item
- Strong positive correlation between DiscountApplied(%) and PreviousPurchases

## Learning Resources & References
**Concepts Learned:**
1. **Pandas DataFrame Operations** - Data loading, cleaning, groupby, describe()
2. **Data Visualization** - Matplotlib & Seaborn for bar plots, boxplots, heatmaps, count plots
3. **Statistical Analysis** - Correlation analysis, descriptive statistics
4. **EDA Workflow** - Complete exploratory data analysis pipeline

**References Used:**
1. Pandas Documentation - https://pandas.pydata.org/docs/
2. Seaborn Tutorial - https://seaborn.pydata.org/tutorial.html
3. Matplotlib Documentation - https://matplotlib.org/
4. OASIS Infobyte Task List - Official project guidelines

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Files in this Repository
- `01-Retail_sales_EDA.ipynb` : Complete EDA notebook with all analysis and visualizations

--
**Submitted by:** Shreya Pandey  
**GitHub:** ayerhsp
