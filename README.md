# Calt10CPU
A CPU design which may be written to a PLD and will execute ASM instructions coded into an array of input switches.
Each file in this repository corresponds to a different region of the CPU for a different task. The ALU does 8 bit arithmetic, 
the DAU computes data addresses, the PAU computes program addresses, and the control unit receives input codes indicating instructions, 
then sends command signals out to the different regions of the CPU.
