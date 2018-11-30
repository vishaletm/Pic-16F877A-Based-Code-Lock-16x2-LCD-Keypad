# PIC 16F877A Based Electronic Lock with 16x2LCD And 4x3 Keypad

The system is fully controlled by the 8 bit microcontroller 16F877A which has a 8Kbytes of ROM for the program memory. The password is stored in the EPROM so that we can change it at any time. The system has a Keypad by which the password can be entered through it. When the entered password equals with the password stored in the memory then the relay gets on and so that the door is opened. 

The code is built in a modular style to allow a user to find ways to modify project. In start the D Lock programs loads with a default code of "2345" format is *2345# which can be enter to unlock the door, the code cam be change by entering the master code in the format *23455#new 4 digit code. In this program I display only the result on LCD and lock will be connected to PORTA bit 0 where I put led for simulation.
Read More at :microcontrollerprojects00.blogspot.com/2012/03/pic-microcontroller-based-electronic.html

![enter image description here](http://1.bp.blogspot.com/-krtKPqnBrIE/UpHP1FqIbzI/AAAAAAAAAf8/5XIuvPS-g60/s1600/index.jpg)


![enter image description here](http://2.bp.blogspot.com/-umTJIv4a_hc/UJx9MAwoFQI/AAAAAAAAAV8/neKy-f2xZZA/s1600/up.jpg)

