# owl8

![owl8](https://raw.githubusercontent.com/yfuku/owl8/master/images/owl8.jpg)

macropad

* Keyboard Maintainer: [yfuku](https://github.com/yfuku)
* Hardware Supported: owl8 PCB, Pro Micro
* Hardware Availability: https://shop.dailycraft.jp/

Make example for this keyboard (after setting up your build environment):

    make dailycraft/owl8:default

Flashing example for this keyboard:

    make dailycraft/owl8:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Physical reset button**: Briefly press the button on the PCB
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
