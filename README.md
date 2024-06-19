# iMX6ULL-DEV-Board

iMX6ULL-DEV-Board is a development board based on NXP i.MX6ULL. It is composed of core board and carrier board. The boards were developed in KiCad 8.0.

## Core Board
* i.MX6ULL, MCIMX6Y2CVM08AB, ARM Cortex-A7, 798MHz.
* Samsung, KLM8G1GETF-B041, 8GB eMMC.
* Micro, MT41K256M16, DDR3L, 512MB.
* DDR4 edge connector.

## Carrier Board
* micro SD x 1, 4-bit width.
* LCD.
* CSI.
* UART1, UART2.
* USB1: used as power and flash the eMMC.
* USB2: expand to 4 USB Type-A by USB Hub (GENESYS GL850G-HHY22).
* ENET1, ENET2: PHY SMSC LAN8720A-CP-TR.
* GPIO.

## How to use
* Connect the J2 (upright corner marked "Power Download") to 5V by a Type-C line.
* Connect the Type-C (the 2nd Type-C connector marked "UART1") to PC, it is the console.
* Insert micro SD to slot (downright corner marked "micro SD").
* Set the code switch to 1 0 0 0, boot from micro SD.
* Swith on (upright corner marked "ON OFF").

## Contact:
Feel free to contact me yan.cheng@hnautocontrol.com.
