# Home_Sales

In this challenge, I used SparkSQL to determine key metrics about home sales data. Then, Spark was used  to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.


Parts of the Home_Sales Challenge:
1. A Spark DataFrame is created from the dataset. 
2. A temporary table of the original DataFrame is created. 
3. A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. 
4. A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. 
5. A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. 
6. A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places, and includes runtime.
7. A cache of the temporary "home_sales" table is created and validated. 
The query from step 6 is run on the cached temporary table, and the run time is computed. 
8. A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. 
9. A temporary table of the parquet data is created. 
10. The query from step 6 is run on the parquet temporary table, and the run time is computed. 
11. The "home_sales" temporary table is uncached and verified. 

Notes:
- Used Google Colab to run, due to techinical difficulties otherwise
- Did have help from tutors to work on the homework
