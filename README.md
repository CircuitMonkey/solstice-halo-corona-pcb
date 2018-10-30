# solstice-core-starfire-pcb
Solstice Design System —  *Corona* HaLo —  Eagle PCB

PCB files for the **Circuit Monkey** *Corona* **Solstice** *HaLo*

Format is EagleCAD 9.x schematic and board layout

*Corona* is a *Solstice* Hardware Locus (HaLo) module/shield.  The Corona allows you to add a small breadboard to to the top of your Solstice Core module.

For more details, check out the product page at

  * https://www.circuitmonkey.com/product/0741   ( [404 - not found] this link is not yet active)


![PCB CAD Image](images/corona-cad-image.png)

### Revision Notes
* Rev. 0 - Initial board design.  This revision was made for evaluation and only
one unit ever made.  Not shared in this repository.

* Rev. A - First revision meant for human consumption.


#### Rev A. Issues:
  * Forgot to swap Vin and GND pins on HaLo connector.   Vin was dangerously close to GND mounting hole.  Was swapped on core StarFire board but we goofed in updating the Rev. A design for this board.  Solution for now is to pluck connector pins 1 and 2 out of HL4 passthrough connector prior to soldering.  Also, black sharpie the legend for those to pins.  Attempting to use these pins would short Vin to GND.


## Designed by Circuit Monkey
Creative Commons Attribution, Share-Alike license, check license.txt for more information. Derivative of "Arduino Leonardo Reference design" (http://www.arduino.cc/en/Main/ArduinoBoardLeonardo)

All text above must be included in any redistribution
