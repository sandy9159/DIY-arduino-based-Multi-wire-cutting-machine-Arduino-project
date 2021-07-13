![MVI_0019 00_06_22_07 Still005](https://user-images.githubusercontent.com/19898602/125383958-d65df680-e3b5-11eb-8fc0-be0a309fefb8.jpg)
![MVI_0019 00_04_22_21 Still004](https://user-images.githubusercontent.com/19898602/125383477-17a1d680-e3b5-11eb-813d-5936a6ef9c2a.jpg)
![lolo](https://user-images.githubusercontent.com/19898602/125381855-479baa80-e3b2-11eb-89a2-2c3f8af22dda.png)



Hello friends in this video I have made a Multiple wire cutter machine using arduino.
There are 4 different colors of wires which feed to cutter via a single motor,
for feeding different color feeder motor drive by a stepper motor and shaft mounted gear get of feeder motor engage with the opposite gear to feed respective color of wire.

I have used a 2.8" nextion HMI for the user interface.
user can enter how much quantity and length for wire to cut.

Using HMI is very best idea because this Nextion HMI have on board 
uController on it.
Means all the HMI coding Is stored in HMI itself no extra load on Arduino.
this will make coding simple and fast, HMI itself have some GPIO’s on board


#   VIDEO 
You can watch the full video here I have shown all main main points of build this cool multi wire cutting machine 
https://www.youtube.com/watch?v=VW07FaIvl_c&t=91s


#  COMPONENTS 

> Ardiuno nano


> Nextion HMI


> A4988 stepper driver IC


> NEMA 17 STEPPER MOTORS


> High torque metal gear servo motor


> 6mm ID bearings


> 9mm Blades


> T8 lead screw


> T8 lead screw nut


> Stepper motor shaft copling


> SK8 8MM shaft holder


> 8mm Linear bearings


> 8mm SS smooth rod


> DC gear motor


> Custom PCB

> M6 rod 

# CONSTRUCTION 

![MVI_0019 00_01_09_03 Still001](https://user-images.githubusercontent.com/19898602/125382857-17550b80-e3b4-11eb-863d-0f2208112576.jpg)

First I take the 12 mm birch plywood sheet and cut it down in 180 x 200 small piece this will became the base

of ou machine, using wood is good idea its easy to drill hole into them at same time they are very strong 



![MVI_0019 00_01_53_14 Still002](https://user-images.githubusercontent.com/19898602/125383079-77e44880-e3b4-11eb-91f2-823b965b970a.jpg)

I have printed may parts in PLA on my 3D printer 

I have artilliary genius 3D printer all the parts I have printed in 30% infill.

I printed all  my parts in PLA because its easy to get Quality print with minimal care, while ABS prints needs more care 


![MVI_0019 00_03_04_09 Still003](https://user-images.githubusercontent.com/19898602/125383287-d27da480-e3b4-11eb-8804-f2df9c5ab4c5.jpg)


Then I mointed SK8 8mm shaft holder on the wooden sheet

this holder holds 8mm smooth rod on which our motor will be slide


![MVI_0019 00_04_22_21 Still004](https://user-images.githubusercontent.com/19898602/125383504-21c3d500-e3b5-11eb-95d8-f00d843dc7dc.jpg)


Then I install the side part which I printed in White PLA 

on this part we will install our Stepper motor and M6 threaded rod where we place our Gear system

this part is design such like that we can adust the placement of every component later on 

and that Yellow 3D printed part is monted on 8mm linear bearings 

our DC motor with gear mounted on this part further this will connect with Stepper motor via 

T8 lead screw , so the whole DC motor assembly can move horizontally. 


![MVI_0019 00_06_22_07 Still005](https://user-images.githubusercontent.com/19898602/125383979-df4ec800-e3b5-11eb-827d-ab08e37724fa.jpg)

This are the Gear which I printed in PLA this gears are used to drag wire to the cutter.

![MVI_0019 00_08_48_09 Still006](https://user-images.githubusercontent.com/19898602/125384234-3c4a7e00-e3b6-11eb-8c2b-2c95dde74a02.jpg)

This the wire cutting mechanism which have 2 pysichal parts one is directly mounted on 

base wooden sheet and stepper motor installed to this part

ond one part is installed with blade and 2 3mm ss rod is attached to this part

all parts are placed such like that stepper motor pull the upper blade in downward direction

and wire get cut in this motion. 


