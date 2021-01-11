# Day 2
_1/5/2020_

## What i learned in coding school is...
how to code


## 1. What are the three states of a Promise?
  Promise--> It means instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in future.
  It is created by using a 'new' keyword.
  A promise has three states:
    1. Pending--> The promise is started but not finished.
    2. Resolved--> The promise is completed successfully.
    3. Rejected--> The promise has failed.
## 2. How do promise seek to resolve the issues of "callback hell"?
   By using multiple async methods, we will quickly go into a callback hell situation but by using promises into your code callback hell can be avoided since it will be more cleaner and easier to read.

## 3. What is the difference between .then() and .catch() ?
      .then() is only for resolved, whereas, if a promise fails, we can use .catch().
      For example:
      function asyncFunction(){
        return new Promise((resolve, reject)=>{
          setTimeout(()=> {
            let num = Math.random() * 100;
            if (num<50){
              resolve("Success!");
            }else{
              reject("Failed!")
            }
          }, Math.random() * 3000)
        })
      }

      asyncFunction()
      .then(result =>{
        console.log(result);                         /*If num=45   output: Success!*/
      })
      .catch(error=>{
        console.log(error);                          /*If num=60   Output: Failed!*/
      })


      Day-2 Afternoon Project:   https://shiwanirana.github.io/mvc-gregslistapi/.