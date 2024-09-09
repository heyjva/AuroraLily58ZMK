# ZMK config files for an Aurora Lily58

![Picture of Aurora Lily58 with niceview on left and trackpad on right](https://github.com/heyjva/Knucklehead-zmk-config/blob/main/img/20240805_081439.jpg?raw=true" alt="Picture of Aurora Lily58 with niceview on left and trackpad on right)

## Base Setup
Keymap is based on knucklehead adapted and customized for lily58 layout.

Base Keymap can be found here by minusfive: https://github.com/minusfive/zmk-config

Left side has niceview and left side currently has 35mm Cirque trackpad.  

## Cirque Touchpad
See cirque branch for code adapted from Mr-turing's repo to make the track work on ZMK: https://github.com/Mr-Turing/zmk-soflechoc

As well as used badjeff's zmk base (branch: feat/pointers-move-scroll) and cirque input module: https://github.com/badjeff (See west.yml for all repo's used for building)

Cirque touchpad is using holykeebs 35mm module: https://holykeebs.com/products/35mm-touchpad-module

Removed R1 on cirque circutboard for I2C operations: https://holykeebs.com/products/35mm-touchpad-module

Also soldered a wire from DR pad to 1 pin on nicenano for data interupt pin required for ZMK.

![DR pad location](https://github.com/heyjva/Knucklehead-zmk-config/blob/main/img/CirquePinout.jpg?raw=true)
![DR pad location](https://github.com/heyjva/Knucklehead-zmk-config/blob/main/img/20240805_081208.jpg?raw=true)
![DR pad location](https://github.com/heyjva/Knucklehead-zmk-config/blob/main/img/20240805_081157.jpg?raw=true)

Otherwise followed holykeebs guide for soldering GND, 3.3V, SDA, and SCL pins: https://docs.holykeebs.com/guides/touchpad-module/


## Keymap

![Keymap](https://github.com/heyjva/Knucklehead-zmk-config/blob/main/img/splitkb_aurora_lily58.svg?raw=true)
