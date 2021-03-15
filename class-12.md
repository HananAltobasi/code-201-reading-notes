# Charts
* are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
* They’re easier to look at and convey data quickly, but they’re not always easy to create.
* a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.
* It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.
![img](https://www.freevector.com/uploads/vector/preview/16716/FreeVector-3D-Charts-Graphics.jpg)

### steps for creat Chart:
1) Setting up: The first thing we need to do is download Chart.js.
2) Drawing a line chart: the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
3) write a script that will retrieve the context of the canvas
4) Drawing a pie chart: Our line chart is complete, so let’s move on to our pie chart.

# Chart.js

* You can download the latest version of Chart.js from the GitHub releases or use a Chart.js CDN.
* It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.

## Usage
* Chart.js can be used with ES6 modules, plain JavaScript and module loaders.
* To create a chart, we need to instantiate the Chart class. we need to pass in the node, jQuery instance, or 2d context of the canvas of where we want to draw the chart.

## Responsive Charts
* When it comes to changing the chart size based on the window size.
* a major limitation is that the canvas render size (canvas.width and .height) can not be expressed with relative values, contrary to the display size (canvas.style.width and .height).
* these sizes are independent from each other and thus the canvas render size does not adjust automatically based on the display size, making the rendering inaccurate.

![image](https://user-images.githubusercontent.com/79087406/111154600-11812200-859c-11eb-91f1-07ab1b4597c1.png)

## Basic usage of canvas
* has only two attributes, width and height(These are both optional and can also be set using DOM properties).
* can be styled just like any normal image (margin, border, background…).
* When no styling rules are applied to the canvas it will initially be fully transparent.

## Drawing shapes with canvas
Working with paths is essential when drawing objects onto the canvas.

## Applying styles and colors
* we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
  * fillStyle = color: Sets the style used when filling shapes.
  * strokeStyle = color: Sets the style for shapes' outlines.
* draw semi-transparent (or translucent) shapes.
  * This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
  
## Drawing text
* The canvas rendering context provides two methods to render text:
  * fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
  * strokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
![image](https://user-images.githubusercontent.com/79087406/111156711-ba308100-859e-11eb-8e7a-f07e6f23afd0.png)

## Advanced text measurements
* measureText(): Returns a TextMetrics object containing the width, in pixels.






























