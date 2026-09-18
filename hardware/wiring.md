# Full Wiring Chart

| From | To |
|------|----|
| Battery + | TP4056 B+ |
| Battery - | TP4056 B- |
| TP4056 OUT+ | MT4608 IN+ |
| TP4056 OUT- | MT4608 IN- |
| MT3608 OUT+ | Sliding switch common (middle) pin |
| Sliding switch common pin | 5V rail |
| MT3608 OUT- | GND rail |
| 5V rail | Ardunino 5V |
| GND rail | Arduino GND |
| Ardunio 3V3 | DFPlayer VCC |
| Arduino 3V3 | OLED VDD |
| Arduino GND | DFPlayer GND |
| Arduino GND | OLED GND |
| Arduino TX1 | 1kΩ -> DFPlayer RX |
| DFPlayer TX | Arduino RX0 |
| Arduino A4 | OLED SDA |
| Arduino A5 | OLED SCL |
| DFPlayer DAC_R | TRRS TIP |
| DFPlayer DAC_1 | TRRS RING1 |
| DFPlayer GND | TRRS SLEEVE |
| Up button | D2 -> GND |
| Down button | D3 -> GND |
| Left button | D4 -> GND |
| Right button | D5 -> GND |
| OK button | D6 -> GND |