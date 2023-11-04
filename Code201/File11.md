# 🐙 Audio and Video in HTML; Domain Modeling Revisited 🐙

## 📝 Assigned Homework Questions:

❓ Explain how the ability to use video and audio on the web has evolved since the early 2000s.

In the early 2000s, the dominant audio/video method on the internet was to use Adobe Flash.  It had several security vulnerabilities.  Internet speeds back then were also a fraction of what they are now, and that limited the ability for video back then.  One of the significant changes to come about due to faster speeds and greater processing power has been the ability to livestream nowadays.  My memory of that time is also that copyright infringement was a LOT more lax on hosting sites such as YouTube back then.

❓ Describe the use of the `src` and `controls` attributes in the `<video>` element.

The `<video>` element allows devs to easily embed a video onto a webpage.  The `src` (which stands for "source") attribute contains the path address to the video file.  The `controls` attribute inserts the broswer's video control interface onto the page so that users can control playback and audio details.

❓ Why is it important to have fallback content inside the `<video>` element?

If the broswer accessing the webpage is unable to support the `<video>` element (such as if it is an old broswer), that text content will alert the user to the fact that the video can't play.  It is suggested that a link to the video be given within that text so that the user can manually navigate to the other page to watch it.

❓ Write a very short story where `<audio>` and `<video>` are characters.



<br>

❓ How does Grid layout differ from Flex?

Grid is a two-dimensional layout system whereas Flex uses only one-directional flow.  The two can work together very nicely.  Flex is better at pushing elements away from each other and Flex is supported more widely on the internet.  Grid is better at overlapping elements and is sturdier.  Flex will wrap new lines of text that don't fit down to the next line independent of how the lines above are stacked, whereas Grid will line the new rows up with the ones above along grid lines similar to how stacked bricks look in a brick wall.  Grid is mostly defined on the parent element, wheras Flex is mostly on the children elements.

❓ Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

_**Grid Container**_ is the element on which `display: grid` is applied.  It is the name of the topmost CSS class.  The direct parent of all the grid items.

_**Grid Items**_ are therefore the direct descendant children of the grid container. It is the name of the CSS class directly inside of the Grid Container.

_**Grid Lines**_ are the dividn lines that make up the structure of the grid.  They can be either horizontal (row) or vertical (column).  The lines form the border of a grid cell.

>`<grid container>`
>
>`<grid item>....</grid item>`
>
>`<grid item>....</grid item>`
>
>`</grid container>`

<br>

❓ Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

* It can save bandwidth
* It can preserve image quality
* It can make solving the situation more simple/faster

❓ Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.



❓ How is `srcset` more helpful for responsive images than CSS or JavaScript?


    
<br>

<br>

## 📚 Links to the Assigned Reading:

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
