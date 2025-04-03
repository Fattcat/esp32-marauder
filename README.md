# esp32-marauder
Custom esp32-marauder
## Created by JustCallMeCoco
## Edited by Fattcat

## Please give me STAR

# How to upload code ?
### check IMG !
## Follow this instructions down to correctly upload code
### as first go to give STAR to JustCallMeCoco to his GitHub (he deserves it a LOT)
### For MORE DETAILED Installation Go here
- https://github.com/justcallmekoko/ESP32Marauder/wiki/installing-firmware-from-source
- Download this repo (click GREEN BUTTON "Code" and download .zip file)
- when you downloaded it, then UNZIP it and open in Arduino IDE this file "esp32_marauder.ino"
- ! Also UNZIP "libraries.rar" (Download Win RAR for it) and paste that libraries to your ARDUINO LIBRARY FOLDER !
- Plug in your esp32 to your PC
- in Arduino IDE Sellect this board "Esp32 Dev Module" and sellect correct  
- add "ap.config.txt" to your SD Card (! MUST BE THERE !)
- After all changes DO NOT FORGET to save, and hit upload button (button located on top leftcorner and arrow pointing to right side)
- It can take 2 - 3 minutes to compile
- When it shows connecting .... (and here lot of dots) PRESS and HOLD ***BOOT*** Button on your esp32
- then press and release ***EN*** button and release ***BOOT*** button
- This ensure to switch esp32 into ***Flashing Mode***.
- Not it should be good to go.


## Evil Portals
- If you want to add Evil Portals (html) u need to attack SD Card (I RECCOMMEND 8 GB Capacity !, cuz when I tried 32 GB it then does not work)
- Go here https://github.com/bigbrodude6119/flipper-zero-evil-portal/tree/main/portals
- Pickup evil Portal which your want to use (u can download all of them) and paste them in your SD Card 

# CONNECTION
esp32 -> TFT Touch 240x320px Display 2.8 Inch
- 3.3V -> VCC
- GND -> GND
- CS -> D17 (or Pin TX2)
- RESET -> D5
- DC -> D16
- MOSI -> D23
- SCK -> D18
- LED -> connect to esp32 pin 3.3V
- MISO -> D19
- T_CLK -> D18
- T_CS -> D21
- T_DIN -> D23
- T_DO -> D19
- T_IRQ -> not connected

## Builtin SD Card Module (is optional)
- SD_MISO -> D19
- SD_MOSI -> D23
- SD_SCK -> D18
- SD_CS -> D12

## GPS Module (neo 6m)
### This is not necessary but is useful when is part of full pack :D
- VCC -> 5V
- GND -> GND
- TX -> D4
- RX -> D13

## This down was Fixed
- TFT Display Touch inverted
