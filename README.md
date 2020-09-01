# Micro-ESP8285
Micro wi-fi board with ESP8285 chip


The voltage regulator can be a RT9193, MIC5205 or other. If you have a 3.3V power supply, you can obmit IC1 and C3 and apply 3.3V to the VCC Pin.

Diode D1 is needed only if you use sleep function.

On the ADC pin there is a voltage divider (R5/R6), you can calculate it for the input range that you need. The ESP ADC pin accepts 1 volt max.

All the I/O pin are available throught the two 5 pin headers, except GPIO0, TXD, RXD (available on serial connector) and GPIO15 (available on a chopper pad on the bottom side of the PCB).

You can find a suitable serial interface / programmer on my github page.
