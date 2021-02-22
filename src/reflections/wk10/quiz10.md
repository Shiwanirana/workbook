# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A 'namespace' is used to keep one set of names separate from others. If you have two classes with same name, then one class declared in one namespace does not conflict with the other class declared in other namespace.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
'Class' is a reference type, means two variables can have same reference and so the operation on one variable will affect the other variable, whereas 'struct' is a value type, which means each variable contains its own copy of values and an operation on one variable can not affect the other variable.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
'void' is the method that returns an instance of a class, yet no return type.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
The access modifier is 'public' for the Start() method.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
'string' is a data type that indicates that the information here is of that type.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract means this class is restricted and can not be used to create objects, but in case you want to access it, than it must be inherited from other class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A 'virtual' means declared in the base class and redefined by a derived class according to its own need.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
1. Private--> accessible within the same class.
2. Public--> accessible to all the classes.
3. Protected--> accessible within the same class, or in a class that is derived from that class.
4. Internal--> accessible within the current assembly.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
A private class hides its member variables and functions from others. Only functions of the same class can access its private
```