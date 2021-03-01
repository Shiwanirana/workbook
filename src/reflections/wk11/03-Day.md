# Day 3
_02/24/2021_

## What i learned in coding school is...
how to code


## 1. What is SQL injection?
      SQL injection (SQLi) is a common attack that uses malicious SQL code to access the backend company sensitive information.
      The attacks can be an unauthorized way of doing things like viewing, deleting, etc.

## 2. What are 3 methods SQL injection can be done by?
      The 3 methods are:
      1. In-band SQLi--> This is the most common types of attack in which the attacker is using same channel of communication for the attacks and the results.
      Error-based: The database produces some sort of error due to the attacker's action and then the attacker uses that error message to gather information about the database.
      Union-based:The attacker uses the union statement which contains multiple select statements to gather the information.
      2. Inferential(Blind)--> These depend on the response and behavioral patterns of the server so are slow.
      Boolean: In response of the attacker's query the server send a response in true or false manner.
      Time-based: In this there is a wait in response from the server, and the attacker can see from the time that the response to be true or false.
      3. Out-of-band SQLi--> This is an alternative to both the above attacks. This can be done when certain features of the database is enabled.

## 3. How can we detect and sanitize SQL injection attacks?
      By limiting result sets like preventing blank searches, validating user's inputs and data prior processing can be helpful.

      Afternoon Project: https://shiwanirana.github.io/ctaskmaster/.
      