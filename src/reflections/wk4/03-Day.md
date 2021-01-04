# Day 1
_12/6/2020_

## What i learned in coding school is...
how to code


## 1. What is the purpose of Async / Await?
They reduce the "don't break the chain" limitation of chaining promises.
syntax:
const doSomething = async () => {
  console.log(await doSomethingAsync())
}

## 2. What must you do in order to await a promise inside of a function?
    When you await a promise, the function is paused until the promise settles.Use setTimeout()function, in order to wait for a promise to finish before returning.

## 3. What are some of the primary benefits of Async/ Await ?
    1. Easier debugging: Debugging is hard on promises as debugger will not step over async code, but in case of async/await, it is easier as for the compiler its just like synchronous code. 
    2. Multiple async functions in series:
    Async functions can be chained easily making the syntax more readable and easy.