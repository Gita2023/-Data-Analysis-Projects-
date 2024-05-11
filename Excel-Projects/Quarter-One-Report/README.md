This project involves data cleaning processes applied to product sales data to calculate the increase in product orders between the years 2022 and 2023. The following operations are performed on the data:

1. Check for duplicate data and remove it if it exists.
2. Standardize the product category names using an appropriate formula.
3. Extract the month and year from the order date using the `month()` and `year()` formulas.
4. Calculate the total before tax, which is equal to the retail price multiplied by the order quantity.
5. Calculate the order total, which equals the total before tax plus the tax due.
6. Calculate the total sales for Q1 (first quarter) using the `SUMIF` function with the year column as the criterion and a specified year, summing the order total in this case.
7. Use the `SUMIFS` function, which accepts multiple ranges of criteria and multiple criteria, to calculate sales for the years 2022 and 2023 by month.
