# Table-Tennis-Robot (TTR) (2023-2024)
A custom-built &amp; designed 4-axis Table Tennis Robot capable of replicating most shot techniques in the sport &amp; more.

# Overview

Table tennis has always been one of my favourite sports ever since I was young. But because I had limited access to training partners, I decided to put my engineering skills to work to build my very own opponent capable of playing at every level. For this to be possible, it had to have multiple degrees of freedom from a mechanical point of view. 

# Mechanical design

For the table tennis ball to be ejected to begin with, I decided to replicate the classic design for most sports-ball launchers, which would be the ball being fed into two high-speed motors that then "hug" the ball and fling it at high speed. This method was favoured for many reasons, one of the most important ones being that adjusting either the lower or upper motor's speed (or both), topspin and bottomspin could be dialed in a very precise manner. The ball's exit speed could also be fine-tuned, especially with precision high-speed brushless motors, which from the beginning became the obvious candidate. The basic shots should as smash, topspin, backspin, and push, were all covered by this method of ejection. For the shot to be able to hit every angle and area of the table, the shooter had to have the ability to both pitch and yaw and, at the same time, travel up and down the Z-axis. Early on, I was settled on 3 axes of freedom, but one of the most fundamental techniques in table tennis is the sidespin. To solve this problem, I decided to add another axis of freedom: the ability to roll/rotate the whole launch mechanism. This not only allowed sidespin, but also the amount of sidespin depending on the angle of the launching mechanism. This whole mechanical design makes it possible to create an infinite range of different shots with topspin, backspin, sidespin, angle och power all being able to be microadjusted. 
