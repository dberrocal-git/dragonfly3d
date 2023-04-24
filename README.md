# Dragonfly3D with BIGTREETECH SKR mini E3 v2.0

Modified Ender 3 Pro "Dragonfly3D", Klipper printer_data config

- STM32F103 28KiB bootloader and 8mhz crystal
- 4x TMC2209 in UART mode
- GPIO micro-controller startup to "!PA14"

The Raspberry Pi Zero W itself is used as a second MCU to control the ADXL sensor and as main MCU controller.

A maximum acceleration of 5900mm/s<sup>2</sup> has been achieved and thanks to a CHT nozzle (clone) and a copper heatbreak, flow rates of around 20mm<sup>3</sup>/s have been obtained allowing the speed to be increased to around 200 mm/s without sacrificing quality. Not bad for a bed slinger printer 😄.
