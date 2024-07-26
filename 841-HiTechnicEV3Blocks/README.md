# HiTechnic EV3 Blocks Readme 

## Version 0.2

Revision History:
0.11    Initial release  
0.12    Fixed problem with non en-US installations.  English strings will now show up for other  
        language installations.  Eventually the strings will be localized.  
0.20    EV3 Blocks are now split into individual .ev3b files so you only need to import the blocks  
        for the sensors that you have.  Also numerous bug fixes involving I2C sensor data.  Angle  
        Sensor now has mode that gives all data, including RPM.  
0.21	Removed the Gyro sensor which is not grouped with the other two analog sensors supported  
	by the EV3.  


This is a preliminary release of HiTechnic sensor blocks for the new LEGO Mindstorms EV3.  The 
HiTechnic.ev3 file contains 5 HiTechnic sensor blocks:  
    Angle       (Now with RMP!)  
    IRSeekerV2  
    Accelerometer  
    Compass  
    
These sensor blocks make it possible to program with these sensors in the EV3 software.  Except for  
the Angle sensor, only Measure modes are supported.  To use these blocks in a loop or with a switch,   
you will need to use your own Comparison block and then use the result of the comparison with the loop  
or switch.  Future releases of the HiTechnic EV3 blocks will include Comparison modes so that the   
sensors can be read directly from Wait, Loop and Switch blocks.

## Installation:
1) Extract the .ev3b files from the downloaded zip file.  
2) From the LEGO EV3 software, select Block Import from the Tools menu.
3) From Block Import, Browse to the folder where the HiTechnic .ev3b files are located.
4) Select the desired .ev3b file.
5) Click Import.
Repeat steps 4 and 5 for all other blocks you want to import.
6) Restart the EV3 software.


