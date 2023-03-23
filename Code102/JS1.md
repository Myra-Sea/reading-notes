# JavaScript - Introduction

*JavaScript is a scripting programming language that allows complex, interactive features.  It has many, dynamic capabilities.  It was created (and is trademarked by)  Oracle.*

Originally, it existed only inside of the html pages and would run only in the browser on the client's side.  This is achieved by either: 
1. embedding the code directly inside the HTML file using the tags `<script>...</script>` or, alternatively, specified as `<script language="javascript">...</script>`

2. Including a line in the HTML file referencing an external JavaScript file. This reference is coded as `<script src="script.js">...</script>`  **This second method is the preferred, better practice choice.**

Recently, JavaScript has begun to be used directly within the servers on the back end as well.

<br>

![divider line](divider.gif)

<br>

## Definitions

**DOM API** is how JavaScript can interact with the parts of a webpage while in the browser.

**Variables** are containers for storing data values.  For example, the letters x, y, z commonly found in Alegbra.  *The process of creating a variable is also known as **declaring** a variable.* There are 4 ways JavaScript variables can be expressed/declared:
1. **var**
2. **let**
3. **const**
4. **no label at all, undeclared**

In other words, `var X = 5` is the same as `let X = 5` and both of those are same as simply `X= 5`

<br>

![divider line](divider.gif)

<br>

It is best practice to always use `var`, `let`, or `const` instead of leaving the value undefined.  Of those 3 choices, it is best to always try to use `const` (denotes a fixed value) unless you want the value of the variable to be changeable, in which case use `let`.

The label `var` was used from 1995 to 2015, whereas the let and const keywords was added to JavaScript in 2015.  Therefore, if you want your code to run in older browsers, you must use var.

```
So, for example, if:

const price1 = 5;

const price2 = 6;

let total = price1 + price2;

Price1 and price2 are declared as being constant values that cannot be changed, whereas the variable total is declared as being a value that can be changed.
