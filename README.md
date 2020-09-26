# SimpleModbus NG

SimpleModbus is a collection of Arduino libraries that enable you to communicate serially using the Modicon Modbus RTU protocol.

This project was born as an updated version of http://code.google.com/p/simple-modbus/ by Bester Juan, because his code lacks support for commands other than 3 and 16. More importantly the code is now on github, so you can contribute easily.

This project is actively maintained, so feel free to ask for features or report bugs!

## Features

This library adds support for command 6 and supports the use of more arduino pins. 
The goal of the project is to support all usable MODBUS commands on arduino and expose all arduino pins so you can use an arduino as an advanced automation controller for both analog/digital in/out.

NEW: Support for SoftwareSerial, really useful on AtTiny85. You can find both the library and an example that works reliably on attiny85 microcontroller.

## Usage
Simply copy the SimpleModbusMaster or SimpleModbusSlave or both, into your Arduino IDE **libraries** folder. Then restart the IDE and open the corresponding example from the example_master or example_slave folder.
