# Forms
![IMG](https://www.computerhope.com/jargon/f/form.jpg)
* enabling users to search.
* allow users to perform other functions online.
* You will see forms.
  - when registering as a member of a website. 
  - when shopping online.
  - when signing up for newsletters or mailing lists.

## Form Controls
types of form controls:
* ADDING TEXT
* Submitting Forms
* Uploading Files
![image](https://user-images.githubusercontent.com/79087406/110475958-223c1e80-80ea-11eb-84b6-daac56a0d1d3.png)

## How Forms Work
![image](https://user-images.githubusercontent.com/79087406/110476157-58799e00-80ea-11eb-92f1-18122b30395f.png)

## Form Structure
* form element: This element should always carry the action attribute and will usually have a method and id attribute too.
* action: Every form element requires an action attribute.
* method: Forms can be sent using one of two methods: get or post.

## Text Input
* input element: is used to create several different form controls.
* type="text": When the type attribute has a value of text, it creates a single-line text input.

# LISTS, TABLES AND FORMS

## Bullet Point Styles(list-style-type)
![image](https://user-images.githubusercontent.com/79087406/110479258-df7c4580-80ed-11eb-8ef5-46d867de0ce2.png)

## Images for Bullets(list-style-image)
* You can specify an image to act as a bullet point using the list-style-image property.
* The value starts with the letters url and is followed by a pair of parentheses. 

## Positioning the Marker(list-style-position)
![image](https://user-images.githubusercontent.com/79087406/110479966-9e386580-80ee-11eb-8dbc-1d25dad1c00d.png)

## Styling Forms
![image](https://user-images.githubusercontent.com/79087406/110480216-ebb4d280-80ee-11eb-99c8-7a961348ee8e.png)

## Cursor Styles
The cursor property allows you to control the type of mouse 
cursor that should be displayed to users.

## Web Developer Toolbar
This helpful extension for Firefox and Chrome provides tools to show you the CSS styles that 
apply to an element when you hover over it, along with the structure of the HTML.

1) Outlines: When you hover over an element, a red outline will be 
drawn around it, showing you how much space the element takes up.
2) Structure: While you are hovering over an element, the structure will be shown at the top of the window.
3) CSS styles: When hovering over an element, click with your mouse to display the CSS.

#  EVENTS
![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events-1200x900.png)

## DIFFERENT EVENT TYPES
![image](https://user-images.githubusercontent.com/79087406/110481444-3f73eb80-80f0-11eb-8da8-1c8a4c6539d4.png)

## HOW EVENTS TRIGGER JAVASCRIPT CODE 
1) Select t he element node(s) you want the script to respond to. 
2) Indicate which event on the selected node(s) will trigger the response. 
3) State the code you want to run when the event occurs. 
4) 
## TRADITIONAL DOM EVENT HANDLERS 

All modern browsers understand this way of creating an event handler, 
but you can only attach one function to each event handler. 
![image](https://user-images.githubusercontent.com/79087406/110482405-536c1d00-80f1-11eb-8997-23524ddc6c71.png)

## EVENT LISTENERS 
* Event listeners are a more recent approach to handling events. 
* They can deal with more than one function at a time but they are not supported in older browsers.
![image](https://user-images.githubusercontent.com/79087406/110482866-cbd2de00-80f1-11eb-9225-55666c905bb7.png)

## EVENT FLOW
![image](https://user-images.githubusercontent.com/79087406/110483063-03da2100-80f2-11eb-925a-8480c36750ec.png)

## FLOW MATTERS
![image](https://user-images.githubusercontent.com/79087406/110483239-32f09280-80f2-11eb-80e8-83746a907e55.png)

## THE EVENT OBJECT 
When an event occurs, the event object tells you information about the event, 
and the element it happened upon. 

## EVENT DELEGATION 
![image](https://user-images.githubusercontent.com/79087406/110483603-8ebb1b80-80f2-11eb-8d77-43e04f855c79.png)
 
## DIFFERENT TYPES OF EVENTS
Events are defined in:
* W3C DOM EVENTS: The DOM events specification is managed by the W3C (who also look after other specifications including HTML, CSS, and XML).
* HTM LS EVENTS: details events that browsers are expected to support that are specifically used with HTML. 
* SOM EVENTS: Browser manufacturers also implement some events as part of their Browser Object Model (or BOM). 

## USER INTERFACE EVENTS 
![image](https://user-images.githubusercontent.com/79087406/110484464-5831d080-80f3-11eb-8205-847e01561b40.png)

## LOAD 
* used to trigger scripts that access the contents of the page. 
* The event is automatically raised by the window object when a page has finished loading the HTML and all of its resources: images, CSS, scripts. 
* The setup() function would not work before the page has loaded because it relies on finding the 
element whose id attribute has a value of username, in order to give it focus. 

## FORM EVENTS 
![image](https://user-images.githubusercontent.com/79087406/110484742-9e872f80-80f3-11eb-86a8-dd1bf702ba16.png)

## HTM LS EVENTS 

* DOMContentLoaded: Event fires when the DOM tree is formed (images, CSS, and javaScript might still be loading).
* hashchange: Event fires when the URL hash changes (without the entire window refreshing).
* beforeun load: Event fires on the window object before the page is unloaded. 


