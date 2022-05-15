# CPE 487 Final Project: Siren with Pmod Frequency Control

The aim of this project was to create a simple way to change the frequency of an FPGA audio output using a potentiometer. To do this, we used existing code from Lab 5 (DAC Siren) and meshed it together with the VHDL code for the Pmod used in Lab 6.

## What we did

1. Activate the port pins for the DAC input by adding it as a parameter in "siren.xdc"
2. Connect ADC input to pitch value controlling frequency in "pitch.vhd"
3. Send changed frequency value from pitch.vhd to speaker via siren.vhd

## How to run this code

1. Load all the files in the repository into a Vivado project.
2. Run Synthesis
3. Run Implementation
4. Generate Bitstream
5. Connect DAC to Speaker and the JA port on the Nexys A7 Board
6. Connect ADC to the Potentiometer and JB port on the Nexys A7 Board
7. Auto-connect the FPGA to the computer
8. Program and run the code

## Demo:
https://user-images.githubusercontent.com/40646481/168453721-e57f53fe-908c-4262-a353-6c434da0a8b0.mp4

