# rhythmpad

![rhythmpad](https://files.catbox.moe/82le4t.png)

A compact 2x4 macropad with 7 switches, a rotary encoder switch in the 2x4 top right, and an OLED screen. It is planned to be used for rhythm games but also a soundboard.
D
* Keyboard Maintainer: [Tristan Chan](https://github.com/TristanChanCraig)
* Hardware Supported: Custom Made PCB, Seeed XIAO RP2040
* Hardware Availability: [HackClub](https://hackclub.com/)

Make example for this keyboard (after setting up your build environment):

    make rhythmpad:default

Flashing example for this keyboard:

    make rhythmpad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
