# STM32F103-Breakout-Board

This was my first attempt at PCB design, which was a STM32 based breakout/development board. This project allowed me to explore the full workflow of embedded hardware development all the way from schematic capture to PCB layout to bring-up to writing/debugging firmware. 

(Insert Photos)

## Features

- STM32F103C8T6 microcontroller
- 3.3V power input
- SWD debug header for ST-LINK
- BOOT0 pulled low (Boot from flash)
- NRST reset by shorting with tweezers
- Status LED
- I2C buffer circuitry
- SPI1 breakout on PA4-PA7
- 16MHz External crystal

**Altium Viewer:** [STM32F103 Breakout Board](https://kernel-viewer-cdn1.365.altium.com/106/client/index.html?feature=embed&source=ED9DA921-DC9D-4101-A86E-9B3499E344B4&activeView=3D)

## Progress

I was able to successfully flash a simple LED blinking program to the board, after having to desolder one of the headers to make space for the 14-pin debug connector for the ST-LINK. Next, I will test the other peripherals to validate it as a functional development board.
