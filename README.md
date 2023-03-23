# 8-Bit-Accumulator-using-Verilog-Programming-in-NEXYS-4
This project is based on Verilog Programming Language. Our purpose to shift our bits left - right.
The objective of this project is to design a 8 bit accumulator that can perform the operations parallel load Operation , Right shift Operation , Left Shift Operation and the flipping operation and the goal is to design and simulate the result in Vivado Software and display the output in Artix NEXYS -4 Board.
Shift Registers are used for data storage or for the movement of data and are therefore commonly used inside calculators or computers to store data such as two binary numbers before they are added together, or to convert the data from either a serial to parallel or parallel to serial format.
The individual data latches that make up a single shift register are all driven by a common clock ( Clk ) signal making them synchronous devices.Shift register IC’s are generally provided with a clear or reset connection so that they can be “SET” or “RESET” as required.A shift register basically consists of several single bit “D-Type Data Latches”, one for each data bit, either a logic “0” or a “1”, connected together in a serial type daisy-chain arrangement so that the output from one data latch becomes the input of the next latch and so on. 
Shift register IC’s are generally provided with a clear or reset connection so that they can be “SET” or “RESET” as required. Generally, shift registers operate in one of four different modes with the basic movement of data through a shift register being:
* Serial-in to Parallel-out (SIPO)  -  the register is loaded with serial data, one bit at a time, with the stored data being available at the output in parallel form.
* Serial-in to Serial-out (SISO)  -  the data is shifted serially “IN” and “OUT” of the register, one bit at a time in either a left or right direction under clock control.
* Parallel-in to Serial-out (PISO)  -  the parallel data is loaded into the register simultaneously and is shifted out of the register serially one bit at a time under clock control.
* Parallel-in to Parallel-out (PIPO)  -  the parallel data is loaded simultaneously into the register, and transferred together to their respective outputs by the same clock pulse.
* Right Shift: In this operation the bits are shifted towards right and the vacant bits are stored with the input shift bit.
* Left Shift:In this operation the bits are shifted towards left and the vacant bits are filled with the input shift bit.
* Flipping:In this operation flipping of bits will happens.
