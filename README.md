# Project_Optical_Tachometer
Optical tachometer is used to measure RPM(Revolution Per Minute) of any rotating body, in our case, a running DC motor

## Devices
We uses ATmega4809 Curiosity Nano and MPLAB IDE.


### How to use?
Please download the code and open it with MPLAB IDE.
Make sure you have a breadboard(or two), a 16x2 LCD display, a DC motor,a L9110 motor driver, a photoresistor, a LED(yellow or red is preferable), resistors(220Ω and 10KΩ) and multiple wires.
Connect the components as following:



First, please run the code, and you should see the program built successfully in the box below. The LCD display and the yellow LED should light up.
Next, please check if the distance between LED and LDR is within 2 cm.
Then, please push the propeller a bit to give the DC motor strength to overcome the static friction and start running. Put the DC motor in the middle of the LED and LDR. Make sure the propeller does not touch the breadboard.
Soon the RPM value is visible on the LCD display and the value updates once every second.




#### Credits
Aowen Shi(aowshi@utu.fi), Jiachen Yao(jiayao@utu.fi), Guanghang Chen(guchen@utu.fi), Honghao Du(hongdu@utu.fi), Bowen Hu(bowehu@utu.fi) have done contribution to building up this project.
