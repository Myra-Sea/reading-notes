# CSS

*CSS stands for Cascading Style Sheets.  It is a coding language, that allows control over how HTML elements look, enabling creativity of design.  For example, it can change the color or size of text, whether an element moves on a page(animates), and how sections are laid out on the screen.*

CSS defines rules that should be applied to elements on the page.  

<br>

![divider line](divider.gif)

<br>

CSS uses its own syntax.  It begins with a **selector** that identifies which HTML element (for example p or h1) the rules will apply to.  It then has an **opening curly bracket {**. Next is the **declaration** consisting of a **property** (example: color, font-size, or border-color), followed by a **colon**, and then the **value** being ascribed to it (example: green, 5em, or 50%), followed by a **semi-colon**. The syntax then ends with the **closing curly bracket }**.

If multiple declarations are needed for the selected HTML element they should all be placed within the one pair of brackets, one written after another.  For readability, they can each be placed on a separate line within the code:

```
selector {

    property: value;
    
    property: value;
    
    property: value;

}
```

<br>

![divider line](divider.gif)

<br>

CSS has modules. For example, there is a module for backgrounds.  It is defined by globally agreed upon specifications and is developed by a group within the World Wide Consortium called the "CSS Working Group" as well as independent invited experts.  The creators work very hard to ensure that old CSS previously used on websites will continue to function as new CSS features are created.

<br>

![divider line](divider.gif)

<br>

## Ways to insert CSS into a webpage

1. **External CSS:**  This method is the best practice for using CSS.  A separate CSS file that can change the look of an entire website.  There should not be any HTML tags inside this external file.  Instead, a reference to this external CSS file must be made inside of a <link> element in the <head> section of the HTML page.  This is the location because it's information for the browser instead of the viewer.  It will need to be written in this head location for every html page of the website that you wish to look the same.
`<link rel="stylesheet" href="style.css">`

2. **Internal CSS:**  This method is CSS inside of the HTML document.  This method uses HTML <style> </style> tags with the CSS syntax inside.

3. **Inline CSS:**  This is styling code directly inside the HTML element itself.  As a result, the code will appear as if it is written in HTML due to the lack of curly brackets.

```
The website browser will look for CSS in the above order.  It reads all external CSS first, followed by applying any internal CSS, and then applies any inline CSS.  As a result, the inline CSS rule will override the internal CSS rule, which in turn takes priority over the external CSS rule.
```

<br>

![divider line](divider.gif)

<br>

Example:  To make all `<p>` elements on a page appear red, the code would be

```
p {
color: red;
}
```
