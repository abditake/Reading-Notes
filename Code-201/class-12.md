# [Class 12: - Chart.js, Canvas](/README.md)

- ## Chart.js 
- ## Canvas Api
<hr>


# Chart.js

- ## `chart.js`: Js Plugin that html5's canvas element to draw a graph onto a webpage. 

## The Chart.js is imported at by making a script tag at the top of the page like so.
```
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>

```
## Chart.js has different features for drawing line graphs, bar charts, pie charts and all sorts of ways to visualize your data. 
- ### the script is what will receive the context of the canvas

<hr>

# Canvas Api

- ## `canvas`: this element creates a fixed section where you can render context. The same way a painter has a canvas this tag creates that place so the script can create charts(in our case).

- ## `fallback content`: content that is displayed when older browser have don't support your context; video,audio and picture. 

- ## `drawing`: on a canvas you not only are able to use charts but also draw anything you want on the designated section. there are basic shapes but what you build is up to you.

- ## `color`: the canvas has an option to color all sorts of images. 
 ```
 fillStyle = color
 strokeStyle = color
 ```
- ## `drawing text`: By using two methods you can have the canvas render all sorts of text. 
```
fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

```
