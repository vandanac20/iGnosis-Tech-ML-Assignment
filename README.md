# iGnosis-Tech-ML-Assignment
# Customer Insights Analysis

This project focuses on analyzing customer transaction data to identify the most profitable products and characteristics of the most loyal customers. The analysis is based on two datasets: `transaction_data.csv` and `purchase_behaviour.csv`.

## Project Overview

The goal of this project is to help the marketing department focus on the most important market segments and position products more effectively. Specifically, we aim to:
- Identify the top 3 most profitable products.
- Determine the characteristics of the most loyal customers.

## Datasets

1. **transaction_data.csv**
   - Columns: DATE, STORE_NBR, LYLTY_CARD_NBR, TXN_ID, PROD_NBR, PROD_NAME, PROD_QTY, TOT_SALES

2. **purchase_behaviour.csv**
   - Columns: LYLTY_CARD_NBR, LIFESTAGE, PREMIUM_CUSTOMER

## Analysis Steps

1. Merge the datasets on `LYLTY_CARD_NBR`.
2. Calculate total sales for each product to identify the top 3 most profitable products.
3. Analyze customer segments to determine the characteristics of the most loyal customers.
4. Identify the best-selling product based on the total quantity sold.

## Results

### Top 3 Most Profitable Products

The top 3 most profitable products are identified based on total sales.

### Characteristics of Most Loyal Customers

Customer segments are analyzed based on total sales and transaction counts to determine the most loyal customers.

### Best-Selling Product

The best-selling product is identified based on the total quantity sold.
