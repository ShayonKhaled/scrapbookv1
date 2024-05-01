---
title: "Groot, CNC, Frsky D8/D16"
date: "2023-03-08"
categories: 
  - "scrapbook"
tags: 
  - "5-day"
coverImage: "Untitled-design-9.jpg"
---
<!--more-->

Printed a Groot today (the filament was a bit wet so the print didn't come out that good.

Thomas helped me configure the end-limits of the CNC machine today as well as uploading g-code into the machine. So if we send a file consisting of g-code to the machine, it's gonna move the axes following the instructions of the g-code. The next step is to install the spindle onto the CNC. It's going really fun, I'm finding the process fascinating.

Also changed the radio protocol of the tinywhoop (Grasshopper) from D16 to D8. I was getting random radio signal loss errors even when flying like 20 inches away from me. Then I found out the D16 protocol was using too much of the CPU. Downgraded to D8 protocol and the problem was gone. Weird, this is the first time I ever got bottlenecked by a microcontroller's processing capability. Well, it is what it is.
