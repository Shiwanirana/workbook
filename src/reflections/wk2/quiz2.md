# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
The keywords used to declare a variable are:
1. var-->Global scope,can be updated and re-declared.
2. let-->Local scope,can be updated but not re-declared.
3. char-->Local scope,neither be updated nor re-declared.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is defined as a block of code used to perform a particular task.
Syntax:
function function-name(parameters){
  //code written here
}

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID--> It stands for:
S-->Single responsibility principle: This means single function should be responsible for only one particular task. 
O-->Open closed principle:This means, 'open' for 'extension', but 'closed' for 'modification'. 
L-->Liskov substitution principle:a subclass should override the parent class methods in a way that does not break functionality from a client’s point of view.
I-->Interface segregation principle: A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.
D-->Dependency Inversion principle:Abstractions must not depend on details. Details must depend on abstractions.

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The index of pineapple is '2', or it can be written as,
fruit[2](= pineapple).
'fruit' is an array containing 5 elements. The index of an array always starts from '0'.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
Javascript basic conditionals are:
1. if-->If the condition is true.
2. else-->If statement with else condition.
3. else if-->Used for at least three conditions. 
4. Switch-->Block of code to be executed.
Other main conditional is:
4. Ternary--> Same as if else, but a single line statement.
Syntax:
condition? expressionIfTrue: conditionIfFalse
For example:
function person(isStudent){
  return(isStudent?'good':'bad')                         /*output: condition isStudent true returns good else return bad*/
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
for ( let i = 0; i < arr.length; i++ )
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for 'Document Object Model', it defines the logical structure of a document. HTML file is first accessed to render DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Six Data Types that are primitives, checked by typeof operator:
undefined : typeof instance === "undefined"
Boolean : typeof instance === "boolean"
Number : typeof instance === "number"
String : typeof instance === "string"
BigInt : typeof instance === "bigint"
Symbol : typeof instance === "symbol"
null : typeof instance === "object"
Structural Types:
Object : typeof instance === "object"
Function : a non-data structure, though it also answers for typeof operator: typeof instance === "function"

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters: are the variables listed as a part of the function definition.
Arguments: are the values passed to the function when it is invoked.
For example:
function function-name(parameter1,parameter2){     /*function sum(x,y){      */
  //code here                                      /*       //code here      */
}                                                  /*      }                 */

function-name(argument1,argument2)                  /* sum(2,5)             */
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive Value: The values are directly stored in the location that the variable can access. The primitive values stores data in the 'stack'.
Types of primitive values are:
1. Number
2. Boolean
3. String
4. Null
5. Undefined

Reference Value: The values are stored in the variable location acts as a pointer to a location in memory where the objects are stored. These values stores data in the 'heap'.
Types of reference values are:
1. Object
2. Array
3. Function
```