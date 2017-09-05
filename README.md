# ALU68

## Introduction

ALU68 is a board sold by Dave from [mechkeys.ca](https://mechkeys.ca/) who also provided the original hex and JSON files

Current maintainer: [Jake Besworth](https://github.com/jakebesworth)

Originally taken from [JC65 QMK configuration](https://github.com/qmk/qmk_firmware/tree/master/keyboards/jc65)

These docs are for the QMK version of the PCB. [More info on docs.qmk.fm](https://docs.qmk.fm/)

## Building Hex Map

Make example for this keyboard (after setting up your build environment):

See [build environment setup](https://docs.qmk.fm/build_environment_setup.html) then the [make instructions](https://docs.qmk.fm/make_instructions.html) for more information.

```Bash
cd qmk_firmware/
make alu68-default
```

## Flashing

1. Press flash button

Put Keyboard into bootloader mode by clicking RESET button `Put the keyboard into DFU mode for flashing`. This button is default fn+home (top-right key) on ALU68 

2. Flash keyboard

Make and flash default keyboard:

```Bash
cd qmk_firmware/
make alu68-default-dfu
```

Linux compatible way

```Bash
cd qmk_firmware/keyboards/alu68/
sudo make keymap=default dfu
```

## JSON Config File

[Keyboard Firmware Builder](https://kbfirmware.com/)

### Edit JSON

You can upload the JSON file here, and using the KEYMAP section and different layers, can change what keys are mapped to what

[QMK keycodes](https://docs.qmk.fm/quantum_keycodes.html#qmk-keycodes)

### Export

You can export new Hex, JSON, and even qmk_firmware src from the editor. The qmk_firmware will produce the C code needed to flashing / compiling

## Default Keyboard layout

### Layer 1

![Layer 1 of ALU68](https://github.com/jakebesworth/ALU68-QMK/raw/master/images/layer1.png)

### Layer 2

![Layer 2 of ALU68](https://github.com/jakebesworth/ALU68-QMK/raw/master/images/layer2.png)