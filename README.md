## Website Performance Optimization portfolio project

We have to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

### Optimizations Made

#### Part 1: Optimize PageSpeed Insights score for index.html

- Moved the scripts to end.
- Used the media = print for the print stylesheet
- Inlined complete stylesheet
- Loaded Web Fonts efficiently by using WebFont Loader
- Compressed some images

#### Part 2: Optimize Frames per Second in pizza.html by main.js

- Selected DOM Elements efficiently by using getElementByID() and getElementsByClassName()
- Changed the " changePizzaSizes " method to optimize the pizza's width assignment, to avoid Forced Synchronous Layout
- Made sure DOM properties are accessed as less as possible, moved some declerations outside loops.
- Optimized the " updatePositions " method, and used CSS property transfom, to reduce paints.
- Efficient Calculation of Pizzas that slide on page
- Reduced the time to change the size of a pizza.

### Running the Application
To Run the application
1. Download the repository
2. Start index.html
3. Make sure you try all pizzas at Cam's Pizza Shop.

### Reference
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

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
