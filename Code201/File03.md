# 🌼 HTML Lists, the CSS Box Model, & Control Flow with JavaScript 🌼

Quoted from the assigned reading:
>The padding sits around the content as white space

Quoted from the assigned reading:
>The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements.

<br>

## Assigned Homework Questions:

❓ When should you use an `unordered list` in your HTML document?

You can use an unordered list when the order of the items listed doesn't matter.  Such as when making a list of objects packed inside of a moving box.

❓ How do you change the `bullet style` of unordered list items?

In CSS, use the `list-style-type` property and either a circle, disc, or square.

The assigned reading adds that:
>A fourth bullet type has been defined in the WebTV interface, but not all browsers support it: triangle.

and 

>If not present and if no CSS list-style-type property applies to the element, the user agent selects a bullet type depending on the nesting level of the list.

❓ When should you use an `ordered list` vs an `unorder list` in your HTML document?

Use an ordered list when you want the list to be numbered to show the correct order flow that steps should be followed in.  An example would be the instructions on the back of a box of microwave pizza (trying to remove the plastic film AFTER microwaving the pizza would be disasterous!  LOL!)

An unordered list can be used when the order the contents are listed in doesn't matter.  For example, a shopping list.

❓ Describe two ways you can change the numbers on `list items` provided by an ordered list?

* The `reversed` attribute will order the list contents in reverse order, from high to low.

* The `start` attribute will start counting from whatever number you place next to it.  For example, if you use `start="4"` then the list will begin with the fourth integer (such as the letter D or the Roman numeral IV).

* To quote the assinged reading concerning the third potential way:
>`type`
>
>Sets the numbering type:
>
>`a` for lowercase letters
>
>`A` for uppercase letters
>
>`i` for lowercase Roman numerals
>
>`I` for uppercase Roman numerals
>
>`1` for numbers (default)
>
>The specified type is used for the entire list unless a different `type` attribute is used on an enclosed `<li>` element.



<br>

❓ Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

❓ List and describe the four parts of an HTML elements box as referred to by the `box model`.

The _**Content Box**_ is the area where your content is displayed.

The _**Padding Box**_ is the white space wrapped directly around the outside of the content box.

The _**Border Box**_ is a line that wraps around the edge of the padding, thus seperating the content and any padding from the outside.

The _**Margin Box**_ is the outermost layer, wrapping around the outside of the border box, so that it contains inside of it the border, padding, and content.  It thus forms whitespace between this box and any other elements on the page.

<br>

❓ What `data types` can you store inside of an `Array`?

❓ Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?
>const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

❓ List five shorthand operators for assignment in javascript and describe what they do.

❓ Read the code below and evaluate the last expression and explain what the result would be and why.

 >let a = 10;
 >let b = 'dog';
 >let c = false;
>
> // evaluate this
> (a + c) + b;

❓ Describe a real world example of when a conditional statement should be used in a JavaScript program.

❓ Give an example of when a Loop is useful in JavaScript.

<br>

<br>

## Links to the Assigned Reading:

* [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
* [Unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
* [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
* [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
* [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
* [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
* [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
* [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
