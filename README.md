# esmodio
ESMOD is an input/output device which is compatible with MODBUS RTU. The device has 8 digital input, 8 digital output 4 analog input

https://github.com/enginsubasi/esmodio/wiki

# esmodio Features and Specifications

* 12-24V Wide Supply Range
* MODBUS RTU compatible via RS-485 physical interface
* 8 Channel Digital Output (0-Vs, Vs means supply voltage)
* 8 Channel Digital Input (0-24V)
* 4 Channel Analog Input (12 bits. Default 0-24V. Optional 0-10V or 0-3.3V)

<img src="https://github.com/enginsubasi/esmodio/blob/main/img/20230104_004013_Img.jpg" width="50%" height="50%">

# MODBUS Specifications

Following functions are enabled to use this device.

* 0x01: Read Coils. To get current status of digital outputs
* 0x02: Read Discrete Inputs. To get current status of digital inputs
* 0x03: Read Holding Registers. To get analog inputs
* 0x05: Write Single Register: To set output data
* 0x15: Write Multiple Registers: To set output data multiple

<img src="https://github.com/enginsubasi/esmodio/blob/main/img/20230104_004104_Img.jpg" width="50%" height="50%">

# Applications

* Test platforms, test benches
* Plant automation
* Generic automation
* PC controlled platforms
* Data acquisition system
* Data logging

<img src="https://github.com/enginsubasi/esmodio/blob/main/img/20230104_004128_Img.jpg" width="50%" height="50%">

IO Definition

<img src="https://github.com/enginsubasi/esmodio/blob/main/img/20230104_004128-Img2.jpg" width="75%" height="75%">
