# Day 1
_12/7/2020_

## What i learned in coding school is...
how to code

## What is Scope?
   A scope defines a boundary to a variable. When ever a variable is declared, it can be accessed by various functions according to its boundary limits. A scope can be of two types:
   1. Local Scope: It has a limited boundary or it bs accessed within a limited area. If a variable is defined inside of a particular function, its scope is local to that unction,which means only that function can access that variable.
   
   2. Global Scope: As per the name, it has global access,which means if a variable is globally declared, any function can access its value when ever is required. It is always declared outside of a function.
   For example:
   var y=5;
   function number(){                  
   var x = 3;            
   console.log(x);    Result of console.log(x) is: 3(Local in scope)
   console.log(y);    Result of console.log(y) is: 5(Global in scope)
   }

## What is Hoisting?
   When you use some function or variable even before declaring them, it is known as hoisting. It is a default behavior of javascript. One of the benefit of hoisting is that it allows a function call even before it appears in the code.

## In what cases might you use let vs const vs var?
   Var has a global scope, while const and let has a local scope. Var variables can be re-declared and updates within its scope, let variables can be updated but can not be re-declared where as const variables can neither be updated nor re-declared. So if you know the value of your variable is fixed, you can use 'const' else 'var' or 'let' as per the requirement and scope.  