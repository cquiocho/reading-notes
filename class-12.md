![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)

## Chart.js

**Charts.js is a JavaScript plugin that usess HTML5's `<canvas>` element to easily draw graphs and charts: Bar charts, line charts, pie charts and more.**

Setting up Charts.js:

1. Download Chart.js.
1. Copy Chart.min.js out of the unzipped folder.
1. Paste into active directory you'll be working in as a `<script>` (place above JS script).
1. Create new html page.
1. Import the script.

![Canvas Script Import](images/import-script.PNG)

## Basic Usage of Canvas

**`<canvas>` looks like an image element without *src* or *alt* attributes. `<canvas>` tag should be placed within HTML content in order to render.**

`<canvas>` has only **two** attributes that are optional (default 300px x 150px):
- width
- height 

*Both attributes can be set up using DOM properties.*

> The `<canvas>` element can be styled like any normal image.

To display something on `<canvas>`, a **script** is required:

![Canvas Get Element](images/canvas-get-element.PNG)

## Drawing Shapes with Canvas

`<canvas>` only supports **two** primitive shapes:

1. Rectangles
1. Paths - lists of points connected by lines.

- All other shapes must be created by combining one or more paths.

**There are 3 functions that draw rectangles in `<canvas>`:

> 1. `fillRect(x, y, width, height)` - Draws a filled rectangle.
> 1. `strokeRect(x, y, width, height)` - Draws a rectangular outline.
> 1. `clearRect(x, y, width, height)` - Clears rectangular area making it transparent. 

Rectangular shape example:

![Rectangular Example](images/rectangular-example.PNG)

## Applying Styles and Colors with Canvas

## Drawing Text with Canvas


