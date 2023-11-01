# 🐥 Readings: CSS Layout Using Flexbox 🐥

## 📝 Homework Assignments:

❓ Flexbox is designed for one-dimensional content. Explain what this means.

It primarily focuses on either the horizontal or the vertical axis of the container it is arranging/aligning the items inside of.  It takes a bunch of items with different sizes and returns the best layout for those items.  Instead of setting rigid dimensions for the browser to follow, it provides flexible boundaries to hint how the content could display. Items "flex" (expand) to fill additional space or shrink to fit into smaller spaces. For example, it can plan an ideal layout for a sidebar.  In that example, it would lay the sidebar and content inline, and where there isn't enough space it would break the sidebar onto a new line.  Flex layouts can:  display as a row or column, respect the writing mode of the document, can convert from single line to wrap onto multiple lines, can visually reorder items away from their order in the DOM, can distribute space inside the items to make them bigger or smaller according to the space available in the parent, can distribute space around the items and flex lines in a wrapped layout using the Box Alignment properties, and align the items on teh cross axis.

❓ Explain the difference between the main axis and cross axis.

The _**main axis**_ is set by the `flex-direction` property.  If that is a `row` then the main axis is along the row.  If it is, instead, a `column` then the main axis is along the column.  Flex items move as a group on the main axis.

The _**cross axis**_ runs perpendicular to the main axis.  Therefore, if the main axis is `row` then cross-axis is `columm`, and if main axis is `column` them cross-axis is `row`.  On the cross axis you can move items individually OR as a group, so that they align against each other the flex container.

❓ How can using certain properties of flexbox negatively impact accessibility?

Anything the can change the order of items in flexbox or grid can cause problems.  Properties that reorder the visual display away from how things are ordered in the HTML document will confuse screen readers.  For example, `row-reverse` and `column-reverse` values only reorder the visual order, not the logical order.  The logical order is the order that a screen reader will read out the content in and that anyone using the keyboard will follow.  That means that using `row-reverse`  or `column-reverse` will cause tabbing between table elements (for example navigation links) to become disconnected, because the keyboard navigation follows the DOM instead of the visual display.

<br>

<br>

❓ What are some advantages of using flexbox over float?

The following layout design tasks are easy with flexbox but are not possible with float (or are difficult with float):
* Vertically centering a block of content inside its parent
* Making all the children of a container take up an equal amoutn of the available width/height, regardless of how much width/height is avaialable
* Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content

❓ How does this topic connect with your long term goals?

Whether planning out how to arrange things in a room, on a wall or on a website, I enjoy the creative process of design.  The design layout of a website can dramatically impact whether or not a first time user will stay and come back again in the future to your site.  If it is difficult to find what they are looking for a first time user is likely to give up in frustration and move on to a different website (i.e. give their money to a different business).  Flexbox opens up a lot of design styling potentials, making them easier to achieve than in the past.

<br>

<br>

## 📚 Links to the Assigned Reading:

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

[CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

[Learn CSS - Layout](https://web.dev/learn/css/layout/)
