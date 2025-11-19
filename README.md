# LEEDS HACKSPACE CUBE CONTROLL BOARD

# This READ me is a work in progress, please check back soon  :

This repository is for the new control board for the Leeds hackspace Cube art installation, this board will take input from a pc and output commands to the 16 Lines of addressable LEDS at 5v logic.  

<img width="402" height="251" alt="image" src="https://github.com/user-attachments/assets/368b161a-b8c6-44ab-8492-208775e14491" /><img width="323" height="207" alt="image" src="https://github.com/user-attachments/assets/fe021a87-1833-4190-ae8a-52cd3438f9b9" />

wiring diagram visualisation ( not final revision) 

<img width="414" height="460" alt="image" src="https://github.com/user-attachments/assets/d3f01a46-f69f-4c2b-ac29-a3edda79f03d" />

( the cube ) 



## Board info :

### Purpose : 
This control board is designed to take a Raspberry pi pico / pico-W and convert 16 data lines from 3v3 voltage to 5volt data and output this to the 16 LED strings of the Hackspace Cube. this board also includes extra ports for expansion and other functions for future upgrades. the board is about 10cm by 6cm and is deigned to be placed into an encloser with the users connectors of choice attached and soldered onto the PCB DATA outputs.   



### Reference text: 

<img width="328" height="257" alt="image" src="https://github.com/user-attachments/assets/778e9361-7bda-4f7c-917e-a38e4b6a62d4" />

<img width="344" height="146" alt="image" src="https://github.com/user-attachments/assets/47dafa98-c270-443b-b109-7c8edf730b17" />


The test points for the DATA and GPIO are as follows.
Data: to the left-hand side of the resistor above " D-1 example " the label. the left hand side is 5v

GPIO: test point to the right-hand side of the resistor below the labelling. with the left hand side being 3v3 volts

see below for the visual.

<img width="241" height="725" alt="image" src="https://github.com/user-attachments/assets/9a7bb0d7-c4b5-4c08-8607-8333cef3c763" />




### Spare pin header :
The pin header by pins 16-28 are spare for future expansion of the cube the numbers listed on the PCB are the GPIO numbers of the pico. There are extra GND pins to the right of this pin header.

<img width="588" height="152" alt="image" src="https://github.com/user-attachments/assets/a5db5426-c5de-4d6b-a94a-5990e6ef0a3f" />

### Smothing caps :
There are 100nf smoothing caps on the main voltage rails for 5v and 3v3 these are set at locations around the board first set next to the pico and then one set pure bank of 4 logic shifters. ( see below images for examples )

<img width="432" height="402" alt="image" src="https://github.com/user-attachments/assets/b3219247-ba2a-41fa-92d5-3ea5f70891ba" />


<img width="205" height="145" alt="image" src="https://github.com/user-attachments/assets/55308101-48d3-4244-9840-cda3a05797be" />

### Main outputs : 
The controller board has two main Data output connectors in the form of two sets of pinheaders to connect to the users connector of choice this also mimicked the original breadboard design and allows for drop in replacement if required using the original ribbon cables. 

Connector 1 = Data 1-8 plus one GND pin
Connector 2 = Data 9-16 plus one GND pin

<img width="152" height="270" alt="image" src="https://github.com/user-attachments/assets/808801f8-8beb-47bc-9ac5-812c2c846ad8" />
<img width="151" height="279" alt="image" src="https://github.com/user-attachments/assets/a271330b-e0dc-4df1-aa4c-8b0c212fbe10" />


### Power : 
This controller board is powered by the Pico's usb input port. 



## History of this project: 

So some history of this project. back in 2022 ( give or take a covid lockdown ) it was found that the original micro controller board for the cube had broken. work was undertaken to revers engineer this board and make a replacement for 2022 Leeds lightweight. roll on to 2025 and we are still using the fear inducing Bread board that looks like something you find in a suite case in a mission impossible film that needs defusing ( see below image ) so when packing down the cube i decided to make a pcb to replace this and help move the Cube to a more user friendly plug and play design. 


BREAD BOARD 
![IMG_2710](https://github.com/user-attachments/assets/d3698fc7-a4cd-495c-b639-95eeb6295c4a)


