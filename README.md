## Website Performance Optimization portfolio project

### Getting started

You can download the files of this project then open index.html in your prefered browser.
You can also access the website by clicking or typing https://lking97.github.io/Web-Optimization/ into your bowser.

## Optimizations to Pizza Site

1. Modified the code to calculate the number of pizzas needed to fill the webpage based on browser inner dimensions.

2. Moved the document.body request out of for loop in the changePizzaSizes and updatePositions functions. This prevents the browser from having to render the page every time the loop iterates.

3. Cached the needed DOM elements so that the brower isn't querying the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons

4. Changed all instances of querySelector to the more efficient getElementById and getElementByClassName depending on whether a class or id is needed.
