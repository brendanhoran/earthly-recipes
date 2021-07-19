# Collection of earthly.dev recipes

## Overview
Use earthly to build various dev environments.


## How to use
1. Install https://earthly.dev   
2. Copy the recipe that you need and rename it as `Earthfile`.   

## Listing of Earthfiles
* Earthfile-MicroPython -- Builds Micropython firmware and ESP-IDF toolchain.   
  Arguments:
  * ESP_IDF_VERSION -- Sets the branch/version of ESP-IDF to build.   
  * SERIAL_PORT -- Sets the device name of the serial port to use, EG; `/dev/ttyUSB0`.   
