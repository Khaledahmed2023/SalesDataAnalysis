# SalesDataAnalysis
This script processes daily sales data from a store that sells threads in various colors. 
It extracts information such as customer names, sales amounts, and thread colors from a messy string format.
After cleaning and organizing the data, it calculates total sales, counts the number of threads sold in each color, 
and prints out the results.

Data Description:
- The sales data is provided as a string named 'daily_sales'.
- Each transaction is separated by commas, and individual transaction details are separated by ';,;'.
- Each transaction contains customer name, sale amount, and thread color(s) information.
- The script cleans up the data by replacing the delimiter and splitting each transaction into its constituent parts.
- It then calculates total sales by summing up the numeric values extracted from the sales data.
- Additionally, it counts the occurrences of each color thread sold and prints out the results.
