---
title: "Read my ID card lol"
date: "2024-07-09"

coverImage: "felica.jpeg"
---
<!--more-->
I had made an NFC reader using an ESP8266 and a PN532 module few months back for a different project. It had been collecting dust on the desk. Tonight I was curious if I could read anything from my University card using that, and turned out I could. 

It's a Felica card, so I looked up an example code for reading Felica cards using PN532. Finding the correct service code was a bit challenging. But as with most things in the world, I'm not the first person who wanted to try doing this. 

So, after doing some searches on Google, I quickly found some students from other Japanese universities who tried to read their ID cards and shared their findings. After trying a service code I found online, I found my ID number and my date of admission (to the programme) unencrypted which was in HEX. After that, all I had to do was convert it to ASCII.  

Now I have a card reader that can check the ID cards of my university lol. Might use it in a future project, idk. Was fun tinkering with it regardless.