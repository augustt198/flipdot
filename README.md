# flipdot

A driver board for my 16x28 flipdot display (Luminator MAX 3000).

The `connector` folder has a PCB for converting the 3x32 connector on the display to a
2x32 connector (which is easier to find cables for).

The `driver` folder has the driver board. Ideally I would like a footprint that fits both a teensy
and an ESP2866.

### Notes

- 15V is a good voltage to flip the dots, 50mA seems like enough current.
