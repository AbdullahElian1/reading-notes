# Chart.js

Chart: better for displaying data visually than tables.

A great way to get started with charts is with Chart.js, 
a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.

example

1-we need to download chart.js



2- to do a line chart in html

\<canvas id="buyer> </canvas>

3-in the script tag

document.getElementById('buyers').getContext('2d');

new Chart(buyers).Line(buyerData);


4- create our object.


# Canvas

\<canvas> => has two attributes:

 1-width 

 2- height

canvas can be  styled just like any normal image .

fallback content:

example

\<canvas id="stockGraph" width="150" height="150">
  current stock price: $3.15 + 0.15
\</canvas>


Drawing rectabgles:


1- fillRect(x, y, width, height) => Draws a filled rectangle.

2-strokeRect(x, y, width, height) =>Draws a rectangular outline.

3-clearRect(x, y, width, height) =>Clears the specified rectangular area, making it fully transparent.





 




