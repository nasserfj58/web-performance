# Web-Optimization

## For this project I did this steps to provide an optimized Project

### To improve index.html performance I did this steps:  
1. Optimize and compress all the photos in index.html (I download the out src phots and did the same with them).
2. Minify and  compress all css and html and js included in the index.html page.
3. I made the print style only get download in print action by adding media=print.
4. I made the analytics.js defer so it will not block the rendering of the index.html.

### In main.js I did this steps:
In the callback function in DOMContentLoaded event inside scroll event I didt this steps:
1. Calculate number of rows based on screen resolution (for pizza).
2. Get the number of required pizza to fill the screen.

### In changePizzaSizes function:
1. Make  the random Pizza Container out of the loop and I use getElementsByClassName to get because it's faster.
2. Get the size of the pizzaContainer to use it in the for loop rather than fixed number.
3. Since all the pizzas is the same size I create newwidth varible that contain the size of one of the pizzas and use it.
4. To Set pizzaContainer.style.width.
