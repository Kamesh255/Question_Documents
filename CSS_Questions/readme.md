###  (1) how to add comments on css?

```bash
 CSS comments are not displayed in the browser, but they can help document your source code. 
 - in CSS coment /* this text was commented */
 - in HTML coment <!--this text was commented-->
```

### (2) Why do we use pseudo-class?
```bash
    A pseudo-class is used to define a special state of an element.

    For example, it can be used to:

    - Style an element when a user mouses over it
    - Style visited and unvisited links differently
    - Style an element when it gets focus
pseudo classes:-  :activ, :hover, :empty, :first-child, : focus  etc.
```

### (3) How is specificity applied?
``` bash
        A elements apply more then one CSS selectors so that time specificity give the CSS property according to rank of CSS selectors

        <html>
        <head>
        <style>
            #demo {color: blue;}
            .test {color: green;}
            p {color: red;}
        </style>
        </head>
        <body>

        <p id="demo" class="test" style="color: pink;">Hello World!</p>

        </body>
        </html>
``` 

### (4) What method allows an element to be moved from its current position?
```bash
    The position property specifies the type of positioning method used for an element
    There are five different position values:

    - static
    - relative
    - fixed
    - absolute
    - sticky
```
