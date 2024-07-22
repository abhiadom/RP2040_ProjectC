# RP2040 Project

This is a simple project for the RP2040 microcontroller.

## Structure

- `src/main.c`: The main program file.
- `include/utils.h`: Header file for utility functions.
- `src/utils.c`: Source file for utility functions.

## Build Instructions

```sh
gcc -o rp2040_project src/main.c src/utils.c -I include
./rp2040_project
