# Music WLED Controller
Hi! Welcome to another one of my for fun projects! I have fallen in love with the WLED program by Aircookie (https://github.com/Aircoookie/WLED/wiki). My only issue with this wonderful LED program is that I cant sync the LEDs to songs when I host a party (pre-covid of course)! Well I decided to give this issue a go myself. So far, I have this dedicated PCB that incldes all the possible peripherials that work with WLED. This PCB works with other music visualiser programs I have used, I just need to merge these programs together.
## Included on the PCB
* 5-18V Input (The voltage is passed through to the LED screw terminal so make sure the voltages match!)
* Power LEDs
* Microphone input and amp
* 2.5mm audio input
* IR LED
* Screw terminal for conecting LEDs
* Hardware switch to toggle between AUX and Mic input
* ESP32 microcontroller
* Reset and IO0 buttons
* Programming header
## RE Higher Voltage LED Strips
This controller is designed to work with addressable LED strips that run on 5-18V that are currently being designed by me. These LED Strips are chunked into groups of three or six (every 10cm is a new chunk). Each chunk has its own step-down converter to give it's LEDs five volts. A big issue with regular 5V LED strips is, after a few meters, the voltage drop of the strip changes the color of the LEDs. By adding step-down converters, the voltage drop from 12 volts to say, maybe, 9 volts would not be an issue as the step down converters can use those 9 volts anyway.
