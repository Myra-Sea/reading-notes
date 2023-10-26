# 💮 Creating Hyperlinks, Intro to CSS Layout, JavaScript Functions, & Pair Programming 💮

<br>

## Assigned Homework Questions:

❓ To create a basic link, we wrap text or other content inside what element?

An `<a>` element

❓ The `href` attribute contains what information?

The website address that is being linked to.  It is an attribute of the `<a>` element.  It is also known as a **Hypertext Reference** or a **target**

❓ What are some ways we can ensure links on our pages are accessible to all readers?

* For the sake of visual readers:  Use descriptive link text
* For the sake of search engines:  Include keywords in the link text
* For the sake of screen readers:  Don't inlucde the word "link" nor "link to" in the link text. Screen readers already tell the visually impaired that fact
* For the sake of screen readers:  Keep the link text as short as possible
* For the sake of screen readers:  Don't repeat the URL as part of the link text.  It sounds horrible when screen readers spell them out
* For the sake of screen readers:  Minimize having multiple copies of the same text linked to different places
* Reduce confusion for all: Add clear wording to reduce any confusion about links that will cause a donwnload, live stream, or other potentially unexpected effect (such as a pop-up window)

<br>

❓ What is meant by “normal flow”?

The way that elements lay themselves out on a webpage is you don't change anything about them with CSS.  It is designed to make the content readable even if the user is on a limited browser or screen reader device.

❓ What are a few differences between block-level and inline elements?

**Block-level elements** involve boxes laid out one after the other, vertically, beginning at the top of a containing block.  Each block-level element always starts on a new line.  It fills the available space of the parent element that is containing it.  It occupies the entire horizontal space of its parent element container and vertical space equal to the height of its contents.

**Inline elements**, on the other hand, are restricted to being only the size of their contents.  Most text sequences and generated content are in-line level by default.  They don't appear on new lines.  Instead, they all sit on the same line along with any adjacent (or wrapped) text content as long as there is space for them to do so inside the width of the parent block level element.

❓ ___ positioning is the default for every html element.

Static.  It puts the html link in its normal position in the document flow.

❓ Name a few advantages to using absolute positioning on an element.

* The dev can specify the distance the element should be from each of the containing element's sides
* An element with absolute positioning exists on its own layer separate from everything else.  That means the dev can create isolated user interface features that don't interfere with the layout of other elements on the page.

❓ What is a key difference between fixed positioning and absolute positioning?

**Absolute positioning** fixes an element in place relative to its nearest ancester or initial containing block

**Fixed positioning** fixes an element in place relative to the visible portion of the viewport.  This means useful user-interface items (like navigation menus) can be fixed in place to always be visible no matter where on the page the user scrolls to

<br>

❓ Describe the difference between a function declaration and a function invocation.

**Declaration** is the first step.  It is the act of assigning a name (and possibly parameters and/or statements) to a function that's being created

**Invocation** is the act of using a function by including the name of the function in the code somewhere, followed by a set of parentheses 

❓ What is the difference between a parameter and an argument?

A **parameter** is a value (which is included inside of the parentheses) needed for a function to do its job correctly. The required reading says that sometimes parameters are refered to as being arguments.

An **argument** is a value being passed to (or from) a function. 
[(Source of the following quote:)](https://www.w3schools.com/js/js_function_parameters.asp)
> The parameters, in a function call, are the function's arguments.
> JavaScript arguments are passed by value: The function only gets to know the values, not the argument's locations.
> If a function changes an argument's value, it does not change the parameter's original value.
> Changes to arguments are not visible (reflected) outside the function.

<br>

❓ Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

I like the greater efficiency (higher quality code) that comes from two sets of eyes and two brains focusig on creating the same work. It is also exciting to have the opportunity to learn from other students who may have a different solution/approach than myself. I also like the job interview and workplace environment readiness aspects of paired programming.

<br>

<br>

## Links to the Assigned Reading:

* [Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
* [Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)
* [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
* [CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
* [CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)
* [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
* [Functions – Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)
* [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)
  
