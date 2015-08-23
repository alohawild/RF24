# RF24
RF 24 items
This is a list of programs I wrote for the Arduino using Sparkfun's 
new breakout board for RF24.

The hook up is based on Sparkfun's hookup:

https://learn.sparkfun.com/tutorials/nrf24l01-transceiver-hookup-guide?_ga=1.203014865.1581405881.1315105237

This hookup uses pins D9-10 for the SPI connection and 11-13 too.

I am using 5V power.

I use D3 to do the old PWM LED dimming routine with 220 Ohm resister on the slave Arduino.

I put a sliding potentiometer and measure it on A0 on the command Arduino.

I pass one large unsigned int and do math to make three two digit value for it. 
I intend to have three values at one time.

