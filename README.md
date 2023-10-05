# All for One Project

The goal of this project was to practice the use of queries in the SQL language, using the MySQL relational database.

The database present in the northwind.sql file was used and it was decided to use containers to upload the application. Files were created in the deasfionN.sql format, each representing a query executed in the database. The remaining files were developed by Trybe.

Workbench was also used to visualize tables and queries.

### To start the project:
Clone the repository and run the commands below:
```
- docker compose up
- docker exec -it all_for_one bash
- npm install
```

### Project requirements:
| Requirement | Description |
|-----------|-----------|
| 01 | Display only product names from the 'products' table |
| 02 | Display data from all columns of the 'products' table |
| 03 | Write a query that displays the values of the column that contains the primary key of the 'products' table |
| 04 | Count how many records there are in the 'product_name' column of the 'products' table |
| 05 | Create a query that displays data from the 'products' table from the fourth record to the thirteenth |
| 06 | Display the data from the 'product_name' and 'id' columns of the 'products' table so that the results are in alphabetical order of names |
| 07 | Show only the ids of the last 5 records in the 'products' table ordered by 'id' |
| 08 | Make a query in the `employees` table that returns the full name of the employee (`first_name` and `last_name` columns) with the name `full_name` and also the full location (`city`, `state_province` and `address` columns ) with the name `location`. |
| 09 | Show all values in the 'notes' column of the 'purchase_orders' table that are not null |
| 10 | Show all data from table 'purchase_orders' in descending order ordered by 'created_by' where 'created_by' is greater than or equal to 3 |
| 11 | Display the data from the 'notes' column of the 'purchase_orders' table where it's Purchase generated based on the 'Order' value is greater than or equal to 30 and less than or equal to 39 |
| 12 | Show the results of the 'submitted_date' column of the 'purchase_orders' table where the 'submitted_date' is April 26, 2006 |
| 13 | Show the result of the 'supplier_id' column of the 'purchase_orders' table where the 'supplier_id' is 1 or 3 |
| 14 | Show results from the 'supplier_id' column of the 'purchase_orders' table where the 'supplier_id' is greater than or equal to 1 and less than or equal to 3 |
| 15 | Show only the hours, without the minutes and seconds, from the 'submitted_date' column of all records in the 'purchase_orders' table |
| 16 | Display results from the 'submitted_date' column of the 'purchase_orders' table that are between '2006-01-26 00:00:00' and '2006-03-31 23:59:59' |
| 17 | Show records from the 'id' and 'supplier_id' columns of the 'purchase_orders' table where the 'supplier_id' is either 1, or 3, or 5, or 7 |
| 18 | Show all records from the 'purchase_orders' table that have the value in the 'supplier_id' column equal to 3 and the value in the 'status_id' column equal to 2 |
| 19 | Show the number of orders that were placed in the 'orders' table using 'employee_id' equal to 5 or 6, and that were sent using the 'shipper_id' column method equal to 2 |
| 20 | Add to the 'order_details' table a record with 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL and 'inventory_id': 129 |
| 21 | Add with a single 'INSERT', two rows to the 'order_details' table with the same data as requirement 20 |
| 22 | Update all data in the 'discount' column in the 'order_details' table to 15. |
| 23 | Update the data in the 'discount' column of the 'order_details' table to 30, where the value in the 'unit_price' column is less than 10.0000 |
| 24 | Update the data in the 'discount' column of the 'order_details' table to 45, where the value in the 'unit_price' column is greater than 10.0000 and an id is a number between 30 and 40 |
| 25 | Delete all data in the 'unit_price' column of the 'order_details' table where the value is less than 10.0000 |
| 26 | Delete all data in the 'unit_price' column of the 'order_details' table where the value is greater than 10.0000 |
| 27 | Delete all data from table 'order_details' |
