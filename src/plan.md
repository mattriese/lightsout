components:
---------------
game:
- before each render, check for win or not
-
PROPS:
- width
- height

STATE:
- array of arrays of booleans or something to keep track of which squares are lit
- win/not win?

EVENTS:
- funciton to change state, which is passed to the cells as a callback to a prop?
- when board clicked, determine which square was clicked and change the status/state of the appropriate neigboring squares.

------------
square:
PROPS:
- status(lit or not)
- callback that can change the state from the gameboard.

STATE:
