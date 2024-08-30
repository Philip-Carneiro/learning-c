# Assessment 15: Project - Simple Shell

## Objective

Apply all the skills you've learned by developing a simple shell program that can execute commands like `ls`, `pwd`, and `echo`.

## Instructions

1. Create a file named `assessment_15.c`.
2. Write a C program that:
   - Implements a basic shell interface that reads input from the user.
   - Parses and executes commands using `fork`, `exec`, and `wait` system calls.
   - Handles basic commands like `ls`, `pwd`, and `echo`.

3. Compile and run the program.

## Expected Output

```c
$ ls file1.txt file2.c $ pwd /home/user $ echo Hello, World! Hello, World!
```

## Skills Covered

- Combining all the learned concepts.
- Understanding process creation and management.
- Parsing and executing user commands.
