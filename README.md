# Two wheeled self balancing robot

A two-wheeled self-balancing robot, PID control architecture. Four PID controllers are implemented to control the position, velocity, rotation (measured using Quadrature Encoders) and the tilt angle of the robot. 

## Description of 4 Tasks 
1. Driving as fast as possible a distance of 3m.
2. Similar to 1. But additionally a 360° turn at about 1m and 2m travelled.
3. During balancing an additional weight is added and the robot compensate it (stay/return).
4. Driving a figure 8 by combining two circles with 1m diameter each. 

## Video Demonstration of 4 Tasks 
[Balance Bot Video Demonstration](https://youtu.be/-k-lZ_CcU4U)  
[eYRC 2016 - Balance Bot Theme Finals](https://www.youtube.com/watch?v=ncqQBZ67XNE&t=7s)  

## Repository Contents
- **code** - The entire firmware with all the libraries
- **datasheets** - Contains all the datasheets and references
- **images** - Images of the robot and the joystick controller
- **report** - Documentation on the working of the robot and all the task submissions
- **schematics** - Hardware schematic of the robot and the joystick controller

## Balance Bot
![](https://github.com/heethesh/Balance-Bot/blob/master/images/Balance%20Bot%20Components.jpg)

## Wireless Joystick Controller
![](https://github.com/heethesh/Balance-Bot/blob/master/images/Wireless%20Joystick%20Controller.jpg)

## Control Architecture
![](https://github.com/heethesh/Balance-Bot/blob/master/images/Cascaded%20PID%20Block%20D
