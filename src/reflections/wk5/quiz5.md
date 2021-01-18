# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CRUD: C--> Create 
      R--> Read
      U--> Update
      D--> Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
C-Create--> 201(Created)
R(Read)--> 200(OK)
U(Update)--> 405(Method Not Allowed)
D(Delete)--> 405(Method Not Allowed)
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM--> Stands for Object-Relational Mapping, is a library in NPM(Node Package Manager)
We are using Postman when interacting with MongoDB.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
PUT and POST are two HTTP request types that includes a body.

```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
1. Synchronous
2. Asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from "mongoose"
let Schema = mongoose.Schema;
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is a spacial function which contains three parameters, req(request), res(response) and next. When ever a user is logged in, express gives a request object with the user's information and also access to response object.

```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
1. Request
2. Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://localhost:8080/api?tag=winter
```