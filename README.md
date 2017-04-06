# Website Performance Optimization Project

The challenge was to optimize this online portfolio for speed! In
particular, optimize the critical rendering path and make this page
render as quickly as possible by applying the techniques taught in the
[Critical Rendering Path course](https://www.udacity.com/course/ud884).

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
