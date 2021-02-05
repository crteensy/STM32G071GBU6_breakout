# STM32G071GBU6_breakout
Breakout board for the STM32G071GBU6

## Partially tested
I've built one of these and measured:

- (unpowered) no shorts
- (unpowered) diode between I/O and ground
- (powered) 3V3 output is fine

Reset was not tested.

I didn't have the exact switch (KMR2) but one with an extra ground tab (KMR2xxG) but you that's not a problem - the ground tab doesn't touch antything.

The boreakout board was not tested with external circuitry yet.

## Short description

A very simple breakout board for the STM32G071GBU6:

![3D view](https://github.com/crteensy/STM32G071GBU6_breakout/blob/main/STM32G071GBU6_breakout-3d.png)

Reset circuitry (pull-up, cap, push button to GND) can be connected to PF2/NRST by closing solder jumper JP1.


