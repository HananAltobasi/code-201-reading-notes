# Images

![img](https://art-u2.infcdn.net/articles_uploads/2013/05/IMG_15052013_144347.png)

* A picture can say a thousand words, and great images help make the difference between an
average-looking site and a really engaging one.

* If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

* To add an image into the page you need to use an (img) element.

* src: This tells the browser where it can find the image file.

* alt: This provides a text description of the image which describes the image if you cannot see it.

* title: You can also use the title attribute with the (img) element to provide additional information about the image. 

* height: This specifies the height of the image in pixels.

* width: This specifies the width of the image in pixels.

## Where to Place Images in Your Code

1)before a paragraph:

The paragraph starts on a new line after the image.

2)inside the start of a paragraph:

The first row of text aligns with the bottom of the image.

3)in the middle of a paragraph:

The image is placed between the words of the paragraph that it appears in.

### Aligning Images Horizontally

used to indicate how the other parts of a page should flow around an image.

* align: allowing text to flow around its left-hand side.

* left: allowing text to flow around its right-hand side.

### Aligning Images Vertically

* top: This aligns the first line of the surrounding text with the top of the image.

* middle: This aligns the first line of the surrounding text with the middle of the image.

* bottom: This aligns the first line of the surrounding text with the bottom of the image.

### Three Rules for Creating Images

1)Save images in the right format: Websites mainly use images in jpeg, gif, or png format.

2)Save images at the right size: You should save the image at the same width and height it will appear on the website.

3)Use the correct resolution: Computer screens are made up of dots known as pixels, Images used on the web are also made up of tiny dots.

### Image Formats

![img](https://www.practicalecommerce.com/wp-content/uploads/images/0001/0138/file_type_comparison.png)

* JPEG: Whenever you have many different colors in a picture you should use a JPEG.

* GIF: Use GIF or PNG format when saving images with few colors or large areas of the same color.

### Image Dimensions

* REDUCING IMAGE SIZE: You can reduce the size of images to create a smaller version of the image.

* INCREASING IMAGE SIZE: You can't increase the size of photos significantly without affecting the image quality.

* CHANGING SHAPE: Only some images can be cropped without losing valuable information (see next page).

### Cropping Images

When cropping images it is important not to lose valuable information.

### Image Resolution

Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

### Vector Images

Vector images differ from bitmap images and are resolution-independent, Vector images are commonly created in programs such as Adobe Illustrator.

### Animated GIFs

show several frames of an image in sequence and therefore can be used to create simple animations.

# Color

![img](https://www.clipstudio.net/wp-content/uploads/2019/11/0045_001.jpeg)

### Foreground Color (color)

* The color property allows you to specify the color of text inside an element. 

specify any color in CSS in one of three ways:

1)rgb values: These express colors in terms of how much red, green and blue are used to make it up.

2)hex codes: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.

3)color names: There are 147 predefined color names that are recognized by browsers.

### Background Color (background-color)

You can specify your choice of background color in the same three ways you can specify foreground colors:
RGB values, hex codes, and color names (covered on the next page).

### Understanding Color

Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.

### Contrast

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

* Low Contrast
* High Contrast
* Medium Contrast

### CSS3: Opacity (opacity, rgba)

CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements,
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to
indicate opacity.

### CSS3: HSL Colors

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

* Hue: is the colloquial idea of color.
* Saturation: is the amount of gray in a color.
* Lightness: is the amount of white (lightness) or black (darkness) in a color.

### CSS3: HSL & HSLA

The hsl color property has been introduced in CSS3 as an alternative way to specify colors.

individual values inside parentheses for:

* Hue: This is expressed as an angle (between 0 and 360 degrees).
* saturation: This is expressed as a percentage.
* lightness: This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.
* alpha: This is expressed as a number between 0 and 1.0.

# Text

![img](https://spec.fm/static/img/specifics/002-header.png)

If you design on a Mac, it is important to check what the typefaces look like on a PC because PCs can render type less smoothly.
But if you design on a PC, then it should look fine on a Mac.

### Typeface Terminology

* Serif: have extra details on the ends of the main strokes of the letters.
* Sans-Serif: have straight ends to letters, and therefore have a much cleaner design.
* Monospace: Every letter in a monospace (or fixed-width) font is the same width.

### Techniques That Offer a Wider Choice of Typefaces

typefaces are subject to copyright, so the techniques you can choose from are limited by their respective licenses.

* font-family: The user's computer needs the typeface installed. CSS is used to specify the typeface.
* font-face: CSS specifies where a font can be downloaded from if it is not installed on the computer.
* Service-based Font-Face: Commercial services give users access to a wider range of fonts using @font-face.

### Specifying Typefaces (font-family)

allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
The value of this property is the name of the typeface you want to use.

### Size of Type (font-size)

enables you to specify a size for the font, There are several ways to specify the size of a font:

* pixels: they allow web designers very precise control over how much space their text takes up, The number of pixels is followed by the letters px.
* percentages: The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.
* ems: An em is equivalent to the width of a letter m.

### Type Scales

You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.

### CSS3: Drop Shadow

The text-shadow property has become commonly used despite lacking support in all browsers. 

### styling links

* link: This allows you to set styles for links that have not yet been visited.
* visited: This allows you to set styles for links that have been clicked on. 

### Attribute Selectors

You met the most popular CSS selectors on page 238. There are also a set of attribute selectors that allow you to create rules that apply to 
elements that have an attribute with a specific value.

![image](https://user-images.githubusercontent.com/79087406/110038665-b56f0000-7d48-11eb-8dce-9cc0c11f6fca.png)

## three most commonly used image formats in websites and mobile applications — JPEG, PNG and GIF

these 3 formats together comprise of more than 95% of all images loaded on websites,
these 3 image formats have significant differences :

* TL;DR:

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. 
Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos.
Use GIF format for images that contain animations.

* Compression

Almost all forms of data that we see on the internet — text, image, video etc.
are compressed to reduce the size of data and ensure faster transmission. 
Choosing the correct format and compression is a major factor that determines image size.

* Colours

There is a significant difference in the number of colours that can be supported by these 3 formats.

- JPEG: images can support around 16 million colours, This is what makes them suitable for storing images of natural scenes.
- PNG: images mainly have two modes — PNG8 and PNG24. 
- GIF: images are limited to 256 colours.

* Animation

refers to any change or movement in the image. It doesn’t necessarily have to have frame rates like an animated video,
but essentially a part or the entire image changes with time.
(Of these 3 formats, only GIF supports animation).
