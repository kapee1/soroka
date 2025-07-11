# soroka - DIY-Friendly 40% keyboard

![PXL_20240908_092151507](https://github.com/user-attachments/assets/d3ecc987-b74d-41c7-9bb6-479619c4c737)

### Build guide [[EN]](https://github.com/kapee1/soroka/blob/main/build%20guides/Soroka%20v2%20Build%20guide%20%5BEN%5D.md) | [[RU]](https://github.com/kapee1/soroka/blob/main/build%20guides/Soroka%20v2%20Build%20guide%20%5BRU%5D.md)

__Parts for v1 and v2 are not compatible!__


### Main features:

* Easy to build. Great for soldering practice.
* Supports all cyrillic symbols in base layer.
* Compatible with most base-kit keycap sets. No 40s addons needed.
* Optional Panasonic EVQWGD001 or EC-11 encoder
* Plate also optional. You can build keyboard without a plate to reduce cost.
* Variable bottom-row with a 3u spacebars support.
* Customizable magnet panels
* VIAL/QMK/[ZMK Firmware](https://github.com/aroum/zmk-soroka) by [aroum](https://github.com/aroum)
* *NEW!* Hotswap PCB (untested, but should be fine). Hotswap PCB uses different diodes. Please check the BOM file at the end of this README file.

### Layout:
![keyboard-layout (2)](https://github.com/user-attachments/assets/f78fa71a-8598-459b-90e7-10e8fc8debf0)


### Sizes:
![sizes](https://github.com/user-attachments/assets/43c70d04-38ef-4c08-8f5c-f754aee75991)

## Hotswap PCB BOM (Be careful, it's still untested!)
| Part     | Quantity |
|----------|----------|
| Soroka PCB (HS)   | 1   | 
| RP2040-Zero (unsoldered pins) | 1   |
| Any MX Hotswap Sockets | 52   |
| BAT54C, SOT-23 Diodes  |  27 | 
| Panasonic EVQWGD001 (optional) or EC-11 Encoder | 1   |  

## Soldered PCB BOM
| Part     | Quantity |
|----------|----------|
| Soroka PCB (Soledered)   | 1   | 
| RP2040-Zero (unsoldered pins) | 1   | 
| 1N4148w SOD-123 Diodes        | 50  | 
| Panasonic EVQWGD001 (optional) or EC-11 Encoder | 1   |  

## Assembly BOM:
| Part     | Quantity |
|----------|----------|
| Soroka PCB (Soledered or Hotswap)   | 1   | 
| Soroka Plate (Optional)       | 1   | 
| Soroka Case                   | 1   | 
| Soroka Panel                  | 1   | 
| Soroka Spacer                 | 1   | 
| Oval feets 22x4x1.5mm         | 4   |  
| Silicone washers 2x5x1        | 9   |
| M2 x 4mm Screws               | 13  |  
| M2 Inserts 3mm (OD3.2)        | 13  |  
| Round magnets 3x1 mm          | 8   | 


In case of cover with screws, you don't need spacer and magnets, but you will need:

| Part     | Quantity |
|----------|----------|
| M2 x 5 mm Screws                       | 8  |  
| M2 Brass Standoffs Female-Female 11 mm | 4  |  

