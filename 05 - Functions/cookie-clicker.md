# Cookie Clicker

Count and display the number of clicks when a user clicks on the cookie image.

## Objective
Practice creating **Functions**.

## Your Challenge
1. Create a folder called "cookie-clicker".
2. Open the folder in Atom and create the following files:
  * index.html
  * styles.css
  * app.js
3. In your index.html file, initialize the file using the shortcut ```!```, then press tab. You should get something like the following.

``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

4. Link your CSS and JS files as follows.

``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="styles.css">
  <title>Document</title>
</head>
<body>

  <script src="app.js"></script>
</body>
</html>
```

5. In your HTML, create the following
  * ```img``` of a cookie with an id of "cookie"
  * ```h1``` with an id of "counter"

6. In your JS, store the cookie image and heading elements in variables using the following pattern. Use ```document.getElementById()``` for your image and h1 elements.:

``` JavaScript
var image = document.getElementById('put the id here');
```
7. Create a variable called ```count``` and set it equal to 0.
8. Create a function called ```update``` that will take in no arguments. In this function, do the following:
  * Set the count variable equal to the current count value + 1
  * Change the innerHTML of the heading element to display the current count. Use ```.innerHTML``` as follows. Change "element" to be the heading element, and change the text to display the current count.:

``` JavaScript
element.innerHTML = "Text";
```
9. Execute the function when you click on the image using this pattern. Change the "element" to the cookie image:

``` JavaScript
element.addEventListener("click", update);
```

## Stretch Goal
1. Display a congratulatory message every 50 clicks. Hint: Use an if statement and the modulus (%) operator
2. Add multiple cookies on the page and keep track of clicks for each cookie being clicked on.
