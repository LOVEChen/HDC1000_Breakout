HDC1000 Breakout Board
======================

Here are Eagle files for my HDC1000 Breakout Board. It should work with the HDC1008 too, but I haven't tested it.

<p align="center">
  <a href="image.png"><img src="https://github.com/ftruzzi/HDC1000_Breakout/blob/master/image.png" align="center" height="374"   width="400" ></a>
</p>

The HDC1000 is a digital humidity sensor with integrated temperature sensor. More info and datasheet here: http://www.ti.com/product/HDC1000.

##Features and parts list:

* **U1:** HDC1000 IC from Texas Instruments, DSBGA-8 package.
* **C1:** 0.1uF 0805 package decoupling cap.
* **R1,R2:** 4.7k-10k ohm, 0805 package. I2C pull-up resistors.
* **R3:** 10k ohm, 0805 package. Pull-up resistor to VCC, for the DRDYN pin. Leave the pin floating if not used.
* **R4, R5:** 10k ohm, pull-down resistors to GND for address selection.
* **ADR0, ADR1** solder jumpers to VCC, connect to change the chip address (default: 0x41).

You can visit my website at www.truzzi.me. Arduino library [here](https://github.com/ftruzzi/HDC1000-Arduino).

Any suggestions or comments are appreciated!
