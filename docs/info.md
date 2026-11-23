<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

El sumador recibe dos operandos de 8 bits cada uno y genera un resultado de 8 bits.
El circuito es combinacional, tan pronto se modifica una entrada, la SUM se actualiza.
No hay salida de carry.

## How to test

Provide two 8-bit numbers as inputs via the ui_in and uio_in pins.
Observe the 8-bit sum output on the uo_out pins.
Ensure that all connections are made correctly as per the pinout configuration.
For example, if you input the binary numbers 00001101 (13 in decimal) and 00000111 (7 in decimal) on ui_in and uio_in respectively, the output on uo_out should be 00010010 (20 in decimal).

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
No external hardware is required for this project. It operates purely based on the digital inputs provided and generates a digital output. However, for testing and demonstration purposes, you may use input switches and output LEDs or a similar setup to visualize the input and output binary numbers.
