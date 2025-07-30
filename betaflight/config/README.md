# Building Betaflight for Elarion F405 FC

Steps:
- Follow [Betaflight building guide](https://betaflight.com/docs/category/building) to setup build environment
- Copy `ELARIONF405` folder to `betaflight/src/config/configs`
- In `betaflight` directory apply OSD patch with `git apply ./0001-Use-SPI-Mode-0-for-MAX7456.patch`
- Build firmware with `make ELARIONF405`
- Built firmware can be found in `obj/` folder
