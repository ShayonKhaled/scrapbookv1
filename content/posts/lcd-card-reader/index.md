---

title: "LCD and card reading"
date: "2024-07-12"

coverImage: "lcdcardreader.jpeg"
---
<!--more-->
Connected an LCD to the card reader circuit today. To display the reading there. Fortunately this LCD that I borrowed from lab has an i2c expander on the back, so the connection was super easy, just two data wires.
I'm working with this Hitachi HD44780 driver-based LCD after a long time; the last I worked with this was a few years ago. Back then the i2c backpack was available, but it wasn't as popular in my country so I would have to connect all pins (16?) of the LCD to Arduino which made it a pain in the neck to use. 

Funny how accessible and cheap electronics has become in the last decade.
