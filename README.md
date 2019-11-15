# espeasy_rfid
Attaching a PN532 RFID Reader to an ESPEasy Board

Sounds easy enough, doesn't it?
Well, no. First of all: The PN532 tends to hang for no obvious reason. That has been taken care of in ESPEasy. If you provide a pin for resetting the PN532 ESPEasy will do it for you.

Because I started with ESP-01 I used GPIO0 for SDA and GPIO2 for SCL. Turns out that one has to be super careful when doing that. 
