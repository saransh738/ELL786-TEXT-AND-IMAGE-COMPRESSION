# PART 1:TEXT-COMPRESSION
## OBJECTIVE
This is a programming assignment which requires you to encode and decode binary message bits using repetition codes and arithmetic codes.
## INPUT
A text file of size 1 KB of your choice.

## EXPERIMENT 1:
1) Read the input text-file and convert it to a binary string, say of length M bits.
2) Generate a random binary error pattern of length M with hamming weight d such that the non-zero entries are uniformly distributed across M bits.
3) XOR the above error pattern with the message bits to obtain a new sequence denoted by y.
4) Using y, retrieve the text-file without any error detection/ correction coding.
5) In the decoded file, compute the percentage of modified characters with respect to the input file.
6) Repeat the above experiment by varying the value of d = {10, 100, 200,500, 5000}.


