# file-analyzer-lib

File Analyzer (Library Version)

A portable C program that analyzes a file and reports:
- Lines
- Words
- Characters
- File size
- Text/Binary detection

Built using C standard library functions.
Works on Windows and Linux.

## Features
- Count lines, words, characters
- Detect text vs binary files
- File size using fseek/ftell
- Portable: works on Windows and Linux

## Why this project?
This project is designed for beginners learning:
- File handling in C
- Buffering concepts
- Compiler and systems-programming basics

## Build & Run
```bash
gcc main.c analyzer.c -o analyzer
./analyzer test.txt

