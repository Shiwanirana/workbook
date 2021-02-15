# Day 5
_02/12/2021_

## What i learned in coding school is...
how to code

## 1. In a SQL table, what is the difference between information in a row and information in a column? How does this compare to using a document database?
      In a SQL table,
      Rows are called records, it includes the information/data
      Columns are called fields, it includes the information about someone you are mentioning in the rows.
      For example:
      Name        Age         ID       //(Column: Name, Age, ID)
      John        20          287394   //(Row: The actual data)
      Lee         24          835407

## 2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
      create table characters
      ( first varchar(20),
        last varchar(20),
        age number(3),
        description varchar(255),
        id int
      )

## 3. What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;
  
      1. A delete is used to delete the rows of a table. The above delete will delete all the row of the table, but as delete is a DML(data modification language) command, it can be rolled back.
      2. A drop is used to delete all the data and table at once and it can not be rolled back. It is a DDL(data definition language) command.

      Afternoon Challenge: Capstones Project