# OBJECT

Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world.

variables and functions take on new names:

*  VARIABLES BECOME PROPERTIES.
*  FUNCTIONS BECOME METHODS.

It has five properties and one method. The object is in curly braces. It is stored in a variable called hotel . 

![image](https://user-images.githubusercontent.com/79087406/110230570-9922bd00-7f1a-11eb-84b7-3277b0e2f844.png)

# Document Object Model (DOM) 

specifies how browsers should create a model of an HTML page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

### THE DOM TREE IS A  MODEL OF A WEB PAGE 

![image](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)

* As a browser loads a web page, it creates a model of that page.The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes.
* Each node is an object with methods and properties.
* Accessing and updating the DOM tree involves two steps: 

1)Locate the node that represents the element you want to work with. 
2)Use its text content, child elements, and attributes. 

### Caching DOM Queries

Methods that find elements in the DOM tree. 

### ACCESSING ELEMENTS 

DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

METHODS THAT RETURN ELEMENT:

* GROUPS OF ELEMENT NODES: If a method can return more than one node, it will always return a Nodelist.
* FASTEST ROUTE: Finding the quickest way to access an element within your web page will make the page seem faster and/or more responsive. 

### NODELISTS: 

* Nodelist is a collection of element nodes.Each node is given an index number.

The order in which the element nodes are stored in a 
Node List is the same order that they appeared in the 
HTML page. 

When a DOM query returns a Nodelist, you may want to: 

1) Select one element from the NodeList. 
2) Loop through each item in the Nodelist and perform the same statements on each of the element nodes.

* they are a type of object called a collection, look like arrays and are numbered like arrays.

* Nodelist properties and methods:

1) The l ength property tells you how many items are in the Nodelist. 

2) The i tern() method returns a specific node from the Nodelist when you tell it the index number of the item that you want (in the parentheses). 

### TRAVERSING THE DOM 

When you have an element node, you can select another element in relation to it using these five properties. 

* parentNode: ThpreviousSibling 
* nextSibling: These properties find the previous or next sibling of a node if there are siblings.
* first Child last Child: These properties find the first or last child of the current element. 

### WHITESPACE NODES 

Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements. 

### HOW TO GET/UPDATE ELEMENT CONTENT 

To work with the content of elements you can: 

1) Navigate to the text nodes: This works best when the element contains only text, no other elements. 
2) Work with the containing element: This allows you to access its text nodes and child elements. 

* CCESS & UPDATE A TEXT NODE WITH NODEVALUE: When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property. 
* ACCESSING & CHANGI NG A TEXT NODE:
  * To work with text in an element, first the element node is accessed and then its text node.
  * The text node has a property called node Value which returns the text in that text node.
  * You can also use the node Va 1 ue property to update the content of a text node.

* ACCESS & UPDATE TEXT WITH TEXTCONTENT: The textContent property allows you to collect or update just the text that is in the 
  containing element (and its children).
  
* ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML: Using the i nnerHTML property, you can access and amend the contents of an element, 
  including any child elements. 

### ADDING ELEMENTS USING DOM MANIPULATION 

DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML).

It involves three steps: 

1) CREATE THE ELEMENT: createEl ement (): You start by creating a new element node using the createElement() method. 
2) GIVE IT CONTENT: createTextNode(): creates a new text node.
3) ADD IT TO THE DOM: appendChild(): you can add it to the DOM tree with this method.

### REMOVING ELEMENTS VIA DOM MANIPULATION 

DOM manipulation can be used to remove elements from the DOM tree. 
1) STORE THE ELEMENT TO BE REMOVED IN A VARIABLE.
2) STORE THE PARENT OF THAT ELEMENT IN A VARIABLE.
3) REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT.

### CROSS-SITE SCRIPTING (XSS) ATTACKS

If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, 
an attacker could gain access to your users' accounts.

### XSS: VALIDATION & TEMPLATES
* FILTER OR VALIDATE INPUT: The most basic defense is to prevent users from entering characters into form fields that they do not 
need to use when providing that kind of information. 
* LIMIT WHERE USER CONTENT GOESp: Malicious users will not just use <script> tags to try and create an XSS attack.

### XSS: ESCAPING & CONTROLLING MARKUP 

Any content generated by users that contain characters that are used in code should be escaped on the server. You must control any markup 
added to the page. 

### What is the hardest thing about writing code?

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

### Why problem domains are hard

![image](https://flylib.com/books/2/623/1/html/2/images/032112247x/graphics/02fig01.gif)

* The reason is because you can’t really see what you are trying to build very clearly.
* The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.

### Programming is easy if you understand the problem domain

* given the entire problem domain in the form of a spec that was clear and unambiguous.
* took the time to clearly understand the problem domain before writing any code.
* make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.
* able to learn that problem domain.
* impact marketing themselves and branding can have on their opportunities.





* 
