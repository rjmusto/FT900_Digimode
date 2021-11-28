# FT900_Digimode
Project design files for RadCom FT900 Digimodes article.

Includes Schematic diagramm PDF file, Gerber files for pcb manufacture and two STL files for 3D printing the box lid and base.

Photos also shown of the USB Audio Interface used.
And the USB Isolator used for the CAT Connection.
*** Note that I have removed the DC-DC supply module (small black block woth 4 pins) from this USB Isolator as I find they are very noisy.
The secondary side can be powered from the micro USB connector, supplied from the Rig side of things.
***

Note also that, dispite what's shown on the data sheet, the dual channel audio isolating transfortmer seems to use just one core internally.
This obvioulsy means that a signal applied to one winding will appear on all 3 others, which at first sight would seem to be a problem.
However, I find in practice it doesn't really matter. As long as the receive audio is not high enough to trip the switch, everything works fine.
