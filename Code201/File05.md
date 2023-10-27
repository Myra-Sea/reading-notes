# 🌺 Images, Color, & Text Styling 🌺

## Assigned Homework Questions:

❓ What is a real world use case for the `alt` attribute being used in a website?

The text description of images is used <sup>(either read outloud by a text reader or written on the screen during slow internet connections)</sup> when a user can't see the image.

❓ How can you improve accessibility of images in an HTML document?

* Do NOT put title attributes in images because it might not be handled correctly by browsers nor screen readers.
* Make sure captions and `alt` text say different things.
* Write accurate descriptions in the `alt` text
* The following link (which was a page attached to the assigned reading) provides _**HTML**_-related tips:  [What HTML features promote accessibility?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/HTML_features_for_accessibility).
* The following link (from the same accessibility guide as the last one) provides _**CSS**_-related tips: [How can we design for all types of users?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Design_for_all_types_of_users)

❓ Provide an example of when the `figure` element would be useful in an HTML document.

The HTML element was created as a way to annotate an image with captions in a compact, easy-to-understand way, providing essential information supporting the main text. A few examples of its use that were given by the reading assignment are:  a code snippet, audio, video, equations, a table, or several images.

❓ Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.

Scalable Vector Graphics (SVG) are the best format to save images in when the picture that need to look accurate no matter how smuch you shrink or expand it.  Because everyone has different levels of eyesight, the most helpful places to use SVG images is for the most important images, like the navigation menu of a website, diagrams, and icons.

A Graphics Interchange Format (gif) is the best format for the opposite needs. Use a gif format if you have a very simple image or animation, and you want it to show up on the most computers. Because a gif imae is so simple it won't take up much memory space in your computer, either.  It is an old way to save images (created back in 1987). So if you need the image to appear on old computers then it is a safe choice.   

❓ What image type would you use to display a screenshot on your website and why?

A PNG would be the best choice for not losing any image quality.  However, a Lossless WebP format would compress the information better.  If the pixelization caused by compression isn't a problem then a JPG would be best as far as file size goes.

<br>

❓ Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

The background color is the color seen behind the words and images on a webpage.  If you think of the contents of a webpage as being like words or drawings on a piece of paper, then the background color would be the color of the paper.

The foreground colors are the ones being put on top.  In the same analogy as before, the foreground colors would be whatever color ink you are writing and drawing onto the paper with.

❓ Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

A safe way to introduce colors that make things pop without overdoing it is to only use the strong colors as accents. A few choice pieces of text the blogger wants to stress, the headers, footers, navigation menus, the borders around images, and other accent areas that don't take up too much space on a screen nor contain much text are safe places for eye-catching colors.  For readability (which is what a blog is all about!) the main body of the page with the text should be kept as close to a white background as possible.  Also, adding one or two colorful images can do wonders and are usually nice to see on blogs.

❓ What should you consider when choosing fonts for an HTML document?

Accessibility factors include legibility (including its size, styling, weight, and color contrast), how much screen space it takes up (and other design factors), and whether the font is "web safe" (ie. the compatibility of the font-family chosen).

Legal factors include copyright ownership of font families.

❓ What do font-size, font-weight, and font-style do to HTML text elements?

* Font-size is the quickest (and often the easiest to see) way to change how much vertical space the text takes up on the screen (the amount of horizontal space used will change as well, but it's normally not as easily apparent).  Changing the size makes the words as a whole bigger or smaller.
* Font-weight affects how bold (thick) the letters are.
* Font-style affects whether or not the text is slanted (italic).

❓ Describe two ways you could add spacing around the characters displayed in an h1 element.

* Altering the box elements is the first thing to come to mind.  The margin and padding.
* Centering the header may also provide a quick solution.
* If needing to add more space above and below, then one of the best solutions would be to use the `line-height` property to change the height of the header line.
* If needing to add more space between the words, then the best solution would be to use the `word-spacing` property.


## Links to the Assigned Reading:

* [HTML Media](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)
* [Using Images In HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
* [Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
* [Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)
* [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
* [Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
* [Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
