# Simple-Robot-With-Arduino
This is a simple robot source code with 3 sensors, 2 motors and all connected to the motor driver.


# Before you start coding,

The motors will not work with 5V. I used 6 1.5V batteries to power it and it worked flawlessly however you can use anything you like. You have to connect the sensors ground and Vcc part to a single row in a breadbord otherwise there is not enough spaces. The cable management might get a little confusing but if you organize well (I didn't), it won't be a problem. Now it is advised to solter the jumper wires connected to the motor driver because they won't stick and  break off easily however I didn't solder it and it became a  major problem. So don't be like me and please solder it. Last but not least, please make sure to have a knowledge of Arduino before you start using this code. 



# How it works


When sensor detects something that is closer than 25 cm on the left, it will stop turning the right wheel to move left and vice versa. Now if it detects something closer than 25 cm in the front, it will start spinning the wheels backwards until there is no obstacle. The sensor will print values like the following oreder,


Sensor in the left - Sensor in the Front - Sensor in the right


# Circuit Diagram

https://www.circuito.io/app?components=512,11021,13959,13959,13959,7654321



NOTE THAT THIS SCHEMATIC IS NOT COMPATIBLE WITH THE CODE. MANY PINS ARE DIFFRENT FROM WHAT IT IS CONNECTED HERE SO DON'T EXACTLY COPY PASTE FROM IT! THIS IS JUST TO GIVE YOU A BRIEFING ABOUT WHAT TO DO!
