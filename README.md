# EDA_Customer_Support_Tickets
Exploratory Data Analysis (EDA) to customer support tickets for various tech products, related to hardware issues, software bugs and network problems, as well as information about the customer, ticket type, priority and other relevant details - Python.

1. Data Source:
- Data source found on Kaggle.
- The dataset consists of customer inquiries related to hardware issues, software bugs, network problems, account access, data loss, and other support topics.
- It provides information about the customer, the product purchased, the ticket type, the ticket channel, the ticket status, customer satisfaction and other relevant details.
- CSV file with 8469 rows and 17 columns.


2. Data Exploration and Visualization:
- In Python, Exploratory Data Analysis (EDA) organized in 11 steps:
- Step 1: Introduction
- Step 2: Import Libraries
- Step 3: Reading Dataset
- Check for Unique and Duplicated Values
- Missing Values
- Step 4: Data Reduction
- Step 5: Feature Engineering
-  Creating Features
- Step 6: Data Cleaning / Wrangling
- Step 7: Statistics Summary
- Step 8: EDA Univariate Analysis
- Step 9: Data Transformation
- Standardization of numerical variables (Z-Score Normalization, using StandardScaler)​
- Step 10: EDA Bivariate Analysis
- Convert categorical columns to numerical ones, for comparision (using factorize)​
- Step 11: EDA Multivariate Analysis

- In terms of Visualization, use Seaborn and Matplotlib libraries to create several graphs:
- Pie chart to get the distribuition by gender, resolution, ticket priority, customer satisfaction rating;
- Histogram for customer age, customer satisfaction rating by ticket priority, customer satisfaction rating by ticket type;
- Count plot (vertical and horizontal) to get the sum of product purchase, brand, ticket subject, ticket channel, ticket type;
- Heatmap for correlation of all variables.
