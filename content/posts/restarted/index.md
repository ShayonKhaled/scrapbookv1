---
title: "Restarted"
date: "2023-08-17"
categories: 
  - "scrapbook"
tags: 
  - "6-day"
coverImage: "August-17-6-day-2.jpg"
---
<!--more-->

Started working on the barcode scanner project again. This time to rush everything and just finish a base prototype. Aesthetics can wait. Functionality comes first.

I'm not sure if I said this before but the main problem is that we're using a Raspberry Pi Zero and a barcode scanner _module_ here. And since fabricating one custom USB cable isn't an option right now, I'm having to use three different cables to make the module talk with the Raspberry Pi.

It would've been way sleeker and slimmer if I could just use an ESP32 instead. Get the barcode from the module and send that to the server through an API. Easypeasy.

Perhaps for next version, too late to suck up the sunk cost for this one.
