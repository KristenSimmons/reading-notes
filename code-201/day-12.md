# Canvas & Chart.js

## JavaScript Canvas
1) What does the canvas allow a developer to acheive?
Adding the canvas element to s site allows the developer to draw 2D graphics using JavaScript.
2) What is the importance of the closing canvas tag?
To use the canvas feature, you need to include both an opening and closing canvas tag. Everything inside the tags will be the fallback content that will display only if the browser doesn’t support the canvas element. For example: 
< canvas width="500" height="300" id="canvas">The browser doesn't support the canvas element</ canvas >

3) Explain what the getContext() method does.
Initially, the canvas is blank. To draw something, you need to access the rendering context and use it to draw on the canvas. The canvas element features the getContext() method that returns a render context object. The getContext() takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface.When using the canvas element, it’s important to check if the browser supports the getContext(). Most current browsers do

## Chart.js Documentation
1) What is Chart.js and how it can be brought into your project?
Chart.js is an application that can be used by developers to add data charts to their programs. There are several chart types that can be used. The chart an be created in a seperate js doc or by adding it right into the html. 
2) List 3 different Chart types you can create using Chart.js.
Chart.js can create just about any type of chart. Some commone types are: bar, line, dot, pie and scatter charts. The type of data you are needing to display will decide the best chart to use.

## Creating Animated Charts 
1) What are some advantages to displaying data via a chart over a table?
Charts are better for displaying data visually than tables. Charts are easier to look at and convey data quickly, compared to tables. 
2) How could Chart.js aid your previously created applications visually?
I could use Chart.js on my Odd Duck page to display the voting data collected. I could have used this in Code 102 when creating my personal page with a quiz. A chart would have been a fun way to display the data back to the user regarding the questions.

## Resources
- [JavaScript Canvas](https://www.javascripttutorial.net/web-apis/javascript-canvas/)<br>
- [Chart.js Documentation](https://www.chartjs.org/docs/latest/)<br>
- [Easily Create Animated Charts](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)<br>
- [Drawing Shapes w/Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)<br>
- [Applying Styles & Colors - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)<br>
- [Drawing Text - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)<br>