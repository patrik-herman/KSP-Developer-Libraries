# dev_canvas
In-development supportive library for dev_drag. Feel free to add more functionalities.

-  **compatibility:** 5+
- **requires:** none
- **unpacks:**
   - on init - dev_canvas.init()

## Functions

#### dev_canvas.init(x, y, width, height)
Inits the library in **on init** callback.
##### Params:
   - **x**: x coordinate of the canvas.
   - **y**: y coordinate of the canvas.
   - **width**: width of the canvas.
   - **height**: height of the canvas.

#### dev_canvas.updateObject(objIndex)
Sets x, y, width and height of an object.

#### dev_canvas.addRect(x, y, width, height, pic)
Draws a rectangle.
##### Params:
   - **x**: x coordinate of the rectangle.
   - **y**: y coordinate of the rectangle.
   - **width**: width of the rectangle.
   - **height**: height of the rectangle.

#### dev_canvas.reload()
Reloads all objects.