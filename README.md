# Arcade Controller Remapping
Remaps the controls for an arcade controller after or before physically changing the wiring to make it more compatible. As games evolve throughout the years, older controllers may lose the compatibility to play them. In this case, we explore the limitations of a controller's d-pad and how we can use software to remap the buttons after altering them. Specifically we want the controller to handle situations that require the bottom row of buttons and two adjacent directional buttons all registering at the same time (6 inputs at once).

**D-pad Limitations**
----------------------------------------------------------------------------------------------------------------------------
In games or software that require up and down or left and right to be simultaneously pressed down on, you will notice that while you can physically input it, it will not work. This is because of hardware limitations put in place. Think of a playstation controller. The d-pad is made up of a single piece (refer to image below). When up is pressed on, the bottom part of the d-pad is lifted up. This makes it so it's impossible to press both at the same time. The same can be said for left and right. On the other hand, the face buttons do not have such a limitation. In this case we require rewiring and rearranging of the buttons.
<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/158707198-661237d0-d65c-4052-8b89-7404ad52653b.png" width="400" height="200"/><img>
</p>

**Remapping**
----------------------------------------------------------------------------------------------------------------------------
Let's say the default layout of your arcade stick is like so:

<img src="https://user-images.githubusercontent.com/100814612/158709638-01e5cd9a-83e4-4bf4-a63c-d0a1dcb38160.png" width="500" height="300"/><img>&nbsp;&nbsp;

We would want to change the wiring so that it ends up like this physically:

<img src="https://user-images.githubusercontent.com/100814612/158712199-aa7336af-01b7-4d7e-8a2a-8587ea3fcace.png" width="500" height="300"/><img><img>

**Changing the Wiring**
----------------------------------------------------------------------------------------------------------------------------
(1) Unscrew all the screws from the bottom of the controller.  
(2) Take a photo of the internal layout of the wires. (For reference later)  
(3) Pull on the black heatshrinked wires out one by one from all of the buttons. There are two attached to every button.  
(4) There are two clips on the left and right side of each button. Use a screwdriver to push those tabs on both sides inwards and the button will fall out of its socket.  
(5) With all the buttons pulled, flip the controller over and start reinserting the buttons into the desired layout.  
(6) Rewire the buttons up as they originally were (Refer to photo taken in step 2).  
(7) Close the controller up and test that everything still works.

Your internals may look something like this. Some controllers have color coded wiring and buttons to make the process easier.
<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/158708297-8877d16a-f36f-4178-b0f4-851791078aef.png" width="400" height="250"/><img><img src="https://user-images.githubusercontent.com/100814612/158708549-8fec77ae-e9fe-4f44-8eb3-ba622adbac98.png" width="400" height="250"/><img>
</p>

**Diagrams**
----------------------------------------------------------------------------------------------------------------------------
General layout for an arcade stick. Worth while to take a look if you're thinking of making a plate yourself or trying to plan out button placements.

![arcade layout](https://user-images.githubusercontent.com/100814612/158711528-74201d75-06fb-47e5-8c21-66512ab26db4.png)


**Results**
----------------------------------------------------------------------------------------------------------------------------
After all this rewiring and swapping. The gpc script will allow you to revert your changes. The template used in the script is ps3 buttons, but you can use what you want if you import the correct library. Do note if you are not using a ps3 based arcade stick, I have left a template for remapping other controllers in the code itself. You can use that to alter your setup. You can either use the remapper function or the swap function. Swapping may be easier. If you only plan to use your arcade stick on PC, the joytokey software may be more intuitive to use. The script will set the controls as follows:

<img src="https://user-images.githubusercontent.com/100814612/158712515-f690fbb0-c3fa-478d-8737-38656e1a9d37.png" width="400" height="250"/><img>
