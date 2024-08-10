# PZEM-017 Wireless
Built-in wireless functionality with ESP32-C3 and ESPhome

## Notes
- note that PSU is reverting to the default voltage with no current limit while the communication is lost
- CAN bus is wired directly from the PSU, you shall use "professional" board to connect the backplane
- there's a layer of insluating tape (polyimide, kapton) below the CAN transceiver
- no need to update serial number within the code, it will be fetched from a CAN messages
- current limiting is working only above 48V on an output terminals (not just configured voltage)

![HW](https://github.com/taHC81/pzem017-wireless/blob/main/PZEM-017-wireless.jpg?raw=true)
