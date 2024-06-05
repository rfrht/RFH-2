# RFH-2
Remote Control unit compatible with most modern Yaesu radios. Includes Schematics, Gerber Files and Board Design.

## What is this?
This is a remote control that is compatible with most modern and recent Yaesu radios. It mimicks the same functionality of [Yaesu FH-2](http://lmgtfy.com/?q=yaesu+fh-2) remote control, at a fraction of the cost ane with a enormous cool factor: YOU CAN ACTUALLY BUILD IT!

Check how [Jim N5JGE](https://www.qrz.com/db/N5JGE) actually built something [**really nifty**](https://github.com/jgedmond/RFH-2/commit/793899766d5572a83a48a860f2a84d2ef02e2b0a) without the need of an enclosure for the board!

## How does the board looks like?
This is the board layout in its full glory (slightly changed from FH-2, because... usability++):

![RFH-2](https://raw.githubusercontent.com/rfrht/RFH-2/master/Design/RFH-2-top.png)

## Did you prototype it?
Yup. Picture below:
![RFH-2 Prototype](https://raw.githubusercontent.com/rfrht/RFH-2/master/Design/prototype.jpg)

## What are the compatible radios?
Yaesu FT-991, FT-991A, FT-950, FTDX-9000, FTDX-5000, FTDX-3000, FT-2000, FTDX-1200, FT-1000MP

## Nice, I liked it! How do I get one?
1. Download the Gerber [.zip file](https://github.com/rfrht/RFH-2/raw/master/Design/RFH-2-gerbers.zip)

2. Send the Gerber ZIP to any PCB Print Service. I have used [JLCPCB](https://jlcpcb.com/quote), they are dead cheap - Paid $2 for 5 boards

3. Buy the switches and the resistors. The most critical part here are the switches: The board has the footprints for this specific switch, which is [Digikey Part EG6117-ND](https://www.digikey.com/products/en?keywords=eg6117-nd). The Resistors and Capacitor are through-hole and the values are in the Schematic.

4. How do I wire it? For wiring, wire the tip of a standard 3-pin audio plug and the `GND` part of the plug. Leave the center floating.

Of course you can also download [Eagle 9](https://www.autodesk.com/products/eagle/free-download) and play with the schematics and PCB layout in [Design](/Design) folder.

## CHANGELOG

### Revision C (May 27, 2024)
* Fixed the flipped Down arrow and F/B button reported in [Issue 1](https://github.com/rfrht/RFH-2/issues/1) by jgedmond - thank you!

### Revision B (Jun 8, 2019)
* Fixed the push-button pinout
* Now makes extensive use of ground plane
* Rewired the board
* Larger holes, suitable for a screw, with symmetrical holes at the board edges
* A through-the-hole pad for the signal input
* Added a few centimeters more to accomodate the $ABOVE changes
* And that's it folks!

### Revision A (Apr 28, 2019)
* Initial release

73s de PY2RAF.
