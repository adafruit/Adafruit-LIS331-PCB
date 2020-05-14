## PCB files for the Adafruit LIS331 Family of High-g 3-Axis Accelerometers
### LIS331HH
<a href="http://www.adafruit.com/products/4626"><img src="assets/4626.png?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>
### H3LIS331
<a href="http://www.adafruit.com/products/4627"><img src="assets/4627.png?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>
### Links
PCB files for the Adafruit LIS331 Family of High-g 3-Axis Accelerometers. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4626
* https://www.adafruit.com/product/4627

### Description

Accelerometers are becoming fairly common, and their clear connection to movement makes them a particularly good choice for learning about sensors in a tangible way. It’s not hard to find an accelerometer that can measure accelerations up to 16g, but if you need an accelerometer that can measure even larger amounts of acceleration, your options narrow. The ICM20649 is a great sensor and can measure up to ±30g, but it also comes with a magnetometer that you may not need for your project.

Enter the LIS331 family of accelerometers from ST, including the H3LIS331 and LIS331HH. As their model numbers may suggest, the LIS331s are close cousins to the venerable LIS3DH accelerometer that is on every Circuit Playground, from the Circuit Playground Classic to the newest Circuit Playground Bluefruit. The LIS331s however can measure a wider range of acceleration values.

The LIS331HHis capable of measuring up to ±24g on each of its three axes for a total range of 48g! Should that not be enough for you the H3LIS331 will certainly have you covered. At the reasonable cost of some signal noise at lower “human level” accelerations, the H3’ can measure up to ±400g! The mind boggles at trying to think of what would need to measure that much acceleration. Perhaps you bought a surplus Sprint missile to start your own space program, or maybe you have an idea for a rocket sled based pizza delivery startup. The sky is the limit!

In addition to their substantial measurement capability, the LIS331s have built in and configurable high-pass and low-pass filters to adjust the readings to your application. Adjustable data rates also allow you to adjust how frequently to take measurements depending on your power budget, and SPI and I2C interfaces give them flexibility to allow them to be used in a range of applications.

The breakout for the  LIS331 family takes one of these little dynamos and puts it on a custom made PCB in the STEMMA QT form factor, making them easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors, allowing you to make solderless connections between your development board and the LIS331s, as well as being chained with a wide range of other sensors and accessories. We’ve of course broken out all the pins to standard headers and added a voltage regulator and level shifting so allow you to use it with either 3.3V or 5V systems such as the Metro M4 or Arduino Uno respectively.

Fancy as they are, breakouts alone won’t get you far, so we’ve written libraries for CircuitPython and Arduino along with example code to make them simple to use. The documentation for how to use the libraries as well as wiring diagrams on the following pages will show you how to use them to get you started.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
