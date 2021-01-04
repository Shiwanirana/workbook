# Day 3
_12/17/2020_

## What i learned in coding school is...
how to code

## 1. What are the two common operations that we will set in the handler?
      Handler is an object with 'traps'.
      The two main operation are:
      1. get --> for reading a property
      2. set --> for writing a property

## 2. What do you have to make sure you are doing with every Get to ensure the value does not become undefined?
      get operator takes two parameters, the object and the  property being accessed.
      You need to return the value stored in the key.
## 3. What are some of the benefits of the proxy object that we are using in our structure for applications? 
      Proxies are used in some browser frameworks. It wraps another object and operations and handle then on its own or allowing the object to handle them.
      The Syntax:
      let proxy = new Proxy(target,handler),
      where, target-->an object to wrap
             handler-->an object with traps.