Nearly everything in flutter is a widget and we work on these widgets.
There are no separate files for layout, customization or text alignment.
when a widget state changes the widget rebuilds itself
according to the snake. This saves the dev's time as it
can be described as functions of state.
we don't have
to write extra code for updating a UI element when the state
changes.
The program creates a diff which is the minimum
changes needed to update the render tree.
we don't need to
bridge the UI rendering code to the native platform.
