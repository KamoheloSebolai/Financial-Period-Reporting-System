# Financial-Period-Reporting-System

This project is aimed at analyzing and visualizing financial data over multiple periods, focusing on various financial metrics, including bad_amount, badi_amount, and total_amount. The dataset represents financial amounts across different customer groups and periods, and this project processes the data to uncover trends and insights. The goal is to track the total financial amount (total_amount) across time and visualize how it changes.

## Project Overview

In this project, we analyze a dataset that contains financial data across different customer groups and periods. Using Python, Pandas, and Matplotlib, we clean the data, process it, and visualize the trends of different financial amounts, especially the total_amount, over time. The project helps in understanding how financial amounts fluctuate across periods, potentially assisting businesses in making informed decisions.

The dataset has multiple columns that represent different financial categories such as:

- bad_amount: A financial value representing a specific category.
- badi_amount: Another financial metric with a different significance.
- g1_amount, l1_amount, l120_amount, etc.: Various amounts grouped by different financial categories.
- total_amount: The overall sum of the different amounts for the given period and customer group.

We focus on cleaning the data, identifying trends, and plotting visualizations of how these amounts evolve over time.

## Data Description
The dataset contains the following columns:

- demarcation_code: Code indicating the demarcation or region (e.g., BUF).
- period_code: The period for which the data is relevant (e.g., 2024M01).
- customer_group_code: A code representing the customer group.
- bad_amount: Amount in the bad_amount category.
- badi_amount: Amount in the badi_amount category.
- g1_amount: Amount in the g1_amount category.
- l1_amount: Amount in the l1_amount category.
- l120_amount: Amount in the l120_amount category.
- l150_amount: Amount in the l150_amount category.
- l180_amount: Amount in the l180_amount category.
- l30_amount: Amount in the l30_amount category.
- l60_amount: Amount in the l60_amount category.
- l90_amount: Amount in the l90_amount category.
- total_amount: The total of all the amounts for the given period.
- financial_year: The financial year (e.g., 2024).
- period_length: The length of the period (e.g., month).
- financial_period: The specific period identifier (e.g., 1).
- item: A code indicating the item type.
- amount_type: The type of the amount (e.g., ACT).


## Technologies Used
- Python: The primary programming language used for data manipulation and analysis.
- Pandas: Used for handling, cleaning, and analyzing the data.
- Matplotlib: Used for creating visualizations to represent trends in the financial data.
