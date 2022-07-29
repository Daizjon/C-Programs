This has four cpp files. <br />
**pgminfo:**
Your first PGM program should take a PGM file on standard input and report the number of rows, the number of columns, the total number of pixels, and the average value of all the pixels, padded to three decimal places. Your program should work on all valid PGM files, and should print out an error (using cerr) on any invalid PGM file. Examples of invalid PGM files are:
Those that don't begin with P2.
Those that don't have non-negative integers after the P2.
Those that don't have the number 255 after the number of rows and columns.
Those that contain the wrong number of pixels after the P2. This includes having too many pixels.
Those that contain pixels whose values are not numbers between 0 and 255.
Example of how to run: UNIX> ./pgminfo < Red.pgm <br />

**bigwhite:**
his program takes two numbers as its command line arguments -- the number of rows and the number of columns. It then writes a PGM file on standard output which contains that number of rows and columns, all of white pixels. Again, you should error check to make sure that the proper number of command line arguments are given, that they are integers and in the proper range. On an error, print the error statement to stderr.
Example: UNIX> ./bigwhite 20 10 > a.pgm
This will create a PGM file a.pgm, which has 20 rows and 10 columns of white pixels.
<br />

**neg:**
Neg takes a PGM file on standard input, and prints a PGM file on standard output that is the negative of the input file. If the PGM file is not valid (same parameters as pgminfo), print an error to standard error.
<br />

**hflip:**
Hflip reads a PGM file on standard input, and prints a PGM file on standard output. The output file should be the horizontal reflection of the input file -- in other words, left is right and right is left.
You'll have to use a vector for this program.
