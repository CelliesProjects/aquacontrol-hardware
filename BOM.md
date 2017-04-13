## Description.

This BOM lists the parts needed to build a 5 channel LED controller.
The built hardware can be controlled with the Aquacontrol2 software.

### Items needed to assemble a Aquacontroller.

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

You will need some wire to connect the parts on the breadboards.

I use some color coding on my boards

| Color | Used as: |
| :-----: | ----- |
| Red    | 12 Volt from PSU
| Red    | 5 Volt from 7805 output to D1 mini 5V input. 
| Green  | 12 Volt from LED strip to mosfet drain.
| Black  | To ground.
| Grey   | I2C data/clock lines.
