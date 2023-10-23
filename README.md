# qorthoz

qorthoz is an ortholinear 10.25u qaz compatible pcb with usb c and jst ports for case compatibility, rgb breakout strip and 6 additional pins for switch or rotary extensions.

## Layout

![](https://github.com/calvin-mcd/qorthoz/blob/main/Images/KLE.png)

## Pictures

![](https://github.com/calvin-mcd/qorthoz/blob/main/Images/top.jpg)
![](https://github.com/calvin-mcd/qorthoz/blob/main/Images/bottom.jpg)

## Firmware

Firmware is written for vial and the source code is provided for edits.

## RGB Strip

Please note that the PCB is using a STM32 MCU which runs on 3v3 logic. Using a 5V rgb strip can sometimes interfere with the 3v3 Data Signal from the MCU. If you use a 5V rgb strip solder Data IN and GND to the beginning of the strip but *DO NOT* solder power to the beginning but anywhere else on the strip. This should be enough to avoid 5V Power interference with the 3v3 Data IN.

## Disclaimer

This PCB has been fully tested and is confirmed to work. However, no-one involved in this project is responsible for any usage issues that may arise. Order at your own risk. Feel free to edit, modify and otherwise utilise these files.

## License

This project is released under the GPL v3 License. Please refer to the LICENCE file.

## Credits

This pcb has been made on request krisenplan. Do check out their beautiful qaz and qez compatible cases! https://www.printables.com/@Krisenplan

The silkscreen logo has been taken from the german 40s keyboard discord ClackTales!

As always big thanks to the many people who helped me and inspired this board!

Any questions, contact Calvin0563 on Discord. 