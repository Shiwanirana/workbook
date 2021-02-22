# Day 3
_02/17/2021_

## What i learned in coding school is...
how to code

## 1. What is an Enum, and what are some use cases for them?
      Enum is a special class with a group of constants that are not changeable, only can be read.
      For Example:
      enum Months
      {
        January,       //0
        February,      //1
        March,         //2
        April          //3
      }

## 2. How can you modify an Enum?
      Enum can be modified by simply giving a value to the constant.
      For Example:
      enum Months
      {
        January,       //0
        February= 4,  //4
        March,        //5
        April         //6
      }

## 3. How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)
      We can use enum in rock paper scissors game.

      public enum Options
      {
        Rock,
        Paper,
        Scissors
      }
      
      public Winner(Options player, Options computer)
      {
        if(player == computer)
        {
          return "Draw";
        }
        else if(player == Options.Rock && computer == Options.Scissors || player == Options.Paper && computer == Options.Rock || player == Scissors && computer == Options.paper)
        {
          return "Player wins";
        }
        else 
        return "Computer Wins";
      }
      We are also using IEnumerable in our projects and is used to iterate among our classes using the for loop.

      Afternoon Project: GregsList Api in C# (https://shiwanirana.github.io/cgregsapi/.)