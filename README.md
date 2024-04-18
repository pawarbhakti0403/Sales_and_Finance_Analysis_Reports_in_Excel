# Objective:

AtliQ Hardware is a company that sells hardware like PCs, Mouse, Printers, etc. to different customers. They have 2 types of customers, one is Physical stores that are known as Brick & Mortar like Croma and Best Buy and the second is E-commerce like Amazon and Flipkart. 

The AtliQ Business users have been given files to build reports the data contains more than 7 Lakhs records, and have to build sales and financial reports of the company.

# The Reports consists of 
## Sales Report:
1. Customer Net Sales Performance
2. Market performance Vs target
3. Division report
4. New products in 2021
5. Top 5 Countries in 2021
6. Top & Bottom 5 products

## Finance Report:
1. P & L statement by Fiscal year
2. P & L statement by Market
3. GM % by Quarters

# Workflow:

#### 1. ETL (Extract, Transform & Load) & Power Query:
Loaded all CSV files to power query and ensured that there were no missing values, removed duplicates, checked data quality and integrity, and verified the unique and distinct values are equal for the primary id column of the dimension table. 
#### 2. Data Modelling: 
Connected all the tables in a Star Schema. Created the dim_date table in power query containing Date, Month, Year, Fiscal Year & Fiscal Month then connected dim_date to the model in power pivot.
#### 3. Power Pivot & Pivot Table:
Leveraged power pivot to create new measures and columns, ensuring seamless integration between the datasets. Utilized pivot table to create a report, analyzing the customer net sales, marketing performance & target achieved.
#### 4. DAX (Data Analysis Expressions):
Created 10+ new measures like net sales for each customer as well as growth% for the current year compared to the previous year, COGS, Gross Margin, and GM % by using formulae such as sum, calculate, divide, etc. Created new Columns using Functions like Related, Calculate, Format, and extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.
#### 5. Conditional Formatting:
Applied conditional formatting to enhance the data presentation & readability for effective decision-making.

# Insights:
1. The top 3 customers of AtliQ are Amazon, AtliQ e-store & Atliq exclusive.
2. In 2021, AtliQ launched 16 new products with the highest sales obtained by AQ Quarty, AQ Trigger, and AQ Gen Y.
3. A notable amount of 51.6 million in Gross Margin is observed for the India
