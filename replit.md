# Lab: Listas y Pilas (Lists and Stacks in C)

## Overview
A C programming lab exercise focused on implementing linked list and stack data structures. Students implement functions in `exercises.c` and run tests via `bash test.sh`.

## Project Structure
- `exercises.c` — Student exercise file (only file meant to be edited)
- `arraylist.h` / `arraylist.c` — ArrayList/List TDA implementation
- `stack.h` — Stack TDA interface
- `test.c` — Test suite (do not modify)
- `test.sh` — Build and test runner script

## Language & Toolchain
- Language: C
- Compiler: GCC (via Nix stable-25_05)
- No package manager needed

## Running Tests
Open the Shell and run:
```bash
bash test.sh
```

## Workflow
- **Start application**: Runs `bash test.sh` (console output)
  - Compiles `test.c` with GCC
  - Runs the test suite
  - Shows pass/fail results per exercise

## Notes
- Only `exercises.c` should be modified by students
- No web server or frontend — pure C console application
- Git integration in `test.sh` is for student progress tracking
