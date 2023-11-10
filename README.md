# SeEEeeEeedy robo-bauble
The core idea is a ESP32S3 in a Bauble, ideally moves(inside or outside of Bauble), ESP32S3 is on a PCB we make

Join here https://u.easyeda.com/join?type=project&key=f08e7f41234b4b76908aa2b974636c57&inviter=faeb85eb21e24ff0abed2badd48c6564

![image](https://github.com/tiffoknee/robo-bauble/assets/812771/fa0de807-758e-4f1b-a588-5c86f541ab2e)


# conclusions from meetings
### Meet 1

Roughly basing on the Seeed Xiao breakout board and the Seeed Xiao. decoration is the breakout board and for now we use an off the shelf XIAO. But future we make our own board with XIAO footprint. So splitting the development.

~~https://thepihut.com/products/seeed-studio-xiao-esp32s3

https://thepihut.com/products/seeeduino-xiao-expansion-board

But later swapping in something like this for the XIAO board: https://jlcpcb.com/partdetail/3198295-ESP32_S3_WROOM_1N4/C2913197~~

### Meet 2
xiao is too easy, just getting a packaged ESP32S3 is not much harder and much cheaper

This board: https://oshwlab.com/chris_9044/sandtable_copy
Changed to this packaged chip(same footprint, more ram, need to remove amp) https://jlcpcb.com/partdetail/3198302-ESP32_S3_WROOM_1N8R2/C2913204

Next step is to make an EASYEDA project copied off this.

## Things to add to board
Probably I2C as main comms? << max 20cm and even then, only if you're on the moon?
Battery?
Charger/wires
actuator/motor driver
LED

##Decoration ideas
Bauble is an eyeball?

Bauble moves?

Bauble has tentacles?

Probably there is a light.

Power board from a few of these LED coils, coil on top of below Bauble: https://www.adafruit.com/product/5140
