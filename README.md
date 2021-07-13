

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

My custom PCB is the main part of this project thanks to [JLCPCB](https://jlcpcb.com/IAT ) to make possible this cool project


I always order My PCB from [JLCPCB](https://jlcpcb.com/IAT ) becuase I trust them they have quality PCB and as fast as 24 hour PCB turn around time.

we will see abouut this Multipurpose PCB further in this post.



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


# CUSTOM PCB

![FTQFHXZKLBNXU2X](https://user-images.githubusercontent.com/19898602/122632825-db9b8e80-d0f2-11eb-8281-3239f1275adc.jpg)
![147494540_1146948692400891_5797782675789162173_o](https://user-images.githubusercontent.com/19898602/122632834-ee15c800-d0f2-11eb-9385-0bcb4b05119a.jpg)

Making such projects without PCB is night mare yes trust me
you cannot get wanted result and professional touch in your project if you ignore PCB
So some days back I have developed my Multipurpose PCB.
This PCB is used to build wide range of arduino projects 

followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors

![147560983_1146948889067538_4990854912671411429_o](https://user-images.githubusercontent.com/19898602/122632848-fff76b00-d0f2-11eb-955e-207472be636d.jpg)
![component](https://user-images.githubusercontent.com/19898602/122632849-01289800-d0f3-11eb-970a-53fc1b6e0b58.jpg)


I have design circuit and PCB in [easyEDA](https://easyeda.com/) and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get 18$ welcome coupon from [JLCPCB](https://jlcpcb.com/IAT ).


