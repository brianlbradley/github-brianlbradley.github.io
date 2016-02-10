## Website Performance Optimization portfolio project

This project has two parts:

Part 1
  Optimize the index.html site to achieve 90 or higher on page speed insights https://developers.google.com/speed/pagespeed/insights/
  The word "optimize" appears throughout the code to denote where specific optimization has occurred"
     1)To achieve this i optimized the images in a program on my MAC called GIMP.  The images were too large, and GIMP allowed me to alter the size and also change the quality.
     2)I chose to Inline the CSS from GoogleLeapis and from the style.css and print.css files.
     3)I used ASYNC on the Javascript for faster page rendering.
 Overall I achieved a page speed score of 91.

 Part 2
   This challenge was to optimize Pizza.html for the page to run 60fps on scrolling. These optimizations were performed on main.js
      1) Optimize the UpdatePositions function by moving the ScrollTop out of the for loop
      2)Reduced the number of pizzas to 25 from 200 when the page loads  called by document.addEventListener('DOMContentLoaded', function()
      3) The size of the pizzas on the switch slider needed to take < 5ms in the Console.  To achieve this i moved the for loop outside of the code and created a variable as part of the loop



Acknowledgements:
-getElementsByClassName vs querySelector Allhttps://jsperf.com/getelementsbyclassname-vs-queryselectorAll/18
-Susan from the Udacity private coaching helped with the general ideas for the project.
-ScrollTop explanation   http://www.w3schools.com/jsref/prop_element_scrolltop.asp
-Lynne-Daniels/GitHub for help with slider optimization
-Two Udacity classes on Web Optimization
-Remove Render-Blocking JavaScript  |  PageSpeed Insights  |  Google Developers
-https://developers.google.com/speed/docs/insights/BlockingJS

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

### Optimization Tips and Tricks
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

### Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

* <a href="http://www.reddit.com/r/webdev/comments/280qkr/would_anybody_like_to_post_their_portfolio_site/">A great discussion about portfolios on reddit</a>
* <a href="http://ianlunn.co.uk/">http://ianlunn.co.uk/</a>
* <a href="http://www.adhamdannaway.com/portfolio">http://www.adhamdannaway.com/portfolio</a>
* <a href="http://www.timboelaars.nl/">http://www.timboelaars.nl/</a>
* <a href="http://futoryan.prosite.com/">http://futoryan.prosite.com/</a>
* <a href="http://playonpixels.prosite.com/21591/projects">http://playonpixels.prosite.com/21591/projects</a>
* <a href="http://colintrenter.prosite.com/">http://colintrenter.prosite.com/</a>
* <a href="http://calebmorris.prosite.com/">http://calebmorris.prosite.com/</a>
* <a href="http://www.cullywright.com/">http://www.cullywright.com/</a>
* <a href="http://yourjustlucky.com/">http://yourjustlucky.com/</a>
* <a href="http://nicoledominguez.com/portfolio/">http://nicoledominguez.com/portfolio/</a>
* <a href="http://www.roxannecook.com/">http://www.roxannecook.com/</a>
* <a href="http://www.84colors.com/portfolio.html">http://www.84colors.com/portfolio.html</a>
