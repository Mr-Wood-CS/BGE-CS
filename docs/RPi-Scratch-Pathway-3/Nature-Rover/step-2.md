# Scroll the Background

!!! information "Info"

    All code instructions in this step are to added to the **`hills sprite`**

At the start of the game, you need to make sure that it is in the correct position and on the back layer.

Add the code blocks below to your program.

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/1.0.png){ width="200" }
</span>

> **`Layers`** are like stacked sheets of clear plastic that you can draw images on. If an image on the top of the stack is covering the image below it, you will not be able to see the bottom image properly. Background images should be near the back layer. Images closer to the viewer should be near the front layer.

## Cloning

The hills sprite needs to make a copy of itself. These are called **`clones`**. 

We need to move the orginal **`hills sprite`** to the far right-hand side of the screen.

Add the code blocks to the bottom of the **`When I recieve start`** block

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/2.0.png){ width="500" }
</span>

## Moving the Hills Sprite

When the **==left==** and **==right==** broadcasts are received, the **`hills`** sprite should move. To give the appearance of moving in the correct direction, the background moves **`left`** when the **`rover`** is moving right. The direction of **`motion`** should be opposite to the **==broadcast==**.

So, if the broadcast is **==left==**, then the **==x==** position will increase. If the broadcast is **==right==**, then the **==x==** of the hills will decrease.

To make it look like the rover is moving left and right, the background will scroll instead of the rover moving.

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/3.0.png){ width="500" }
</span>

Add the following code blocks to control the motion of the hills sprite and its clone.

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/4.0.png){ width="200" }
</span>

> Test: Use the controller or the arrow keys to move around. The rover should appear to be moving left and right.

## Managing the Positioning

At the moment, there are two copies of the hills sprite: the original and a clone. When you get to the end of either one, you’ll notice that the screen is just white.

To fix this, the sprite and its clone need to be moved to the other side of the screen when they go too far.

Create a new broadcast called scroll and add the block to the start script.

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/5.0.png){ width="400" }
</span>

To detect if the hills sprite or its clone have moved too far to the left or right, add the code blocks to reset their positions to the other side of the screen.

<span style="display: block; text-align: center;">
![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-2/6.0.png){ width="280" }
</span>

> Test: Click the green flag to reset the scene and then use the controller or arrow keys to move the rover. 

> The background should scroll, and the rover should never reach the end.

## Finished?

> When you are sure that your program works as it should do, move onto **'Step 3- Scroll more sprites`**