# Airbnb NYC Data Cleaning Project

## Overview
Data cleaning performed on the New York City Airbnb Open Data 2019 dataset as part of Level 1, Project 3 for the OASIS Infobyte Data Analytics Internship.

## Technical Stack
Python, Pandas, NumPy, Google Colab, KaggleHub API

## Data Cleaning Process
1. **Missing Value Imputation**: Addressed 9,890 null values across `name`, `host_name`, and `reviews_per_month` columns using appropriate imputation strategies.
2. **Duplicate Removal**: Identified and removed 9 duplicate records from the dataset.
3. **Outlier Treatment**: Filtered listings based on price, retaining records with prices between $10 and $999 to remove erroneous entries.
4. **Data Standardization**: Applied consistent formatting to categorical variables:
   - `neighbourhood_group`: Converted to uppercase
   - `room_type`: Converted to title case
5. **Data Type Conversion**: Converted `last_review` column to datetime format to ensure data integrity.

## Results Summary
| Metric | Initial Dataset | Cleaned Dataset |
| --- | --- | --- |
| Total Records | 48,895 | 48,586 |
| Null Values | 9,890 | 0 |
| Duplicate Records | 9 | 0 |

## Repository Contents
1. `project_3.ipynb`: Jupyter Notebook containing the complete data cleaning pipeline.
2. `AB_NYC_2019_Cleaned.csv`: The final cleaned dataset prepared for exploratory data analysis.

## Data Source
New York City Airbnb Open Data 2019  
Kaggle: https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

## Project Status
Completed. Dataset is validated and ready for Exploratory Data Analysis.# Airbnb NYC Data Cleaning Project



