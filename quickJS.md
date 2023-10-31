# 🦄 Below are copies of all my JavaScript-related notes so far 🦄

## 📺 102 Lecture Notes:

JavaScript delivers user interface action.  JavaScript is interactive, unlike HTML which is the static structure, or CSS which is static styling.

It is personalized for the user's experience.  Based on input, we will get different output.  Its purpose is to take information and do something with it based on the programming code.

 JavaScript is a rare gem in that it is used in both front end AND back end programming.

JavaScript has its own language syntax rules

**Variables** are containers for holding onto information
  + You get to make the container
  + You get to decide the information
  + You get to decide what to do with that information
  + An analogy would be that a moving box with the label "Kitchen" on it would be expected to contain contents related to the kitchen 

**Conditional**

Each line of JavaScript should end with a semicolon `;`

4 Ways to Declare a Variable
* _**let**_ is used if the variable can be changed
* _**const**_ is used if the variable can NOT be changed
* _**var**_ is an antique way of declaring variables.  It should be avoided because nowadays it may give unexpected results
* (no keyword) is a bad way of declaring a variable and should be avoided 

Dynamic components are part of JavaScript but not all JavaScript is a dynamic component

JavaScript will work no matter where you place it within an HTML file.  It will run and thereby write the code in the location in which you place it.  So, for example, if you place a `document.write` command inside the header that text will appear in the header, but if you place that same command below the `</main>` then it will be written below the main, or if you put the same command inside of the footer then the text would appear in the footer.

JavaScript can be added to website files in muliple ways
+ External file
  + Typically the file is called `app.js` or `script.js`
  + Link the external file using the command `<script src ="ScriptFileNameHere"></script>` Using the typical file name that will be `<script src="script.js"></script>` REMEMBER: Wherever you create the link within your HTML file is where the browser will run it.  A good place for it within the Course 102 labs is at the start of the `<body>` because we want the browser to run the entirety of our 102 lab JavaScript files before loading the visible elements of the webpage.
  + This method is best practice 
+ Internal JavaScript:  It can be added directly inside an HTML file by using the HTML tag `<script>...</script>`
  + The contents inside the HTML script element would be written in pure JavaScript
  + This method is NOT good practice

<br>

Data Types
* _**String**_ is text
  * When writing the code, it will be surrounded in quotes.  JavaScript prefers single quotes to be used `'`
  * Examples: 'Myra' , 'two' , '2' , 'one hundred and twenty' , '120'
* _**Number**_ is strictly equal to the numerical value
  * Do not use quotation marks
  * Examples: 2 , 120
* _**Boolean**_ data types are only either TRUE or FALSE

<br>

Basic JavaScript Commands (ie. Basic Functions & Methods):
+ _**alert**_ creates a popup box containing text, to which the only the thing the user can respond with is to hit the "Okay" button
  + It is the most basic function within JavaScript
  + The command 'alert' should always be followed by a set of parentheses `()`
  + The message you would like to have appear inside of the popup box is placed inside of the parentheses
  + If that message is being written in the code as a text strings, place it inside of quotation marks `""`
  + At the end of the line place a semicolon `;`
  + For example: `alert("Hello everyone! I am a popup box");` 
+ _**console.log**_ is a basic JavaScript command that sends information to the console
  + The console is "under the hood" of a browser (In Chrome, access it via: right-clicking --> Inspect --> Console)
  + Like the alert function, this command is also followed by a set of parentheses and a message
  + Whatever is inside of the parentheses is what will appear inside of the console
  + For example: `console.log("I am written in the console");`
+ _**document.write**_ will write a dynamic component onto the webpage
  + Places data onto your webpage
  + Example 1 (using a string): `document.write("A string of words to have appear on the webpage goes here");`
  + Example 2 (using a variable): `document.write(myName);`
+ _**let**_
  + Follow the `let` keyword with the variable name
  + Then the equal sign `=`
  + Then whatever value you would like to give the variable
  + Example: `let myName = 'Myra';`
  + The value of the variable can be changed by reassigning it.  For example, `let myName = 'Myra';` can be changed in a later line of code to `myName = 'Sam';`
+ _**const**_
  + Example: `const myName = 'Myra';` will retain the value "Myra" even if on a later line you wrote `myName = 'Sam';`  In fact, it would cause an error message that would stop the program from running at that point in the code.

As soon as JavaScript encounters an error, it will stop running and you will never see anything that is in the code after the error

<br>

<br>

### Additional Credit:

The phrasing used inside the 102 Lecture Notes section often originates from how CodeFellows instructor Kassie Bradshaw phrased her explanations of the concepts to us during lectures.  Thank you for being an amazing teacher, Kassie! 💜

<br>
