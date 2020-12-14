# Day 3
_12/9/2020_

## What i learned in coding school is...
how to code


## 1. What are the main ways to write information to the console? Why/when should you use each style.
      Console is an object which provides access to the browser's debugging console.
      The various ways to write information to the console are:
      console.log()--> It is used mainly to print the output to the console.
      For example: console.log(1) or console.log("Hello")   /*Gives output: 1   and  Hello*/
      console.count()--> It is used to count the number a function is hit.
      For example: for(let i=0;i<4; i++){console.count(i)}   /*Output: 0:1  1:1  2:1  3:1*/
      console.error()--> It is used to show an error message to the console. The error message will be highlighted in red color.
      For example: console.error("Error Message")       /*Output: Error Message*/
      console.warn()--> It is used to show a warning message to the console. The warning message will be highlighted in yellow color.
      For example: console.warn("Warning Message")      /*Output: Warning Message*/
      console.clear()--> It is used to clear the console window.
      For example: console.clear()     


## 2. Which tab allows you to see the breakpoints of HTML/CSS and how can this tab be useful when debugging HTML?
      'Source tab' in Dev tools allows us to see the breakpoints of HTML/CSS. Breakpoints work same as a debugger. It stops a code and accesses it line by line. Click on the line number and it will add a breakpoint to your code and then you can navigate to your code by up and down arrows on the right side of the window. 
      

## 3. Outside of writing everything to the console, what is a better way to debug your code?
      Writing a keyword 'debugger' to your code is also a better way for checking the code. It is same as adding breakpoints but instead of opening your code in the source tab and then adding breakpoint, it can be directly applied by writing debugger in the main code in virtual studio code.