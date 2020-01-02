# An Arduino core for the Serpente boards

This is an Arduino Core I created to allow my uLisp Lisp interpreter to be run on Serpente boards. You could also use this on its own to program the Serpente boards in C from the Arduino IDE.

![image](http://www.ulisp.com/pictures/3j/Serpente-small.jpg) 

For full information about the Serpente boards see: [Serpente Documentation](https://serpente.solder.party).

To buy the boards see: [Serpente - A Tiny CircuitPython Prototyping Board](https://www.tindie.com/products/arturo182/serpente-a-tiny-circuitpython-prototyping-board/) on Tindie.

To get uLisp for the Serpente boards go to https://github.com/technoblogy/ulisp-serpente.

#### Installing the Serpente core

Install the Arduino Core as follows:

* Download the repository **serpente-core**.
* Move it into your **Arduino/hardware** folder.

When you restart the Arduino IDE there should be a new heading **Arturo182 Serpente Boards** on the **Boards** submenu with a single **Serpente** entry.

#### Description

These boards are based on the Microchip ATSAMD21E, an ARM Cortex M0+ CPU with a 48 MHz clock. There are three variants which differ only in the type of USB connector provided. Each board provides 256 KB flash and 32 KB RAM, and also include a separate 4 MB SPI DataFlash chip.

#### I/O pins

Apart from the power pins the boards provide six multi-purpose pins:

| Label | Functions |
| ----- | --------- |
| D0 | Digital I/O, analogue input, analogue output (PWM), MOSI. |
| D1 | Digital I/O, analogue input, analogue output (PWM), SCK. |
| D2 | Digital I/O, analogue input, analogue output (PWM), MISO. |
| D3 | Digital I/O, analogue input, analogue output (PWM). |
| D4 | Digital I/O, analogue input, analogue output (PWM), SDA, TX. |
| D5 | Digital I/O, analogue input, analogue output (PWM), SCL, RX. |

#### LED

The Serpente has an RGB LED connected to the following Arduino pin numbers:

| Pin | Functions |
| --- | --------- |
| D6 | Red. |
| D7 | Green. |
| D8 | Blue. |
