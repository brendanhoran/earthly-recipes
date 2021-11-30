# Collection of earthly.dev recipes

## Overview
Use earthly to build various dev environments.


## How to use
1. Install https://earthly.dev   
2. Copy the recipe that you need and rename it as `Earthfile`.   

## Listing of Earthfiles
* Earthfile-MicroPython -- Builds Micropython firmware and ESP-IDF toolchain.    
  Arguments:
  * ESP_IDF_VERSION -- Sets the branch/version of ESP-IDF to build. (Normally do not need to set this, its defined in the earth file)   
  * SERIAL_PORT -- Sets the device name of the serial port to use, EG; `/dev/ttyUSB0`. (Only needed for the flash and erase targets)   

* Earthfile-Rust-ESP32 -- Builds Rust firmware for the ESP32 device    
  Arguments:    
  * BUILD_BINARY -- The name of the binary image built from your project that should be flashed to the device (Only needed in the flash target)    
  * SERIAL_PORT -- Sets the device name of the serial port to use, EG; `/dev/ttyUSB0`. (Only needed for the flash and erase targets)    


* Earthfile-lattice-ulx3s-fpga -- Tooling, compile, simulate, place and route tooling for Lattice FPGA's.   
                                  Mostly aimed for use with the [ULX3S](https://ulx3s.github.io)
  * WORK IN PROGRESS   
