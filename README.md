# d3rangesliderSCXML

Simple experiment.

# Test

Launch a local web server, e.g.:
`python -m http.server`

then open the web page: localhost:8000/rangeslider.html

Open the console and see the state transitions as they happen.

# Issues

-	After reaching MAX or MIN really fast, the handle does not return to the normal hovering behaviour until it is not dragged again.
-	The hovering of the bar is not yet implemented.
-	While dragging, if you release the mouse whit the pointer outside of the handle, everything works fine. If you release with the pointer on the handle the statechart does not go back to "hovering-handle" state, but instead remains in "movingL" or "movingR". At least it is a recoverable behaviour.