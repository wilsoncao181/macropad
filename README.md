# macropad

I couldnt think of a better name :(

My hack pad has 5 buttons and a rotary encoder and uses qmk firmware. 

I just wanted to learn something new and this has been a very fun experience.

## Features

very simple sandwich mount case

buttons will copy, paste, cut, undo and redo.

Rotary encoder will mute when clicked and turning it controls volume

## CAD model
held together by 4 m3 bolts, one in each corner of the case. It has two printed piece. 

The case which houses the pcb and has a cutout for the USB, and the plate which the keys will sit ontop of.

Made in fusion 360

<img src=Screenshots/CAD.png alt="CAD" width="500"/>
<img src=Screenshots/Top_Plate.png alt="CAD" width="500"/>
<img src=Screenshots/Bottom_Case.png alt="CAD" width="500"/>


## PCB
My PCB was made in KiCad 9.0.

Schematic:


<img src=Screenshots/Schematic.png alt="Schematic" width="500"/>

PCB:


<img src=Screenshots/PCB.png alt="PCB" width="500"/>

## Firmware
I used QMK firmware for it. (It took me way too long)
the rotary encoder changes volume. press to mute
The 5 keys will:
copy, 
paste, 
cut,
undo and 
redo.

#BOM
So to make this youll need:

-5x Cherry MX Switches

-5x DSA Keycaps

-4x M3x16mm SHCS Bolts

-1x EC11 Rotary Encoder

-1x XIAO RP2040

-1x Case (2 printed parts)


Thats it!

Anyways have a good day
