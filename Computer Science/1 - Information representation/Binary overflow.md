- When doing binary addition, for example when using two's complement set up, if the answer is larger than the largest possible number that the avaliable number of bits can represent, it can cause overflow errors.

- For example, when using 8 bit data representation in a two's complement set up, the largest number that can be represented is +127 and the smallest is -128. If the answer to an addition problem exceeds those bounds, an overflow error occurs as there are not enough bits to represent the larger number (e.g. you get 134 as an answer, that number cannot be represented by 8 bits in a 2's complement setup as it is above 127).


