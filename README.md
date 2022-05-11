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
5. Connect DAC and ADC to the corresponding ports on the FPGA
6. Auto-connect the FPGA to the computer
7. Program and run the code

