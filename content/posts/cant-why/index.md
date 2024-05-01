---
title: "CAN't, why?"
date: "2023-07-16"
categories: 
  - "scrapbook"
tags: 
  - "6-day"
coverImage: "July-16-Day-6.jpg"
---
<!--more-->

_Pardon the pun, CAN't help it._

Can't seem to get the CAN bus module with the ESP32S2 board working. I even tried using a Digispark (Attiny85-based) to communicate with the CAN module and pass that data onto the ESP32S2, only to realize Attiny85 doesn't have hardware SPI and hence won't work with the libraries I'm using.

Ugh, I don't have enough time before the presentation to code my own library from scratch now nor modify the existing ones.

I'll keep trying to get the ESP32S2 to work with the CAN bus module, I guess. So little documentation available online. Embedded can be trivial.
