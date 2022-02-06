# DIY-Mini-Stator-Winding-machine-Prototype-Arduino-based-project

![g](https://user-images.githubusercontent.com/19898602/152666290-6b863576-a9bc-4372-85a0-57e0ebff98aa.png)

Hello friends I have made a mini stator winding machine using Arduino, this is just a prototype this machine is not accurate.
This just give us idea how stator winding machine can work.
In this project I have used two stepper motor one used to rotate wire arm and one will rotate the stator.
Copper wire passed from the hollow tube and when wire arm rotate it wind coil to the pole.
alternate pole windings are clockwise and anticlockwise respectively. 
I have added a reciprocating mechanism off camera this will help to wind coil with some width otherwise arm will wind coil on a single point. 

# COMPONENT USED

> Arduino Nano
> A4988 stepper driver
> 2 x Nemw 17 stepper motor
> 3D Printed parts
> 5mm OD hollow tube
> copper wire
> timing belt
> timing pulley 
> Nextion HMI

# PROCEDURE

![image](https://user-images.githubusercontent.com/19898602/152666347-a99e733a-e41f-42d3-93e1-edc100107a9a.png)
![image](https://user-images.githubusercontent.com/19898602/152666352-e68c0a6a-4fc4-4f98-99e5-8c3b38c55763.png)

First I have made base for machine from the wooden sheet.
its 12mm thick wodeen sheet 
the measurement of the base sheet is 100 x 250 mm 
I used jigsaw machine to cut the wooden sheet 
and at last I have added 4 rubber legs to the bottom o the machine

![image](https://user-images.githubusercontent.com/19898602/152666388-33eed44c-c4a8-4398-9b83-5e23740cb65b.png)
![image](https://user-images.githubusercontent.com/19898602/152666393-48850232-45f9-4366-9f57-ea97f8233cb0.png)

then I 3d printed some parts to hold bearing and this part will fixed at front and back of the stepper motor
I have used white PLA filament with 20 % infill to print this part
I printed the part in my artillery genius 3d printer

![image](https://user-images.githubusercontent.com/19898602/152666428-dbb22748-81c5-48f1-acc5-c80f806cffda.png)
![image](https://user-images.githubusercontent.com/19898602/152666434-4fd1c894-457e-473a-9b2d-29defc175fc5.png)

Now I bring one NEMA 17 stepper motor whose specification are as following

> Step Angle: 1.8 °
> Current: 1.2 A/Phase
> Holding Torque: 4.2 kg-cm
> Detent torque: 2.2 N.cm (Maximum)
> Lead Wires: 4
> Shaft diameter: 5 mm

I placed the bearing holder 3d printed part in front and back of the stepper motor


![image](https://user-images.githubusercontent.com/19898602/152666516-de083c23-073f-4454-b46f-7810c05df762.png)
![image](https://user-images.githubusercontent.com/19898602/152666525-229ca5be-5b09-4a1d-be8b-f2f5cb14081f.png)
![image](https://user-images.githubusercontent.com/19898602/152666538-c3d7c504-4994-4887-96e1-4fc7f6f12e35.png)

Now I bring the 5mm OD hollow SS tube this is the one of the most important part of the machine
copper wire passed through this tube and wind on to the pole

I cut it in reuired length with the help of angle grinder and polished it using my mini lathe machine

![image](https://user-images.githubusercontent.com/19898602/152666582-4028f9c9-30e3-467c-802c-20fff37ea770.png)

Now I assemble the tube assembly as shown in image.
I first place a timing pulley on to the shaft of stepper motor
and I also placed one another timming pulley to the hollow tube
and connect both of the pulley with the help of closed loop timing belt
in this way when stepper motor rotate the tube is also rotate 



I have used my multipurpose PCB for Arduino based resistor reel cutting machine project. If you want to have this PCB
Please find the Gerber file from the link below so that you can order your own PCB
I suggest you JLCPCB.COM to choose your PCB manufacturer they really have very good service and low price
Multipurpose PCB link https://oshwlab.com/sharmaz747/multipurpose-pcb

![image](https://user-images.githubusercontent.com/19898602/147902257-944dde5c-a1d4-4965-8f19-e7afe7c55594.png)


![image](https://user-images.githubusercontent.com/19898602/147902264-771d306d-764e-43c0-839d-90a81e485e16.png)


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
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get 27$ welcome coupon from [JLCPCB](https://jlcpcb.com/IAT ).










