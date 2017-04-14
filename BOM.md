## Description.

This BOM lists the parts needed to build a 5 channel LED controller.
The built hardware can be controlled with the Aquacontrol2 software.

#### Parts needed to build the Aquacontroller hardware.

Most parts can be purchased just about everywhere.
<br>Specific parts which I found hard to source have a link to the the webshop I use to buy the item.
<br>If you think you have a better or cheaper option for any of the items, let me know.

| Pos.  | No req:  | Item description: | Remark / Buy it at:  
|:-----:| :------------:|:-----------------| :------------------------------------------------------------
| 1     | 1             | WeMos D1 mini    | [ebay.com](http://www.ebay.com/itm/191787524741?_trksid=p2057872.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT)
| 2     | 3             | breadboard PCB   | [hackerstore.nl](https://hackerstore.nl/Artikel/831) or [aliexpress.com](https://www.aliexpress.com/store/product/Universal-Breadboard-400-point-MW-201-Solderless-Prototype-Bread-board-PCB-for-arduino-raspberry-pi-2/1270976_32398566022.html)
| 3     | 1             | 128 x 64 I2C OLED    | [ebay.com](http://www.ebay.com/itm/0-96-I2C-IIC-SPI-Serial-128X64-White-OLED-LCD-LED-Display-Module-for-Arduino-ZD-/282416950341?hash=item41c15cac45:g:eygAAOSwHsRYEd61)
| 4     | 1             | 2.1MM DC BARREL JACK - breadboard friendly   | [kiwi-electronics.nl](https://www.kiwi-electronics.nl/2.1mm-DC-barrel-jack-Breadboard-compatible) or [aliexpress.com](https://www.aliexpress.com/item/Breadboard-friendly-3-5-1-3mm-DC-barrel-jack-for-raspberry-pi-for-bread-board-A206/32694934128.html)
| 5     | 5             | IRLZ44N mosfet   | 
| 6     | 5             | 1/4W 470R gate resistor    | 
| 7     | 2             | 1/4W 4.7K I2C pullup resistor    | 
| 8     | 1             | 7805 voltage regulator    |
| 9     | 1             | N4001 diode    | 
| 10    | 1             | 0.22uF 50V electrolytic capacitor    | 
| 11    | 1             | 0.1uF 50V ceramic capacitor    | 
| 12    | 1             | 6pin terminal block    | [ebay.com](http://www.ebay.com/itm/10Pcs-2-54mm-0-1-Universal-6-Pin-6-Poles-PCB-Screw-Terminal-Block-Connector/182310502636)
| 13    | 4             | Arduino 8pin straight stackable shield header | Pin length equal to POS 14!
| 14    | 1             | Arduino 6pin straight stackable shield header | Pin length equal to POS 13!
| 15    | 2             | 8pin straight female header |
| 16    | 1             | 6pin straight female header |
| 17    | 1             | 4pin straight female header |

### Wiring
You will also need some wire and some electronics solder to connect the parts on the breadboards.

I use color coded wiring on my boards:

| Color | Used as: |
| :-----: | ----- |
| Red    | 12 Volt from PSU
| Red    | 5 Volt from 7805 output to D1 mini 5V input. 
| Green  | 12 Volt from LED strip to mosfet drain.
| Black  | To ground.
| Grey   | I2C data/clock lines.

## Images:

1. #### Wemos D1 mini MCU:
![wemos-d1-mini-small](https://cloud.githubusercontent.com/assets/24290108/25041455/659e4bdc-2110-11e7-8824-fadc77a6a3cf.jpg)

1. #### breadboard PCB:
![breadboard_pcb_mw-201_small](https://cloud.githubusercontent.com/assets/24290108/25041189/a5c55fa4-210e-11e7-9007-787b08e0d6ac.jpg)

1. #### DC barrel jack with thin pins:
![dc-barrel-jack-small](https://cloud.githubusercontent.com/assets/24290108/25041190/a5ca3d08-210e-11e7-90db-d32be9c45fe4.jpg)

1. #### 6pin terminal block:
![6pin_terminal](https://cloud.githubusercontent.com/assets/24290108/25041576/4161bce4-2111-11e7-9407-9a6ec3af9b88.jpg)
