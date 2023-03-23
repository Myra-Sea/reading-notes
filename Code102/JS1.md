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

**Assignment operator** is the `=` sign in JavaScript code.  It functions to assign a new value to a variable.

**Variables** are containers for storing data values.  For example, the letters x, y, z commonly found in Alegbra.  *The process of creating a variable is also known as **declaring** a variable.* There are 4 ways JavaScript variables can be expressed (declared):
1. **var**
2. **let**
3. **const**
4. **no label at all, undeclared**

`var X = 5` is the same as `let X = 5` and both of those are the same as simply `X= 5`

<br>

![divider line](divider.gif)

<br>

It is best practice to always use `var`, `let`, or `const` instead of leaving the value undefined.  Of those 3 choices, it is best to always try to use `const` (denotes a **fixed** value) unless you want the value of the variable to be changeable, in which case use `let`.

The label `var` was used from 1995 to 2015, whereas the let and const keywords was added to JavaScript in 2015.  Therefore, if you want your code to run in older browsers, you must use `var`.


For example, if:
```
const Price1 = 5;

const Price2 = 6;

let total = price1 + price2;
```
Price1 and Price2 are declared as being constant values that cannot be changed, whereas the variable total is declared as being a value that can be changed.

<br>

![divider line](divider.gif)

<br>

When information is received from a user, it is called **User Input.**  

One way that it can be recieved in JavaScript is via the `prompt` command.  This command will generate a dialog box where a user can enter whatever data they wish.  Whatever they enter will be stored into a variable to be used later by the code.

The code for a JavaScript prompt command is:

`<script> let ... = prompt("..."); </script>` 

where the first ellipsis is whatever label you wish to give the variable, and the second ellipsis is whatever instruction or question you wish to ask the user inside of the dialog box.