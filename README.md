# File Statistics in C

## Project Description

A simple C program that reads a text file and calculates the number of characters, words, and lines present in the file. It demonstrates basic file reading and character processing in C.

## Features

- Open a text file in read mode
- Count characters in the file
- Count words in the file
- Count lines in the file
- Display file statistics
- Close the file using `fclose()`

## Technologies Used

- C
- File Handling
- `FILE`
- `fopen()`
- `fgetc()`
- `fclose()`

## How to Run

1. Create a file named `file_statistics.c`.
2. Create a `data.txt` file in the same project folder.
3. Add some text to `data.txt`.
4. Compile the program using a C compiler.
5. Run the program.

Example using GCC:

```bash
gcc file_statistics.c -o file_statistics
./file_statistics

===== File Statistics =====

File Statistics:
Characters: 79
Words: 14
Lines: 3

Author

M.Likitha
