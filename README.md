# 2100031911__Backend

#Task
 For this example, let's assume we have a simple database for a retail store. Our database has the following tables:

1. Customers : Information about customers.
2. Products: Information about products.
3. Orders: Information about orders made by customers.
4. OrderItems: Information about items in each order.

 Table Structures

 Customers
 CustomerID       FirstName         LastName                 Email                          DateOfBirth 
 1                John                Doe                 john.doe@example.com              1985-01-15 
 2 	 	            Jane 		           Smith 	              jane.smith@example.com            1990-06-20 

Products
 ProductID 		 ProductName		        Price 
 1 			       Laptop 		            1000 
 2		        Smartphone       	      600 
 3            Headphones              100 
 
Orders
  OrderID 		 CustomerID 		   OrderDate  
     1 			     1		          2023-01-10 
     2			     2          		2023-01-12 

 OrderItems
 OrderItemID 		 OrderID 		 ProductID 		 Quantity 
        1 			      1   			  1         	 1       
        2             1           3            2      
        3			        2           2            1   
        4             2           3            1 

Sample Queries
1. List all customers.
2. Find all orders placed in January 2023.
3. Get the details of each order, including the customer name and email.
4. List the products purchased in a specific order (e.g., OrderID = 1).
5. Calculate the total amount spent by each customer.
6. Find the most popular product (the one that has been ordered the most).
7. Get the total number of orders and the total sales amount for each month in 2023.
    8.Find customers who have spent more than $1000.
