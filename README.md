# Collatz-Sequence-Solver

The "Collatz Sequence Solver" is a Python code that efficiently solves the Collatz problem for a given positive integer, n. The Collatz problem, also known as the 3n+1 problem or the hailstone sequence, involves applying a specific set of operations to a given number until it reaches the value 1.

The code utilizes a while loop to repeatedly perform the following steps:

    Print the current value of n.
    If n is odd (i.e., n % 2 is not equal to 0), update n by multiplying it by 3 and adding 1.
    If n is even, update n by dividing it by 2 (using integer division).
    Repeat steps 1-3 until n becomes 1.

After the while loop terminates (i.e., n reaches 1), the code prints the final value of 1.

To use the "Collatz Sequence Solver," the user needs to input a positive integer n. The code then displays the generated Collatz sequence starting from n, providing insights into the number of steps required to reach 1.

Example usage:
Enter n: 27
Sequence: 27 82 41 124 62 31 94 47 142 71 214 107 322 161 484 242 121 364 182 91 274 137 412 206 103 310 155 466 233 700 350 175 526 263 790 395 1186 593 1780 890 445 1336 668 334 167 502 251 754 377 1132 566 283 850 425 1276 638 319 958 479 1438 719 2158 1079 3238 1619 4858 2429 7288 3644 1822 911 2734 1367 4102 2051 6154 3077 9232 4616 2308 1154 577 1732 866 433 1300 650 325 976 488 244 122 61 184 92 46 23 70 35 106 53 160 80 40 20 10 5 16 8 4 2 1
