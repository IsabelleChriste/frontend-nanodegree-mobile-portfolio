# Website Optimization Project for Udacity

This project is to understand and optimize a website according to Udacity guidelines using Web Development tools.

## Getting started

Clone or download my project on github using this link:
<https://github.com/IsabelleChriste/frontend-nanodegree-mobile-portfolio>

Project has been tested on :
* Firefox 50.1.0 
* Chrome Version 55.0.2883.87 m (64-bit)
* Chrome Canary Version 57.0.2983.0 canary (64-bit).

### Part 1 : PageSpeed Score of 90 for mobile and desktop

Steps taken to get the score of 90 on index.html :

* Removal of Google Fonts
* Saving the small icons locally in the img folder
* Reducing the sizes of all the images using GIMP 2 with a plugin called "Save for web"
* Minified perfmatters.js, print.css and style.css using plugin Minifier in code editor Brackets
* Moved CSS files in the index.html in noscript tag
* Removed the color background for the class .hero

### Part 2 

#### Resizing Pizza under 5ms

* Simplification of the switch part as the original was too complicated
* Changed getSelector to getElementByClassName

#### Reaching 60FPS when scrolling

* Reduction of the number of pizza on screen
* Reduction of the size of the small pizza picture and the pizzeria
* Updated the function UpdatePosition
* Changed getSelector to getElementByClassName
* Use of transform and translateX to make the function faster