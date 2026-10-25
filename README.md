# Second Largest Distinct Number

A C program that finds the **second largest distinct integer** in an array using an efficient single-pass algorithm.

This project was created to practice C programming fundamentals, including pointers, dynamic memory allocation, functions, and algorithm design.

## Features

- Finds the second largest distinct number in an array.
- Handles duplicate and negative numbers.
- Validates user input and array size.
- Uses dynamic memory allocation (`malloc` and `free`).
- Handles cases where no second largest distinct number exists.
- Uses an efficient **O(n)** time complexity algorithm.

## Requirements

- GCC, Clang, or another C99-compatible compiler.
- C99 or later.

## Compilation

Compile the program using GCC:

```bash
gcc -std=c99 -Wall -Wextra -pedantic main.c -o second_largest
```

## Usage

Run the compiled program:

**Windows (Git Bash):**

```bash
./second_largest.exe
```

**Linux / macOS:**

```bash
./second_largest
```

Enter the array size and then provide the integer values.

## Example

**Input:**

```text
Enter the array size: 6
Memory allocated!
Enter the numbers: 4 9 2 15 7 11
```

**Output:**

```text
Second largest number is 11.
```

## Edge Cases

| Input Array | Result |
|---|---|
| `{10, 5, 8, 3}` | `8` |
| `{5, 5, 3, 2}` | `3` |
| `{-8, -2, -5}` | `-5` |
| `{7, 7, 7}` | No second largest distinct number |
| `{5, 0, -3}` | `0` |
| `{2, 1}` | `1` |

## Algorithm

The program maintains three variables:

- `largest` – stores the largest number found so far.
- `second_largest_value` – stores the second largest distinct number.
- `found` – indicates whether a second distinct value has been found.

The algorithm iterates through the array once, updating the two largest distinct values when necessary.

**Complexity:**

- **Time:** O(n) – each element is processed once.
- **Auxiliary space:** O(1) – the search algorithm uses a constant amount of additional memory.
- **Total space:** O(n) – the input array is dynamically allocated.

## Learning Objectives

This project demonstrates practical experience with:

- Arrays and pointers in C.
- Functions and passing values through pointers.
- Dynamic memory management.
- Boolean logic and conditional statements.
- Input validation and error handling.
- Basic algorithm optimization.

## License

No license has been specified for this project.
