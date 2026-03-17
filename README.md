# macropad

I couldnt think of a better name :(

My hack pad has 5 buttons and a rotary encoder and uses qmk firmware. 

I just wanted to learn something new and this has been a very fun experience.

## Features

Very simple sandwich mount case with a 4.9.. tilt!

Buttons will copy, paste, cut, undo and redo.

Rotary encoder will mute when clicked and turning it controls volume

## CAD model
Held together by 4 M3x20mm bolts, one in each corner of the case. It has 3 printed piece. 

The case which houses the pcb and has a cutout for the USB, and the plate which the keys will sit ontop of.
The screws will be screwed from the bottom and will go through 2mm of the tilted plate, 16mm of the main body and 2mm of the top plate. The bottom of the the tilted plate has holes to allow the entire screw (including the head) to travel through.

Made in fusion 360

<img src=Screenshots/Assembled_CAD1.png alt="CAD" width="500"/>
<img src=Screenshots/Assembled_CAD2.png alt="CAD" width="500"/>
<img src=Screenshots/Assembled_CAD3.png alt="CAD" width="500"/>


## PCB
My PCB was made in KiCad 9.0.

Schematic:


<img src=Screenshots/Schematic.png alt="Schematic" width="500"/>

PCB:


<img src=Screenshots/PCB.png alt="PCB" width="500"/>

## Firmware
I used QMK firmware for it. (It took me way too long)
The rotary encoder changes volume and presses to mute
The 5 keys will:
-copy, 
-paste, 
-cut,
-undo and 
-redo.

## BOM
So to make this you'll need:

-5x Cherry MX Switches

-5x DSA Keycaps

-4x M3x20mm SHCS Bolts (20mm not 16)

-1x EC11 Rotary Encoder

-1x XIAO RP2040

-1x Case (3 printed parts)


Thats it!

Anyways have a good day
