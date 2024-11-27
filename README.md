# Customer Segmentation Analysis: Driving Effective Marketing with Data-Driven Insights

### Project Overview
The project aims to analyze customer data to identify distinct segments within the customer base. By understanding these segments, businesses can create targeted marketing strategies, improve customer engagement, and drive higher sales and retention rates.

### Project Structure
This project follows a structured approach, documented through the following steps:

#### Dataset:

1. InvoiceNo    : a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
2. StockCode    : a 5-digit integral number uniquely assigned to each distinct product	
3. Description  : product name
4. Quantity     : the quantities of each product (item) per transaction
6. InvoiceDate  : the day and time when each transaction was generated
7. UnitPrice    : product price per unit
8. CustomerID   : a 5-digit integral number uniquely assigned to each customer	
9. Country      : the name of the country where each customer resides	


Online Retail
Source: UC Irvine Machine Learning Repository
Link: https://archive.ics.uci.edu/dataset/352/online+retail

#### Methodology
- Exploratory Data Analysis: Cleaned and preprocess the dataset, identifying trends
- CLustering: K-Means
- Data transformation: Principal Component Analysis (PCA)

#### Tools
Python, Google Slides

### Results

#### Exploratory Data Analysis
Link: https://github.com/akuabubuq/customer-segmentation-analysis/blob/main/Exploratory%20Data%20Analysis.ipynb
1. Data Cleaning and Preprocessing:
- Mostly user in dataset comes from united kingdom, hence we will filter the data to only United Kingdom customers
- There is 135080 nulls value in Customer ID and 1454 nulls value in Description
- December 2011 doesn't have a full month day, hence we will filter out records in December 2011
2. Findings
- Monthly sales have shown growth over the past four months, driven by an increase in the number of orders from our users.
- However, the average order value has been declining, indicating that customers are spending less per order.
- The retention rate has fluctuated over the last 11 months, reflecting inconsistencies in retention across cohorts.
- Only about 38% of our user base has made recent transactions, highlighting a weak performance in user retention.

#### Clustering Analysis
Link: https://github.com/akuabubuq/customer-segmentation-analysis/blob/main/Clustering%20Analysis.ipynb

#### Slides Presentation: Marketing Analysis
Link: https://docs.google.com/presentation/d/12-taL0XsSVlQ8S6-2UnQLVqBUYdFnbYi_Jx1F3TWrsk/edit?usp=sharing
