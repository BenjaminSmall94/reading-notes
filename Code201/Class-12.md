# Chart.js and Canvas

[Home](../index.md)

## Online Articles

### Animated Charts with Chart.js

Charts in many ways are better for visually displaying data than tables. Thankfully Chart.js is a tool that can make displaying charts easy. Chart.js is a plug in for JavaScript that requires you to download it before use. It works with the HTML `<canvas>` element. Through the use of objects, JavaScript can manipulate the `<canvas>` element and draw all sorts of charts.

### Downloading Chart.js

Download instructions are located [here](https://www.chartjs.org/docs/latest/getting-started/installation.html)

### Canvas Basic Usage

Canvas is an element with two attributes height and width which can be styled in HTML, CSS, or through DOM properties in JavaScript. If no styling is applied it will be fully transparent and 300px wide and 150px tall. It is very easy to specify fallback content by putting alternate content in the `<canvas>` element. Canvas provide a fixed-size drawing surface to manipulate one or more rendering contexts, of which 2D is the most common. After the canvas and context is selected there are numerous methods allowed to draw different shapes on the canvas.

### Drawing Shapes with Canvas

> One unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y)

Canvas natively supports two primative types, rectangles and paths (lines). Thankfully there are functions that combines these lines for drawing more complex shapes.

The Rectangle methods are fillRect, strokeRect, and clearRect.

The path functions are `beginPath()`, `closePath()`, `stroke()`, `fill()`, `lineTo(x, y)`, `move(x, y)`, `arc(x, y, radius, startAngle, endAngle, counterClockwise)` and `arcTo(x1, y1, x2, y2, radius)`.

### Applying Styles and Colors

You can set fillstyle or strokeStyle to change the color of your shapes. You can also set globalAlpha to uniformly draw multiple items with the same transparency. Additionally the following methods/properties apply

- `lineWidth`
- `lineCap`
- `lineJoin`
- `miterLimit`
- `getLineDash()`
- `setLindDash()`
- `lineDashOffset`

### Drawing Text

Two main methods exist for drawing text

- `fillText(text, x, y [, maxWidth])`
- `strokeText(text, x, y [, maxWidth])`

The following properties can be used to alter the text being drawn

- `font`
- `textAlign`
- `textBaseline`
- `direction`
