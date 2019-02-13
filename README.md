# Light Blue Year

A PCB designed in KiCAD for mounting the Core51822 module using the
Nordic Semiconductor nRF51822 BLE microcontroller.

Has footprints for a voltage divider and capacitor for battery voltage
sensing.

Designed for (optional) use with a holder for two AAA batteries, which
should last over a year with low intensity usage.

Footprints for a temperature and air humidity sensor chips on a part of
the board that can be broken off.

Two mounting holes, and a hole to hang the board on.

Since the connectors for the Core51822 use 2 mm pitch, and smt connectors
for it cost more than the nRF module itself, the idea heare is to mount
the Core51822 on the underside of the board, just soldering it. Then 
mount the battery holder on top of it.

All pins from the module are broken out.

A 4 pin SWD programming header is also broken out.

Has a prototyping area.

I2C pull up resistors have footprints on the board. And one LED.

Mount what you want, leave the rest unpopulated.

Intended for manual (not stencil) soldering of the SMT components.

There is a footprint for one SMT LED and one IR Phototransistor.

Also a separate battery connector can be mounted if desired.

Designed in collaboration with @possan

This is my first project with KiCAD, please have oversight with any
strangeness.