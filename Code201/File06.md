# 🦚 JavaScript Object Basics, Problem Domain, & DOM 🦚

## 📝 Homework Assignments:

❓ How would you describe an object to a non-technical friend you grew up with?

It is a container that holds information in an organized fashion.  The pieces of information are stored as pairs (separated by a colon), called "properties" and their associated "values".  For example, if you were recording some basic demographic information about yourself, you might record a _property_ called something like "name" and the _value_ you would record would be your name.  You could also record another _property_ called something like "age" with the _value_ of that property being your age!

❓ What are some advantages to creating object literals?

* Simplicity and readability
* Easy nesting
* Efficiency of sending a single object instead of needing to send several items individually
* Ease of use compared to an array, if youw ant to identify individual items by name

❓ How do objects differ from arrays?

1.
   * Objects are unordered collections of property-value pairs
   * Arrays are ordered listts of values, each of which is associated with an index number

2.    * The values inside of objects are accessed using the property names as the identifiers
      * The elements inside of arrays are accessed using the numerical indexes

3.    * An object is typically used when you want to store related data together and access the contents using label-like names
      * An array is typically used when you want to store a list of values

❓ Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

When an object property name is held in a variable.

❓ Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
>const dog = {
>
>name: 'Spot',
>
>age: 2,
>
>color: 'white with black spots',
>
>humanAge: function (){
>
>console.log(`${this.name} is ${this.age*7} in human years`);
>
>}
>
>}

It refers to the values contained inside this one specific object. It's talking about the current object the code is being written inside For example, `this.name` is Spot and `this.age` is 2 (times 7 for human years being 14).

Using the `this` keyword enables you to use the same method definition for every object you create.

<br>

<br>

❓ What is the DOM?

The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the internet.  It is a programming interface for web documents.  It represents the page so that programs can change the document structure, style, and content.  The DOM represents the document as nodes and objects.  Doing so allows programming languages to interact with the page.  As an object-oriented representation of the page, the document can be modified with JavaScript.

❓ Briefly describe the relationship between the DOM and JavaScript.

The document as a whole (including all of its elements such as tables) are parts of the document object model for that document.  The elements can be accessed and manipulated using the DOM and a scripting language like JavaScript.

The DOM is a Web API used to build websites.  It is not a programming language.  It was designed to be independent of any particular programming language, making the structural representation of the document available from a single, consistent API.

JavaScript is the language used, whereas the DOM is what is used to access the document and its elements.  Without the DOM, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

Even though most web developers will only use the DOM through JavaScript, impelementations of the DOM can be built for any language.

<br>

<br>

## 📚 Links to the Assigned Reading:

* [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
* [Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
* [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
* [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
