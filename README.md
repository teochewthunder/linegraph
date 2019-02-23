# Line Graph

- JSON object is used to store the data.
- one set of data is rendered using Nodes, which are square divs placed at intervals along a vertical bar depending on the value.
- the lines from Node to Node are thin divs, rotated from the start Node so that the end point touches the next Node. The width of the lies and the angle of rotation are calculated using *Pythagoras's Theorem*.

Once we have one set of data, we render all the other sets of data. Then we overlap them so that they form an entire chart.

*Note: There's a fair amount of CC3 being used and some of it may not render well on Safari.*
