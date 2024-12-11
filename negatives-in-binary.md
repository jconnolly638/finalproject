### Negative Numbers in Binary

Now we know how to represent numbers in binary. But there's a problem--this system only works for positive numbers! In the decimal system, you can represent a negative by putting a "-" symbol on the front of the number, but that's not an option in binary, since binary is limited to ones and zeroes for readability by a computer.

The most common way to solve this problem is called two's complement. In this system, computers are programmed to understand that the largest bit (or digit) in a binary number always represents the "sign" of the whole number (positive or negative.) Let's look at the binary representation of the number 12:

1101

To get the two's complement of this number, we first add a "1" to the left as the new most significant digit:

11100

Then we invert every other digit:

10011

Finally, we add "1" to the final product as if it's a positive number:

10100

This is the "two's complement" of 12. To read it, we (or a computer) simple read the most significant digit as a negative number, then the rest as positives, and add them all together. Adding these numbers gives us:

-(2^4^) + 2^2 = -12

To represent positive 12 in a two's complement system, we simply add a zero to the front of the number:

01101

[back to readme](README.md)
