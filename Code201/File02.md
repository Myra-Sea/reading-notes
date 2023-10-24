# 🪷 HTML text tags, CSS structure, and JavaScript basics 🪷

Understanding proper coding formatting and structure is vital to writing good, functional code.  Proper structure will make the contents of a website more enjoyable and easier to read.  Proper formatting will make the code easier/faster to both write and maintain.

<br>

| Jump within this page to: |
| ------ |
| 👩🏻‍💻 [HTML Text Fundamentals](https://myra-sea.github.io/reading-notes/Code201/File02.html#) | 
| 👨🏻‍💻 [HTML Formatting](https://myra-sea.github.io/reading-notes/Code201/File02.html#) |
| 👩🏽‍💻 [How CSS is Structured](https://myra-sea.github.io/reading-notes/Code201/File02.html#) |
| 👩🏿‍💻 [JavaScript Basics](https://myra-sea.github.io/reading-notes/Code201/File02.html#) |
| 👨🏿‍💻 [JavaScript Conditionals](https://myra-sea.github.io/reading-notes/Code201/File02.html#) |
| 📝 [Homework Assignments](https://myra-sea.github.io/reading-notes/Code201/File02.html#-homework-assignments) |
| 📚 [Links](https://myra-sea.github.io/reading-notes/Code201/File02.html#-links-to-the-assigned-reading) |

<br>

## 👩🏻‍💻 HTML Text Fundamentals

Regardless of the medium it's being read/written on, most structured text consists of headings and paragraphs.  This is the case, whether reading an old fashioned newspaper, chapters in a printed book, or product reviews on a website.  When writing HTML code, headings can be wrapped in heading elements, such as `<h1>` ... `</h1>` for example. Paragraphs can be wrapped in `<p>` ... `</p>` elements.

## 👨🏻‍💻 HTML Text Formatting

There are many less well known but ueseful HTML elements for formatting text.
A few examples include:
+ Description lists
+ Blockquotes
+ Inline quotations
+ Citations
+ Abbreviations
+ Subscripts
+ Superscripts

## 👩🏽‍💻 How CSS is Structured

Each CSS rule starts with one or more **selectors**.  It tells the browser which HTML element to apply a CSS style to.

## 👩🏿‍💻 JavaScript Basics

An operator is a mathematical symbol (for example, `+` or `=`) that produces a result based on two values/variables.

## 👨🏿‍💻 JavaScript Conditionals

Explaining an `if...else` statement:

The expression inside of the `if()` is the test.  It compares the variable with the string to determine whether the two are equal.  If the two are equal then the first block of code will run.  If the the two are not equal then the second block (the one after the `else` statement) will run instead.

Comparison operators are used to test the conditions inside our conditional statements.

<br>

<Br>

## 📝 Homework Assignments:

❓ _**Why is it important to use semantic elements in our HTML?**_

They are recognized and expected by client computers around the world.  Their function is known to the client device that is receiving your page from the server.  If you do not use them, then the element may not be interpreted correctly.  Two of the most impactful results will be to search engines and screen readers.

❓ _**How many levels of headings are there in HTML?**_

Six. `<h1>` is the main, top level heading, whereas `<h6>` is the smallest subheading.

❓ _**What are some uses for the `<sup>` and `<sub>` elements?**_

The superscript and subscript elements may be used when marking up items like dates, chemical formulas, and mathematical equations, in order for them to convey the correct meaning.  For example, X <sup>2</sup> quickly conveys the algebraic formula "*X to the power of 2*." It takes up less room on the client's screen than the potentially confusing shorthand `X^2` would use, and it is less likely to be misunderstood as being a label the way that something like `X2` might be confused as being.  As a similar example, H<sub>2</sub>O is universally recognized as conveying the chemical formula for water.

❓ _**When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**_

If the element is wrapped around an acronym, then a plain text expansion should normally follow in order to provide a hint to user agents about how to announce/display the content.  If the element is wrapped around an abbreviation, and the abbreviation is a fairly short word, then `title` can be included within the element in order to provide the full expansion.

For example, `<p>You should go ask <abbr title="Reverend">Rev.</abbrev> Smith about that!</p>`

<br>

❓ _**What are ways we can apply CSS to our HTML?**_
+ An external stylesheet
  + This is the most common and useful method
  + It uses a separate file with a `.css` extension
+ An internal stylesheet
  + This is created inside of an HTML document using `<style>` elements within the `<head>` area of the html code
+ Inline styles
  + This method is also within an HTML document but only affects a single element and is contained within a `style` attribute
  + This is the hardest code to read, the least efficient method to maintain, and should be avoided at all costs

❓ _**Why should we avoid using inline styles?**_

 It is the opposite of a best practice.  Changing a style could potentially require editing multiple lines within a single page.  Mixing CSS code with HTML code and content may also lead to confusion when a programmer is attempting to read the code.

❓ _**What is representing the selector in the following block of code?**_ 
` h2 {
     color: black;
     padding: 5px;
   }`

h2.  It will target all `<h2>` elements in an attached HTML file.

❓ _**Which components are the CSS declarations in the following block of code?**_
` h2 {
     color: black;
     padding: 5px;
   }`

There are two declarations within the curly brackets.  They are `color: black` and `padding: 5x`

❓ _**Which components are considered properties in the following block of code?**_
` h2 {
     color: black;
     padding: 5px;
   }`

There are two human-readable identifiers defining the specific aspect/style to apply an element to.  Those two properties are `color` and `padding`.

<br>

❓ _**What data type is a sequence of text enclosed in single quote marks?**_

String

❓ _**List 4 types of JavaScript operators.**_

+ Addition
+ Assignment
+ Strict equality
+ Does not equal

❓ _**Describe a real world Problem you could solve with a JavaScript Function.**_

Code that speaks sentences outloud for the blind may involve a JavaScript addition operator concatenating strings of learned words.  Also, a program might use a JavaScript operator as well when a person uses code to perform math (code that solves how much to tip a waiter, a screen in a pedometer that shows the total number of steps walked, a page that shows the sum of an online shopping cart, etc.).

❓ _**An `if` statement checks what?**_

A condition

❓ _**The code block will be execute if the `if` statement evaluates to what?**_

If it is true

❓ _**What is the use of an `else if` in JavaScript?**_

If the programmer wants more than two outcome choices to be true.  Each extra choice will require an additional outcome block placed betweeb `if () {}` and `else {}`.

❓ _**List 3 different types of comparison operators in JavaScript.**_

`===` to test whether one value is identical to another

`!==` to test whether one value is NOT identical to another

`<` to test whether one value is less than another

`>` to test whether one value is greater than another

`<==` to test if one value is less than or equal to another

`>==` to test if one value is greater than or equal to another

❓ _**What is the difference between the logical operator `&&` and `||`?**_

`&&` allows a JavaScript programmer to chain together two or more expressions in an "AND" manner, so that all of them have to invidually evaluate as `true` in order for the whole expression to be `true`.

`||` allows a JavaScript programmer to chain together two or more expressions in an "OR" fashion, so that only one or more of them have to invidually evalue to `true` for the whole expression to be `true`.

<br>

<br>

## 📚 Links to the Assigned Reading:

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[Advanced HTML Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

[How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

[JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[Making decisions in your code — JavaScript conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

[How to Write a Git Commit Message](https://cbea.ms/git-commit/)

<br>
