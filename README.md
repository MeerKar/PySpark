# PySpark

This small project, is to find out the knowledge of SparkSQL to determine key metrics about home sales data. 
 Spark is used to create temporary views, partition the data, cache and uncache a temporary table,
and verify that the table has been uncached.



Using SparkSQL is following questions has been answered:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

<img width="250" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/d7d5c331-57f9-4d08-8ef5-78537e9a14f6">

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

<img width="241" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/a93fe72d-9f12-4226-b76d-63d7e9ce5f48">


What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 
Round off your answer to two decimal places.

<img width="330" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/1d38949a-4fd9-4890-91e9-af889bb01456">


What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

<img width="370" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/27fe6a50-aecb-4153-8eb2-dc474b4703ca">

Cache your temporary table home_sales.

<img width="330" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/8b36f6db-55de-42df-bf80-b4854fff2abc">


Check if your temporary table is cached.

<img width="378" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/414c9108-2af9-4dc2-9462-6732ad459238">

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. 
Determine the runtime and compare it to uncached runtime.

<img width="349" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/388467ae-8507-454c-82ba-68c2e25e12d9">

Partition by the "date_built" field on the formatted parquet home sales data.

<img width="756" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/11371ff9-3efe-4b72-8338-80777e46691b">

Partition by the "date_built" field on the formatted parquet home sales data.


Create a temporary table for the parquet data.

<img width="460" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/361e1a0b-e19e-4dcb-ac06-96c2074661bd">

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

<img width="353" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/6bfcfde6-3e31-4360-b3a2-ee11854b92b2">

Uncache the home_sales temporary table.

<img width="383" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/2f3162af-d135-4dc5-888f-9726e0b1e0a6">

Verify that the home_sales temporary table is uncached using PySpark.

<img width="367" alt="image" src="https://github.com/MeerKar/PySpark/assets/116701851/aa04578f-d0c6-4a56-ac28-0f22e5c7a959">
