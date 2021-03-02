# Lists

Lists can be nested inside one another, There are three different types of lists:

### Ordered lists:

are lists where each item in the list isnumbered.


![img](https://i1.wp.com/www.webfulcreations.com/wp-content/uploads/2012/09/ordered-lists.jpg?w=347&ssl=1)


### Unordered lists:

are lists that begin with a bullet point.

![img](https://amazewebtech.com/wp-content/uploads/2020/03/types-of-unordered-list-in-html.gif)


### Definition lists: 

are made up of a set of terms along with the definitions for each of those terms.

![img](https://slideplayer.com/slide/13664890/84/images/5/Definition+Lists+in+HTML.jpg)

# Boxes

### Box Dimensions (width, height)

By default a box is sized just big enough to hold its contents, you can use the height and
width properties.

### Limiting Width (min-width, max-width)

Some page designs expand and shrink to fit the size of the user's screen.

min-width: property specifies the smallest size a box can be displayed at when the browser
window is narrow.

max-width: property indicates the maximum width a box can stretch to when the browser
window is wide.

![img](https://miro.medium.com/max/730/1*wTfLqr-Og1W5LvUCqV7X-Q.jpeg)

### Overflowing Content

The overflow property tells the browser what to do if the content contained within a box is larger
than the box itself.

have two values:

1) hidden: This property simply hides any
extra content that does not fit in the box.

2) scroll: This property adds a scrollbar to the box so that users can scroll
to see the missing content.

#### Every box has three available properties that can be adjusted to control its appearance:

![image](https://user-images.githubusercontent.com/79087406/109612582-9dc12d00-7b38-11eb-91cc-4b62314ef826.png)

### White space & Vertical Margin

Border Width

The border-width property is used to control the width of a border.

Border Style

You can control the style of a border using the border-style property.

Border Color

You can specify the color of a border using either RGB values, hex codes or CSS color names
(as you saw on pages 251-252).

Shorthand (border)

The border property allows you to specify the width, style and
color of a border in one property.

padding

The padding property allows you to specify how much space should appear between the
content of an element and its border.

margin

The margin property controls the gap between boxes. Its value is commonly given in pixels,
although you may also use percentages or ems.

# ARRAYS

What do you know about it?

It is a special type of variable, It doesn't just store one value; it stores a list of values.

### CREATING AN ARRAY
https://miro.medium.com/max/1398/1*sGqOnNBQy7J7Cnmwf_ZlWg.png
You create an array and give it a name just like you would any
other variable (using the var keyword followed by the name of the array). 

![img](https://miro.medium.com/max/1398/1*sGqOnNBQy7J7Cnmwf_ZlWg.png)

### VALU ES IN ARRAYS

Values in an array are accessed as if they are in a numbered list. It is important to know that the
numbering of this list starts at zero (not one). 

#### NUMBERING ITEMS IN AN ARRAY :

Each item in an array is automatically given a number called an index. 

#### ACCESSING ITEMS IN AN ARRAY 

To retrieve the third item on the list, the array name is specified
along with the index number in square brackets. 

#### NUMBER OF ITEMS IN AN ARRAY 

Each array has a property called length, which holds the number
of items in the array.

### EXPRESSIONS 

 evaluates into (results in) a single value, 
there are two types of expressions: 

1) EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE 

2) EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE

## IF ... ELSE STATEMENTS

Here you can see that an if ... e 1 se statement allows you
to provide two sets of code:

1. one set if the condition
evaluates to true

2. another set if the condition is
false 

![img](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-if-else-statment.png)

## SWITCH STATEMENTS 

starts with a variable called the switch value. 

Each case indicates a possible value for this variable and the code that should run if the
variable matches that value. 

![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Switch-case-execution-flow.jpg)

#### TYPE COERCION & WEAK TYPING 

If you use a data type JavaScript did not expect, it tries to make sense of the operation rather
than report an error. 

#### TRUTHY & FALSY VALUES

every value in JavaScript can be treated as if it were true or false; and
this has some interesting side effects. 

#### CHECKING EQUALITY & EXISTENCE 

Because the presence of an object or array can be considered truthy, it is often used to check
for the existence of an element within a page. 

#### SHORT CIRCUIT VALUES 

Logical operators are processed left to right. They short-circuit (stop) as soon as they have a
result - but they return the value that stopped the processing (not necessarily true or fa1se).

# loops

check a condition. there are three types of loop:

### 1) for 

if you need to run code a specific number of times.

![img](https://cf.ppt-online.org/files1/slide/f/fqUhbIKJBalrm6FYzyjCWpQE4ATOSu1GgHZcv5XN7D/slide-6.jpg)

### 2) while

if you do not know how many times the code shold run.

![img](https://cf.ppt-online.org/files1/slide/f/fqUhbIKJBalrm6FYzyjCWpQE4ATOSu1GgHZcv5XN7D/slide-8.jpg)

### 3) do while

it will always run the statement inside the curly braces at least once.

![img]( https://media.geeksforgeeks.org/wp-content/uploads/20191118154342/do-while-Loop-GeeksforGeeks2.jpg)

