# Voron-2.4-Parts

Respect to the standard Voron 2.4 parts the ones which are listed in this repository include some printer cinematics and functional modifications (aka MOD)
I did implement these in my two Voron V2.4-300 printers and I personally think those are worth installing in a build, even a new one.

This is one of my printers during its assembly phase which is using those MODs as a reference

![image](https://user-images.githubusercontent.com/76037248/139673867-772d6020-2921-4a36-a244-ae9941130e27.png)

Here is a quick description of the MOD(s), their purpose and a links (in the titles) to the specific repository in case you would look to read more about each

## 1. [Braced motor tensioner for Standard BOM Z drives](https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod)
This MOD Improves the steadiness of the NEMA motors in respect to the standard Z-Drives and allows a better regulation of the transmission pulley.
The Stepper motor is hold by four bolts to a bracket which hold to the frame and to a top flange.

![image](https://user-images.githubusercontent.com/76037248/139678518-38fa6084-1987-4aad-b447-0f8192add18e.png)
![image](https://user-images.githubusercontent.com/76037248/139678531-7070acf7-27a3-476d-a3b0-bfe4da09e809.png)

## 2. [Pinned mod on AB drives frames, XY Joints, Z-Idlers, AB idlers](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod)
M5 Bolts which are used in the standard BOM as shaft for the bearings are replaced by 5mm OD pins (shafts). The printed parts are tailored for the shafts
This MOD reduces potential wabble of the bearings on the shafts allowing better belts movements

![image](https://user-images.githubusercontent.com/76037248/139678589-e655102c-c59f-407d-82ee-204d15b0a2c6.png)
![image](https://user-images.githubusercontent.com/76037248/139678610-d6c08d9e-b4d5-4c2c-98e1-70ac82004dd5.png)
![image](https://user-images.githubusercontent.com/76037248/139678628-586f0904-0819-4894-ba42-1f6533e507b4.png)


## 3. [Spherical Bearings Z-Joints](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C)
GEC5 Spherical bearings are used in the amended Z-Joints parts to provide a better contact method for the Z joints and improve gantry geometry stability to slightly more optimum.

![image](https://user-images.githubusercontent.com/76037248/139678661-c8cbea85-02dc-420c-8a0d-ade93924ffb0.png)
![image](https://user-images.githubusercontent.com/76037248/139678671-0eef8c65-527b-4a34-83d2-f587e74bfd96.png)
![image](https://user-images.githubusercontent.com/76037248/139678689-42134482-06c9-42ca-b66e-a1ecd9b7be6d.png)

## 4. [MGN-12 X-Axis]()
This MOD alters the XY joints and the X-Carriage as the dual MGN9H rails are replaced with a single MGN12H. The XY 6mm belt is directly clamped to the MGN12 block by the carriage.
Obviously this MOD requires that an MGN-12H linear rail and carriage is installed instead of BOM rails

![image](https://user-images.githubusercontent.com/76037248/139678717-1af88849-ff51-43b7-8486-a1e0ac1cd63e.png)
![image](https://user-images.githubusercontent.com/76037248/139678739-55e4140c-f805-46a6-a1d6-cf0ba76232f2.png)

## 5. [Magnetically attachable Z-Probe (aka Klicky probe)](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/JosAr/Klicky-Probe)
Microswitch based inductive probe replacement which I did personally refined the design of to allow better attach/detach robustness and support tilted gantry scenarios

![image](https://user-images.githubusercontent.com/76037248/139678767-3f066687-78da-4fe5-a770-eadb8bbc790a.png)
![image](https://user-images.githubusercontent.com/76037248/139678788-9ff89a93-a077-49db-992e-488ebc24c8fd.png)

## 6. [AB-BN 30 Hot-End](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Badnoob/AB-BN)
This is replacement to the stock Afterburner which hosts a larger part cooling fan (5015 blower fan)
This Hot End allows to print materials which require sustained cooling like e.g. PLA 

![image](https://user-images.githubusercontent.com/76037248/139678814-4409623c-6d2c-4358-a340-c7546eebcceb.png)
![image](https://user-images.githubusercontent.com/76037248/139678828-2cf2785a-5db2-41c7-b593-5785bb544d21.png)

## 7. [Never-More Micro V5 recirculating air filter](https://github.com/nevermore3d/Nevermore_Micro)
Back blanking plate is used instead of the exhaust filter housing if you are using a nevermore filter instead.

![image](https://user-images.githubusercontent.com/76037248/139678849-c4f24734-be1c-4843-ae51-0bdf71aaf6a6.png)
![image](https://user-images.githubusercontent.com/76037248/139678859-c0d339bf-8242-44dc-8756-c2bec5b35fa0.png)
![image](https://user-images.githubusercontent.com/76037248/139678880-ec443c2f-109c-407b-8d58-d762c4d340ef.png)

## 8. [Direct drive Z-Drives](https://github.com/ocgeek/Voron_2.4_Galileo)
This is not a MOD but rather a different Z-Drive design. It does not transmit movement by means of large pulley and belt but it direct drives the pulleys via a planetary gearbox between the stepper motor and the pulley shaft. It is exactly what happens in a smaller scale in the well-known Galileo extruder. This planeray gear setup is in fact a Galileo Galilei design.
This is not yet officially released design to the general Voron Discord community and as such no questions can be asked by users which have not a serial already nor it can be discussed in public channels. That said I moved both my two printers to these drives… and as I also use a Galileo extruder, I decided to name my Voron as “Voron Galileo” 😊


