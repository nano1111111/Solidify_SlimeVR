
# Solidify SlimeVR Tracker

Inspired by the Hyperion SlimeVR tracker.

I have designed it with a fitting case so you can order all the parts and assemble it directly.




## Parts list
- Wemos D1 mini ESP8266
- commercially available TP4056 boards
- 180K Resistors
- 1N5817 diode
- 12D06 switch
- BMI160
- 503450 Li-Po Polymer battery
- JST 2.0 header (optional)
- Header pins
- Case (3D printed)


## Assembly
A step by step guide on how to assemble the tracker

* **Step 1**
---------- 
    Prepare all your components
    Soldering Iron
    Solder
    Wemos D1 mini
    TP4056 Boards
    BMI160 
    12D06 Switches
    503450 Li-Po Battery
    Header Pins 
    wire cutters
------------
- **Step 2**
Start by soldering the header pins to the Wemos D1 Mini. Ensure that all pins are soldered flat to the board, as there is no space to spare in the case.

To assist with this, I suggest using a breadboard. Cut the edge off one side of the breadboard with a sharp knife, allowing you to place the Wemos D1 Mini flat on the header pins.

---
- **Step 3**
Do the same for the IMU you bought. Place it as desired on the breadboard, but ensure the header pins are on the side opposite the main components.

---
- **Step 4**
With the TP4056 things are tricky as the header pins have to be soldered relativly straight to the board. It is tricky but doable, so please go along carefully and take your time with each board you work with.

---
- **Step 5**
Take out the PCB and solder to it for ease of assembly the resistor to the slot labeled "180kΩ", do the same with the diode on the slot "1N5817" however please mind the polarity on the diode.

---
- **Step 6**

Wemos D1 mini
 * Press the Wemos D1 Mini into its designated area on the PCB. Solder only one pin initially to make it easier to ensure the board is flat before soldering the rest.


BMI160
* Do the same as above with the Wemos D1 Mini, the space on the PCB for the IMU is directly in the middle, but please make sure that the IMU is soldered as flat as possible for the best tracking results.

TP4056
*  As with the TP4056 board, making sure that it allings rather perfectly with the silkscreen marking on the PCB is not easy but necessary as you will have problems charging the tracker with a lid on the case. So please take as much time as needed to ensure best functionality.

JST 2.0 header
    
*  This is the easiest component to solder. Simply drop it in and solder, but be mindful of the polarity as marked on the PCB.

----
- **Step 7** 
The case is a three-part assembly consisting of the case itself, a PCB and battery separator called the tray, and the lid.
- Start with the tray and place the battery in the designated space at the bottom.
- Insert the tray into the case with the battery leads in the upper right corner (when the case's ports and switch are facing you).
- Insert the assembled PCB into the case, ensuring the USB port of the Wemos D1 Mini does not obstruct the placement.
- Finally, place the lid. It may require some force or minor adjustments by trimming plastic for a proper fit.
## Flashing

You may need to change the I²C address in the firmware. Use the web firmware flasher available here "https://slimevr-firmware.bscotch.ca/". The tool is straightforward to use. However, avoid clicking on any video links on the page as they will lead to a rickroll (seriously).
## Extensiontracker
There is a hole in the back of one of the case versions for a 2nd IMU for tracking, the wires can be soldered onto the respectivly named pads on the PCB.

It is however completly optional and not strictly necessary for the tracker to function properly, if you do use it however please change settings accordingly when going through the flashing procedure.


## Strap
You can use 50mm elastic fabric band for the straps, I suggest you use buckles for the hip and chest tracker.

