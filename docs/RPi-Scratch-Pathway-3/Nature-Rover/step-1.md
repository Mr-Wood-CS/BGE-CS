# Controling the Rover

!!! information "Info"

    All code instructions in this step are to added to the `rover sprite`


In this step, you will use the keyboard to move your rover up and down.

At the moment, you should see a scene with a robotic rover and a hilly background.

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/background.png){ width="400" }
</span>

## Broadcasting and Recieving the Start Message

The rover will control the start of the game by broadcasting a start message when the green flag is clicked.

Add the code blocks below to your project and change the message to `start`.

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/1.0.png){ width="200" }
</span>

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/1.1.png){ width="200" }
</span>

!!! information "Note"

      ==For now, the rover should appear in front of the **background sprite**.==

      Move the rover to the front layer by adding the **`go to front layer`** block to then end of **'When I recieve start'** block.

      <span style="display: block; text-align: center;">
      ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/1.2.png){ width="250" }
      </span>

## Adding Keyboard Controls

You are going to use the keyboard controls to make the rover look as if it is moving towards or away from the viewer.

Add the codeblocks below and change the broadcast message of each `code block` to look exactly like the blocks in the image.

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/2.0.png){ width="250" }
</span>

## Moving the Rover

When the up button is clicked or the up arrow is pressed, the rover should change its `y` position by a small amount. Increasing `y` will make the rover move up. Decreasing `y` will make the rover move down.

Add the code blocks below to your project.

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/3.0.png){ width="200" }
</span>

==You don’t need to worry about the left and right motion yet. Left and right motion will be added in the next step of the project.==

## Adding Perspective

Perspective makes the rover appear further away when moving up and closer when moving down.

Add the code blocks below to your project.

<span style="display: block; text-align: center;">
  ![Alt text](/RPi-Scratch-Pathway-3/Nature-Rover/Images/Step-1/4.0.png){ width="350" }
</span>

## Finshed?

> Save and test your project. If it is working correctly, the rover should get bigger or smaller depending on which key is pressed.

> When you are sure that your program works as it should do, move onto **'Step 2- Scroll the background`**