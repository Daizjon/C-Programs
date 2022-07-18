 A disassembler takes binary, machine language code and converts it into text-based assembly language (the opposite of an assembler).
 
 The Program will be given two required arguments and one optional argument.

First user argument: This argument specifies the input file, which is a binary file encoded in machine language.

Second user argument: This argument specifies the output file, which will be a text file representing the assembly code for the given machine language. If the user specifies a dash (-) as the output file, then your code will write to stdout. NOTE: This is easier to implement than you think. stdout is a FILE * data type!

Third user argument: (optional to the user). The user can either specify a or x. The argument 'a' will tell your disassembler to make the register names the ABI register names (second column in the register table above). If the user specifies 'x', your disassembler will decode register names as a variation of x0 through x31 (see example output below). If the user does NOT specify a third argument, then you must assume ABI register names.

The input file is simply a binary file that lists instructions. Each instruction is exactly 4 bytes and is in little-endian byte order. No other fields are present in the input file.
