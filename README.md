# processorEmulator

Emulator for a rudimentary processor that can execute the following instructions


LODC:   Loads constant op2 into register op1\
ADDC:   Adds constant op2 to regster op1\
SUBC:   Subtracts constant op2 from register op1\
ADDR:   Adds register op2 to register op1\
SUBR:   Subtracts register op2 from register op1\
PRNT:   Adds register op1 to output buffer\
JMNZ:   Jumps to op2 if register op1 is not zero\
JMIZ:   Jumps to op2 if register op1 is zero\
LODM:   Loads from memory location at register op2 into register op1\
STRM:   Stores register op2 at memory location at register op1\
HALT:   Halts
