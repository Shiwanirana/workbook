# Day 1
_12/15/2020_

## What i learned in coding school is...
how to code


## 1. What problem does using exports solve?
      Using export, you can just use those modules which are required in you code. 

## 2. How does export differ from export default?
      If you want to export multiple objects, you need 'export', 
      For example:
      function f1(){}
      function f2(){}
      export {f1},{f2}

      but if you want a single object, 'default export' is what you need. 
      For example:
      export default function f1(){}     

## 3. What is a benefit of using the Module System?
      1. Module system helps to organize a code in a better way.
      2. Debugging is easier.
      3. Performance is increased using this system.