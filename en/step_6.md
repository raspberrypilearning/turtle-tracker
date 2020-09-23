## Importing data from a file

Scratch allows you to import data from a file. This is really useful when you have lots of data that you want to use and it would take too long to type it. 

--- task ---
Select Turtle A. It has lists that have been created but which don't have any coordinates in them. 

Check the boxes to see Turtle A's lists  on the Stage. 

--- /task ---

We have prepared some more data based on routes that real turtles have taken around Poiloa. You can download these data files and import them into your project so you can find out where the turtles went. 

--- task ---

Right-click (or tap and hold) one of the turtle data links below, your choice, and choose 'Save link as ...' . Save the file on your local computer, a shared network drive or an external drive such as a USB drive. Remember where you saved it and what the file was called. 

--- collapse ---
---
title: If you are using an iPad
---

On an iPad, using the Safari browser, click on your chosen Turtle link to view the data and then click the share icon

--- /collapse ---


[Turtle 21 Data](https://raw.githubusercontent.com/raspberrypilearning/turtle-tracker/draft/en/resources/poilao%20turtle%2021.csv){:target="_blank"}

<a href="https://raw.githubusercontent.com/raspberrypilearning/turtle-tracker/draft/en/resources/poilao%20turtle%2021.csv" download="turtle-21.csv" title="Turtle 21 Download">Turtle 21 Download</a>

<a href="https://raw.githubusercontent.com/raspberrypilearning/turtle-tracker/draft/en/resources/poilao%20turtle%2021.csv" target="_blank" title="Turtle 21 View">Turtle 21 View</a>

--- collapse ---
---
title: If you can't download or import the file
---

If you are unable to to download a file then you can click or tap on one of the turtle files to open it in your browser. You can then enter the data into the `x coords`{:class="block3variables"} and `y coords`{:class="block3variables"} lists for Turtle A as you did for Turtle 2. This is easier if you have a partner to read out the numbers. 

--- /collapse ---

--- /task ---

--- task ---
Now go back to Scratch. 

![animation of importing x coords](images/import-x-coords.gif)

Right click (or tap and hold) on the `Turtle A: x coords`{:class="block3variables"} list on the stage and choose import. 

Select the file that you downloaded, it will be something like 'turtle5.csv'. 

When you are asked 'which column should be used?', enter the number 1. The x coordinate data is in the first column of the file.

Scratch will load the data from the first column in the file into the Turtle A's x coords list.

--- /task ---

--- task ---
Now repeat the importing of the data for the y coordinates. 

Right click (or tap and hold) on the `Turtle A: y coords`{:class="block3variables"} list and choose import.

Choose the same file as before. 

This time, choose column **2** which contains the y coordinate data for the same turtle. 

--- /task ---

--- task ---
Select Turtle A under the stage and change its name to match the number of the turtle you imported, such as Turtle 21. This will help you remember which turtle data you have used.

![Screenshot highlighting name of Turtle A](images/rename-turtleA.png)

--- /task ---

--- task ---
Copy the code from Turtle 3 to your new turtle by dragging it. 

--- /task ---

--- task ---
Click on your turtle to find out where this turtle went. 

--- /task ---

--- task ---
If you have time you can download more data and follow the journeys of more turtles. You can duplicate a turtle and change its costume colour if you need more turtles. 

If you need to delete the data a turtle and start again then you can select the turtle and add the following blocks. Just click on the blocks to run them.

```blocks3
delete all of [x coords v]
delete all of [y coords v]

```
--- /task ---

--- task ---
Look at the locations visited by your turtles. If you are in a group you could also look at the results for the turtles chosen by others.

Questions to think about:
+ Do all the turtles start at a similar place? Why do you think that is?
+ Are there other locations visited by multiple turtles? Why do you think they would go there?
+ Why do the lines connecting the locations sometimes go across the island? Remember you only have one location per day. How do you think the turtles travelled between the locations?
--- /task ---

--- save ---
