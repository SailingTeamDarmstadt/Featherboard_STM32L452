# Featherboard_STM32L452
Our custom designed PCB for the STM32L452 in the Feather format design

# Warning
We added a charging circuit for a LiPo, but didn't test it previous to release. **If you want to use the charging circuit please check the design for yourself and make sure nothing bad can happen. You have been warned!**

## Intended use

We designed this board as a coprocessor for Marlin to control the onboard servo motors but also with a future use as an autopilot for roBOOTer. 

To keep the production cost low we chose the same STM microcontroller used throught our boats already.

## Feature list
- STM32L452RET chip
- USB-C connector for power supply and programming connection
- Additional programming header, simmilar to the one used throught our PCBs (usually not populated)
- DFU/programming jumper, to choose the chip mode
- Micro SD card slot to store/read data
- Status LEDs for power, charging, CAN and Timer usage as well as additional, free programable ones
- Access to CAN interface


