# What googled learned from its quest to build the perfect team
* Sometimes random people work better together than a group of a bunch of people with similar backgrounds.
* Google spends millions of dollars tracking its employees lives.
## Project Aristotle
* Google started to study their teams and fgure out why some stumbled and other soared.
* They found that most of the effective groups of people hung out outside of work and socialized.
* After looking at over a hundred groups for more than a year, Project Aristotle researchers concluded that understanding and influencing group norms were the keys to improving Google's teams.
## Transform Syntax
* The transform property comes in two different settings, two dimensional and three dimensional.  Each of these come with their own individual properties and values.
## 2D Scale
* Using the scale value within the transform property allows you to change the appeared size of an element.
## 2D Translate
* The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
## 2D Skew
* The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.
## 3D Rotate
* Using the rotateX value allows you to rotate an element around the x axis, as if it were being bent in half horizontally.
## 3D Scale
* By using scaleZ three-dimensional transform elements may be scaled on the z axis.
## 3D Translate
* Elements may also be translated on the z axis using the translateZ value.
## 3D Skew
* Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale.  Elements may be skewed on the x and y axis, the transformed three-dimensionally as wished, but they cannot be skewed on the z axis.
## Transform Style
* On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed.
## Backface Visibility
* When working with three-dimensional transoforms, elements will occasionally be transformed in a way that causes the to face away from the screen.
# Transitions
* For a transition to take place, an element must have a change in state, and different styles must be identified for each state.
## Transitional Property
*  The transition-property determines what properties will be altered in conjunction with the other transitional properties.
# Transitional Properties
```
background-color
background-position
border-color
border-width
border-spacing
bottom
clip
color
crop
font-size
font-weight
height
left
letter-spacing
line-height
margin
max-height
max-width
min-height
min-width
opacity
outline-color
outline-offset
outline-width
padding
right
text-indent
text-shadow
top
vertical-align
visibility
width
word-spacing
z-index
```
## Transition Duration
* The duration in which a transition takes place is set using the transition-duration property.  The value of this property can be set using general timing values, including seconds and milliseconds.
## Transition Timing
* The transition-timing-function property is used to set the speed in which a transition will move.
## Transition Delay
* On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property.  The delay sets a time value, seconds or millisecones, that determines how long a transition should be stalled before executing.
# Animations
## Animations Keyframes
* To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule inclueds the animation name, any animation breakpoints, and the properties intended to be animated.
## Animation Name
* Once the keyframes for an animation have been declared they need to be assigned to an element.
## Animation Duration, Timing Function, and Delay
* Once you have declared the animation-name property on an element, animations behave similarily to transitions.
# Customizing Animations
## Animation Iteration
* By default, animations run their cycles once from beginning to end and then stop.  To have an animation repeat itself numerous times the animation-iteration-count property may be used.
## Animation Direction
* On top of being able to set the number of times an animation repeats, you may also delcare the direction an animation completes using the animation-direction property.
* Values for the animation-direction
- normal
- reverse
- alternate
- alternate-reverse
## Animation Play State
* The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively. 
## Animation Fill Mode
* The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run.
# CSS3
### Fade in
* Having things fade in is a fairly common request from clients.  
### Change Color
* Animating a change of color used to be unbelievaly complex, with all kinds of math involved in calculating seperate RGB values and then recombining them.  Now, we just set the div's class to "color" and specify the color we want in our CSS.
### Grow & Shrink
* To grow an element, you used to have to used its width and height, or its padding.  But now we can use CSS3's transform to enlarge.
### Rotate Elements
* CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.  Give your div the class "rotate" and add the following to your CSS.
### Square to Circle
* A really popular effect at the moment is transitioning a square element into a round one, and vice versa.  With CSS, its a simple effect to achieve, we just transition the border-radius property.
### 3D Shadow
* 3D shadows were frowned upon for a year or so, because they weren't seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces.
### Swing
* Not all elements use the transition property.  We can also create highly complex animations using @keyframes, animation and animation-iteration.
### Inset Border
* One of the hottest button styles right now is the ghost button; a button with no background and a heavy border.  We can of course add a border to an element simply, but that will change the elements postion.