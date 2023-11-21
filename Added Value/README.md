90% of the "Added Value" script is done by me. The business team was interested in comparing the data in Snowflake with the data in the portal. For this goal:
1-I pulled out the tabale "FormSubValue" from Snowflake with SQL queries ( using Snoeflake connecter); and pivoted it around the " Filed_name" column  to generate a similar table to the portal's table.
2- I split the data based on years and cleaned the duplicate "work orders" or any null values and cleaned them.
3- Then imported the portal's data and compared them with Snowflake's data by features such as "work order number", " Submitted date", " Submission Id", etc.
4- Finally, it turned out the tables are very similar, just the portal's data isn't cleaned and has duplicates and null, then the result was presented in a dashboard.

![Value Added](Dashboard_ValueAdded.jpg)
![Value Added](Dashboard_ValueAdded2.jpg)
