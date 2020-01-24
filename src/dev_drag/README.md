# dev_drag
A library to enable object dragging and object selection on canvas.

-  **compatibility:** 5.6.5+
- **requires:** dev_canvas, dev_intersect
- **unpacks:**
   - on init - dev_drag.init()
   - outside - dev_drag.control()

## Functions

#### dev_drag.init()
Inits the library in **on init** callback.

#### dev_drag.control()
Inits the library outside all callbacks.

#### dev_drag.drawOutline(objIndex)
Draws an outline around an object. It is required for the command to be followed by `dev_drag.showOutline(objIndex)` if the outline is hidden.

#### dev_drag.showOutline(objIndex)
Makes the outline appear.

#### dev_drag.hideOutline(objIndex)
Makes the outline appear.