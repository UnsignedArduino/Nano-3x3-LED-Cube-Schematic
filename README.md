# Nano-3x3-LED-Cube-Schematic

Schematic for a simple 3x3 LED Cube using the Arduino Nano.

You can find the code for the cube [here](https://github.com/UnsignedArduino/Nano-3x3-LED-Cube).

This uses 9 IO pins sourcing current to control the 9 LEDs on each plane, and 3 IO pins sinking the plane's current to control which layer is active, therefore it uses the [`LEDCubeXZOutYIn`](https://github.com/UnsignedArduino/Nano-3x3-LED-Cube/tree/main/lib/LEDCube/IO/DirectIO/LEDCubeXZOutYIn) class. (IO pins source/**out**put current to the XZ plane and sink/"**in**put" current to the Y layers) If you would like to change the wiring, refer to the instructions in the [Nano-3x3-LED-Cube](https://github.com/UnsignedArduino/Nano-3x3-LED-Cube#changing-wiring) repository.

![Schematic for the 3x3 LED Cube, made in KiCad.](https://github.com/UnsignedArduino/Nano-3x3-LED-Cube-Schematic/raw/main/Nano%203x3%20LED%20Cube%20Schematic.png)

The schematic was designed in KiCad.
