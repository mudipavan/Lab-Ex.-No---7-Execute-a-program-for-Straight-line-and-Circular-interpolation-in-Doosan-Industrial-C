# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation








Circular Interpolation

### output

![image](https://user-images.githubusercontent.com/94828517/204609507-a95af910-a9d7-4b4e-9a4a-abd2b9dc1115.png)
![image](https://user-images.githubusercontent.com/94828517/204609646-9189ced2-26df-4508-a802-545f8aafbd39.png)
![image](https://user-images.githubusercontent.com/94828517/204609755-2a68ce91-ddca-4aef-a11d-b9e7b54a5bdf.png)
![image](https://user-images.githubusercontent.com/94828517/204609906-35162a57-f450-4625-86ef-8a1e15458e50.png)
![image](https://user-images.githubusercontent.com/94828517/204610009-0d1404d6-cd8c-4419-a486-7d8eb7a7742b.png)
![image](https://user-images.githubusercontent.com/94828517/204610245-f3994b61-9488-437b-bc50-a8a0da44d08a.png)
![image](https://user-images.githubusercontent.com/94828517/204610454-a1656092-b8f8-41eb-bea4-25abcd417853.png)


Robot:

Linear Interpolation:

![image](https://user-images.githubusercontent.com/94828517/204611017-5a1d4909-8230-4839-b643-e2ad1cb14f3d.png)

Circular Interpolation:

![image](https://user-images.githubusercontent.com/94828517/204611097-7d6be567-3e46-4c08-a571-79e68f8e8e68.png)




### Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
