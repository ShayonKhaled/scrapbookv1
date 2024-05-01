---
title: "Fixed, again"
date: "2023-03-30"
categories: 
  - "scrapbook"
tags: 
  - "27-day"
coverImage: "Untitled-design-36.jpg"
---
<!--more-->

Two of the tinywhoop's motors weren't starting up on their own at the same time as the other motors. They were shaking and either starting up after a few moments or not starting at all. I thought I burned out the motors or the ESCs during one of the crashes.

But turned out the wires just came loose. Disassembled the quadcopter, reflowed the solder joints of the motor wires and it was working fine again. At least, for a short while.

Then the problem came back. Increased the arm speed which solved it again temporarily, but not for too long. At the end of the day, the battery connector started getting loose again (just like last time with the old connnector) and at some point after restarting I couldn't get it to arm.

The video feed was still transmitting but there was no OSD (On-screen Data). So either I killed the flight controller part of the AIO (All-In-One) board (if that's even possible), or the firmware got deleted again due to the low voltage supplied by the battery connector. That's probably the case.

Flying FPV quadcopters is a very high-maintenance hobby indeed.
