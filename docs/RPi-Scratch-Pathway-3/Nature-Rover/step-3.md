# Scroll More Sprites

When adding more sprites to your scene, these need to scroll left and right as well.

We will now add some more objects to your scene, and scroll them in a similar way.

Add a tree sprite to your project and set its starting position by adding the code blocks below.


![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/tree.png){ width="150" }



![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/1.0.png){ width="205" }


The tree sprite should also move in the opposite direction to the broadcast as well.

As the tree is closer to the viewer, it should appear to move a greater distance than the hills each time the button or key is pressed.

To create this moving effect, change the **==x==** values that the tree sprite moves by when the **`left`** and **`right`** broadcasts are received by adding the code blocks below.


![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/2.0.png){ width="220" }


> Test: Click the green flag and check your left and right buttons work. The tree should move each time you click on the controller.

## Resetting the Tree Position

At present, when the tree reaches the very edge of the screen, it stops moving.

To fix this we move the tree to the other side of the screen when its **==x==** coordinate is too high or too low.

Using a forever loop, and if blocks, check the x coordinate of the tree, and move it to the other side of the screen when x is higher than 290 or lower than -290.

Add the code blocks below to the end of the **`when I recieve start`** code block.


![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/3.0.png){ width="450" }


> Test: move your rover sprite around the screen. When the tree reaches the edge, it should vanish off the edge of the screen and reappear on the other side.

Lastly, make the rover turn left and right so that it faces the direction it is moving in, and resets at the start.

!!! informatio "Info"

    All code instructions in this step are to be added to the **`rover sprite`**

Add the **`set rotation style`** code block to the end of the **`when green flag clicked`** code block.


![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/4.0.png){ width="370" }


Add the code blocks below to make the rover the point in the right direction.

![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/5.0.png){ width="200" }


Add the **`point in direction`** code block to the end of the **`when  recieve start`** code block.


![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-3/6.0.png){ width="370" }


> Test: Run your project and test it. Make sure the tree appears to fall off the edge of the screen and appears on the other side when the rover moves.