# 🦓 Below are copies of the CSS-related content of all my reading notes so far 🦓

## 102 Lecture Notes

CSS is the language used for styling HTML elements.  If you don't have the HTML element in your HTML file then you will never see that specific CSS style instruction.
+ Classes and IDs are used in CSS to target specific HTML elements in order to style them.
+ It defines rules that will be applied to HTML elements.  It defines the rule that will be used when you reference either that element or that unique CSS tag.
  + For example, if you wanted to make the text of all paragraphs on the page red colored, the CSS code would be `p {color: red}`

CSS syntax (its language rules) uses curly braces `{`

Structure of a CSS Rule <sup>(this structure is used regardless of what HTML element is being targeted and also whatever styles are being applied to that element)</sup>:
1. _**Selector**_: Identify the HTML element you want to select
2. Opening curly bracket: `{`
3. _**Property**_: The aspect being manipulated or modified for that element
4. The colon symbol: `:`
5. A blank space
6. _**Value**_
7. The semicolon symbol: `;`
8. Closing curly bracket: `}`

A typical, highly readable choice when writing the code is like this: 
>selector {
>
>property1: value;
>
>property2: value;
>
>property3: value;
>
>}

**Classes** can be used multiple times

**IDs**, on the other hand, are unique.

There are three way to be able to incorporate CSS into an HTML file
* External Stylesheet:  The industry best practice of putting all the CSS into its own separate file
* Internal Styles:  Places the CSS code itself directly inside of the HTML document
* Inline **Styles**:  Places the instructions inside the element itself. It will therefore be written in HTML

With incorporating CSS using an **external stylesheet**, use the following format in the HTML file.  Best practice is to place this in the head section:
`<link rel="stylesheet" href="style.css">`
Meaning:  link (What is it being linked to? Answer: a stylesheet) href (name of your CSS file)
+ Each html file within the website would need that set of instructions placed in the head.

When adding **internal styles**, use the following HTML format in the head section instead:
`<style> selector {property: value;} </style>`

The browser is reading the HTML instructions in order.  Because it is placed on a later line in the code than the external stylesheet link, the internal style will replace what the instructions from the external stylesheet had been.  The internal style is the one that will be shown from that point in the HTML code onward.  A weak analogy but one that I can think of would be like the set of instructions for creating a scratch off art surface: The first part of the instructions (the external stylesheet) would say to paint the entire piece of paper a rainbow of different colors, and then the next part of the instructions (internal style) would say to paint the entire piece of paper chalk black, resulting in black being all that is seen in the end (at least until someone uses the paper to make scratch art).
  
An example of **inline style** would be `<body style="background-color: green;>"....</body>`
Any inline styles written in the code after internal styles would replace the internal style for the same reason as was explained above.


[Click here](https://www.reddit.com/media?url=https%3A%2F%2Fi.redd.it%2Ffeel-the-difference-v0-ndvzegr4jzla1.jpg%3Fs%3Df68eeb10ac44c162c1a1a7f8ec5e3fbca4f1b466) for a meme demonstrating the relationship between HTML versus CSS.

<br>

### Additional Credit:

The phrasing used inside the 102 Lecture Notes section often originates from how CodeFellows instructor Kassie Bradshaw phrased her explanations of the concepts to us during lectures.  Thank you for being an amazing teacher, Kassie! 💜

<br>
