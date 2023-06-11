# Exp01 SQL query to fetch FIRST_NAME from the worker table using the alias

## AIM:

To fetch first name from sample work table using alias naming in SQL.
## ALGORITHM:
1. Create a sample table in SQL using CREATE TABLE syntax

2. Insert all the values and Titles respectively using INSERT INTO syntax

3. Now check whether all the rows are affected or not by fetching the table

4. After checking, now we can use alias naming for fetching First_Name column from the EMPLOYEE table

5. We can use its syntax ,SELECT Alias_name AS Alias_variable_name for fetching the column.The results will be displayed accordingly.
## PROGRAM:
```sql
create table Employee(
  First_name varchar(50),
  Last_name varchar(50),
  Age int
);
insert into Employee (First_name, Last_name,Age)
values ('Harry','Potter',21);
insert into Employee (First_name, Last_name,Age)
values ('Ron','Weasley',21);
insert into Employee (First_name, Last_name,Age)
values ('Hermione','Granger',21);
insert into Employee (First_name, Last_name,Age)
values ('Draco','Malfoy',21);
insert into Employee (First_name, Last_name,Age)
values ('Sirius','Black',40);
insert into Employee (First_name, Last_name,Age)
values ('Severus','Snape',40);
insert into Employee (First_name, Last_name,Age)
values ('Rubeus', 'Hagrid ',38);
insert into Employee (First_name, Last_name,Age)
values ('Neville', 'Longbottom ',22);
insert into Employee (First_name, Last_name,Age)
values ('Luna', 'Lovegood' ,22);


select First_name as fn from Employee;
```

## OUTPUT:
![image](https://github.com/VaishnaviMariappan/EXP01_SQL/assets/94169913/97bc4280-96b0-4660-ab85-bb943cc21a03)
## RESULT:
### Thus we have obtained the required column using alias.
