# 🦀 CSS Transitions and Transformations 🦀

## 📝 Assigned Homework Questions:

❓ What does a CSS transform allow the developer to do to an element?

It allows developers the ability to resize, re-position, and change elements in two-dimensional and three-dimensional ways!  Distortion on the 2D field include: _transform_ the rotation (positive values rotate clockwise; negative values rotate widdershins), _transform_ the scaled appearance size of an element (values between 0.99 to 0.01 shrinks an object; any value = or greater than 1.01 makes an element appear larger), _translate_ the position up/down left/right of where it used to be, _transform_ the skew of an object (distort elements on the horizontal axis, vertical axis, or both), and any combinations of those.  Distortions on the 3D field use the `perspective` property (the higher the depth value the further away the perpective will seem and therefore smaller changes) to make the same distortions as in the 2D field but with the addition of the z axis.

<br>

🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞

<br>

❓ Examples of a transform:

**2D Rotate Example**
>.box-1 {
>
>  transform: rotate(20deg);
>
> }
>
>.box-2 {
>
>transform: rotate(-55deg);
>}

_Notes about using rotate in 2D:_
* The center point of rotation is defaulted to be at 50% horizontally and 50% vertically
* That center point can be changed to something else by using the `transform-origin` property

<hr>

**2D Scale Example #1**
>.box-1 {
>
>transform: scale(.75);
>
>}
>
>.box-2 {
>
>transform: scale(1.25);
>
>}

_Notes about using scale in 2D:_
* `scaleX` will scale the width of an element
* `scaleY` will scale the height of an element
* To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously. Use `scale` while declaring the x axis value first, followed by a comma, and then the y axis value.

**2D Scale Example #2**
>.box-1 {
>
>transform: scaleX(.5);
>
>}
>
>.box-2 {
>
>transform: scaleY(1.15);
>
>}
>
>.box-3 {
>
>transform: scale(.5, 1.15);
>
>}

<hr>

**2D Translate Example**

>.box-1 {
>
>transform: translateX(-10px);
>
>}
>
>.box-2 {
>
>transform: translateY(25%);
>
>}
>
>.box-3 {
>
>transform: translate(-10px, 25%);
>
>}

_Notes about using translate:_
* `translateX` will change the position of an element on the horizontal axis
* `translateY` will change the position of an element on the vertical axis.
* To set both the x and y axis values at once, declare the x axis value first, followed by a comma, and then the y axis value.
* The distance values used within the translate value may be any general length measurement, most commonly pixels or percentages.
* Positive values will push an element down and to the right of its default position
* Negative values will pull an element up and to the left of its default position.

<hr>

**2D Skew Example:**
>.box-1 {
>
>transform: skewX(5deg);
>
>}
>
>.box-2 {
>
>transform: skewY(-20deg);
>
>}
>
>.box-3 {
>
>transform: skew(5deg, -20deg);
>
>}

_Notes about using skew in 2D:_
* `skewX` distorts an element on the horizontal axis
* `skewY` distorts an element on the vertical axis
* To distort an element on both axes, declare the x axis value first, followed by a comma, and then the y axis value.
* The distance calculation of the skew value is measured in units of degrees. Length measurements, such as pixels or percentages, do not apply here.

<br>

🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐🦐

❓ What does a CSS transition allow the developer to do to an element?

It alters the appearance/behavior of an element whenever a state change occurs (for example when it is hovered over, active, focused on, targeted, etc).  Different styles must be identified for each state (for example, by using the pseudoclasses `:hover:`, `:focus:`, `:active:`, and `:target:`).

❓ How does a CSS animation differ from a CSS transition?

Animations allow the appearance and behavior of an element to be altered in multiple keyframes.  Whereas transitions provide a chane from one state to another, animations on the other hand can set multiple points of transition on different keyframes.

<br>

❓ What are some benefits to using CSS transitions on websites?

They can:
* Increase user engagement
* Increase user interest
* Draw attention to something such as a call to action, thereby emphasizing functionality
* Give feedback to users about their interactions on the page
* Help a website to remain trendy (for example, to create a ghost button that has no background but has a heavy border)

❓ How this topic fit in with your long-term goals?

They speed up the ability to create flashy looking styling on a webpage, thereby making more efficient use of the time spent coding.

<br>

🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀🦀

<br>

## 📚 Links to the Assigned Reading:

[CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

[CSS Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

[8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

[Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/QWMxRR)

[6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)

[CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/dyBqVo)

[404](https://codepen.io/kieranfivestars/pen/MYdQxX)
