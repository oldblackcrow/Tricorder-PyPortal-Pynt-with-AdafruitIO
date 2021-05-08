Adafruit PyPortal Pynt - CircuitPython Powered Internet Display - 2.4" TFT

PowerBoost 1000 Charger - Rechargeable 5V Lipo USB Boost @ 1A - 1000C

Garmin LIDAR-Lite Optical Distance LED Sensor - V4 - Keep in mind that the Garmin requires 5v power SEPARATE from the PyPortal. So, cut the power wire on the I2C STEMMA cable and wire directly from the Garmin to a 5v source (in this case the PowerBoost). Make sure to connect BOTH the Ground from the I2C STEMMA cable and the Ground from the Garmin into a common Ground on the PowerBoost

Some kind of power switch. I used a basic Breadboard-friendly SPDT Slide Switch

The code was supplied by Adafruit from their PyPortal UI example. With some help from the community, I integrated the Garmin LIDAR and AdafruitIO code. 

Graphics are modifications of images and sounds found on https://memory-alpha.fandom.com
