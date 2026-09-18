# Arduino Nano MP3 Player

A portable, battery-powered MP3 player built around an Arduino Nano v3 and a DF Player Mini. It features a 0.96" OLED status display, tactile push button controls, and a 3.5mm headphone output, and is rechargable over USB-C via a TP4056 module.

**Status:** work in progress, prototyping on breadboard.

## Features
- Play / pause
- Next / previous track
- Volume up / down
- OLED display showing trach number, volume, and play state
- Headphone output thorugh a TRRS jack module
- LiPo powered, USB-rechargable, with a slide switch for power

## Hardware
| Part | Notes |
|------|-------|
| Arduino Nano (v3) | ATmega328P, 5V logic |
| DF Player Mini MP3 module | Plays MP3/WAV from a microSD card |
| 0.96" OLED Display | I2C, SSD1306 driver |
| TRRS audio jack module | Headphone output |
| Tactile push buttons | Volume up/down, play/pause, next/previous track |
| 1kΩ resistor | In series on the Nano -> DF Player RX line for better audio quality |
| MT3608 step-up converter | Boosts battery voltage to a regulated 5V |
| TP4056 charger module | USB-C charging |
| Slide switch | Main power control |
| microSD card | FAT32 formatted |

Full parts list with links: [`hardware/BOM.md`](Hardware/BOM.md)
