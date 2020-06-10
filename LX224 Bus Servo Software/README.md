# Information for use of the LX224 Bus Servo Motor from Hiwonder

## Setting up servos
First install the debug driver softwware on a Windows PC. The application logo is a yellow gear

Next, open the bus servo terminal application. You should get the following screen (parameters tab shown): 
<img src="/LX224 Bus Servo Software/images/hiwonder_bus_servo_terminal image.PNG" width="50%">

Plug in the debug board to the computer, power source and one servo motor. 

Find the correct port on the left side, ensure baud rate is 115200, and press open port. If a new port appears when plugging in the board, that is usually the correct one. 

In the software, press the read button to read the current motor paramters. Then set the ID number to the desired ID and press apply to write the changes to the connected motor. 

Do this for all motors on the robot. For this code, please follow the serail ID schematic on the home page of this repo. 

