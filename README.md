[![Build Status](https://travis-ci.org/pfalcon/micropython.png?branch=pfalcon)](https://travis-ci.org/pfalcon/micropython) [![Coverage Status](https://coveralls.io/repos/pfalcon/micropython/badge.png?branch=pfalcon)](https://coveralls.io/github/pfalcon/micropython?branch=pfalcon)
#

1. This build is using the MicroPython fork from Pfalcon.

2. This build is using the port for the ESP32-CAM from Tsaarni:

https://github.com/tsaarni/esp32-camera-for-micropython


# MicroPython on ESP32-CAM with OV2640 camera support

![Imgur](https://i.imgur.com/8v4lsjd.jpg)

This repository contains a fork of [MicroPython](http://micropython.org/) that implements a Python module called `camera` for capturing images with OV2640 camera sensor.

The python module is based on driver by Espressif (see [here](https://github.com/espressif/esp32-camera)).  It utilizes I2S to implement communications with the camera without external FIFO chip.  Very minor change was necessary to make the driver compatible with MicroPython, see fork [here](https://github.com/tsaarni/esp32-camera-for-micropython).  The driver is implemented in C.  Using it requires a custom build of MicroPython itself.  


## Working build

Checkout the wiki.

## How to compile 

Checkout the wiki.