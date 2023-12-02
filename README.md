# Bloop Box Tailboard with Power Supply

## THIS IS NO LONGER MAINTAINED AND THEREFORE ARCHIVED! 

[![CI](https://github.com/bloop-box/bloop-box-tailboard/actions/workflows/ci.yml/badge.svg)](https://github.com/bloop-box/bloop-box-tailboard/actions/workflows/ci.yml)

![Tailboard 3D Render](https://bloop-box.github.io/bloop-box-tailboard/3D/BloopBox%20Tailboard-3D_top.png)

[Documentation](https://bloop-box.github.io/bloop-box-tailboard)

The board is designed using KiCAD 6 with production and assembly by JLCPCB in mind. All parts are selected to be
available from JLCPCB. At the time of writing as many parts as possible are used from their basic library.

- two power inputs
  - 5.5x2.1mm barrel-jack
  - USB-C
- Can handle 5V to 28V inputs
- Can deliver 5V with up to 3A to the mainboard (assuming it gets enough power)
- Additional circuitry to prevent damage in case two power supplies are connected
- Two buttons connected to the Raspberry Pi, per default used for volume control
- Three LEDs 
  - One to show status of power supply
  - Two can be remote-controlled by Raspberry Pi through the Mainboard

If you just need the 5V USB-C input and don't want the active circuitry you can use the [Tailboard Light](https://github.com/bloop-box/bloop-box-tailboard-light).
