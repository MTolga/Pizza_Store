# Pizza_Store
Database for pizza store including pizza types, orders and other details.

The given SQL code is a set of different SQL queries that can be executed on a database. The database in this case is "Pizza.dbo" which contains different tables, such as "pizza_types", "pizzas", "order_details", "orders".

The SQL functions and statements used in the code are:

JOIN: The join clause is used to combine the data from two or more tables into a single result set. In the first query, the JOIN clause is used to combine the data from the "pizza_types" and "pizzas" tables on the "pizza_type_id" column.

INNER JOIN: This type of join returns only the rows from both tables where there is a matching value in both tables. In the second query, the INNER JOIN is used to combine the data from the "order_details" and "pizzas" tables on the "pizza_id" column.

UPDATE: The update statement is used to modify data in a table. In the third query, the "price" column of the "pizzas" table is updated to 9.75 where the "pizza_id" column is equal to "pepperoni_s".

LEFT JOIN: This type of join returns all the rows from the left table and the matching rows from the right table. If there is no match, NULL values will be returned for the right table. In the fourth and fifth queries, the LEFT JOIN is used to combine the data from the "pizzas", "order_details", and "orders" tables on the "pizza_id" and "order_id" columns respectively.

SUM: The SUM function is used to calculate the sum of a set of values. In the second, sixth, seventh, and eighth queries, the SUM function is used to calculate the total revenue, total quantity, total amount and total revenue respectively.

GROUP BY: The group by clause is used to group rows that have the same values into summary rows. In the second, fourth, fifth, sixth, seventh, and eighth queries, the GROUP BY clause is used to group the data by different columns such as "pizza_id", "size", "price", "date", "pizza_type_id" and "quantity".

CASE: The case statement is used to evaluate a set of conditions and return a result based on the first true condition. In the fifth query, the CASE statement is used to categorize the orders into "Morning", "Afternoon" and "Evening" based on the time of the order.

COUNT: The count function is used to count the number of rows in a query. In the ninth and tenth queries, the COUNT function is used to count the number of orders and the quantity of pizzas ordered respectively.

DATEPART: The DATEPART function is used to extract a part of a date/time value. In the tenth and eleventh queries, the DATEPART function is used to extract the hour and weekday from the "time" and "date" columns respectively.

CAST: The CAST function is used to convert an expression from one data type to another. In the eleventh query, the CAST function is used to cast the result of the average quantity of pizzas ordered per order to a decimal with a precision of 10 and a scale of 3.
