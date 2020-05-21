# wativ_instrument_design
 a collection of instrument designs

This Max patch can be used to extract positional features from an iphone such as: gyroscope (pitch, roll, yaw), accelerometer (x, y, z), compass heading, gravity (x, y, z) and altitude (m kPa).
To this data from an iphone to this Max patch an OSC app such as GyrOCS must be installed on the iphone.  A potion or all of this data can be used as an input to control any desired output.


To use this Max patch follow these steps:
Download an iphone OSC app that reports needed data such as GyrOCS by Bitshape.
https://apps.apple.com/us/app/gyrosc/id418751595
Open the app and type in the ip address to which your computer is currently assigned is the space labeled “Target IP Address”. In the field labeled “Port” type in 9999.  Tap on the lock button at the top left hand corner of the screen.
On your computer open the Max patch called iPhone_gyro_accel_Weki.maxpat.
Open Wekinator with the following settings:  
Listening on port 6448
	13 input
	Choose a desired number of “All continuous” outputs
Create an output that’s interesting to you.

