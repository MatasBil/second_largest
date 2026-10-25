Second Largest Number
A small C program that reads an array of integers and finds its second-largest distinct value.

Features
Validates the array size and user input.
Dynamically allocates memory for the array.
Finds the second-largest distinct number in a single pass.
Handles arrays with fewer than two distinct values.
Frees allocated memory before exiting.
Requirements
GCC, Clang, or another C compiler
C99 or later
Build
gcc -std=c99 -Wall -Wextra -pedantic -o second_largest main.c
Run
./second_largest
The program prompts for the array size and then reads each array element.

Example
Enter the array size: 5
Memory allocated!
Enter the numbers: 4 9 2 7 9
Second largest number is 7.
Behavior
The program reports that there is no second-largest number when all input values are equal or when the array contains fewer than two distinct values.

License
No license has been specified for this project.
