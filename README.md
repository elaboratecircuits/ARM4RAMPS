# ARM4RAMPS
ARM Cortex-M3 based board as improved replacement for Arduino MEGA2560 R3 in RAMPS based devices  

The aim of the project is direct replacement for Arduino MEGA2560 R3 boards

The project is in prototype phase. 

Until production phase schematics, layout drawings and free prototypes will be available to selected active developers.

The design documents will be released after active shiping. 


- based on NXP LPC1769 ARM Cortex-M3 MCU in LQFP100 form
- developer friendly - full debug environment:
       - standard 10pin JTAG header  
       - 6pin NMI ISP header  (RESET, GND, ISP_BOOT, 3V3, TX, RX)
       - onboard integrated tact switches for RESET and ISP_BOOT 
- 4.5 to 36V operating input voltage range
- high speed buffered inputs and outputs, 5V tolerant
- integrated Ethernet 10/100M based on LAN8720 circuit
- integrated ESP8266 WiFi. Support for ESP07, ESP12 E/F, ESP14 modules on 2mm headers (these modules are removable)
- integrated micro SD card
- full support for our new EC_RAMPS board and future Smart Displays editions 



FRONT SIDE


![alt tag](https://github.com/elaboratecircuits/ARM4RAMPS/blob/master/ARM4RAMPS.PNG)



ARM4RAMPs + EC_RAMPS - STACK



![alt tag](https://github.com/elaboratecircuits/ARM4RAMPS/blob/master/ARM4RAMPS-EC_RAMPS-stack-side.PNG)


ACTUAL PCB


![alt tag](https://github.com/elaboratecircuits/ARM4RAMPS/blob/master/ARM4RAMPS_pcb.jpg)





