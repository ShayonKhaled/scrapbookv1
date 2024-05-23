---

title: "Troubleshooting display cluster"
date: "2024-05-19"

coverImage: "dcluster.jpeg"
---
<!--more-->

I was trying to get the display cluster to work today. It was a part of the final project I submitted for a course back in 2023. The displays are driven by SPI, and since I couldn't find any library with multi-display support, I made them work for the project by rapidly activating and deactivating the Chip Select pin of the corresponding display as they were being updated. Well, sort of. It was still pretty glitchy. 

Today I started from scratch again. Found out for whatever reason activating display 1 activates display 2 as well, but if I activate only display 2 display 1 doesn't get activated, which I would expect to happen if the CS pins of them somehow got shorted. Display 3 works fine. 

I guess the issue is with the PCB. Maybe the traces of the CS pins of Display 1 and 2 are too close to each other. I don't know. 

Next time I will probably just go with one dedicated microcontroller per display. Multiplexing CS pins of a boatload of displays sounds cool, but maybeeeeee not worth it. 

I picked up an e-paper display a while ago that I've been meaning to try. Sigh, I wish I had more time in my day to allocate to fun stuff like these.

University sucks sometimes. 