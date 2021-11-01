# Voron-2.4-Parts

Respect to the standard Voron 2.4 parts the ones which are listed in this repository include some printer cinematics and functional modifications (aka MOD)
I did implement these in my two Voron V2.4-300 printers and I personally think those are worth installing in a build, even a new one.

This is one of my printers during its assembly phase which is using those MODs as a reference

![image](https://user-images.githubusercontent.com/76037248/139673867-772d6020-2921-4a36-a244-ae9941130e27.png)

Here is a quick description of the MOD(s), their purpose and a links (in the titles) to the specific repository in case you would look to read more about each

## 1. Braced motor tensioner for Standard BOM Z drives
This MOD Improves the steadiness of the NEMA motors in respect to the standard Z-Drives and allows a better regulation of the transmission pulley.
The Stepper motor is hold by four bolts to a bracket which hold to the frame and to a top flange.
https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod

## 2. Pinned mod on AB drives frames, XY Joints, Z-Idlers, AB idlers
M5 Bolts which are used in the standard BOM as shaft for the bearings are replaced by 5mm OD pins (shafts). The printed parts are tailored for the shafts
This MOD reduces potential wabble of the bearings on the shafts allowing better belts movements

## 3. Spherical Bearings Z-Joints
GEC5 Spherical bearings are used in the amended Z-Joints parts to provide a better contact method for the Z joints and improve gantry geometry stability to slightly more optimum.

## 4. MGN-12 X-Axis
This MOD alters the XY joints and the X-Carriage as the dual MGN9H rails are replaced with a single MGN12H. The XY 6mm belt is directly clamped to the MGN12 block by the carriage.
Obviously this MOD requires that an MGN-12H linear rail and carriage is installed instead of BOM rails

## 5. Magnetically attachable Z-Probe (aka Klicky probe)
Microswitch based inductive probe replacement which I did personally refined the design of to allow better attach/detach robustness and support tilted gantry scenarios

## 6. AB-BN 30 Hot-End
This is replacement to the stock Afterburner which hosts a larger part cooling fan (5015 blower fan)
This Hot End allows to print materials which require sustained cooling like e.g. PLA 

## 7. Never-More recirculating air filter
Back blanking plate is used instead of the exhaust filter housing if you are using a nevermore filter instead.

## 8. Direct drive Z-Drives
This is not a MOD but rather a different Z-Drive design. It does not transmit movement by means of large pulley and belt but it direct drives the pulleys via a planetary gearbox between the stepper motor and the pulley shaft. It is exactly what happens in a smaller scale in the well-known Galileo extruder. This planeray gear setup is in fact a Galileo Galilei design.
This is not yet officially released design to the general Voron Discord community and as such no questions can be asked by users which have not a serial already nor it can be discussed in public channels. That said I moved both my two printers to these drives… and as I also use a Galileo extruder, I decided to name my Voron as “Voron Galileo” 😊


