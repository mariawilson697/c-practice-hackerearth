This program takes a series of integers as input, extracts the last digit from each number, and concatenates those digits to form a new number. It then checks if the resulting number is divisible by 10 (i.e., ends with 0). Based on the result, it prints "Yes" or "No".

Example
Input:

5
15 25 35 41 34
Computation:
Extract last digits: 5, 5, 5, 1, 4

Resultant number: 55514

Check: 55514 % 10 ≠ 0

Output:

No


Input Format
First line: An integer N — number of elements.

Second line: N space-separated long integers.

Output Format
Prints "Yes" if the constructed number is divisible by 10.

Prints "No" otherwise.


Sample Run

Input:
3
10 20 30

Output:
Yes
🛠️ Technologies Used
Language: C

Compiler: GCC

Libraries: stdio.h, stdlib.h, string.h