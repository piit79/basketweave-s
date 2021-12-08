# Build Guide

## Required Components
You will need the following tools and components to build the Basketweave-S (not included in the kit):
![components](https://imgur.com/4uvzEY2.png)
- Soldering iron and solder
- Phillips head screwdriver
- Flush side cutters
- No-clean flux (recommended to prevent bridging on USB pins)
- 70 MX style switches (or 71 when not using the encoder)
- 5 PCB mount 2u stabilizers
- Keycaps (check compatibility, this layout uses many non-standard keys)
- USB Type C cable
## Included Components
The following components are included in the Basketweave keyboard kit:
![kit](https://imgur.com/C8kzkQa)
| Ref     | Component              | Qty | Notes |
| ---     | ---------              | --- | ----- |
| C1, C2  | 22pF Capacitor         | 2
| C3, C4  | 0.1uF Capacitor        | 2
| C5      | 4.7uF Capacitor        | 1
| D1-68, D71-74   | 1n4148 Diode   | 71
| D69, D70 | 3.6V Zener Diode      | 2  | Keep separate from the 1n4148 diodes
| FUSE    | 500mA Resettable fuse  | 1
| ISP     | 6 pin header           | 1
| USB     | GCT USB4085 USB-C port | 1
| POWER   | 3mm LED                | 1
| R1, R7  | 1.5k Resistor          | 2
| R2, R5  | 5.1k Resistor          | 2
| R3, R4  | 75R Resistor           | 2
| R6      | 10k Resistor           | 1
| U1      | ATmega32A-PU           | 1
|         | 40 pin IC socket       | 1
| RESET, BOOT | 6mm push button    | 1
| Y1      | 16MHz Crystal          | 1
|         | EC11 Rotary encoder    | 1
|         | Knob                   | 1
|         | M2 6mm standoff        | 11
|         | M2 10+3mm standoff     | 6
|         | M2 6mm screw           | 6
|         | M2 4mm screw           | 16
|         | Rubber Feet            | 4
|         | Basketweave-S PCB      | 1
|         | Bottom plate           | 1
|         | Switch plate           | 1

### Step 1. Zener Diodes (D69, D70)
**This part has specific orientation** - black line on the diode lines up with the square pad (points left)
![Zener Diodes](https://imgur.com/2dWvPp2)

### Step 2. Resistors (R1-7)
Orientation does not matter. Solder based on the labeled values.
| Ref    | Value |
| ------ | ----- |
| R1, R7 | 1.5k  |
| R2, R5 | 5.1k  |
| R3, R4 | 75    |
| R6     | 10k   |
![Resistors](https://imgur.com/haA16fU)

### Step 3. 1n1418 Diodes (D1-68, D71-74)
**This part has a specific orientation** - black line on the diode lines up with the square pad (points up)
![Diodes](https://imgur.com/qEMczrJ)
Don't forget the D72-74 ones !
![Extra diodes](https://imgur.com/6sOD2Mj)

### Step 4. Capacitors (C1-4)
Orientation does not matter. Solder based on the labeled values.
| Ref    | Value |
| ------ | ----- |
| C1, C2 | 22uF  |
| C3, C4 | 0.1uF |
![Capacitors](https://imgur.com/4xfcnwh)

### Step 5. USB Port
Solder one of the large legs first and check that the port is flush before soldering the other three legs. \
Solder the smaller pins by applying no-clean flux across the pins, then drag a small amount of solder across the pins until all the holes are filled.
![USB port](https://imgur.com/2BZQcIB)

### Step 6. Capacitor (C5)
**This part has a specific orientation** - longer leg goes in square pad (white mark on the capacitor points up)
![Capacitor](https://imgur.com/VPMZwld)

### Step 7. Fuse
Orientation does not matter. Fold down after soldering.
![Fuse](https://imgur.com/mGPtuYl)

### Step 8. Crystal (Y1)
Orientation does not matter.
![Crystal](https://imgur.com/zMjaGQZ)

### Step 9. LED
**This part has a specific orientation** - shorter leg and flat side of the LED line up with the square pad
![LED](https://imgur.com/3Rwh3kY)

### Step 10. Push Button (RESET, BOOT) and IC Socket
Push buttons have no specific orientation. \
Align the notch on the IC Socket with the markings on the PCB. 
![Push button and IC socket](https://imgur.com/CIPhDrD)

### Step 11. Pin Header
Orientation does not matter. 
![Pin header](https://imgur.com/ZYlZZbF)

### Step 12. ATmega32A
Insert ATmega32A into the IC socket. Make sure the notch on the microcontroller aligns with the notch in the IC socket and the markings on the PCB then press gently.
![ATmega32A](https://imgur.com/KjZF7Ug)

###### Step 12b (optional) : Flash your keyboard and check if everything is fine.
It's better to check now before you solder anyhting else.

### Step 13. M2 6mm Standoffs, M2 10+3mm Standoffs, M2 4mm screws, stabilizers
| Component          | Qty | Location     |
| ------------------ | --- | ------------ |
| M2 10+3mm standoff | 6   | Front top    |
| M2 4mm screws      | 5   | Front bottom |
| M2 6mm standoff    | 11  | Back         |
Now is a good time to insert stabilizers too. You can't insert standoffs or stabilizers once the switches have been soldered.
![Screws](https://imgur.com/fUJYUYw)

### 13b (optional) : Rotary encoders
Install one or both the rotary encoders in the desired positions. Remember that you can only install one per side, top or bottom position for each. Solder one of the big legs while pressing it gently to ensure that it's flush. Solder the other leg and check. Solder the five pins.
![Rotary Encoders](https://imgur.com/SlxUt48)

### Step 14. Switches
Insert a few switches on the plate (one on each corner and a few in the middle for example) so that the plate doesn't flex when you insert other switches. \
Place the plate on top of the stabilizers. Be gentle to avoid bending switches legs. \
Install and solder all switches.
![Switches](https://i.imgur.com/RPVrxVe.jpg)

### Step 15. Bottom Plate
(optional) Screw angling feet into the bottom plate. \
Screw in bottom plate using 11x M2 4mm screws. \
Attach rubber feet.
![Bottom plate](https://i.imgur.com/cKc79vs.jpg)

### Step 16. Acrylic Guard
Screw in acrylic guard using 6x M2 6mm screws. Be careful not to overtighten.
![Acrylic](https://i.imgur.com/5vpsVVl.jpg)

### Step 17. Keycaps
Add keycaps.
![Keycaps](https://i.imgur.com/MdegVJQ.jpg)

Done!
