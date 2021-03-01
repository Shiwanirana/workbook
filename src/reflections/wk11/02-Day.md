# Day 2
_02/23/2021_

## What i learned in coding school is...
how to code


## 1. What is the difference between a primary key and a foreign key?
      Primary key is a unique key in a table that can not accept null values and a table can have only one primary key, whereas, a foreign key is a column in the table that is primary key in another table and can accept multiple null values. A table can have multiple foreign key. 

## 2. What is an Alias?
      Alias is used to give a temporary name to a table or a column.
      For Example:
      SELECT column_name AS alias_name
      FROM table_name;

## 3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

Select doctors.doctorId, patients.id
From doctors 
RIGHT JOIN patients ON
doctors.patientId = patients.id

Afternoon Project:  https://shiwanirana.github.io/contractor/.