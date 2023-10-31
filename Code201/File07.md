# 🦩 HTML Tables & JS Constructor Functions 🦩

## 📝 Homework Assignments:

❓ Explain why we need domain modeling.

It creates a conceptual model for a specific problem.  It describes the various entities, their attributes and behaviors, and the constraints that govern the problem domain.  It can verify and validate your understanding of the problem.

❓ Why should tables not be used for page layouts?

The point of a table is that it is rigid.  It is designed for tabular data.  Using it for a different purpose when modern CSS exists is counterproductive to having good, clean code.  Because tables are not the correct tool for laying out web pages and the markup required is more complext than CSS, a screen reader's output will sound very confusing as it interprets tags and reads out the page's content to visually impaired users.  The same overly complex markup structures will also result in the code being harder for the dev to write, maintain, and debug.  Lastly, it won't be responsive.  Unlike proper layout containers, tables are sized according to their content. Therefore, extra measures are needed to get tale layout styling to work effectively across a variety of devices. 

❓ List and describe 3 different semantic HTML elements used in an HTML `table`

1. `<table>....</table>` is used to contain all of the contents of the table code.

2. `<td>....</td>` An abbreviation for "table data," it generates a cell within the table.

By default, the `td` cells end up arranged side-by-side horizontally.  Every cell we create this way makes the row grow longer.  Therefore, the following example
>`<td>`First cell`</td>`
>
>`<td>`Second cell`</td>`
>
>`<td>`Third cell`</td>`
>
>`<td>`Fourth cell`</td>`

would generate a ROW of four cells.

3. `<tr>....</tr>` (abbreviation for "table row") is therefore needed to create a hard break between the desired rows.  For example, you would code a 2 row 4 column (ie. 8 cell) table as follows:
>`<tr>`
>
>`<td>`Cell 1 of Row 1`</td>`
>
>`<td>`Cell 2 of Row 1`</td>`
>
>`<td>`Cell 3 of Row 1`</td>`
>
>`<td>`Cell 4 of Row 1`</td>`
>
>`</tr>`
>
>`<tr>`
>
>`<td>`Cell 1 of Row 2`</td>`
>
>`<td>`Cell 2 of Row 2`</td>`
>
>`<td>`Cell 3 of Row 2`</td>`
>
>`<td>`Cell 4 of Row 2`</td>`
>
>`</tr>`

  
4. `<th>.....</th>` stands for "Table Header" and functions to make the headers stand out more clearly.  Table headers are special cells at the start of a row or column that define the type of data that row or column contains.  Thus making desired pieces of data easier to find.  It also allows screen readers to read out the entire row or column of data at once.

❓ What is a constructor and what are some advantages to using it?

It is a function that defines the set of methods and properties an object can have and then allows us to create as many objects as we like, just updating the values for the properties that are different. A constructor function defines the same properties between many objects.  It is defined using a _function expression_.  It is called using `new`.  Calling a constructor creates a new object, binds the `this` variable to the new object so that the `this` variable can be referred to in the code, runs the code in the constructor, and returns the new object.

Some Advantages:
*  More efficient (requiring less code) and organized than a regular function
*  Greater readability
*  Encapsulation of data and function inside of objects

❓ How does the term `this` differ when used in an object literal versus when used in a constructor?

An _**object literal**_ is a object in which the object contents are literally written out during creation.

The `this` variable is used within methods in order to acces the object's properties and methods from the inside. It refers to the current object the code is being written inside of.  For object literals, the `this` variable often refers to the object itself.  For constructors, a new instance needs to be created first.  The `this` variable refers to the specific instance being created.  

❓ Explain prototypes and inheritance via an analogy from your previous work experience. (NOTE: This is a very common front end developer interview question.)

Prototypes are like a template or master copy. This method is often used when training the same species of animal the same behavior.  After a training plan has proven successful for one member of a species, it can be reused as the template to train future members of that same species.  While certain details may need to be individually tweaked to accomodate slight differences between individuals, the overall plan will remain noticeably similar between the individuals.  For example, the individual training details of a group of rats being trained to climb up a flight of stairs when a bell is rung will have more in common with each other than they would when compared to the individual training details of a group of rats being trained to swim across a tub of water when a bright light is flashed at them.

Inheritance is a way to share and reuse code between objects.  An analogy that draws directly from its name would be the way that parent animals pass on certain genetic traits to their offspring.

<br>

<br>

## 📚 Links to the Assigned Reading:

* [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
* [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
* [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
* [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)
* [HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
