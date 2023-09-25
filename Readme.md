# Heat-Card
 
## Language selection:  
[English](https://github.com/Knockoi/Heat-Card/blob/main/Readme.md) | [简体中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-CN.md) | [繁體中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-TC.md)
  
## Overview
This mini heating station is compact and portable. Compared with the MHP30 mini heating station on the market, it has a larger heating area and is no longer restricted to a small heating area, and its body is thinner so that it can easily fit into your pocket. In addition, it adopts a specially designed PCB and copper column combination, each layer of function can be customized. The operation interface is simple and clear, using simple RGB lights to show the status, other settings can be adjusted through Bluetooth to connect to a mobile phone or a computer, and it supports Bluetooth and USB for firmware upgrade, which guarantees the machine's continuous improvement and updating.
  
 ## Hardware  
- MCU using ESP32 C3
- MOSFET using NCEP40T11G to control the temperature of the hot plate.
- Temperature measurement using PT1000. (-50°C~+500°C)
- Supports USB data transfer and UART data transfer (USB).
- Three-way button to select mode
- RGB display mode and system information
   
 ## Function   
- Imitates reflow soldering.
- Constant Temperature Heating(1) 100~°C.
- Constant temperature heating(2) 200~°C.
- Constant temperature heating(3) 300°C. Fast reflow soldering.
- Rapid reflow soldering time is 2/3 of the time of imitation reflow soldering.
  
 ## Function key   
 - Left button Slide the left switch menu to the left.
 - Right Key Right Slide the switch menu to the right.
 - Center key Press and hold <=3S to confirm.
 - Press and hold the center button >=5S to reconnect Bluetooth.
 - BOOT button Download button. Press and hold Boot, then press Reset to activate the firmware download mode and download the firmware through the serial port.
 - RESET button Press this button to reboot the system.
  
 The basic buttons can be found in ESP32-C3-DevKitM-1.
