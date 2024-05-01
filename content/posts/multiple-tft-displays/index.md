---
title: "Multiple TFT displays"
date: "2023-06-29"
categories: 
  - "scrapbook"
tags: 
  - "6-day"
coverImage: "June-29-6-day-streak.jpg"
---
<!--more-->

Got the example code running on the TFT displays. I'm using the TFT\_eSPI library and a Lolin S2 Mini (my new favorite board) to drive the displays. However, the problem is that the library only supports driving one display at a time. However, since they use SPI protocol to communicate, I guess I'll have activate and deactivate the Chip Select pins of the displays real quick when I'm updating one of them.

The only problem is that the update/refresh speed will also get reduced from the perspective of the Serial Clock with this method. Let's see.

Enjoy a beautiful picture of the campus I took at night.
