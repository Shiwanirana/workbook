# Day 1
_01/4/2021_

## What i learned in coding school is...
how to code


## 1. What are some of the signs and causes of callback Hell?
   The main cause of callback hell is when you try to write javascript code from top to bottom in a way that the execution will take place similarly, but javascript is different. This will make your code messy.

## 2. What does the asynchronous mean and how are callbacks involved?
  Asynchronous code--> It is entirely independent of the other code. it does not matter if one code has started or stopped, there is no need to check on other code.
For Example:
PROCESS1        PROCESS4
     PROCESS3  PROCESS2
Callbacks take some time to produce a result. The asynchronous/ async aldo means take some time, not immediately.
  

## 3. Summarize the 3 ways to avoid/ fix callback hell
  Callback hell is simply a result of poor coding practice.
  The three ways to avoid callback hell are:
    1. Keep the code shallow: Naming functions can be effective for avoiding callback hell.
    2. Modularize: It is always important to make modules while writing a code which in turn gives you better understanding, easier for new developers to understand.
    3. Handle every single error: This will make your code stable.