---

title: "Troubleshooting S2"
date: "2024-07-04"

coverImage: "redundancy.jpeg"
---
<!--more-->
Facing a weird issue with the S2 controller board. I was planning on connecting a bunch of peripheral sensors and devices to it over I2C and SPI, so I put a dedicated 3.3V voltage regulator on the board that would power everything. 

When I first assembled the board, the 3.3V power bus was fine. 

Well, for whatever reason, now it's supplying 4.3V instead of 3.3V there, and I can't figure out why. I changed out the capacitors first (even though I have no idea how them going bad could affect the voltage in such a way), nothing changed. So I swapped out the voltage regulator IC with a new one thinking it was some sort of super weird breakdown behavior. Nuh-uh. Same. 

JLCPCB has a MOQ of 5, so I still had 4 more blank PCBs left. Now I'm assembling another PCB to see if this also gets the same issue, in which case I'll need to go through my circuit design again and see where I messed up exactly. 

Fortunately, the I2C and SPI bus were more of a future expansion thing so right now the 3.3v bus isn't really being used anywhere. It's just been bugging me .




