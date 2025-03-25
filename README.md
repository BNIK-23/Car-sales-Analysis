
![Screenshot 2025-03-25 141309](https://github.com/user-attachments/assets/0cf523cb-3e3b-4ecc-8449-c8d3fc693bdb)


OBJECTIVE
To analyze the Car Sales Dataset to understand the factors that affect car sales as well as the best and worst sellers of the cars, the best and worst selling car makes and body types.

Dataset
Dataset used is from Data.gov website.

Data cleaning Steps:
Created a Star Schema out of the dataset in Power Query.
Deleted unwanted columns for my analysis.
Changed column data types.
Converted the date column into a UK type date format and formatted it as date column.
Removed duplicate values, as well as empty and null values.
Standardized columns casing.
Ensured that Vehicle Identification Numbers in the dimensional table as well as the fact table are the same by merging queries and using the inner join.
Created new custom columns to partition the continuous values in columns Condition and Odometer are divided into ratings/classes.

Tools Used:
Power BI and Power Query

Created a calculated column to calculate the Car Age and then made another conditional column to assign the different ages to classes.
Created a Date table to aid in any time intelligence calculations that may be needed.
Applied DAX formulas to create measures to aid in my analysis.

KPI analyzed include:
Total sales
Average Sales
Sales Trend over time.
Top selling car sellers
Top selling car makes and body types.
Car age effect on sales.
