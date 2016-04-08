Blinking LED Project FIRST
https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins 

<sample code>
import RPi.GPIO as GPIO
import time
GPIO.setmode(GPIO.BCM)
GPIO.setwarnings(False)
GPIO.setup(18,GPIO.OUT)
print "LED on"
GPIO.output(18,GPIO.HIGH)
time.sleep(1)
print "LED off"
GPIO.output(18,GPIO.LOW)
<sample code>


# GoPiGo
(CODE CAMP)
All Hardware can be purchased by following MIT's Purchase Guide Here

https://www.hackster.io/peejster/rover-c42139?ref=platform&ref_id=425_trending___&offset=39


# See Also
How to install Raspberry PI Operating System
https://www.raspberrypi.org/documentation/installation/installing-images/ 

## License
GoPiGo for the Raspberry Pi: an open source robotics platform for the Raspberry Pi.
Copyright (C) 2015  Dexter Industries

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/gpl-3.0.txt>.
