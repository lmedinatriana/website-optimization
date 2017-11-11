## Website Performance Optimization

For this project, I had to optimize this site for speed. Basically, I had to optimize the critical rendering path and make the page render as quickly as possible. 

After testing the site on [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Flmedinatriana.github.io%2Fwebsite-optimization "Google PageSpeed"), I found out that the site was runinng below 60 fps, and consequently it got a poor review both on mobile and desktop.

To resolve these issues, I optimized the images (resizing, and decreasing the quality.), inline the CSS, minimize CSS and JS and finally cache some of the images. Ultimately, All this changes, improved the rendering tremendously.


### Check List

#### Part 1: Optimize PageSpeed Insights score for index.html

#### Part 2: Optimize Frames per Second in pizza.html

### Optimization Resources

* [Udacity Website Optimization](https://www.udacity.com/course/ud884 "Udacity Website Optimization")
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>
