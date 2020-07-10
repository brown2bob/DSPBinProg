# DSPBinProg
DSP Binary Image Program EEProm

This repository covers the space for the development of a Computer to Device EEProm Programmer.
The Computer will be a Windows/Mac device with a standard USB-2 type control.
The programming device is an Arduino Uno style with an internal USB to serial converter.

Arduino start location: https://www.arduino.cc/
Source Code Search:  https://www.google.com/search?channel=cus2&client=firefox-b-1-d&q=arduino+program+eeprom+source

Basic Theory of Operation
1. Binary file gets created in SigmaStudio or Similar Program
2. Binary along with local PC app gets loaded onto computer
3. Computer is connected to device for update
4. App on computer is run to send the binary via USB to the device
5. The Arduino Controller in the device reads in the binary and performs the programming sequence to update the DSP EEProm on the Amplifier Board

Thanks,
Bob
