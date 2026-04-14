<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The 1-bit full adder takes in three inputs: A, B, and Carry-In (Cin). These inputs are combined using XOR, AND, and OR gates to produce two outputs: Sum and Carry-Out (Cout).

## How to test

|input a, b, and c_in | output s | output c_out |
|---------------------|----------|--------------|
|0 0 0                |0         |0             | 
|0 0 1                |1         |0             |
|0 1 0                |1         |0             |
|0 1 1                |0         |1             |
|1 0 0                |1         |0             |
|1 0 1                |0         |1             |
|1 1 0                |0         |1             | 
|1 1 1                |1         |1             | 

## External hardware

LED
