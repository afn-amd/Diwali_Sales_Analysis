Diwali Sales Analysis

Project Overview:
This project analyzes a dataset of Diwali sales using Python libraries like Pandas, Matplotlib, and Seaborn. The goal is to derive key insights on customer demographics, purchasing patterns, and top-selling products. Through exploratory data analysis (EDA), we examine the relationship between customer attributes (such as age, gender, marital status, and occupation) and sales performance.

Dataset:
The dataset used is Diwali Sales Data.csv, which contains over 11,000 rows of customer and transaction data, including the following fields:

    User_ID: Unique identifier for each customer.
    Cust_name: Customer's name.
    Product_ID: Identifier for the purchased product.
    Gender: Customer gender.
    Age Group: Customer age group (e.g., 18-25, 26-35).
    Age: Exact age of the customer.
    Marital_Status: Indicates whether the customer is married (1) or not (0).
    State, Zone: Customer's geographical details.
    Occupation: The field of work or occupation of the customer.
    Product_Category: The category of the product purchased (e.g., Food, Clothing, Electronics).
    Orders: Number of orders placed by the customer.
    Amount: Total amount spent by the customer.

Installation:
To run the project, you need to have the following Python libraries installed
 - numpy, pandas, matplotlib, seaborn

Project Structure:
The code for this project is structured as follows-

    (i) Data Loading and Preprocessing:
          - The dataset is loaded using Pandas.
          - Columns with irrelevant or missing data (Status, unnamed1) are removed.
          - The data is cleaned by dropping rows with missing values, and the Amount column is converted to an integer type.

    (ii) Exploratory Data Analysis (EDA):
            - Gender-Based Analysis: Analyze total sales based on gender.
            - Age-Based Analysis: Study customer age groups and their spending patterns.
            - State-Based Analysis: Examine sales across different states and identify top regions for sales.
            - Marital Status Analysis: Understand how marital status impacts purchasing behavior, split by gender.
            - Occupation-Based Analysis: Investigate how different occupations correlate with spending amounts.
            - Product Category Analysis: Identify the most purchased product categories.
            - Product ID Analysis: Determine the top 10 best-selling products.

    (iii) Visualization:
            - Visualizations are generated using Seaborn and Matplotlib, including bar plots and count plots to provide insights on the following:
                -> Sales distribution by gender, age group, and marital status.
                -> Top-selling states and product categories.
                -> Best-selling products based on order volume.

    (iv) Conclusion:
          - Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are more likely to purchase products from the Food, Clothing, and Electronics categories.

Key Functions

    - Data Cleaning: Removal of irrelevant columns and handling missing data.
    - Descriptive Statistics: Generated using .describe() to provide a summary of key statistics like mean, standard deviation, minimum, and maximum values for numerical columns.
    - Grouping and Aggregation: Grouping data by various attributes (e.g., gender, age group, state, product category) to compute total sales and order counts.
    - Visualization: Various plots for visualizing the sales data and extracting insights.

Conclusion:
This project showcases how sales data can be analyzed using Python to uncover insights on customer behavior and sales trends. By segmenting customers based on gender, age, state, and occupation, businesses can better target their marketing strategies and optimize sales.
