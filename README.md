# IoT wall plug standard

This is a circuit to control any 220v AC device under 4A plugged it.  

## Getting Started with another firmware  

To program the ESP8266 ESP-07 you need an USB <--> serial converter at 3,3v (5v will damage the ESP-07 IOs).  
You can use Arduino IDE to update own sketches.  
Or you can install another firmware in ESP-07 as Lua, uPython, ESPeasy...  
To install another firmware:
* Disconnect device from power  
* Shortcut jumper (IO0 and GND)  
* Connect your favorite USB-serial converter at RX,TX,GND pins  
* Apply power to device (Be careful with 220v AC)
* Upload your firmware with esptool.exe (windows) or another tool for OSX, Linux...  
* Disconnect the jumper (IO0 and GND)
* And restart device



## Built With

[EagleCAD](https://www.autodesk.com/products/eagle/overview)

## Authors

* **RadikalBytes** - *Alfredo Prado* - [@radikalbytes](https://twitter.com/radikalbytes)


## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.


## Acknowledgments

* To my brain for support me every hour ;)
