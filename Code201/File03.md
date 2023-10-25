# 🌼 HTML Lists, CSS Box Model, & JavaScript Control Flow 🌼

The assigned reading says the following about `arrays`:
>Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. Array objects can be stored in variables and dealt with in much the same way as any other type of value, the difference being that we can access each value inside the list individually, and do super useful and efficient things with the list, like loop through it and do the same thing to every value.
>
>If we didn't have arrays, we'd have to store every item in a separate variable, then call the code that does the printing and adding separately for each item. This would be much longer to write out, less efficient, and more error-prone.

<br>

## Assigned Homework Questions:

❓ When should you use an `unordered list` in your HTML document?

You can use an unordered list when the order of the items doesn't matter.  Such as when making a list of objects packed inside of a moving box.

❓ How do you change the `bullet style` of unordered list items?

In CSS, use the `list-style-type` property and either a circle, disc, or square.

The assigned reading adds that:
>A fourth bullet type has been defined in the WebTV interface, but not all browsers support it: triangle.

and 

>If not present and if no CSS list-style-type property applies to the element, the user agent selects a bullet type depending on the nesting level of the list.

❓ When should you use an `ordered list` vs an `unorder list` in your HTML document?

Use an ordered list when you want the list to be numbered to show the correct order flow that steps should be followed in.  An example would be the instructions on the back of a box of microwave pizza.  After all, trying to remove the protective plastic film AFTER microwaving the pizza would be disasterous! 🍕

An unordered list can be used when the order of the contents doesn't matter.  For example, when making a shopping list.

❓ Describe two ways you can change the numbers on `list items` provided by an ordered list?

* The `reversed` attribute will order the list contents in reverse order, from high to low.

* The `start` attribute will start counting from whatever number you place next to it.  For example, if you use `start="4"` then the list will begin with the fourth integer (such as the letter D or the Roman numeral IV).

* To quote the assinged reading concerning a third potential way:
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

Oh woe be to Pyramus **Margin** and Thisbe **Padding**!  Two lovers forever separated by an inpenetrable **Border** wall! He (Margin) sits on the outside with his ear pressed up against the border to hear the sweet nothings that she (Padding) whispers thru to him from her home on the inside. While they may have fallen victim to forbidden love, unlike in the ancient stories of old the two shall never be able to break free of their respective sides of the wall that separates them!  But perhaps it is for the best that the two young lovers can not, for them each committing suicide over a tragic misunderstanding would assuredly release a lioness-like mess of chaotic formatting upon the internet!

❓ List and describe the four parts of an HTML elements box as referred to by the `box model`.

The _**Content Box**_ is the area where your content is displayed.

The _**Padding Box**_ is the white space wrapped directly around the outside of the content box.

The _**Border Box**_ is a line that wraps around the edge of the padding, thus seperating the content and any padding from the outside.

The _**Margin Box**_ is the outermost layer, wrapping around the outside of the border box, so that it contains inside of it the border, padding, and content.  It thus forms whitespace between this box and any other elements on the page.

<br>

❓ What `data types` can you store inside of an `Array`?

Any data type, including other arrays!  The most common ones are strings, numbers, and objects.

❓ Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?
>const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

Yes.

To quote the assigned reading:

>Arrays consist of square brackets and items that are separated by commas.

Inside of the above `people` array, the stored values are numbers and strings.  You can access the stored values using square brackets around the index for each one (for example, the value of 'pete' is `[0]`, 32 is `[1]`, `librarian` is `[2]`, and so on). 

❓ List five shorthand operators for assignment in javascript and describe what they do.

* _Addition_
  * using the shorthand operator `x += f()`
  * means `x = x + f()`
  * It adds the variable on the far right to the current value of the variable `x` so that the result can be assigned back to `x` as a new value.
  * example: `z = z + 8`
* _Multiplicaton_
  * using the shorthand operator `x *= f()`
  * means `x = x * f()`
  * It multiples the variable on the far right to the current value of the variable `x` so that the result can be assigned back to `x` as a new value.
  * example: `y = y * 4`
* _Subtraction_
  * using the shorthand operator `x -= f()`
  * means `x = x - f()`
  * It subtracts the variable on the far right from the current value of the variable `x` so that the result can be assigned back to `x` as a new value.
  * example: `w = w - 7`
* _Right shift assignment_
  * using the shorthand operator `x >>= f()`
  * means `x = x >> f()`
  * It is used to shift the bits of a variable by a specific number of positions to the right and then assign the result back to the variable.
* _Logical OR assignment_
  * using the shorthand operator `x ||= f()`
  * means `x || (x = f())`
  * If the variable on the left had a value equal to `false` or an equivalent (for example, null, 0, etc.) then this operator will assign the variable on the right to become the new value of the lefthand variable.  However, if the lefthand variable was `true` (or an equivalent such as 1) then nothing will happen.

❓ Read the code below and evaluate the last `expression` and explain what the result would be and why.

 >let a = 10;
 >let b = 'dog';
 >let c = false;
>
> // evaluate this
> (a + c) + b;

It results in `10dog`.

The `grouping operator ( )` says to add `a` to `c` first, and then afterwards add `b` to that sum.  That means, you first add the number 10 + the number 0 (which is what false is treated as).  That first part thus equals to 10.  Then adding b in means adding the string `dog`.  So in the end it results in `10dog` 

❓ Describe a real world example of when a conditional statement should be used in a JavaScript program.

The most commonly helpful example is when sensitive information on the internet can only be accessed using an authentication password.  The user must enter the exact correct input before the website will allow them to proceed.

❓ Give an example of when a Loop is useful in JavaScript.

Loops are helpful for automating repetitive tasks or looping thru operations on a collection of items.  As the assigned reading points out, one instance in which this is helpful is when making a shape appear multiple times on a page.  For example, in the 102 Course we were given the assignment of having an image appear on our webpage whatever many of times the user had inputed.

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
