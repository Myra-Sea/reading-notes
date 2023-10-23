# Internet Basics and Website Design

Web developers often create websites, either professionally or in their hobby spare time.  Even when hired to edit an existing website, it is helpful to understand the best practices for creating websites, especially if working for a small company or anticipating solo contract work, because situations may arise such as needing to add new webpages or revamping an old site to a new look.

Plus, in any industry, it helps to be familiar with jargon and basic practices.  An understanding of terminology is vital to be able to seamlessly enter a new career.

<br>

## A Simplified View of How the Web Works

The computers connected to the internet are either clients or servers.  A client sends requests to the server, and the server sends responses back to the client.

_**Clients**_ are the combination of internet-accessing software (such as web browsers) on internet-connected devices the user has (such as a laptop or phone)

_**Servers**_ are the computers storing websites, webpages, and apps.  It sends a copy of the webpage to the client to download for display

An internet connection allows data to be sent and received across the internet.  Transmission Control Protocol (TCP) and Internet Protocol (IP) define how that data should travel (they can be thought of like transport mechanisms).  The Domain Name System (DNS) contains the addresses of websites so that a browser knows which server a website is contained within and can therefore send the HTTP messages to the correct location.  HyperText Transfer Protocol (HTTP) defines a language for clients and servers to speak to each other.

Code files are the primary building blocks of websites.  Examples file types include HTML, CSS, and JavaScript.

Asset files are the fluff and flair.  Examples include images, videos, PDF, and music files.

**When a user types a web address into a browser, the following path is followed:**
1. The browser goes to the DNS server to find the address
2. The brower sends an HTTP request to the server for a copy of the website.  All requests and replies are sent using TCP/IP
3. If the server approves the request a "200 OK" message is sent, followed by data packets (ie small chunks) of the website's files
4. The browser then assembles the data packet chunks into a complete webpage and displays it to the user

<br>

## Website Design Basics

**Website creation tools used by professionals:**

+ Laptop or desktop computer with Windows, macOS, or Linux
+ Text editor to write the code in, such as Visual Studio Code, VIM, Notepad++, Sublime Text, GNU Emacs, or a hybrid (examples: Dreamweaver or WebStorm)
+ Web browsers to test the code in.  For example, a text-based terminal web browser that allows you to see how a website is experience by visually-impaired users is [Lynx](https://lynx.browser.org/) (to use the current version still under development [click here](https://lynx.invisible-island.net/current/) ).
+ Graphics editor for creating images.  Examples include GIMP, Figma, Paint.NET, Photoshop, Sketch, or XD
+ Version control system to manage files on servers, collaborate with a team, share code and assets, and to help avoid editing conflicts.  Git is the most popular version control system.  A couple of hosting services are GitHub and GitLab.
+ FTP program to manage files on servers if it is an old web hosting account (Git has replaced FTP).  Examples include Cyberduck, Fetch, and FileZilla
+ Automation system to automatically perform repetitive tasks such as running tests.  Examples include Webpack, Grunt, or Gulp.
+ Libraries (typically a JavaScript or CSS file) to provide faster writing of common functionality within the code
+ Framework to offer a complete system with some custom syntaxes to write a web app on top of

**When creating a website**

+ Keep all the related files inside a single folder that mirrors the published website's file structure.  The folder should be save in an easy-to-find location, such as the Desktop.
+ Avoid spaces within file names.  Hyphens are currently preferred instead of underscores because the Google search engine views hyphens as word sperators.
+ Computers are case-sensetive.  To avoid errors, be very cautious about saving folders or files using anything other than all undercase letters.

**Additional website creation tips**

+ Before creating a website, take the time to plan and design it. Questions to answer include:
	+ What will the website be about?
  + What information will be presented? It is helpful to think of titles, a few paragraphs of descriptions, and possible images to use
  + What will the website visually look like? Think about fonts, background colors, etc.
  + Is a design guide / design system / brand book needed?  If it is a complex project then use one to lay out detailed guidelines on all the details
+ After design details are decided, sketch out the basic, rough design
+ Be carefult to avoid copyright issues with images and fonts (for example, use only [safe web fonts](https://web.mit.edu/jmorzins/www/fonts.html), or go to a site such as [Google Fonts](https://developers.google.com/fonts) to find fonts that have open source licenses)
+ Start assembling the content, such as hex codes
+ Create an `index.html` file to contain the homepage content
+ Create an `images` folder to contain all the images that will be used
+ Create a `styles` folder to contain the CSS code used to style the content
+ Create a `scripts` folder to contain the JavaScript code used to add interactive functionality to your site

<br>

## HTML Basics

+ HyperText Markup Language is the coding language used to structure a webpage and its contents.
+ To link to a target file in the same directory as the html file just use the filename (example: image.jpg)
+ To link to a target file in a subdirectory write the directory name in front of the path plus a forward slash (example: subdirectory/image.jpg)
+ To link to a target file in a directory **above** the html file write two dots (example: ../another-image.jpg)
+ The Windows file system tends to use backslashes, not forward slashes. However, this doesn't matter in HTML — even if you are developing your website on Windows. You should still use forward slashes in your code.

<br>

## Homework Assignments:    

**_Compose a short poem describing how HTTP sends data between computers._**

<br>

❓ **_Describe how HTML, CSS, and JS files are “parsed” in the browser._**

<br>

❓ **_How can you find images to add to a website?_**

The fastest way is to use the image search page within an internet search engine.  To avoid copyright violations, it is best to set the usage rights of the results to "Public Domain," or if that is not an option (Google) then "Creative Commons licenses."  For basic details on the difference between the two, [follow this link.](http://www.differencebetween.net/business/difference-between-creative-commons-and-public-domain/)

<br>

❓ **_How do you create a String vs a Number in JavaScript?_**

**_What is a Variable and why are they important in JavaScript?_**

<br>

**_What is an HTML attribute?_**

**_Describe the Anatomy of an HTML element._**

**_What is the Difference between `<article>` and `<section>` element tags?_**

**_What Elements does a “typical” website include?_**

**_How does metadata influence Search Engine Optimization?_**

**_How is the `<meta>` HTML tag used when specifying metadata?_**

<br>

**_What is the first step to designing a website?_**

**_What is the most important question to answer when designing a website?_**

<br>

**_Why should you use an `<h1>` element over a `<span>` element to display a top level heading?_**

**_What are the benefits of using semantic tags in our HTML?_**

<br>

**_Describe 2 things that require JavaScript in the browser?_**

**_How can you add JavaScript to an HTML document?_**


<br>

<br>

## Links to the assigned reading for this class:

[Getting Started With the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Designing What Your Website Will Look Like](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

<br>

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[Getting Started With HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[HTML Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

<br>

[How to Start Designing a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

<br>

[Website Coding Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

<br>

[Defining JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

<br>

<br>

## Things I want to know more about

