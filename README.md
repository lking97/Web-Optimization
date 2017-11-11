### Website Performance Optimization portfolio project

## Getting started

You can download the files of this project then open index.html in your prefered browser.
You can also access the website by clicking or typing https://lking97.github.io/Web-Optimization/ into your bowser.

## Optimizations to Pizza Site

1. Moved the document.body request out of for loop in the changePizzaSizes and updatePositions functions.
2. Cached the needed DOM elements so that the brower isn't querying the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons.
3. Changed all instances of querySelector to the more efficient getElementById and getElementByClassName depending on whether a class or id is needed.
4. In the changePizzaSizes function I created an additional for loop for setting the element's width.
