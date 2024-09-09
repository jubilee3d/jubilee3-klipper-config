# jubilee3-klipper-config
base Klipper configuration for Jubilee-3

## Pre-Requisites
* Install [Katapult](https://github.com/Arksine/katapult).
* Configure your Leviathan Board with a *UART Interface* by following the LDO [setup guide](https://ldomotion.com/p/guide/VORON-Leviathan-V12).
  * Note: instructions in the link above describe steps for a UART, USB, or CAN interface. Follow only the steps for the *UART* interface.
  * Note: this Klipper config assumes a UART interface to the Leviathan board, but you can configure it differently as you choose provided that you change the `[mcu]` fields in `printer.cfg`.
* Install KIAUH.
* Install Klipper.
* Install [KTC](https://github.com/TypQxQ/KTC/tree/main)
  * KTC enables us to specify tool-specific XYZ offsets, input shaper parameters, and more.

## Installation

From your klipper machine, clone this repository into a folder named `klipper_config` with:
```bash
cd ~/ && git clone https://github.com/jubilee3d/jubilee3-klipper-config.git klipper_config
```

## References
* [Original LDO Leviathan Config](https://github.com/MotorDynamicsLab/Leviathan/tree/master/Klipper_config)
* [LDO Klipper Config Guide](https://docs.ldomotors.com/en/guides/klipper_multi_cfg_guide)
