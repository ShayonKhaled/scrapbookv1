---
title: "サクラ, ESP32S2, cookies"
date: "2023-03-24"
categories: 
  - "scrapbook"
tags: 
  - "21-day"
coverImage: "Untitled-design-26.jpg"
---
<!--more-->

First day of weekend went as usual. Cleaned my room, went outside and took photos of cherry blossom (sakura).

Late in the night I hooked up one of the Wemos S2 Minis with my computer. No LEDs lit up so I thought it was a DOA (Dead On Arrival), but turned out these didn't have any onboard power indicator, just one LED connected to pin 15.

The code uploading process was a bit tricky as I had to do push the boot button and reset button in a certain sequence to get it to work with Arduino. And even after the code was uploaded successfully, Arduino threw an error message saying the upload was failed.

But the blink code was making the LED blink just fine. After some research, I found out this is a pretty well known bug that hasn't been fixed yet.

Looks like I got my hands on some boards with quite limited documentation and an user community nowhere as large as the Arduino communities.

Who's in for an adventure?
