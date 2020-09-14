## Using coordinates

In this step you will learn how to use x and y coordinates in Scratch to move a turtle to specific locations on the Stage. 

--- task ---

If working **online**, open the [starter project](http://rpf.io/p/en/projectName-on){:target="_blank"} in Scratch.
 
If working **offline**, open the project [starter file](http://rpf.io/p/en/projectName-get){:target="_blank"} in the Scratch offline editor. If you need to download and install Scratch, you can find it [here](https://scratch.mit.edu/download){:target="_blank"}.

When you open the starter project you will see a grid backdrop and turtle sprites. 

![starter project](images/starter_project.png)

--- /task ---

Scratch uses x and y coordinate numbers to indicate locations on the Stage. The x coordinate gives the left-right position and the y coordinate gives the up-down position. The coodinate of the centre of the stage is (x=0, y=0). Let's send Turtle 1 to the centre of the Stage. 

--- task ---
Select the Turtle 1 sprite and click on its Code tab. Add code to move the turtle to the centre of the Stage when the green flag is clicked:

```blocks3
when green flag clicked
glide (1) secs to x: (0) y: (0)
```

--- /task ---

--- task ---

Test your code by dragging Turtle 1 to any location on the stage and then clicking the green flag. Turtle 1 will always go to the centre of the stage. 

--- /task ---

The x coordinate gives a left-to-right position from -240 to 240. Negative x coordinates are to the left of the centre of the Stage and positive coordinates are to the right. 

--- task ---
Add code to get the turtle to 'swim' to the left and then the right of the Stage:

```blocks3
when green flag clicked
glide (1) secs to x: (0) y: (0)
+glide (1) secs to x: (-240) y: (0)
+glide (1) secs to x: (240) y: (0)
```

--- /task ---

The y coordinate goes from -180 at the bottom of the Stage to 180 at the top of the Stage. Negative y coordinates are in the bottom half of the Stage. 

--- task ---
Add code to move the turtle to the top and bottom of the Stage:

```blocks3
when green flag clicked
glide (1) secs to x: (0) y: (0)
glide (1) secs to x: (-240) y: (0)
glide (1) secs to x: (240) y: (0)
+glide (1) secs to x: (0) y: (180)
+glide (1) secs to x: (0) y: (-180)
```

--- /task ---

--- task ---
Can you predict the route the turtle will take with this code? Think about where the turtle will go and then change your code to use these coordinates and see if you are correct.

```blocks3
when green flag clicked
+glide (1) secs to x: (100) y: (100)
+glide (1) secs to x: (100) y: (-100)
+glide (1) secs to x: (-100) y: (-100)
+glide (1) secs to x: (-100) y: (100)
+glide (1) secs to x: (100) y: (100)
```

--- /task ---

--- save ---

