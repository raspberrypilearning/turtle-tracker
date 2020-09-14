## Drawing the route

In this step you will stamp a marker to represent known locations of a turtle and then use the pen draw a path showing its movement. 

When a tag is placed on a turtle, it uses the Global Positioning System (GPS) to detect its current position from a satellite. This data is stored and can be used to work out the route taken by the turtle. 

--- task ---
Add the pen extension to your project. 
--- /task ---

--- task ---
Select the Turtle 1 sprite and add code to draw the route taken by the turtle using the pen:

```blocks3
when green flag clicked
+erase all
+set pen [color v] to (40)
+set pen size to (2)
+pen up
glide (1) secs to x: (100) y: (100)
+pen down
glide (1) secs to x: (100) y: (-100)
glide (1) secs to x: (-100) y: (-100)
glide (1) secs to x: (-100) y: (100)
glide (1) secs to x: (100) y: (100)
```

--- /task ---

You can also add a stamp of the turtle to show the known positions of the turtle. 

--- task ---

```blocks3
when green flag clicked
erase all
set pen [color v] to (40)
set pen size to (2)
pen up
glide (1) secs to x: (100) y: (100)
stamp
pen down
glide (1) secs to x: (100) y: (-100)
stamp
glide (1) secs to x: (-100) y: (-100)
stamp
glide (1) secs to x: (-100) y: (100)
stamp
glide (1) secs to x: (100) y: (100)
```

--- /task ---

--- task ---
Click the green flag to see the turtle draw its route and stamp a marker at each known position. 
--- /task ---

--- save ---
