---
title: "Custom gauges, RTOS"
date: "2023-05-21"
categories: 
  - "scrapbook"
tags: 
  - "78-day"
coverImage: "May-21-78-day.jpg"
---
<!--more-->

Looking into RTOS and custom gauges used by car enthusiasts who strip their cars down to save weight and use custom gauges to get necessary information from the engine instead.

Apparently modern cars use something called CAN (Controller Area Network) bus and I can tap onto it by connecting a microcontroller to the OBD (On-Board diagnosting Program) port. Pretty interesting stuff. Picture for reference, it's not mine.

I think something like that needs RTOS because the gauge must not have any latency - so the speed of the code execution matters just as much as the speed of the car, lol.
