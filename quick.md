# 🦄 Below are copies of the HTML-related content of all my reading notes so far 🦄

## From 102:

+ HTML consists of elements that are made up of 3 parts: an **opening tag**, the **content** that will appear on the page, and a **closing tag**.
+ Extra information, such as styling, can be added using _**attributes.**_
+ _**Semantic elements**_ label the structural purpose of the content they surround.  If the name of the element tells you its purpose then it is a semantic element.  For example, a footer, header, or other section of the page.
  + Using semantic elements helps other coders to understand the structure of your website when reading your code.  For example, it would be possible for the top of your website's code to be called "footer" and a web broswer could still operate fine with that if you told it to (putting the "footer" labelled content at the top of the page), but doing that would make no sense to a person who is looking only at your code.
+ The _**head**_ contains instructions for the browser that the user doesn't see on the page itself
  +  For example, what _**title**_ the browser should display in the tab.
+ The _**body**_ is everything that the user sees on the webpage itself.
  + A _**header**_ is not required but is good practice to have on a page.
  + The _**main**_ contains the majority of the page's content.
  + A _**footer**_ is not required but is good practice to have on a page.

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



## Reference sources being quoted:
[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[Getting Started With HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[HTML Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

<br>
