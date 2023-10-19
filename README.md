!!!THIS WAS NOT WRITTEN BY ME!!!

# Linux-On-Scratch
Linux for the blocky code language Scratch!

## About The Emulator

This is a 32-bit RISC-5 processor emulator, the emulator runs the linux 6.0 kernel

#### Extensions

The emulated processor has 3 extensions:

1. Base Integer Instruction Set (RV32I)
2. Standard Extension for Integer Multiplication and Division
3. Standard Extension for Atomic Instructions

#### IO

The emulator has 1 MMIO device located at 0x10000000, this device is a UART and is what handles the input and output.

#### RAM

The emulator has 64 megabytes of RAM


## Interacting With The Emulator

#### Sending Input

To send input to the emulator (like at the login screen) press the space key once and wait for the text input to appear, type in what you want to type and hit the enter key. 
To enter the enter/newline key press the "left arrow" key.

#### Modifiying the code

Feel free to modify the code however you like and try out different programs and add new MMIO, but please do not call my project your own.



I also created a Github to discuss LOS (Linux On Scratch) and other programming related stuff, feel free to ask any questions you might have there! https://discord.gg/hhewPEawA6
