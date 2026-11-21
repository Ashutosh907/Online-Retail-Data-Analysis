Added Online Retail Data Analysis project.# Online Retail Data Analysis

## 1. Project Overview

This project focuses on analyzing an Online Retail dataset to understand sales performance, customer purchasing behaviour, product performance, and order cancellations.

The objective is to extract meaningful business insights from retail transaction data using Python and Pandas.

## 2. Dataset Description

The dataset contains online retail transactions with information such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The original dataset is approximately 50 MB. It is not included in this repository due to GitHub's browser upload limit.
Dataset Source:https://www.kaggle.com/datasets/carrie1/ecommerce-data


## 3. Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 4. Data Cleaning

The following data cleaning operations were performed:

- Checked missing values and duplicate records.
- Converted InvoiceDate into datetime format.
- Removed duplicate records.
- Identified cancelled transactions.
- Filtered negative and zero quantities.
- Removed records with zero unit prices.
- Created new columns for order month, year, day, and time.
- Calculated revenue using Quantity × UnitPrice.

## 5. Exploratory Data Analysis (EDA)

Performed analysis on:

- Monthly sales and revenue trends.
- Country-wise revenue and order analysis.
- Top-performing products by revenue and quantity.
- Customer purchase behaviour.
- Average Order Value (AOV).
- Customer purchase frequency.
- Returns and cancellation analysis.
- Weekday sales performance.

## 6. Key Business Insights

1. **Monthly Sales:** November 2011 recorded the highest number of unique orders (2,769).
2. **Customer Activity:** November 2011 had the highest number of unique customers (1,664).
3. **Average Order Value:** December 2011 recorded the highest AOV (778.74).
4. **Cancellations:** January 2011 had the highest cancellation rate (17.62%).
5. **Customer Behaviour:** Customer 12748 placed 209 unique orders, making them one of the most frequent customers.

## 7. Conclusion

This project helped identify important patterns in retail sales, customer behaviour, product performance, and order cancellations.

The analysis provides useful insights that can support inventory planning, customer retention, personalized marketing, and reduction of order cancellations.

Through this project, I strengthened my practical skills in Python, Pandas, data cleaning, exploratory data analysis, data aggregation, and business insight generation.

## Author

**Ashutosh Barbole**

GitHub: [Ashutosh907](https://github.com/Ashutosh907)
