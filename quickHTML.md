# 🐎 Below are copies of the HTML-related content of all my reading notes so far 🐎

|Table of Contents|
| ------ |
|[102 Notes](https://myra-sea.github.io/reading-notes/quick.html#-notes-from-102)|
|[201 - HTML Basics](https://myra-sea.github.io/reading-notes/quick.html#-html-basics)|
|[201 - HTML Text Fundamentals](https://myra-sea.github.io/reading-notes/quick.html#-html-text-fundamentals) |
|[201 - HTML Text Formatting](https://myra-sea.github.io/reading-notes/quick.html#-html-text-formatting) |

<br>

## 🧱 Notes From 102:

+ HTM Language consists of elements that are made up of 3 parts (2 tags + something placed in between those tags).  Those 3 parts comprising HTML are: an **opening tag**, the **content** that will appear on the page, and a **closing tag**.
+ Extra information inside the _opening tag_, such as styling, can be added using _**attributes.**_

<br>

+ _**Semantic elements**_ label the structural purpose of the content they surround.  If the name of the element tells you the purpose of what's inside, then it is a semantic element.  For example, a footer, header, nav (navigation menu), table, or other section of the page.
  + `<Strong>` is a semantic element because the purpose of the element is to tell the broswer to strongly emphasize the content (this is especially important for screen readers to have).   However, `<b>` is not because "bold" is an adjective, not a purpose.  If you were describing how a person spoke an important word louder and more forcefully within a sentence to you, you would say that they "strongly emphasized" that important word, NOT that they "bolded" the word.
  + Using semantic elements helps other coders to understand the structure of your website when reading your code.  For example, it would be possible for the top of your website's code to be named "footer" and a web broswer could still operate fine with that if you told it to (putting the "footer" labelled content at the top of the user's screen), but doing that would make no sense to a person who is looking only at your code.
+ The _**head**_ contains instructions for the browser that the user doesn't see on the page itself
  +  For example, what _**title**_ the browser should display in the tab.
+ The _**body**_ is everything that the user sees on the webpage itself.
  + A _**header**_ is not required but is good practice to have on a page.  That's because usually the header stays the same between pages; thereby easily allowing the user to know that they are still on the same website.
  + The _**main**_ contains the majority of the page's content.
  + A _**footer**_ is not required but is good practice to have on a page.  That's becaues the footer doesn't usually change between pages.  Thus easily allowing the user to know that they are still on the same website.

<br>

  + In the early stage of creating a website, if you want to create a temporary placeholder for a link but do not yet want to fill in the link itself yet, you can use a `/` or a `#` inside the `href` quotation marks.
    + For example,  `<a href="#">Link 2</a>` creates a temporary placeholder that looks like this: [Link 2](#)

A nice seeming explanation of many semantic elements that I found from an internet search is: [here](https://www.w3schools.com/html/html5_semantic_elements.asp) 

<br>

## 👩‍💻 HTML Basics

+ HyperText Markup Language is the coding language used to structure a webpage and its contents.
+ HTML uses _**elements**_ that enclose the content in order to make it appear or act a certain way. Elements are created using _**tags**_.
  + For example, a paragraph element uses the tags `<p>` and `</p>`.
  + So, as an example of what comprises an element, in the following HTML code: `<p>A sentence goes here.</p>` the _**opening tag**_ is `<p>` , the _**closing tag**_ is `</p>` , and the _**content**_ is `A sentence goes here.` All together, the opening tag, closing tag, and content, comprise the element.
  + Other examples of what tags can do include: creating a hyperlink, italicizing a word, changing the size of font, etc.
+ To link to a target file in the same directory as the html file just use the filename (example: image.jpg)
+ To link to a target file in a subdirectory write the directory name in front of the path plus a forward slash (example: subdirectory/image.jpg)
+ To link to a target file in a directory **above** the html file write two dots (example: ../another-image.jpg)
+ The Windows file system tends to use backslashes, not forward slashes. However, this doesn't matter in HTML — even if you are developing your website on Windows. You should still use forward slashes in your code.

<br>

## 👩🏻‍💻 HTML Text Fundamentals

HTML is a language made up of what are called "elements," which can be applied to pieces of text to give them different placement assignments (inside a paragraph, inside a bulleted list, etc.), provide structure to a document (create headers, multiple columns, navigation menus, etc.), or embed images (such as videos). Regardless of the medium it's being read/written on, most structured text consists of headings and paragraphs.  This is the case, whether reading an old fashioned newspaper, chapters in a printed book, or product reviews on a website.  When writing HTML code, headings can be wrapped in heading elements, such as `<h1>` ... `</h1>` for example. Paragraphs can be wrapped in `<p>` ... `</p>` elements.

<br>

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


<br>

<br>

## Reference sources:
[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[Getting Started With HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[HTML Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[Advanced HTML Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[Unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

[Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

<br>
