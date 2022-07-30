This sets up a standard checkerboard. <br />
A generalized checkerboard is a rectangular grid one that has four parameters:
R: The number of rows.
C: The number of columns.
SC: The starting character.
CS: The cycle size.
The grid is a (R * C) matrix, where the element in row r and column c, contains the character SC + (r+c)%CS. For example, here's a generalized checkerboard with R=5, C=6, SC = 'a' and CS=4:


a	b	c	d	a	b <br />
b	c	d	a	b	c <br />
c	d	a	b	c	d <br />
d	a	b	c	d	a <br />
a	b	c	d	a	b <br />

The program checkerboard.cpp reads five inputs from standard input. The first four are the parameters R, C, SC and CS, as defined above. The fifth parameter is a width W. The starting character, SC, should be read as a char and the remaining parameters should be read as integers. <br />

The program prints out the specified checkerboard such that each element of the grid is printed as a (W * W) square. Here is an example: <br />

UNIX> ./checkerboard
5 6 a 4 1
