# Day 3
_01/13/2021_

## What i learned in coding school is...
how to code

## 1. In simple terms what is a sub-document?
      When a document is nested in other document, it is called a sub-document.
      
## 2. When might you use a sub-document?
      When you want to see a document with its additional features nested in it, so that you have clear understanding of what is going on.
      For Example:
      const assignmentSchema = new Schema({
        title: {type: String, unique: true},
        //sub-document
        classroom:{
          title: String, keys: String
        }
      })
## 3. How do you add to a collection of sub-documents? What about editing then?
      Steps to add a su-document:
      1. Pass a nested object into a new Model.
      2. Then add the properties into that document.
      3. Then save the document by using .save()

      For editing:
      1. Use a function findOne(), for finding the document you want to edit.
      2. Now get the array/object you want to edit.
      3.Edit the array according to your need.
      4. Save the document using save() function.
