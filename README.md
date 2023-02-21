NAU7802-Dual Channel (based on Adafruit NAU7802)
================

## Installation

* Download the sourcecode ("Code -> Download ZIP")
* Extract to your Arduino library folder (/home folder on Linux; Documents on Windows)

OR

* Clone this library with GIT into your Arduino library folder: `git clone https://github.com/benjaminaigner/NAU7802-DualChannel/`

## Differences to the Adafruit Library

* Added `Adafruit_NAU7802::setChannel` to switch between channel 1 & 2
* Added `Adafruit_NAU7802::setPGACap` to enable / disable the capacitor on channel 2 as PGA stabilizer
* Removed the revision check
* Added 2 channel example

## Original README.md

This is the Adafruit NAU7802 I2C 24-bit ADC sensor library

Tested and works great with the Adafruit NAU7802 Breakout Board
* http://www.adafruit.com/products/4538

This chip uses I2C to communicate, 2 pins are required to interface

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried for Adafruit Industries.
BSD license, check license.txt for more information
All text above must be included in any redistribution

To install, use the Arduino Library Manager and search for "Adafruit NAU7802" and install the library.
