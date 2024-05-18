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





Sample Queries with sql output
1. List all customers.
![1](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/9c7c71a0-4aea-4e8d-8eae-2e142f8f6187)



2. Find all orders placed in January 2023.
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/21f36bbb-5450-4929-aaea-36b235dda685)

3. Get the details of each order, including the customer name and email.
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/31357b68-8995-46cd-bf97-1ba2269c572f)

4. List the products purchased in a specific order (e.g., OrderID = 1).
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/f87dbc8e-d638-4ba4-a1d7-b4c4778fca64)

5. Calculate the total amount spent by each customer.
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/cfebb01e-616a-4bbe-a936-f3682b14e634)

6. Find the most popular product (the one that has been ordered the most).
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/f3d5144d-e259-46ef-bd18-8c4eb4810707)

7. Get the total number of orders and the total sales amount for each month in 2023.
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/ccfde22d-ed87-4b9d-8813-754e85362cdc)

8. Find customers who have spent more than $1000.
![image](https://github.com/harshitha-911/2100031911__Backend/assets/110444788/a755a703-8081-4b13-b3a4-151a39feda68)

