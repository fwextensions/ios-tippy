# Tippy

The whole project took about 1.5 hours, though a chunk of that was trying to figure out why dragging and dropping views wasn't working.  Turns out that if you have the View Controller icon selected in the header above the storyboard, when you add a UI element, it replaces the View as a child of the View Controller.  So you can only have one element, which is undraggable, since it's covering the full area of the View Controller. 

All the required stories were completed, though none of the optional ones. 

![Demo](demo.gif)