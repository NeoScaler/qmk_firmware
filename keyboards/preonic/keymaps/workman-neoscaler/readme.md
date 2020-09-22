# Neoscaler's Workman Preonic layout

Based on the Preonic keymap and work from dudeofawesome. Developed for Preonic Rev3, but should work for others revisions, too.

## Features

- Base Layers
    - QWERTY
    - Workman
    - Dvorak
    - Colemak
- Numpad layer
- Audio

## Building and flashing

1. Put your board in DFU mode with either the button on the bottom, or with a software key in your current firmware
1. Flash:
    ```bash
    $ make preonic/rev3:workman-neoscaler:dfu-util
    ```
