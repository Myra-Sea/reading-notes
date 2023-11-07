# 🪼 ChartJS and Canvas 🪼

## 📝 Assigned Homework Questions:

❓ What does the `<canvas>` element allow a developer to acheive?

It allows a dev to draw 2D graphics using JavaScript.  It requires at least the width and height attributes (so that the size of the canvas has been specified).  The width and height elements can be accessed via the canvas' DOM properties (`document.querySelector(#canvas); const width = canvas.width; const height = canvas.height;`).  The width and height can also be changed using the DOM methods `canvas.width =` and `canvas.height =`.

❓ What is the importance of the closing `</canvas>` tag?

Any content between the canvas element tags is fallback content that will display if the browser doesn't support the `canvas` element.

For example, `<canvas width="500" height="300" id="canvas">Your browser doesn't support the canvas element</canvas>`

❓ Explain what the `getContext()` method does.

The initially created canvas is blank.  Therefore, the `getContext()` method allows access to the rendering context so that it may be used to draw on the canvas.  It takes one argument which is the type of context.  For example using `"2d"` would return a 2D rendering context object, allowing you to draw shapes, text, images, and other 2D objects.

> let canvas = document.querySelector('#canvas');
>
> let ctx = main.getContext('2d');

<br>

❓ What is Chart.js and how it can be brought into your project?

An open-sourced, highly customizable charting library for JavaScript application developers.  It provides a set of frequently used chart types, plugins, and customization options.  It includes built-in chart types as well as community-maintained ones.  It is also possible to combine several chart types into a mixed chart, blending multiple chart types into one on the same canvas.  Custimization plugins include the ability to create annotations, zoom, and drag-and-drop functionalities.  Chart.js has animations turned on by default.  It also comes with built in TypeScript typings and is compatible with all popular JavaScript frameworks.

❓ List 3 different Chart types you can create using Chart.js.

* **Line Charts** plot data points on a line.  This type of chart is often used to show trend data or a comparison of two data sets.
* **Radar Charts** show multiple data point and the variation between them.  This type of chart is often used for comparing the points of two or more different data sets.
* **Bar Charts** show data values represented as vertical bars.  This type of chart is often used to show trend data or a comparison of multiple data sets side-by-side.
* **Bubble Charts** display three dimensions of data at the same time.  The location of the bubble is determined by the first two dimensions and the corresponding horizontal and vertical axes.  The third dimension is represented by the size of the individual bubbles.
* **Doughnut and Pie Charts** are the most commonly used charts.  They are dived into segments, the arc of each segment showing the porportional value of each piece of data.  This type of chart are excellent at showing the relational proportions between data.

<br>

❓ What are some advantages to displaying data via a chart over a table?

The visual display of data conveys data faster than a table does and is easier on the eyes.  Visual elements are more engaging and can capture a viewer's attention more effectively than tables.  A visual representation also tends to make the information more memorable to viewers than numerical data in a table would.

❓ How could Chart.js aid your previously created applications visually?

The votes in the Odd Duck project could be represented inside of a bar chart, like what was shown in the lecture demo. 😉

<br>

<br>

## 📚 Links to the Assigned Reading:

[JavaScript Canvas](https://www.javascripttutorial.net/web-apis/javascript-canvas/)

[Chart.js Documentation](https://www.chartjs.org/docs/latest/)

[Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

[Drawing Shapes With Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

[Applying Style and Colors - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

[Drawing Text - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)
