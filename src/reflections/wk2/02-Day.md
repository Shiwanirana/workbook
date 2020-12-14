# Day 2
_12/8/2020_

## What i learned in coding school is...
how to code


## 1. What are the three ways to syntactically write a function? What are the differences in how the function acts(if any)?
      The three ways are:
      1. Function Declaration: A declared function can be saved for later use and will be executed when it is called.
      It is hoisted which means it can be used before it is defined.
      Syntax:
      function function-name(parameters){//code here}
      2. Function Expression: A function can be defined as an expression and can be stored in a variable.
      It is not hoisted, so can not be used before it is defined. 
      Syntax:
      var x= function(parameters)
      3. Arrow Function Expression: An arrow function is a short form for function expression.
      Syntax:
      var x=(parameters)=>{//code}

## 2. What is the difference between Parameters and Arguments?
      Parameters: are the variables listed as a part of the function definition.
      Arguments: are the values passed to the function when it is invoked.
      For example:
      function function-name(parameter1,parameter2){     /*function sum(x,y){      */
        //code here                                      /*       //code here      */
      }                                                  /*      }                 */

      function-name(argument1,argument2)                  /* sum(2,5)             */

## 3. What are higher order functions? Can you provide an example?
      A Higher-Order function is a function that receives a function as an argument or returns the function as output. 
      For example:
      1. Array.prototype.map: It is used to convert each element of an array.
      For example:
      let arr1=[1,2,3,4,5]
      let arr2=arr1.map(number=>number*2)
      console.log(arr2)                                                                            /*Output: arr2=[2,4,6,8,10]*/
      2. Array.prototype.filter: It is used to select certain items of an array. It accepts 3 arguments.
      For example:
      let arr1=[1,2,5,7,4,8,3]
      let arr2= arr1.filter(number=>number>=5)
      console.log(arr2)                                                                           /*Output: arr2=[5,7,8]*/
      3. Array.prototype.reduce: It is used to execute the callback function on each member of the calling array which results in a    single output value. It accepts two parameters.
      For example:
      let arr=[1,2,3,4,5]
      let sum= arr.reduce(function(accumulator,currentValue){return accumulator+currentValue})    
      console.log(sum)                                                                            /*Output: 15*/