# dev_intersect
A library to validate object intersections.

- **compatibility:** Pretty much every Kontakt version, although SublimeKSP is 5.6+.
- **requires:** none
- **unpacks:** none

## Functions

#### dev_intersect.rectangles(r1left, r1top, r1width, r1height, r2left, r2top, r2width, r2height)
Checks if two rectangles intersect.
##### Params:
   - **r1left**: x coordinate of the first rectangle.
   - **r1top**: y coordinate of the first rectangle.
   - **r1width**: width of the first rectangle.
   - **r1height**: height of the first rectangle.
   - **r2left**: x coordinate of the second rectangle.
   - **r2top**: y coordinate of the second rectangle.
   - **r2width**: width of the second rectangle.
   - **r2height**: height of the second rectangle.

##### Returns:
   - int: 1 (TRUE) or 0 (FALSE).