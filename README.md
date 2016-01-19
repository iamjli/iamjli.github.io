## Website Performance Optimization portfolio project

To visit website, go to iamjli.github.io

Optimizations:
-increased PageSpeed scores for index.html to >90 by reducing image sizes, async-ing scripts, and minifying js files
-optimized framerate when scrolling in pizza.html by removing .scrollTop method from the for loop
-optimized resizing to <2 ms by removing .offsetWidth from the for loop
-changed all .querySelector methods to .getElementByID
-changed all .getSelectorAll methods to .getElementsByClassName
-moved variable declarations outside loops
-reduced number of background pizzas to the minimum of 32
-added 'use strict'; to js functions