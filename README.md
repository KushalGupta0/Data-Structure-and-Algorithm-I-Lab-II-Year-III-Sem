# Data Structure and Algorithm - I Lab (II Year - III Sem)

Institute: Noida Institute of Engineering and Technology
Platform: CodeTantra

## About

This repository contains solution code files for the "Data Structure and Algorithm - I Lab" course as provided on the CodeTantra platform by Noida Institute of Engineering and Technology. The files include C solutions for the programming questions from the course. Each source file corresponds to a specific question and is named according to a simple scheme (see below).

These solutions are provided for educational purposes: to study, understand, and learn from. They are not intended for copying into assignments or exams as-is; please follow your institute's academic integrity rules.

## File naming convention

Files are named using the pattern:

`<module>_<unit>_<question>.c`

Examples:

- `1_1_1.c` — Module 1, Unit 1, Question 1
- `2_1_10.c` — Module 2, Unit 1, Question 10

This repository's root contains many C files such as `1_1_1.c`, `1_1_2.c`, ... which map to the course questions in their respective order.

## Contents and structure

- Each `.c` file contains the solution for a single problem.
- All files are plain C source files and are intended to be compiled with a standard C compiler (e.g., GCC).
- No external libraries beyond the C standard library are required unless explicitly noted inside a solution file.

## How to compile and run (Windows - cmd.exe)

Prerequisites:

- A C compiler installed on your system. On Windows you can use MinGW-w64 (GCC), TDM-GCC, or use WSL with gcc installed.

Example commands (run from the repository directory in `cmd.exe`):

Compile:

```cmd
gcc 1_1_1.c -o 1_1_1.exe -std=c11
```

Run:

```cmd
1_1_1.exe
```

Or explicitly:

```cmd
.\1_1_1.exe
```

If the file reads input from the console or a file, provide the appropriate input as required by the problem.

Notes:

- You can compile multiple files the same way: `gcc filename.c -o filename.exe`.
- If your compiler is not in PATH, add it or use its full path (or use an IDE that provides a build/run command).

## Code style and assumptions

- Solutions are written for clarity and learning rather than micro-optimized performance.
- Most files use standard C (C99/C11). If a file requires a specific standard or flags, that will be noted in the file header comment.
- Expect simple console input/output. Some problems may expect reading from stdin or printing formatted output; check the top comments of each file.

## Contributing or adding solutions

If you want to add or improve a solution in this repository:

1. Follow the existing naming convention for new solutions.
2. Add a brief comment at the top of the file mentioning the problem statement or reference (module/unit/question number).
3. Keep code readable: use comments, descriptive variable names, and avoid hard-coding where possible.
4. If you want to submit changes, open an issue or contact the repository owner (see Contact below).

## Academic integrity and disclaimer

These solutions are provided solely for educational purposes and to help students understand algorithms and C programming techniques. They are not meant to be submitted as-is for graded assignments, labs, or exams. Students should use them as references, adapt and rewrite solutions in their own words, and always follow the institute's academic policies.

Noida Institute of Engineering and Technology and CodeTantra are credited for course content and problem sourcing. This repository is an independent collection of solution examples and is not an official publication by the institute unless stated otherwise.

## Troubleshooting

- If a file does not compile, check the top comments in that file for notes on required compilation flags or input format.
- If you cannot install a compiler on Windows, consider using WSL (Ubuntu) and then run `gcc` from there, or use an online C compiler for quick checks.

## Contact / Credits

- Course: Data Structure and Algorithm - I Lab (II Year - III Sem)
- Institute: Noida Institute of Engineering and Technology
- Platform: CodeTantra

If you are the repository owner and want changes, or if you found an issue, please edit the file directly or contact the owner/maintainer.

---

**Important:** This collection is for learning and reference only. Do not plagiarize. If you are a student, use these samples to study the approaches and write your own solutions for submissions.
