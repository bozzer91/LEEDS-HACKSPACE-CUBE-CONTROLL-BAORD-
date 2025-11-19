# LEEDS HACKSPACE CUBE CONTROLL BOARD

This READ me is a work in progress, please check back soon  :
This repository is for the new control board for the Leeds hackspace Cube art installation, this board will take input from a pc and output commands to the 16 Lines of addressable LEDS at 5v logic.  

<img width="402" height="251" alt="image" src="https://github.com/user-attachments/assets/368b161a-b8c6-44ab-8492-208775e14491" /><img width="323" height="207" alt="image" src="https://github.com/user-attachments/assets/fe021a87-1833-4190-ae8a-52cd3438f9b9" />
wiring diagram visualization ( not final revision) 

<img width="414" height="460" alt="image" src="https://github.com/user-attachments/assets/d3f01a46-f69f-4c2b-ac29-a3edda79f03d" />

( the cube ) 



## Board info :

### Purpose : 
This control board is designed to take a Raspberry pi pico / pico-W and convert 16 data lines from 3v3 voltage to 5volt data and output this to the 16 LED strings of the Hackspace Cube. this board also includes extra ports for expansion and other functions for future upgrades. the board is about 10cm by 6cm and is deigned to be placed into an encloser with the users connectors of choice attached and soldered onto the PCB DATA outputs.   



### Reference text: 

<img width="328" height="257" alt="image" src="https://github.com/user-attachments/assets/778e9361-7bda-4f7c-917e-a38e4b6a62d4" />

<img width="344" height="146" alt="image" src="https://github.com/user-attachments/assets/47dafa98-c270-443b-b109-7c8edf730b17" />


The test points for the DATA and GPIO are as follows.
Data: to the left-hand side of the resistor above the label.
GPIO: test point to the right-hand side of the resistor below the labelling.
see below for the visual.

<img width="241" height="725" alt="image" src="https://github.com/user-attachments/assets/9a7bb0d7-c4b5-4c08-8607-8333cef3c763" />


Spare pin header :
The pin header by pins 16-28 are spare for future expansion of the cube there are extra GND to the right of this.

<img width="588" height="152" alt="image" src="https://github.com/user-attachments/assets/a5db5426-c5de-4d6b-a94a-5990e6ef0a3f" />

Smothing caps :
there are smoothing caps on the main voltage rails for 5v and 3v3 when it leaves the pico and then one set pure set of logic shiters.

<img width="432" height="402" alt="image" src="https://github.com/user-attachments/assets/b3219247-ba2a-41fa-92d5-3ea5f70891ba" />


<img width="205" height="145" alt="image" src="https://github.com/user-attachments/assets/55308101-48d3-4244-9840-cda3a05797be" />


THIS IS A WIRE DIRAGRAM FOR THE HACKSPACE BIG CUBE CONTROL BAORD 

THIS WORK IS TO REPLACE THE OLD BREAD BOARD ( SEE BELOW LINK ) WITH A SIMPLE PCB FOR CONTROLLING THE BIG CUBE 
BREAD BOARD 
![IMG_2710](https://github.com/user-attachments/assets/d3698fc7-a4cd-495c-b639-95eeb6295c4a)

THE PCB WILL HAVE TWO CONECTORS FOR THE CUBE THIS IS DATA LINE 1-8 AND 9-16 IT WILL ALSO HAVE TWO EXTRA EARTH CONECTORS. 
I HAVE ALSO ADDED OPTIONAL SMOOTH CAPS ON THE POWER LINES TO THE LOGIC LEVEL CONVERTERS ON BOTH THE 3V3 ND 5V RAILES ONE SET BY THE PICO AND THE OTHER SET HALF WAY ALONE THE POWER LINE. 
THIS WILL HOPFULLY HELP STOP AND ISSUES WITH ANY NOISE ON THE POWER RAILS 







BIG CUBE 
![IMG_2693](https://github.com/user-attachments/assets/81c77e6a-e804-4cc5-9f33-17d74d97d4d2)
