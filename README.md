# Website Performance Optimization Project

The 1st challenge was to optimize this online portfolio for speed! In
particular, optimize the critical rendering path and make the index.html
page render as quickly as possible.

The 2nd challenge was to optimize Cam's Pizzeria website. The goals
where to resize the pizzas in less than 5ms and to achieve a smooth
60fps when scrolling.

To view the project clone or download the repo and open the index.html
file in your browser.

## My Project Results

### Part 1: Optimize PageSpeed Insights score for index.html

Here are the steps I took to optimize index.html:

* Remove Google Font link
* Add ```media="print"``` attribute to print CSS stylesheet link
* Inline minified CSS for index.html
* Load JavaScript files async
* Resize and optimize images

#### PageSpeed Scores

* 93 Mobile
* 95 Desktop

I set the project up on Github Pages for testing purposes. Here is a
link to the live site:

[https://todmcchesney.github.io/website-performance-optimization/](https://todmcchesney.github.io/website-performance-optimization/)

### Part 2: Optimize Frames per Second in pizza.html

Here are the steps I took to optimize views/js/main.js for
views/pizza.html:

* Moved body.scrollTop property value to a variable outside of the for
loop
* Fixed changePizzaSizes FSL problem by DRYing out the code and removing
unnecessary functions.

Here is a link to the live site:

[https://todmcchesney.github.io/website-performance-optimization/views/pizza.html](https://todmcchesney.github.io/website-performance-optimization/views/pizza.html)
