# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code--> It is dependent on the other block of code.The code only executes if the other code prior to it is completed, which means in a consistent order.
For Example:
PROCESS 1 --> PROCESS2 --> PROCESS3 --> PROCESS4

Asynchronous code--> It is entirely independent of the other code. it does not matter if one code has started or stopped, there is no need to check on other code.
For Example:
PROCESS1        PROCESS4
     PROCESS3  PROCESS2
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a process that waits for an event to occur. For example, clicking a mouse or pressing a key etc
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
O in SOLID principles stands for Open-Closed Principle: Objects should be open for extension but closed for modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Callback/ higher order function--> These are the functions that are passed as parameters to be called later.These functions will run after the other function is finished.
Commonly used callback functions are: map, find and filter.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
Promise--> It means instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in future.
It is created by using a 'new' keyword.
A promise has three states:
Pending--> The promise is started but not finished.
Fulfilled--> The promise is completed successfully.
Rejected--> The promise has failed.
.then and .catch methods are used on promise for success or failure
.catch method is used to capture an error from a promise
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
1. Using `$.ajax` : This allows to create a GET,POST,PUT or DELETE methods.
2. Using `$.get` : With `$.get`, it takes the URL as the first parameter and callback as the second.
3. Using `$.post` : It requests the inputs change. and takes the URL, the Data and the callback as parameters.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API--> Application Program Interface, is a messenger that takes requests, translates and returns response.
For Example: In a restaurant, a waiter acts as an APi, takes your order, translates it to the kitchen and returns your food.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Controller is responsible for contacting any APIs, services, databases, etc.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
It is used for hiding the values of an object inside a class, to prevent the direct access of unauthorized parties.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
HTTP response code for a successful request is : 200-299
For Example:
200 OK : Meaning the success depends on the HTTP methods like : GET, PUT, POSt, etc.
202 Accepted : The request has been received but not yet acted upon.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
The HyperText Transfer Protocol(HTTP) 500 internal server error, indicates that the server encountered an unexpected condition that prevented it from doing the request.
```