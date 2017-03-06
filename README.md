# LCD-VU-meter
An audio signal is delivered to a LiquidCrystal Display and plots over time with Arduino.

A 3.5mm jack is plugged into an Analog input for arduino and maping results into a function to obtain a defined character of 8x5 each one, and use 16 rows divided in 2 8 row-long character and plot it in time by scrolling each column in the whole LCD. The controller is using a complex program in Arduino and conected to the following hardware.

Arduino UNO or any other generic device, even larger versions such as Leonardo, Mega, etc.

20x4 Liquid Crystal Display with HD44780 interface
https://www.sparkfun.com/products/256

An amplifier to receive the analog signal from the jack, I used a LM124N since it's very cheap and easy to find, but there are a lot in the market that are capable of doing that, there are even others that are better which can use a high fidelity signal for the input, in this case it's irrelevant since we're dividing in 16 segments only.
http://www.ti.com/lit/ds/symlink/lm124-n.pdf

3.5mm female and male jack in order to get the input analog signal, you might use an alligator clip or use a female jack and get the wires from it.

iPod or any other player to reproduce the output signal.

Check the [wiki](https://github.com/Jorghe/LCD-VU-meter/wiki) section to see diagrams and code.
