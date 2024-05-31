---
title: "Control systems are fun, learning PID"
date: "2024-05-24"

coverImage: "PID.jpeg"
---
<!--more-->
The DJI motors I was using for the robots we built for the competition also sent various feedback back through the CAN bus. I was aware of it, but previously I didn't really try to use it because I was occupied with other stuff. Now that I have a bit of time in hand, I'm trying to set up a PID algorithm to control the speed of the motor. Previously, we did it by just controlling the acceleration with joystick but as you can guess, that wasn't very accurate. So, this should help make the robot much easier to drive this time.
By the end of the day, I managed to get a fairly stable output with 1% error with a PI system. But yeah, still have a lot to learn. 