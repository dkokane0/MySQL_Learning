# MySQL_Learning



![mysql_import_db](https://user-images.githubusercontent.com/68640332/155476261-f6da5936-bd2b-43d4-9d86-a33bdd660287.PNG)
![mysql_import_check](https://user-images.githubusercontent.com/68640332/155476276-4a55324e-3ed8-4f8b-a765-e6a65174ee2a.PNG)


Key Differences Between Primary key and Unique key:
Primary key will not accept NULL values whereas Unique key can accept NULL values. A table can have only one primary key whereas there can be multiple unique key on a table.

### SQL JOINS
1. The MySQL INNER JOIN is used to return all rows from multiple tables where the join condition is satisfied. It is the most common type of join.
           
       SELECT columns FROM table1 INNER JOIN table2 ON table1.column = table2.column;  
2. The LEFT OUTER JOIN returns all rows from the left hand table specified in the ON condition and only those rows from the other table where the join condition is fulfilled.    
       
       SELECT columns FROM table1 LEFT [OUTER] JOIN table2 ON table1.column = table2.column; 
 
3. The MySQL Right Outer Join returns all rows from the RIGHT-hand table specified in the ON condition and only those rows from the other table where he join condition is fulfilled.
      
       SELECT columns FROM table1 RIGHT [OUTER] JOIN table2 ON table1.column = table2.column;  
      
