# Forcemeter
A java & arduino tool to measure the force applied in a sensor (FSR).

![Running screenshot](/screenshots/connected_small.png)
## Required Java libraries (included in lib folder)
* **RXTX**, library for serial comunication.
* **JFreeChart**, library for graph drawing.
* **JCommon**, JFreeChart need it for working.
* **JSON-Java**, used for data handling between comunications.

## Installation
You can use the libraries included in *lib* folder or download them (e.g. if libs are outdate).
Necessary rxtxSerial.dll bins are in *res* folder in a zip file.

### Download libraries
* Download RXTX binaries (You can download it from [here](http://rxtx.qbang.org/wiki/index.php/Download)).
* Download JFreeChart & JCommon libraries from its [sourceforge](https://sourceforge.net/projects/jfreechart/files/).
* You can download and compile JSON-Java into jar file, from the original repo, [here](https://github.com/stleary/JSON-java).

### Import & configure
1. When you download the binary package, you have to copy "**rxtxSerial.dll**" file to "*%PROGRAMFILES%\\Java\\jre.x.x_xxx\\bin*".
2. The project was made with eclipse. You have to import with eclipse and then import "**RXTXcomm.jar**" as an external jar file. (Also in RXTX downloaded package)
3. Finally, import the json, JFreeChart & JCommon needed libraries as jar files too.

## Required Hardware
* **Arduino board** (this project was implemented in *Mini Pro*).
* If arduino board doesn't have, an **usb-to-ttl** serial adapter.
* **16x2 LCD** Screen (optionally **LCD-I2C** adapter, less cables, there are two codes for each one).
* **FSR** Sensor (in this project we have used an Interlink 402 round from adafruit).
* Buttons, cables, case, etc...
