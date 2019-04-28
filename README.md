# RFH-2
Remote Control compatible with Yaesu FT-991A (and potentially other radios too).

## What is this?
This is a remote control that is compatible with most modern and recent Yaesu radios. It mimicks the same functionality of [Yaesu FH-2](http://lmgtfy.com/?q=yaesu+fh-2) remote control, at a fraction of the cost.

## How does the board looks like?
This is the board layout in its full glory:

![RFH-2](https://raw.githubusercontent.com/rfrht/RFH-2/master/Design/RFH-2-top.png)

## Did you prototype it?
Yup. Picture below:
![RFH-2 Prototype](https://raw.githubusercontent.com/rfrht/RFH-2/master/Design/prototype.jpg)

## Nice, I liked it! How do I get one?
1. Download the Gerber [.zip file](https://github.com/rfrht/RFH-2/raw/master/Design/RFH-2_2019-04-28.zip)

2. Send the PCB file to any PCB Print Service. I have used [JLCPCB](https://jlcpcb.com/quote), they are dead cheap - Paid $2 for 5 boards

3. Buy the switches and the resistors. The most critical part here are the switches: The board has the footprints for this specific switch, which is [Digikey Part EG6117-ND](https://www.digikey.com/products/en?keywords=eg6117-nd). The Resistors and Capacitor are through-hole and the values are in the Schematic.

4. How do I wire it? For wiring, wire the tip of a standard 3-pin audio plug and the `GND` part of the plug. Leave the center floating.

Of course you can also download [Eagle 9](https://www.autodesk.com/products/eagle/free-download) and play with the schematics and PCB layout in [Design](/Design) folder.

## Thanks for saving me SERIOUS buck! How do I give back?
If this project helped you, you can pay me a cup of coffee :) I promise eternal gratitude! Or else, just star it and I'll be also over the moon! o/

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=PWSKBXK4DLNL2)
