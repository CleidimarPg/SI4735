# Si4735 Library for Arduino

This is a library for the SI4844, BROADCAST ANALOG TUNING DIGITAL DISPLAY AM/FM/SW RADIO RECEIVER,  IC from Silicon Labs for the Arduino development environment.  This library is intended to provide an easier interface for controlling the SI4844.

__The SI4835 is a 3.3V part. If you are not using a +3.3V version of Arduino, you have to use a kind of 5V to 3.3V converter.__

By Ricardo Lima Caratti, Oct, 2019. 

__Attention: Code and Documentation  Under construction.__
__Do not try use it for while.__

__To be continue....__


## Summary

1. [Your support is important]()
2. [About the SI4735 Architecture]()
3. [Terminology]()
4. [Labrary Features]()
5. [Library Installation]()
6. [Hardware Requirements and Setup]()
   1. [Schematic]()
   2. [Component Parts]()
   3. [Playing with Arduino UNO or Pro Mini 5v and SI4844]()
   4. [Photos]()
7. [API Documentation](h)
   1. [Defined Data Types and Structures]()
   2. [Public Methods]()
8. [References]()
9.  [Examples]()
10. [Videos]() 


## Your support is important.

If you would like to support this library development, consider joining this project via Github. Alternatively, make suggestions on features you would like available in this library. Thank you!


## About the SI4735 Architecture 

The Si4735 is an .....


## SI4735 Terminology

| Term | Description |
| ---- | ----- |
| SEN | Serial enable pin, active low; used as device select in 3-wire and SPI operation and address selection in 2-wire operation| 
| SDIO | Serial data in/data out pin|
| SCLK | Serial clock pin|
| RST  | Also RSTb—Reset pin, active low |
| RCLK | External reference clock |
| GPO | General purpose output |
| CTS | Clear to send |
| STC | Seek/Tune Complete |
| NVM | Non-volatile internal device memory |
| CMD | Command byte |
| COMMANDn | Command register (16-bit) in 3-Wire mode (n = 1 to 4) |
| ARGn | Argument byte (n = 1 to 7) | 
| STATUS | Status byte |
| RESP | Response byte (n = 1 to 15) |
| RESPONSEn | Response register (16-bit) in 3-Wire mode (n = 1 to 8)| 


## Library Features


## Library Installation



## Arduino 5V and Si4844


## Schematic


### Parts


## Photos 

### SI4735 soldered on adapter


#### Protoboard


## API Documentation



## References

1. [Silicon Labs Si4737 WB/AM/FM Stereo/RDS single-chip receiver HAL library for Arduino ](https://github.com/rickeywang/Si4737_i2c)
2. 


## Videos