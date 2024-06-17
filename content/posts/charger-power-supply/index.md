---

title: "Remotely controlled battery charger power supply"
date: "2024-06-15"

coverImage: "powerisdt.jpeg"
---
<!--more-->
Spent the whole day working on this thing. 

Little lore from before, a few months ago I made this motion sensor which would check for human presence in the lab and turn a smartplug off automatically if no motion around was detected. The idea was that all Lithium battery chargers in the lab would be connected to the smartplug and if anyone started charging a battery and then left the lab (leaving Lithium-based batteries charging unsupervised is risky), the motion sensor would switch the smartplug off. 

However, after finishing making the device, I shortly realized the Lolin S2 Mini I had put in was faulty and didn't work with WiFi. Since I was rapid prototyping with wires directly soldered onto the module, there was no easy way to swap it out. However, for some weird reason, ESPNOW (which uses WiFi feature of ESP32S2) still worked on that board. 

So instead of going for the smartplug way, I decided to make a dedicated power supply for the ISDT battery chargers we had with a 240 watt DC power supply. I repurposed the big metal electronics enclosure of the Ender 5 and put everything inside. I also put a relay module and another Lolin S2 Mini inside, to be able to trigger the DC power output of the power supply on and off as needed; so that I could turn off the battery chargers remotely. 

It's not looking particularly neat inside, but this is just a prototype for the time being. Also, I can finally put the motion sensor that I had worked really hard on into use. 
