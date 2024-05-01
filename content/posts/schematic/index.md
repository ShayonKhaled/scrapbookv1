---
title: "Schematic"
date: "2023-07-18"
categories: 
  - "scrapbook"
tags: 
  - "8-day"
coverImage: "July-18-8-day-streak.jpg"
---
<!--more-->

I couldn't figure out any way to get ESP32S2 to work with CAN Bus module for the life of me. So I opted for a far less elegant but functional solution, using an Arduino Nano to communicate with the CAN bus module and passing that onto the ESP32S2 through I2C.

This is the schematic for the main board, which will be receiving data through the CAN bus module, communicate with the accelerometer, write data onto the SD card etc. The display cluster ESP32S2 will just be receiving gauge values from the main board and display them accordingly on the gauge.
