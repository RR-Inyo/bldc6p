# bldc6p
Driving a blushless DC (BLDC) motor with Raspberry Pi

This is a trial to drive a BLDC motor, in the 6-pulse control mode, by a Raspberry Pi using the pigpio library.
Some of the Raspberry Pi's GPIO pins are connected to an STMicroelectronics X-NUCLEO-IHM001, a motor driver board, to control the three-phase inverter.
You need to "sudo" to run this program.

<img src="RasPi_BLDC.svg" width=600>

The schematic above shows connections between the Raspberry Pi and the X-NUCLEO-IHM001 along with a Hall sensor board available from CQ Publishing in Japan.

