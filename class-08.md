# Layout

![img](https://miro.medium.com/max/1024/1*XCZZZmhQN4rHLw2dW14BZQ.png)

## Building Blocks
* CSS treats each HTML element as if it is in its own box(This box will either be a block-level box or an inline box).
* Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text.
* Block-level elements (start on a new line).
* Inline elements (flow in between surrounding text).

## Containing Elements

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

## positioning schemes

#### allow you to control the layout of a page: 

* normal flow. 
- This is the default behavior(Every block-level element appears on a new line, causing each item to appear lower down 
the page than the previous one).
- The (z-index) property allows you to control which box appears on top.

* relative positioning. 
This moves an element from the position it would be in normal flow, shifting it to the top, right, 
bottom, or left of where it would have been placed.

* absolute positioning. 
This positions the element in relation to its containing element, 
It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements. 

## box offset
tell the browser how far from the top or bottom and left or right it should be placed.

* Fixed Positioning
This is a form of absolute positioning that positions the element in relation to the 
browser window, as opposed to the containing element.

* Floating Elements
allows you to take that element out of normal flow and position 
it to the far left or right of a containing box.

## Screen Sizes

Different visitors to your site will have different sized screens that show different amounts of information.

![img](https://xd.adobe.com/ideas/wp-content/uploads/2019/03/designing-for-multiple-screen-sizes-illustrated-1257x550.jpg)

* when it comes to designing for the web, you are faced with the 
unique challenge that different users will have different sized screens.
* The size of a user's screen affects how big they can open their windows and how much of the page they will see.

## Screen Resolution

refers to the number of dots a screen shows per inch, Some devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

## Page Sizes

web designers often try to create pages of around 960-1000 pixels wide 

## Fixed Width Layouts

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. 
(Measurements tend to be given in pixels).

#### Advantages

* Pixel values are accurate at controlling size and positioning of elements.
* The designer has far greater control over the appearance and position of items on the page than with liquid layouts.
* You can control the lengths of lines of text regardless of the size of the user's window.
* The size of an image will always remain the same relative to the rest of the page.

#### Disadvantages

* You can end up with big gaps around the edge of a page.
* If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read.
* If a user increases font sizes, text might not fit into the allotted spaces.
* The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
* The page will often take up more vertical space than a liquid layout with the same content.

## Liquid Layouts

designs stretch and contract as the user increases or decreases the size of their browser window(They tend to use percentages).
![image](https://user-images.githubusercontent.com/79087406/110383797-7b15a380-8065-11eb-8b15-c843c1d1c207.png)

#### Advantages

* Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
* If the user has a small window, the page can contract to fit it without the user having to scroll to the side.
* The design is tolerant of users setting font sizes larger than the designer intended.

#### Disadvantages
* If you do not control the width of sections of the page then the design can look very different than you intended.
* If the user has a wide window, lines of text can become very long, which makes them harder to read.
* If the user has a very narrow window, words may be squashed and you can end up with few words on each line.
* If a fixed width item.

![image](https://user-images.githubusercontent.com/79087406/110383731-60dbc580-8065-11eb-98a0-108d4163509d.png)

## Layout Grids

Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements — how they are organized on a page.

#### While a grid might seem like a restriction, in actual fact it:

* Creates a continuity between different pages which may use different designs.
* Helps users predict where to find information on various pages.
* Makes it easier to add new content to the site in a consistent way.
* Helps people collaborate on the design of a site in a consistent way.

![image](https://user-images.githubusercontent.com/79087406/110385286-6d611d80-8067-11eb-9dcd-298a11f7cdfe.png)

## CSS Frameworks

* CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating 
printer-friendly versions of pages and so on.
* You can include the CSS framework code in your projects rather than writing the CSS from scratch.
