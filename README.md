# Circuit Boards
 Circuit boards made with Fritzing 
 
## NanoBasic.fzz 

It can be used as a simple to make and use as Ardunino Nano breakout board. 
It provides extra pin outs for supply connected sensors or other devices with power. 8x 3,3V, 8x 5V, 8x GND 
For connecting several I2C devices are there 6x SDA an 6x SCL pin outs available on board. 
8x digital pin outs and also serial TX/RX is available as pin out (same like USB port) for cascading boards.   

## NanoBasic2.fzz 

Same like NanoBasic.fzz, but with 6 additional pin outs for using analog pins from Arduino Nano board.

## PowerSupply5V_V2.1.fzz

Is a circuit board to scale up to 8 parallel power regulators with fixed voltage output, depending on your need. 
For example 8x L7805CV for constant 5V output. 
The input voltage depends on your needed output voltage which you can change by used power regulator type with fixed voltage.
### Notice
You can not use different power regulators with different output voltages one same board. For example 8x L7805CV.
On the other side it's possible to solder only 1, 2, 3, 4, 5, 6, 7 or all 8 power regulators to board depending on your needed power output.
The board supports "solderable" holes for every power regulator to attach an heatsink.
