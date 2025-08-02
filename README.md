# Coffee Sales Project

## Project overview
This Excel project analyses coffee sales data to provide insights into product performance, sales trends, total sales over time, sales by country and other actionable business insights. It includes data cleaning, formula features, pivot tables, charts, and an interactive dashboard to help stakeholders make informed decisions.

## Dataset Used
- File Name:  <a href="https://github.com/preetibyte/coffee-project/blob/main/Coffee%20Sales%20Raw%20Data.xlsx">Coffee Sales Dataset</a>
- This dataset had three key tables. These tables contained all the details about the coffee shop’s sales transactions, customer info, and product specifics.    
  1. Orders     
  2. Customers    
  3. Products        

## Data Cleaning 
- Checking NULL values, blanks and Errors.
- Removing duplicates, and irrelevant columns.
- Make sure data is consistent and clean with respect to data type, data format and values used.

## Data Transformation
- Change the date format (from 9/5/2019 to 5-Sep-2019). 
- Added the units to the numbers by formatting them, like “kg” to the size and “$” to the price column. 
- Combine important columns from the three tables into one sheet. Creating a unified dataset makes easy to work with.
- Using XLOOKUP function to combine customer data (Customer name, email, country) from customer table into the orders table.
- Using INDEX MATCH to retrieve product data, which refers to coffee type, roast type, size, and unit price and insert into orders table.
- To calculate the sales, simply multiplied the columns “quantity” and “unit price”.
- By using IF function, standardized short-form names to full names to make the data more understandable, like changing “Rob” to “Robusta”.
- Important step was to turn the dataset into a table format, which makes it easier to classify and filter data, and is also useful when using pivot tables, as it is possible to refresh the pivot tables and new columns show up automatically.

## Data Analysis
Pivot tables were created to summarise the data and help identify trends in the dataset focusing on relationship between sales and other factors such as date, customers, country.

## Data Visualization
Finally, the dashboard was created by inserting and customizing the pivot charts of corresponding pivot table. For user friendly and interactive experience 3 "Slicers" and 1 “Timeline” were added.      
Below is a snapshot of the final dashboard.
<img width="1158" height="597" alt="coffee Sales Dashboard" src="https://github.com/user-attachments/assets/12a6c3ab-96d1-421a-8c52-ff431926119f" />



