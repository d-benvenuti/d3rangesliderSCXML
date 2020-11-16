# d3rangesliderSCXML

Simple experiment.

# Test

Launch a local web server, e.g.:
`python -m http.server`

then open the web page: localhost:8000/slider.html

Open the console and see the state transitions as they happen.

# Issues

After reaching state "max" while dragging the right handle, if you leave it there, remember to perform a dragL on the left slider to make the statechart working correctly (the opposite goes for the "min" state while dragging the left handle).
