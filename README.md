# STORE-PERFORMANCE-ANALYSIS

## Project Outline

1. [Data Collection](#data-collection)
2. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
3. [Data Analysis](#data-analysis)
4. [Dashboard Creation](#dashboard-creation)
5. [Insights and Recommendations](#insights-and-recommendations)
6. [Documentation](#documentation)

## 1. Introduction
The purpose of this project is to provide a comprehensive analysis of the performance of multiple store locations for a coffee shop chain. The analysis covers the period from January 2023 to June 2023. The project aims to help stakeholders understand sales performance, identify trends, and make informed decisions to improve store operations.

## 2. Data Overview
The dataset used for this analysis includes the following columns:
- `transaction_id`: Unique identifier for each transaction.
- `transaction_date`: Date of the transaction.
- `transaction_time`: Time of the transaction.
- `transaction_qty`: Quantity of items purchased in the transaction.
- `store_id`: Unique identifier for each store.
- `store_location`: Location of the store.
- `product_id`: Unique id
entifier for each product.
- `unit_price`: Price per unit of the product.
- `product_category`: Category of the product.
- `product_type`: Type of the product.
- `product_detail`: Detailed description of the product.
- `Total sales`: Calculated by multiplying `transaction_qty` by `unit_price`.

- <img width="937" alt="Annotation 2024-08-01 155814" src="https://github.com/user-attachments/assets/d88262cb-36ec-43a9-b476-eec26c09cdc5">


## <a name="data-collection"></a>Data Collection
- Gather transaction data for each store location from January 2023 to June 2023.

## <a name="data-cleaning-and-preparation"></a>Data Cleaning and Preparation
The data cleaning process involved the following steps:
- The data was downloaded from Kaggle and loaded into Excel.
- A check for duplicates was performed, and none were found.
- The dataset contains 12 columns and 149,117 rows.
- A calculation was performed to add the `Total sales` column by multiplying the `unit_price` by `transaction_qty`.

- <img width="790" alt="Annotation 2024-08-01 160352" src="https://github.com/user-attachments/assets/ee68489e-bc09-4eb2-bd2a-aad490ec5c39">

- The cleaned data was then loaded into Power BI to create the dashboard.

## <a name="data-analysis"></a>Data Analysis
The dashboard features several key KPIs to evaluate store performance:
- **Total Sales (Revenue)**: $698.8K
- **Number of Stores**: 3
- **Units Sold**: 149.1K
- **Sales by Store Location**: Breakdown of total sales for each store location.
- **Number of Transactions by Percentage**: Proportion of transactions for each store location.
- **Total Sales by Month**: Sales trends over the six-month period.
- **Total Sales of Store Location by Month**: Monthly sales comparison across store locations.
- **Sales by Product Category**: Total sales distribution by product category.

## <a name="dashboard-creation"></a>Dashboard Creation
The dashboard includes the following visualizations:
- **Total Sales by Store Location**: Horizontal bar chart showing total sales for Hell's Kitchen, Astoria, and Lower Manhattan.
- **Number of Transactions by Percentage**: Donut chart displaying the percentage of transactions for each store location.
- **Total Sales by Month**: Line chart illustrating the monthly sales trend from January to June.
- **Total Sales of Store Location by Month**: Stacked bar chart comparing monthly sales for each store location.
- **Sales by Product Category**: Treemap showing sales distribution across different product categories like Coffee, Tea, Bakery, etc.

- 
<img width="739" alt="Annotation 2024-08-01 145915" src="https://github.com/user-attachments/assets/9fb4977d-d42d-416c-b2c7-566a3e306b4d">

## <a name="insights-and-recommendations"></a>Insights and Recommendations
Based on the analysis, the following recommendations are suggested to improve store performance:
- **Focus on High-Performing Categories**: Invest in promoting top-selling categories like Coffee and Tea to boost overall sales. For example, Coffee sales reached $269.95K, indicating strong customer preference.
- **Enhance Low-Performing Categories**: Identify and address potential issues with lower-performing categories to improve their sales. For instance, promoting the "Drinking" category more aggressively could increase its current sales of $72.42K.
- **Monitor Monthly Trends**: Continue monitoring monthly sales trends to identify any seasonal patterns or anomalies. Noting that sales increased from $0.08M in January to $0.17M in June suggests effective promotional strategies during this period.
- **Evaluate Store-Specific Strategies**: While stores are performing similarly, explore store-specific strategies to cater to local customer preferences and further boost sales. For example, the Hell's Kitchen store slightly outperformed other locations in monthly sales, suggesting location-specific customer preferences.

## <a name="conclusion"></a>Conclusion
This Store Performance Analysis project provides valuable insights into the sales performance of different store locations and product categories. By leveraging these insights, stakeholders can make informed decisions to optimize store operations, enhance customer satisfaction, and drive revenue growth.

