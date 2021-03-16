# Transforms
![img](https://webkit.org/blog-files/3d-transforms/poster-circle.png)
 * The transform property comes in two different settings, two-dimensional and three-dimensional.
 * general layout techniques can be revisited with alternative ways to size, position, and change elements.
 * The value specifies the transform type followed by a specific amount inside parentheses.
 * the transform property includes multiple vendor prefixes to gain the best support across all browsers.
 * The transform property accepts a handful of different values.

## 2D Transforms

  Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
 
### 2D Rotate
 * The rotate value provides the ability to rotate an element from 0 to 360 degrees.
 * Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
 * The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.

### 2D Scale
 * allows you to change the appeared size of an element.
 * The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller 
  while any value greater than or equal to 1.01 makes an element appear larger.
 * The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. 

### 2D Translate
  Using the translateX value will change the position of an element on the horizontal axis while using the translateY 
  value will change the position of an element on the vertical axis.
 
### 2D Skew
 is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values.
 Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis.
 
 ## 3D Transforms
 
  control of depth as well as length and width.
  
### 3D Rotate
  With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values,
  including rotateX, rotateY, and rotateZ.
 
### 3D Scale
 By using the scaleZ three-dimensional transform elements may be scaled on the z axis.

### 3D Translate
 Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element.
 Using a positive value will pull an element closer on the z axis, resulting in a larger element.
 
### 3D Skew
 Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.
 
# Transitions & Animations
* With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, 
 focused on, active, or targeted.
* Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes.

## Transitions
* way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
* There are four transition related properties in total, including:

1) transition-property
It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors,
font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another.

2) transition-duration
The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms).

3) transition-timing-function
 * The transition-timing-function property is used to set the speed in which a transition will move.
 * A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

4) transition-delay.
 The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. 

## Animations

### Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name,
any animation breakpoints, and the properties intended to be animated.

### Animation Duration, Timing Function, & Delay
Once you have declared the animation-name property on an element, animations behave similarly to transitions. They include a duration, timing function, and delay if desired.
To start, animations need a duration declared using the animation-duration property.

# 8 SIMPLE CSS3 TRANSITIONS

1) Fade in
 * It’s a great way to emphasize functionality or draw attention to a call to action.
 * Fade in effects are coded in two steps: first, you set the initial state; next, you set the change

2) Change color
 Animating a change of color used to be unbelievably complex, . Now, we just set the div’s class to “color” and specify the color we want in  CSS

3) Grow & Shrink
 To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

4) Rotate elements
 CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.

5) Square to circle
  is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.

6) 3D shadow
  they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces.

7) Swing
 Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

8) Inset border
 One of the hottest button styles right now is the ghost button; a button with no background and a heavy border.
