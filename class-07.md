# Tables

* A table represents information in a grid format. 
* Grids: allow us to understand complex data by referencing information on two axes.
* Each block in the grid is referred to as a table cell.
* In HTML a table is written out row by row.

### Basic Table Structure
![img](https://image.slidesharecdn.com/webengineeringtables-140902224819-phpapp02/95/html-tables-4-638.jpg?cb=1409698159)

![img](https://image.slidesharecdn.com/htmltables-180721142906/95/html-tables-2-638.jpg?cb=1532183439)

### Spanning ColumnS/Rows

* Sometimes you may need the entries in a table to stretch across more than one column (The colspan attribute can be used on a [th] or [td] element 
and indicates how many columns that cell should run across).
* You may also need entries in a table to stretch down across more than one row (The rowspan attribute can be used on a [th] or [td] element 
to indicate how many rows a cell should span down the table).

### Long Tables

* There are three elements that help distinguish between the main content of the table and the first and last rows.
* These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table.

![image](https://user-images.githubusercontent.com/79087406/110251275-6e6f4d80-7f88-11eb-81dc-5ede53ea2342.png)

# WAYS TO CREATE OBJECTS 



### THIS (IT IS A KEYWORD)

used inside functions and objects, Where the function is declared alters what this means. It always refers 
to one object, usually the object in which the function operates.

* FUNCTION IN GLOBAL SCOPE: When a function is created at the top level of a script (that is, not inside another object or function).
* GLOBAL VARIABLES: All global variables also become properties of the window object. 

### RECAP: STORING DATA

To organize your data, you can use an array or object to group a set of related values.

* VARIABLES: has just one key (the variable name) and one value. 
* Arrays: can store multiple pieces of information. 

### WHAT ARE BUILT-IN OBJECTS?

Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window.
These built-in objects act like a toolkit for creating interactive web pages. 

* BROWSER OBJECT MODEL: The Browser Object Model contains objects that represent the current browser window or tab.
* DOCUMENT OBJECT MODEL: The Document Object Model uses objects to create a representation of the current page.
* GLOBAL JAVASCRIPT OBJECTS: The global JavaScript objects represent things that the JavaScript language needs to create a model of.

### THE BROWSER OBJECT MODEL: (THE WINDOW OBJECT)

* The window object represents the current browser window or tab.
* It is the topmost object in the Browser Object Model, and it contains 
other objects that tell you about the browser. 

#### USING THE BROWSER OBJECT MODEL:

* Two of the window object's properties, inner Width and inner Height, show width and height of the browser window. 
* Child objects are stored as properties of t heir parent object. 
* The element whose id attribute has a value of info is selected, and the message that 
has been built up to this point is written into the page. 

### THE DOCUMENT OBJECT MODEL: (THE DOCUMENT OBJECT)

 is the document object, It represents the web page loaded into the current browser window or tab.
 
 ![image](https://user-images.githubusercontent.com/79087406/110252712-64048200-7f8f-11eb-9d98-1656929a847a.png)
 
 #### USING THE DOCUMENT OBJECT 
 
 * The details about the page are collected from properties of the document object. 
 * These details are stored inside a variable called msg, along with HTML markup to display the information. 
 * You have seen the document object's get El ementByid ().

### GLOBAL OBJECTS: STRING O BJECT 

Whenever you have a value that is a string, you can use the properties and methods of the String object on that value.

![image](https://user-images.githubusercontent.com/79087406/110252835-03297980-7f90-11eb-8cfd-5d80e1596f7d.png)

### DATA TYPES REVISITED

* Five of them are described as simple (or primitive) data types. 
* The sixth is the object (and is referred to as a complex data type). 

1) SIMPLE OR PRIMITIVE DATA TYPES 

 * String 
 * Number 
 * Boolean
 * Undefined: (a variable that has been declared, but no value has been assigned to it yet). 
 * Null: (a variable with no value - it may have had one at some point, but no longer has a value). 

2) COMPLEX DATA TYPE 

* 0bject 

### GLOBAL OBJECTS: NUMBER OBJECT 

Whenever you have a value that is a number, you can use the methods and properties of the Number object on it. 

![image](https://user-images.githubusercontent.com/79087406/110253119-4d5f2a80-7f91-11eb-9077-906d91c8b052.png)

### GLOBAL OBJECTS: MATH OBJECT 

The Math object has properties and methods for mathematical constants and functions. 

![image](https://user-images.githubusercontent.com/79087406/110253105-3b7d8780-7f91-11eb-8068-d9b5476dbc51.png)

### GLOBAL OBJECTS: DATE OBJECT (AND TIME) 

![image](https://user-images.githubusercontent.com/79087406/110253143-6f58ad00-7f91-11eb-872b-bcfdf7e8ad5a.png)

# Domain modeling
![img](https://miro.medium.com/max/700/1*UuZRQ57iPmEKsY5wsgGBLA.jpeg)

* is the process of creating a conceptual model in code for a specific problem.
* An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
* that's articulated well can verify and validate the understanding of a specific problem among various stakeholders.

### tips to follow when building domain models:

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Store the newly created object in a variable so you can access its properties and methods from outside.

#### example for Domain modeling

![img](https://i.stack.imgur.com/WkUGA.jpg)

