# Table-Tennis-Robot (TTR) (2023-2024)
![TTR](images/TTR_1.jpg)
#
A custom-built &amp; designed 4-axis Table Tennis Robot capable of replicating most shot techniques in the sport &amp; more.

# Overview

Table tennis has always been one of my favourite sports ever since I was young. But because I had limited access to training partners, I decided to put my engineering skills to work to build my very own opponent capable of playing at every level. For this to be possible, it had to have multiple degrees of freedom from a mechanical standpoint. 

# Mechanical design

For the table tennis ball to be ejected to begin with, I decided to replicate the classic design used in most sports-ball launchers: the ball is fed into two high-speed motors that then "hug" it and fling it at high speed. To make sure I got as good of a hugging motion while at the same time gripping the ball without damaging it, I repurposed old RC-plane wheels. This method was favoured for many reasons, one of the most important being that adjusting either the lower or upper motor's speed (or both), as well as topspin and backspin, could be dialed in very precisely. The ball's exit speed could also be fine-tuned, especially with precision high-speed brushless motors, which from the beginning became the obvious candidate. The basic shots, such as smash, topspin, backspin, and push, were all covered by this method of ejection. For the shot to be able to hit every angle and area of the table, the shooter had to have the ability to both pitch and yaw and, at the same time, travel up and down the Z-axis. Early on, I was settled on 3 axes of freedom, but one of the most fundamental techniques in table tennis is the sidespin. 

To solve this problem, I decided to add another axis of freedom: the ability to roll/rotate the whole launch mechanism. This not only allowed sidespin, but also the amount of sidespin depending on the angle of the launching mechanism. This whole mechanical design makes it possible to create an infinite range of different shots with topspin, backspin, sidespin, angle och power all being able to be microadjusted. To make pitch, yaw, and roll motions possible, I used heavy-duty RC-plane servos as they are very easy to control and offer a great amount of torque for their speed as well. To engage the axes on bearings, I used simple helical gears attached to the servos. I used another servo to feed the balls into the launcher, and to make sure the ball didn't roll in on its own, I used a piece of laminate paper with a hole cut slightly too small. This made the ball not roll into the shooter by itself but at the same time let the ball through if pushed with enough force. The final mechanical model of the launcher is shown below.
#
![Mechanical design](images/Mech_Design.jpg)
#
Because the project involved very high-power spinning motors as well as many other sources of vibration, I decided to construct an aluminum frame similar to that of a 3D printer using standard 20 x 20 extrusion. For the main launcher to be able to move up and down, I decided to use the aluminum extrusions as rails, wherein linear Z-axis rods could be combined with stepper motors for controllable and extremely precise up-and-down movement, again similar to a 3D printer. Two shorter pieces of aluminum extrusion were bolted onto the main launcher with bearings to let it pitch up and down. These two pieces were also attached to the main rail, wherein the Z-axis rods were bolted through them. For stability reasons, 4 stepper motors attached to 4 Z-axis rods were responsible for the up-and-down motion of the entire launcher. A massive 3D-printed box could also be optionally bolted to the bottom frame to house different components.  
#
![Mechanical design final](images/TTR_CAD_Final.png)
