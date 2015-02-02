# HTML5 Canvas based Compass and mouse tracker

This is a concept based on Map &amp; Compass created using HTML5 Canvas, CSS3 &amp; Javascipt with modified **jQueryRotate** Library.

Base of this nugget consists of Three main layers:

1.  **Compass pointer** - upper most (pointer canvas)
2.  **Compass dial** - middle one (mainCanvas)
3.  **Google Map** - lower (mapCanvas)

We have added the mouse position mousemove listener on mainCanvas to detect location of pointer.
Later we have moved the pointer in respective direction by jQueryRotate Library.

Created by [Ganesh Bhosale](http://ganeshbhosale.com) at [Dwij IT Solutions](http://dwijitsolutions.com)

function **onResize** helps to change dimentions of the canvas according to Window.

**Draw** function on every canvas object make it easy to refresh layout whenever we want.
