# Neoscaler's Workman Preonic layout

This layout supports QUERTY, Workman, Colemak, Dvorak layers and is made for use with an US OS keyboard layout. German diacritics are sent via Unicode.

Based on the Preonic keymap and work from dudeofawesome. Developed for Preonic Rev3, but should work for others revisions, too.

## Features

- Base Layers
    - QWERTY
    - Workman
    - Dvorak
    - Colemak
- German diacritics (sent via Unicode)
- Numpad layer
- Audio

## Building and flashing

1. Put your board in DFU mode with either the button on the bottom, or with a software key in your current firmware
1. Flash:
    ```bash
    $ make preonic/rev3:workman-neoscaler:dfu-util
    ```
