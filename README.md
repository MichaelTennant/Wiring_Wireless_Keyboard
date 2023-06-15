# Wiring Wireless Keyboard
## Introduction
I bought a wireless keyboard without a wireless reciever so I am planning on using the Raspberry Pi Pico to create a usb connection on the keyboard. The primary idea is to itterate over each keyboard row powering them on one at a time, and reading the volatages in the subsequent columns. If they are high, this allows me to detect which keys are being pressed at a given moment. The Pico can then use that data to update the program which can then call the pico-superkey-board functions in order to pass the data through to the computer it is plugged in to.

## Usefull libraries
https://github.com/guruthree/pico-superkey-board
