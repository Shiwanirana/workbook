# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The Pillars of Object Oriented Programing are:
1. Encapsulation: Grouping of data anf functions
2. Abstraction: Hiding of Information
3. Inheritance: Sharing of information
4. Polymorphism: Redefining of Information
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
    Encapsulation is the idea that the data of an object should not be directly exposed. It is combining data and functions into a single unit called class. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
    S--> Single Responsibility Principle: Means a class should have one and only one job.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
     A class is basically used to create objects whereas an instance is a concrete thing made by using that class.
     For Example:
     class Box{
       length
       width        /*objects of class Box*/
     }
     let rectangle= new Box(7,8)       /*Instance of class Box*/
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
The Proxy object enables you to create an interceptor for an object to modify fundamental for that object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
    MVC is a design pattern which is used to keep data and display separate. Its prime function is to keep the code readable and manageable, which can be achieved by dividing the code into different sections like controller, service and model, each having their own specific functionality.

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
     Controller--> Controller in the MVC pattern acts like a clerk which is actually interacting with the user. Controller is basically used to draw something on a page and basically is used to call a function. Anything you are doing in your code should go through the controller. Controller provides an interface for the view to alter the model objects.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
     Service--> Service in the MVC pattern is like a brain. Whatever a function is doing should be in the Service section of MVC. The main logic of your code is in this section.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
     Model--> Model in MVC pattern is the part where the elements are  defined. The fields of the object that helps to get/set data from the object.

```

