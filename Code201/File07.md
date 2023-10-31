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

A constructor function defines the same properties between many objects.  It is defined using a _function expression_.

❓ How does the term `this` differ when used in an object literal versus when used in a constructor?

The `this` variable is used within methods in order to acces the object's properties and methods from the inside.

❓ Explain prototypes and inheritance via an analogy from your previous work experience. (NOTE: This is a very common front end developer interview question.)

<br>

<br>

## 📚 Links to the Assigned Reading:

* [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
* [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
* [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
* [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)
* [HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
