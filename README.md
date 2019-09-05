# tableau
This repository contains the analysis done using Tableau

1. Annual Bonus Analysis

Source File: OfficeSupplies.csv
This file contains the data about the order details of the region. It includes the represenative name, item and unit sold.
Attributes: OrderDate,	Region,	Representative Name,	Item,	Units,	Unit Price

Question: The store operates in the three regions and only the top performing employee in each region qualifies for a bonus. Find out which three employees are eligible to get bonuses for this year. Employees are measured on totat sales($)

Solution File Name: Region_Wise_Each_Rep_Total_Sales.tbw
Create a calcuated field Total Sales = [unit price]*[units sold]

2. Timeseries, Aggregation and Filters

Source File: Long-Term-Unemployment-Statistics.xlsx
