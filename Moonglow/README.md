moonglow.cpp reds a file in Moonglow's format on standard input, and prints a very simple output. <br />

Here's Moonglow's format. The text file is composed of words. If a word is a number, then that is a student's score on a question, so you add it to the student's exam score. If the word is not a number, but is the word "NAME", then the next word is the student's name (Moonglow only uses first names -- last names are corporate and impersonal). If the word is "AVERAGE", then you start reading numbers until you read a word that is not a number (or is the end of the file). You average all of those numbers and add that to the score. Since Moonglow is a little scatterbrained, sometimes a number does not follow "AVERAGE." In that case, you ignore the "AVERAGE". <br />

When you are done reading the file, your program should print the student's name, a space, and the student's score. Just use cout for this -- nothing exciting.
