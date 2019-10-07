# DigiMult

The DigiMult features 2 DAC outputs, a trigger input, and an analog input as well as 4 potentiometers and a switch. The module can be programmed using the Arduino IDE. 

Shortly after I started designing this module, CCTV announced the Cascadence. Since my design and CCTV's were almost identical, I decided to make this module compatable with theirs. There are only 4 differences between them:
- The DigiMult is all through hole, making it easier to solder.
- The DigiMult is 8hp instead of 4hp. This is due to the larger through hole components.
- The DigiMult feaures an analog input, which is absent from the Cascadence.
- The DigiMult switch is on pin rather than pin to free up an analog pin for the input.

Information on the Cascadence can be found at [CCTV's website](https://www.cctv.fm/product-page/cascadence) and [their GitHub page](https://github.com/cctvfm/cascadence).

A template.ino and information on modifying CCTV's software to work with the DigiMult will be added soon.

## Files
### DigiMult_xx .brd and .sch
These are the board and schematic files needed to manufacture PCBs. Gerbers need to be generated in Eagle for manufacturing.

### DigiMultParts_xx.md
These are the parts lists for each module. A mouser BOM is available in this file as well.

### DigiMult.ai
These are the panels in Adobe Illustrator format. I make my panels on a laser cutter with 1/8 inch acrylic.

## Updates

### 01 07OCT19
Initial upload. Design is currently untested.