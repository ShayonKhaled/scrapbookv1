---

title: "Server with Flask"
date: "2024-07-16"

coverImage: "flask.jpg"
---
<!--more-->
I set up a web server on Python to receive POST request from the ESP8266. The way it works is, every time a card is swiped, the ESP8266 would send the ID number to the web server in the form of a POST request containing the data in JSON format. And then the server would receive that data, and append that to a .CSV file along with the timestamp. 

Professor had suggested that I use Flask to make the web server. I'd never heard of Flask before, turned out it was some sort of framework to set up servers using Python with minimal coding. They weren't bragging, it literally took me 25 lines to set up a server that would run locally, receive POST request from the ESP8266 and write the log file. 

Initially I faced some issues; I would keep getting a 403 error even when it was working fine when I sent the POST request manually from my phone or the laptop. Turned out Flask by default starts up the server at 5000 which was also used by AirPlay receiver on MacOS (apparently it's a quite known issue), so that's where the conflict was. I manually changed the port to 8000 and it started working fine flawlessly after that. 

The server side's code is ready as it is. On the ESP8266's side, I'm still facing a weird bug where it gets stuck at the "Waiting for card to be swiped" loop after a few seconds and doesn't do anything even when I swipe the card. I'll need to fix that bug, probably next months during the vacation.