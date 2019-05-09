# PCB for the Adafruit 5V ready BMP180 Barometric 

<a href="http://www.adafruit.com/products/1603"><img src="assets/image.jpg?raw=true" width="500px"></a>

This is the PCB for the Adafruit 5V ready BMP180 Barometric 
Pressure/Temperature/Altitude Sensor (BMP085 upgrade)

Format is EagleCAD schematic and board layout

This precision sensor from Bosch is the best low-cost sensing solution for measuring barometric pressure and temperature. Because pressure changes with altitude you can also use it as an altimeter! The sensor is soldered onto a PCB with a 3.3V regulator, I2C level shifter and pull-up resistors on the I2C pins.

The BMP180 is the next-generation of sensors from Bosch, and replaces the BMP085. The good news is that it is completely identical to the BMP085 in terms of firmware/software - you can use our BMP085 tutorial and any example code/libraries as a drop-in replacement. The XCLR pin is not physically present on the BMP180 so if you need to know that data is ready you will need to query the I2C bus.

This board is 5V compliant - a 3.3V regulator and a i2c level shifter circuit is included so you can use this sensor safely with 5V logic and power.

Using the sensor is easy. For example, if you're using an Arduino, simply connect the VIN pin to the 5V voltage pin, GND to ground, SCL to I2C Clock (Analog 5) and SDA to I2C Data (Analog 4). Then download our BMP085/BMP180 Arduino library and example code for temperature, pressure and altitude calculation. Install the library, and load the example sketch. Immediately you'll have precision temperature, pressure and altitude data.

[Our detailed tutorial has all the info you need including links to software and installation instructions. It includes more information about the BMP180 so you can understand the sensor in depth](http://learn.adafruit.com/bmp085) including how to properly calculate altitude based on sea-level barometric pressure.


## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution

