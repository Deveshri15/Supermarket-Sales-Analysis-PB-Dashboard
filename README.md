# Supermarket-Sales-Analysis-PB-Dashboard
Supermarket Sales Analysis-PB-Dashboard

Data Preparation:-
Dataset:- Import the supermarket sales dataset as a CSV file into Power BI.[Storage Mode: Import]

Project Description:-
This project will involve a comprehensive analysis of supermarket sales data, including: 
 
 Data Cleaning:-
•	Remove duplicate records, if any.
•	Convert Date and Time columns to appropriate date and time formats.
•	Ensure numeric fields like Quantity, Unit Price, and Gross Income are correctly set as numeric data types.

Data Transformation:-
In Power Query Editor:
1.	Load and Clean Data: Load the dataset and clean the data by renaming columns and adjusting data types as needed.
2.	Calculated Columns:
- Total Sales: Compute using the SUM of Total for branch-level and product-level analysis.

- Report Design Visuals:
  Card Visual: A card visual in a platform like Power BI can effectively display KPIs like Total Sales, Total Transactions, Average Quantity, Average Unit Price, and Average Rating. Each KPI can be presented on its own card, allowing for a clear and concise overview.
A card visual in a platform like Power BI can effectively display KPIs like Total Sales, Total Transactions, Average Quantity, Average Unit Price, and Average Rating. Each KPI can be presented on its own card, allowing for a clear and concise overview.
  sales by product line and gender visualize through stack bar chart.
  Rating by product and gender visualize through ribbion chart.
  using Donut chart Gross income by gender and payment method visualize.
  I created a slicer for "City" to filter reports based on the location of transactions, or a slicer for "Payment Method" to analyze payments by type.

  Calculated Measures:-
o	Total Sales = SUM(Total)
o	Average Rating = AVERAGE(Rating)
o	Total Transactions = COUNTROWS('Supermarket_Sales-Data')
o Average Unit Price = AVERAGE('Supermarket_Sales-Data'[Unit price])
o Average Quanity = AVERAGE('Supermarket_Sales-Data'[Quantity])


This project provide sales performace of supermarket.






