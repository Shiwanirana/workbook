# Foundations of Web Development

**1.** In the terminal, what is the command `cd` used for?
<!-- enter you answer in the space below -->
```Change Directory-->This command lets you change the current directory or to navigate to other folder.
```
**2.** In the terminal, what is the command `mkdir` used for?
<!-- enter you answer in the space below -->
```Make Directory-->This command lets you to make a new folder.
```
**3.** What is the `\<html>\</html>` tag in a document?
<!-- enter you answer in the space below -->
```<html>-->This is a starting tag which tells the browser that a page is coming up.
```</html>-->This is a closing tag which tells the browser about the page end.Everything on the web page should be between these two tags.
```
**4.** What does `HTML` stand for?
<!-- enter you answer in the space below -->
```Hyper Text Markup Language: This is a standard markup language used to design wed pages.
   HTML structure:
    <!DOCTYPE html>
     <html>
       <head>
         <title>Page Title</title>
       </head>
       <body>

        <h1>hello</h1>

       </body>
     </html>
```
**5.** What Does `CSS` stand for?
<!-- enter you answer in the space below -->
```Cascading Style Sheet: Used to style a web page using color, border, height, width, etc.
   There are three types of CSS:
   1. Inline CSS:These are used to style a specific HTML element. For example: <p style="color:red;">
   2. Internal CSS:These are also called embedded CSS and uses a style tag<style> in head tag<head>. For example:<style type="text/css">
   3. External CSS:These styles are written in a separate css file and this file is linked to HTML file by using link tag.
    For example: <link rel="stylesheet" type="text/css" href="style.css" />  /*link tag in HTML file(Index.html)*/ 
                 h1{ background-color: red;}   /*written in 'style.css' file*/
```
**6.** What are the three components that makeup a `CSS` rule? <br> Example:
```css
 h1.main-title {
   color : rgba(255, 210, 33, .75);
 }
```
<!-- enter you answer in the space below -->
```The three components are:
   1. Selector-->HTML element name, id name, class name, which actually selects an area of a page to be styled. 
   2. Property-->Name of the attribute you want to style for example color, border, background, height, width, position etc.
   3. Value-->Value that will be assigned to an attribute according to its specifications.
   For example:
     h1.main-title {                            /*Selector-h1(element name), .main-title(class name)*/
         color : rgba(255, 210, 33, .75);       /*Property-color : value-rgba(255, 210, 33, .75)*/
         }
         So this will give h1.main-title(selector) a mustard(value-rgba(255, 210, 33, .75)) color(property).
```
**7.** What property would you change if you wanted to make a font **Bold**?
<!-- enter you answer in the space below -->
```  The font-weight property of CSS makes a font look bold.
     For example:
     font-weight: bold;
```
**8.** In what tag does the majority of your code belong?
<!-- enter you answer in the space below -->
```  Majority of the code is in the body tag. What ever appears on a web page should be inside of a body tag.
     <body></body>
```
**9.** What three tags can be used to make lists (not list items)?
<!-- enter you answer in the space below -->
     The three tags are:
```  1. Unordered List : It is used to group a set of related items in no order.
        For example:
        <ul>                              /*Unordered List*/                  Result of Unordered List:
          <li>Coffee</li>                 /*List the item*/                    Coffee
          <li>Milk</li>                                                        Milk
        </ul> 
     2. Ordered List : It is used to group a set of related items in a specific order.
        For example:
        <ol>                               /*Ordered List*/                    Result of Ordered List:
          <li>Coffee</li>                  /*List the item*/                   1. Coffee
          <li>Milk</li>                                                        2. Milk
        </ol>  
     3. Description List : It is used to display name or value pairs such as terms and definitions.
        For example:                                                               
        <dl>                                /*Description List*/                Result of Description List:
          <dt>Coffee</dt>                   /*Defines the term*/                Coffee
            <dd>- black hot drink</dd>      /*Describes each term*/              - black hot drink
          <dt>Milk</dt>                                                         Milk
            <dd>- white cold drink</dd>                                           - white cold drink
        </dl>
```
**10.** Define the display `:flex property:`
<!-- enter you answer in the space below -->
```'display:flux' can be helpful when there is a large empty space and a developer wants to use that. It decides how to evenly    distribute the contents.
      For example:
      display:block;/*you have 3 boxes(h:10px,w:10px),now the boxes will take the size of entire row individually regardless of there  size*/
      Box 1(h:10px, w:10px)
      Box 2(h:10px, w:10px)
      Box 3(h:10px, w:10px)
      display:flex;/* It will evenly distribute the 3 boxes utilizing empty spaces.*/
      Box 1(h:10px, w:10px)                             Box 2(h:10px, w:10px)                                Box 3(h:10px, w:10px)
```
**11.** What `CSS` properties affect the size of a box model?
<!-- enter you answer in the space below -->
```The main properties that affect the size of a box model are 
   Height and Width,Padding, Border and Margin.
   For example:
   div{
     height: 50px;                   <--Gives height to the box/div--> 
     width: 50px;                    <--Gives width to the box/div-->  
     padding: 5px;                   <--Gives padding to the box/
     (padding: 5px 5px 5px 10px)        div(single value means same    
     
                                        padding to all the four sides, 
                                        otherwise the order of padding is:(Top-Right-Bottom-Left),padding is internal to the selector.-->
                       
     border: 6px solid #ffffff;       <--Gives border to the box/div    
     
                                         (includes border size, single,   straight, solid line, color of   border-->
     margin: 6px;                     <--Gives margin to the box/div  
     (margin: 6px 3px 7px 20px)
                                         (single value means same    
                                         margin to all the four sides, 
                                         otherwise the order of padding is:(Top-Right-Bottom-Left),margin is external to the selector.-->-->
   }

```
