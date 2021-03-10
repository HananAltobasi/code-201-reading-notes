# CONTENT PANELS
Content panels allow you to showcase extra information 
within a limited space.

## ACCESSIBILITY & NO JAVASCRIPT
* ACCESSIBILITY 

  Whenever a user can interact with an element: 
  
   • If it is a link, use (a).
   • If it acts like a button, use a button.
   
* NO JAVASCRIPT 

This content would be inaccessible to visitors that do not have JavaScript enabled if we didn't provide alternative styling.   
   
## ACCORDION 
   
* When you click on the title of an accordion, its corresponding panel expands to reveal the content. 
* is created within an unordered list (in a (ul)element). 
* Each (li) element is a new item in the accordion. The items contain: 
  • A visible label (in this example, it is a (button)).
  • A hidden panel holding the content (a (div)).
![image](https://user-images.githubusercontent.com/79087406/110699263-56513580-81f7-11eb-817e-1ebb4c7475a1.png)

## TABBED PANEL

* When you click on one of the tabs, its corresponding panel is shown. 
* Tabbed panels look a little like index cards. 
* You should be able to see all of the tabs, but: 
  • Only one tab should look active. 
  • Only the panel that corresponds to the active tab should be shown (all other panels should be hidden).
* To associate the tab to the panel: 
  • The link in the tab, like all links, has an href attribute. 
  • The panel has an id attribute. 
![image](https://user-images.githubusercontent.com/79087406/110699819-f0b17900-81f7-11eb-967a-dd7339a5d3a9.png)

## Modal Window

* A modal window is any type of content that appears "in front of" the rest of the page's content.
* It must be "dosed" before the rest of the page can be interacted with. 
* A design pattern is a term programmers use to describe a common approach to solving a range of programming tasks. 
* Using modules to build parts of an application has benefits: 
  • It helps organize your code. 
  • You can test and reuse the individual parts of the app. 
  • It creates scope, preventing variable /method names clashing with other scripts. 

## PHOTO VIEWER

* is an example of an image gallery.
* When you click on a thumbnail, the main photograph is replaced with a new image.
* The HTML for the photo viewer consists of: 
  • One large <div> element that will hold the main picture. 
  • A second <div> element that holds a set of thumbnails that show the other images you can view.
![image](https://user-images.githubusercontent.com/79087406/110700822-125f3000-81f9-11eb-8516-95a7af04e8ff.png)

## ASYNCHRONOUS LOADING & CACH ING IMAGES

* This script (shown on the next page) shows two interesting techniques: 
  1) Dealing with asynchronous loading of content.
  2) Creating a custom cache object.

## RESPONSIVE SLIDER

* A slider positions a series of items next to each other, but only shows one at a time.
* The images then slide from one to the next. 
* provides buttons that allow users to navigate between each of the slides and a timer to move them automatically after a set interval. 
* the slider needs two further (div) elements: 
  • A container for the slides.
  • A container for the buttons. 
![image](https://user-images.githubusercontent.com/79087406/110701467-dd071200-81f9-11eb-9583-d6656ce910b2.png)

## SLIDER SCRIPT OVERVIEW

* A jQuery selector finds the sliders within the HTML markup. 
* An anonymous function then runs for each one to create the slider. 
* There are four key parts to the function:
  1) SETUP.
  2) CHANGING SLIDE: move().
  3) A TIMER TO SHOW THE NEXT SLIDE AFTER 4 SECONDS: advance().
  4)  PROCESSING EACH OF THE SLIDES THAT APPEAR WITHIN A SLIDER. 

## CREATING A JQUERY PLUGIN

* jQuery plugins allow you to add new methods to jQuery without customizing the library itself. 
* You can turn any function into a plugin if it: 
  • Manipulates a jQuery selection.
  • Can return a jQuery selection.
* The basic concept is that you: 
  • Pass it a set of DOM elements in a jQuery selection.
  • Manipulate the DOM elements using the jQuery plugin code. 
  • Return the jQuery object so that other functions can be chained off it.   

## BASIC PLUGIN STRUCTURE 
![image](https://user-images.githubusercontent.com/79087406/110701996-97971480-81fa-11eb-85b5-e580f1b12bbc.png)







  






  
