# Nvm

This library implements a simple abstraction layer over native Arduino EEPROM library. It provides a means of reading and writing a contiguous data buffer into EEPROM. 

Main features:

* Reducing EEPROM wear by comparing each byte with the corresponding EEPROM copy and only writing the bytes that have been modified.

Usage examples:

* https://github.com/microfarad-de/li-charger
* https://github.com/microfarad-de/antenna-tuner
* https://github.com/microfarad-de/pi-ups
* https://github.com/microfarad-de/smart-pump
* https://github.com/microfarad-de/tcs-intercom
* https://github.com/microfarad-de/fridge-controller

Git commands:

* `git submodule add ssh://git@github.com/arduino-library/Nvm src/Nvm`
* `git submodule add https://github.com/arduino-library/Nvm src/Nvm`
