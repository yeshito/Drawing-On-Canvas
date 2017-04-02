# Drawing-On-Canvas
Process of drawing in browser using html Canvas and JS

Drawing between arbitrary points is extremely awkward with regular HTML elements.

There are two alternatives:
1. SVG - A dialect for describing documents that focus on shapes rather than text. You can embed an SVG doc in an HTML doc, or include it through an <img> tag.
*original description of shapes preserved, so can be moved or resized at any time*

2. Canvas - A single DOM element that encapsulates a picture
*converts the shapes to pixels as soon as they are drawn and does not remember what the pixels represent. Only way to move a shape on canvas is to clear the canvas and redraw in another position*
