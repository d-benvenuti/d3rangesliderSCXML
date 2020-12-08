# d3rangesliderSCXML

Simple experiment.

# Test

Launch a local web server, e.g.:
`python -m http.server`

then open the web page: localhost:8000/rangeslider.html

Open the console and see the state transitions as they happen.

# Issues

-	The selection is not yet draggable.
-	HOVERING-BAR is implemented as a state, but clicking on the bar makes the statechart go into HOVERING-HANDLE, while, in the correct behaviour, it should go into WAITING (no pointerdown implementation on the DOM element of the bar).

