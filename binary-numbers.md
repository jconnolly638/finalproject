### Binary Numbers

How do binary numbers work? You probably know already that binary numbers are strings of ones and zeroes. They look something like this:

10110111

How would we begin converting this into a number we can easily understand? The answer is to look at binary numbers as a "base-2" number system. Our ordinary (decimal) number system is "base-ten", which means that each place value is ten times greater in magnitude than the place value to its right. For example, in the non-binary number "55", the first digit represents ten times the second digit. In binary numbers, on the other hand, each place value is only two times greater in magnitude than the number to its right. Other than that, the two systems work quite similarly. Let's count up from 1 in binary: 

0000
0001
0010
0011
0100
0101
0110
0111
1000...

Just like counting in decimal, each place value rolls over to 0 after exceeding its maximum (which here is a "1" instead of a "9".) Another way of thinking of binary numbers is that each "1" represents the decimal number 2^(0+x)^, where x is the number of places away from the rightmost digit. So, a "1" in the rightmost digit represents decimal 2^0^ = 1, then a 1 to its left represents 2, then decimal 4, decimal 8, and so on. The entire binary number is the sum of these powers of 2. So what decimal number does the first binary number in this document represent? If you work out the powers of 2, it comes out to 183. Try working it out!

[back to readme](README.md)
