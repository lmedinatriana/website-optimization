## Get Started

To compare optimizations, please check dist and src folders respectively. The scr folder shows the original files to be optimized, meanwhile the dist folder shows the optimizations.

* [Click here](https://lmedinatriana.github.io/website-optimization/ "Website Optimization Project") to view this project.


### About

For this project, I had to optimize this site for speed. Basically, I had to optimize the critical rendering path and make the page render as quickly as possible. 

After testing the site on [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Flmedinatriana.github.io%2Fwebsite-optimization "Google PageSpeed"), I found out that the site was runinng below 60 fps, and consequently it got a poor review both on mobile and desktop.

To resolve these issues, I optimized the images (resizing, and decreasing the quality.), inline the CSS, minimize CSS and JS. Ultimately, All this changes, improved the rendering tremendously.


### Optimizations to Landing Page

* No landing page redirects
* Eliminated render-blocking JavaScript and CSS in above-the-fold content
* Enabled compression
* Minified CSS
* Minified HTML
* Minified JavaScript
* Optimized images
* Prioritized visible content
* Reduced server response time

### Optimizations to views/js/main.js

Optimizations made to views/js/main.js make views/pizza.html to render with a consistent frame-rate at 60fps when scrolling.


* Applied document.getElementById() because Web API call is faster.
* Applied document.getElementsByClassName() because Web API call is faster.
* Created a local variable to save document.getElementsByClassName('randomPizzaContainer') outside the loop so the DOM is not explicitly touched in every iteration.
* Calculated the number of pizzas needed to fill the screen, based on browser window resolution.