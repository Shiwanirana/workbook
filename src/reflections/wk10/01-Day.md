# Day 1
_02/15/2021_

## What i learned in coding school is...
how to code


## 1. What are the three categories of data types? How are they different?
      The three data types are:
      1. Value Type--> In this, the variables contain the values directly.
      For Example:
      int i = 5;
      2. Reference type--> A reference data type holds the address where the value is stored in place of the actual value. A reference type can never have a null value.
      3. Pointer type--> A pointer is variable whose value is the address of other variable. A pointer can have a null value.
      Syntax:
      type *variable-name;
      int *x;

## 2. What are the Value-type data types? What differences do you notice from JavaScript?
      Value Type--> The variables contain the values directly.
      Value types are:
      int,  char,  float,  double,  long,  short,  enum,  bool, etc.
      Javascript has number but in c# we, have int, float, double, etc.
      There is no 'undefined' data type in c#, but in javascript we have 'undefined'.

## 3. How do Reference types work?
      Reference data type holds the address where the value is stored.
      For example:
      string a = "hello";
      a--->0x726300(memory address)-->[0x648400](value of other address)
          0x648400(memory address)-->[hello](the actual value)
      Now in RAM, the system gives a random memory location to variable a, and in that memory location is the actual value "hello".

      Afternoon Project: RockPaperScissor in C# (https://shiwanirana.github.io/rockpaperscissor/.)
