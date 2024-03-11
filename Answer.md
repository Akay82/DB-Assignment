1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram ?

Answer:-

firstly its an Relational DataBase Where One Id is Used in multiple Schema's we can refer this as 
"one to many" Relational database where we have one Parent and it can have Multiple children but each children have only one parent which is product Schema or table 

- "Product" Table Contains ID which is a primary key which should be unique.

- "Category_id" work as a foreign key in "product_Category table".

- This foreign key makes the connection between two tables.


2. How could you ensure that each product in the "Product" table has a valid category assigned to it ?

Answer:-

To Solve this, we will use the "category_id" of "product" table as a foreign key in "product category" table.

- it will link the product table to category table with a unique id


3. Create schema in any Database script or any ORM (Object Relational Mapping) ?
Answer :-

its answer written in app.js