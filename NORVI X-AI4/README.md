# NORVI X-AI4
## 4-Channel Analog Input Expansion Module

The NORVI X modular controller platform. It provides four high-precision channels designed to monitor 4-20mA industrial current loops, 
making it ideal for interfacing with standardized process sensors and transmitters. The module utilizes precision signal amplifiers to
condition incoming field signals, which are then digitized through a high-resolution ADS1115 16-bit I²C ADC.

This architecture ensures accurate data acquisition while minimizing the use of local MCU I/O pins by offloading conversion to the $I^2C$ bus. 
By utilizing the ADS1115. The integration into the NORVI X platform allows for seamless scalability, providing a robust galvanic-ready interface 
between the switching circuitry and the processor.

Datasheet : https://norvi.io/docs/norvi-x-ai4-datasheet/
