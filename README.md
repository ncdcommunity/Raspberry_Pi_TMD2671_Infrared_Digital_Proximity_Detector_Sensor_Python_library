[![ TMD2671](TMD2671_I2C.png)](https://store.ncd.io/product/tmd2671-infrared-digital-proximity-detector-i2c-mini-module/).

#  TMD2671

The TMD2671 is a digital proximity detector that includes an integrated LED driver and IR LED.The proximity detector in this device operates from sunlight to dark rooms and is calibrated to 100-mm.The addition of the micro-optics lenses to the TMD2671 provides highly efficient transmission and reception of IR energy.
This Device is available from www.ncd.io 

[SKU: TMD2671]

(https://store.ncd.io/product/tmd2671-infrared-digital-proximity-detector-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TMD2671 infrared digital proximity detector sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tmd2671-infrared-digital-proximity-detector-i2c-mini-module/">TMD2671 infrared digital proximity detector sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TMD2671.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
