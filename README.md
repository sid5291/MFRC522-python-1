MFRC522-python
==============

A small class to interface with the NFC reader Module MFRC522 on the Beaglebone Black
(Modified from https://github.com/mxgxw/MFRC522-python)

Uses a Polling Method to check Interrupt Registers for an event.

##Status
1.Not Fully Tested

##Requirements
This code requires you to have Adafruit_BBIO installed from the following repository:
https://github.com/adafruit/adafruit-beaglebone-io-python

##Examples
This repository includes a couple of examples showing how to read, write, and dump data from a chip. They are thoroughly commented, and should be easy to understand.

## Pins
You can use [this](http://www.embedded-things.com/wp-content/uploads/2013/08/P9.png) image for reference.

| Name | Pin #       |
|------|-------------|
| SDA  | P9_17       |
| SCK  | P9_22       |
| MOSI | P9_21       |
| MISO | P9_18       |
| IRQ  | (not used)  |
| GND  | P9_1/2      |
| RST  | P8_10       |
| 3.3V | P9_3/4      |

##Usage
Import the class by importing MFRC522 in the top of your script. For more info see the examples.
