
# Chart.js API:
- he HTML canvas element is used to draw graphics, on the fly, via scripting (usually JavaScript). The canvas element is only a container for graphics. You must use a script to actually draw the graphics. Canvas has several methods for drawing paths, boxes, circles, text, and adding images.
- canvas  only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose.
-  About drawing shapes, we used only the default line and fill styles.
-  Before we can start drawing, we need to talk about the canvas grid or coordinate space. The HTML template on the previous page had a canvas element 150 pixels wide and 150 pixels high. I’ve drawn this image with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner (coordinate (0,0)). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top (coordinate (x,y)). Later in this tutorial we’ll see how we can translate the origin to a different position, rotate the grid and even scale it. For now we’ll stick to the defaul
- Drawing text
The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
