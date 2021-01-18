# Day 4
_01/14/2021_

## What i learned in coding school is...
how to code

## 1. What is a virtual property?
      Virtual is an additional property of a database in which the values can be set manually or automatically. Virtual properties can not be saved in the database.
      Use virtual() with schema for the virtual properties.

## 2. When might you use a virtual property?
      You can use virtual property to set multiple properties at once.
      For example: if you have two properties, firstName and lastName, you can create a virtual property fullName by using both these properties.
      
## 3. How do you search by a virtual properties value?
      Virtuals have getters and setters. But Mongoose virtual properties only exists in its model not in the database. You need a query with non-virtual field.