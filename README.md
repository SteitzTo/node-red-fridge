# node-red-fridge

Hi,

At home I often had the problem, the door of the fridge in the cellar don't close exactly, thie failure is very power consuming and result in a total icy fridge.

There is no notification or alarm on the fridge, when thats happend.

It would be nice if Alexa reminds you that the door is not correctly closed.

# Dependencies:

Mosquitto as a MQTT Broker

node-red-contrib-alexa-remote2-applestrudel

# Hardware

[Shelly Door/Windows2 Sensor](https://www.kab24.de/strom-licht/shelly-doorwindow-2-sensor-drahtloser-intelligenter-tuer-fenstersensor-lux-messung.html)

![fridge](https://github.com/user-attachments/assets/cf6a8556-757c-49e2-a26d-7235f27f4d19)


After the Door from the Fridge is open, the trigger is switch and waiting 2 minutes befor my Parents Alexa say: 
"Hello, the Fridge Door ist open.

I implementet also a batterie indicator, when the batterielevel goes unter 10% to remind me to change the batteries.

I hope anybody help this.
Greetings Torsten

