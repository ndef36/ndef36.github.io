Optimization of website
index.html
1. Resize pizzeria image for optimal compression
2. Use media="print" for the print.css file to prevent render blocking
3. Remove google fonts request to eliminate one source of render blocking
4. Move link to style.css to body of index.html to prevent render blocking

views/pizza.html
1. In function changeSliderLabel(size) create a variable sizePizzas to reduce dom query requests
2. Remove the function determineDx and the variables oldWidth, windowWidth, and oldSize
3. Encompass the sizeSwitcher function into the function changePizzaSizes
4. Create variable newWidth to store the values for the switch case in the function changePizzaSizes
5. In function changePizzaSizes Create variable randomPizzas to reduce dom query requests
6. Modify the changepizzaSizes for loop to use the randomPizzas variable

views/css/style.css
1. Use will-change: transform in .mover to reduce painting while scrolling

