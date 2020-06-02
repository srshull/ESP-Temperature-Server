My bedroom gets very cold at night, so I made a network-connected temperature sensor that serves up a local website that allows me to keep track of temperature fluctuations in my room.

I wanted to keep costs low, so I built this project on the very inexpesive esp8266, an Arduino clone that can be programmed in the Arduino environment. I'm using the NodeMCU development board, which can be purchased for $3-4 online. Temperature sensing is done by measuring the voltage across a thermistor - a resistor that changes it's resistance in a predictable way with temperature. 

This was am excellent resource for getting rolling with the esp8266: https://tttapa.github.io/ESP8266/Chap01%20-%20ESP8266.html. He made a similar temperature logging server, but instead of a thermistor he used a temperature sensor IC that communiucates over serial with the esp. 
