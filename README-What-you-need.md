Adafruit PyPortal Pynt - CircuitPython Powered Internet Display - 2.4" TFT

PowerBoost 1000 Charger - Rechargeable 5V Lipo USB Boost @ 1A - 1000C

3000mAh Lipo battery. You can probably get away with 2000mAh, but anything smaller may not last very long.

Panel Mount Extension USB Cable Micro B Male to Micro B Female - I cut and stripped the wires for a better fit. Keep in mind that doing this only provides power, not data.

Garmin LIDAR-Lite Optical Distance LED Sensor - V4 - Keep in mind that the Garmin requires 5v power SEPARATE from the PyPortal. So, cut the power wire on the I2C STEMMA cable and wire directly from the Garmin to a 5v source (in this case the PowerBoost). Make sure to connect BOTH the Ground from the I2C STEMMA cable and the Ground from the Garmin into a common Ground on the PowerBoost

Adafruit NeoPixel LED Strip with 3-pin JST PH Connector 60 LED/meter 0.5 Meter - I am just using one neopixel, so I just cut the first one from the strip. Please keep in mind that the PyPortal Pynt has the D3 and D4 JST ports mismarked, so if you are using the D4 port, the code should say D3 and vice versa.

Some kind of power switch. I used a basic Breadboard-friendly SPDT Slide Switch

The code was supplied by Adafruit from their PyPortal UI example. With some help from the community, I integrated the Garmin LIDAR and AdafruitIO code. 

Graphics are modifications of images found on https://memory-alpha.fandom.com

Sounds were found on TrekCore.com https://www.trekcore.com/audio/

For Internet connection using the Secrets file, you may want to use your smartphone's Hotspot for ultimate portability.
