# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- The onClick() runs the handleAddOne() function.
- dipsatch() calls the addOne() action creator.
- addOne() sets the action type to ADD_ONE.
- the reducer runs the switch statement, at ADD_ONE it sets the total to a new state.
- ...

- TotalDisplay shows the total plus 1.
